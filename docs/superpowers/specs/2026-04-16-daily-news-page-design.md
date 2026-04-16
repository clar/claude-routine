# Daily News Page - 设计文档

## 概述

为 claude-routine 仓库构建一个 GitHub Pages 静态网站，以单页形式结构化展示 GitHub Trending / AI / Crypto 三个领域的每日新闻报告，支持浏览历史日期。

## 数据源

仓库中已有自动化流程每天推送报告文件：

- `github_daily/{YYYY-MM-DD}/trending.md`
- `ai_daily/{YYYY-MM-DD}/report.md`
- `crypto_daily/{YYYY-MM-DD}/report.md`

并非每个日期都有全部三个报告，页面需要优雅处理缺失情况。

## 页面布局

### 顶部日期栏
- 居中显示当前查看的日期
- 左侧 ← 箭头：切换到前一天（有数据的日期）
- 右侧 → 箭头：切换到后一天（有数据的日期）
- 日历图标：点击弹出原生日期选择器，跳转到任意日期
- 默认加载 dates.json 中最新的日期

### 内容区域（垂直堆叠）
三个板块从上到下依次排列：
1. **GitHub Trending** — 渲染 `github_daily/{date}/trending.md`
2. **AI 日报** — 渲染 `ai_daily/{date}/report.md`
3. **Crypto 日报** — 渲染 `crypto_daily/{date}/report.md`

每个板块：
- 带有明确的标题分隔
- Markdown 渲染保留原始的表格、标题、链接结构
- 若该日期无对应报告，显示"该日期暂无报告"提示

### 右侧悬浮导航
- 固定在视口右侧
- 三个锚点按钮：GitHub / AI / Crypto
- 点击平滑滚动到对应板块
- 高亮当前所在板块

## 视觉风格

- 简洁白底，浅色背景
- 无框架，纯 CSS 排版
- 表格样式清晰可读，带边框和斑马纹
- 响应式：移动端右侧导航收起或移到底部

## 技术方案

### 前端
- 单个 `index.html`，内联 CSS 和 JS
- `marked.js` 通过 CDN 引入，用于 Markdown → HTML 渲染
- `fetch()` 加载 `dates.json` 和各日期的 markdown 文件
- URL hash 支持：`#date=2026-04-16` 可直接分享特定日期的链接

### 日期索引
- `dates.json` 文件，结构如下：
```json
{
  "dates": ["2026-04-16", "2026-04-15"],
  "sections": {
    "2026-04-16": ["github", "ai", "crypto"],
    "2026-04-15": ["github"]
  }
}
```
- `dates` 按日期降序排列
- `sections` 记录每个日期有哪些报告可用

### GitHub Action (`.github/workflows/deploy.yml`)
触发条件：push 到 main 分支

步骤：
1. Checkout 代码
2. 运行脚本扫描 `github_daily/`、`ai_daily/`、`crypto_daily/` 目录，生成 `dates.json`
3. 将 `index.html`、`dates.json`、以及所有 `*_daily/` 目录部署到 GitHub Pages（使用 `actions/deploy-pages`）

### 文件结构
```
index.html                              ← 单页应用
.github/workflows/deploy.yml            ← 自动部署 workflow
github_daily/{date}/trending.md         ← 已有数据
ai_daily/{date}/report.md               ← 已有数据
crypto_daily/{date}/report.md           ← 已有数据
dates.json                              ← Action 自动生成（不入库）
```

## 不做的事

- 不引入任何前端框架（React/Vue 等）
- 不需要构建步骤（无 npm/webpack）
- 不做搜索功能
- 不做 RSS 输出
- 不做用户认证
