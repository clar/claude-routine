# GitHub Trending 日报 · 2026-08-22

## 今日焦点

> **Agent Skills 一日横扫 · 本地优先复兴 · Cursor 生态开放 · Mojo 稳步爬坡 · 副项目回潮**
>
> - `mattpocock/skills` 单日 +3,368⭐ 登顶——个人 `.agents/` 目录被大规模复制粘贴
> - `obra/superpowers` 累积 27.5 万⭐，继续巩固"Agent Skill 框架"事实标准地位
> - `AprilNEA/OpenLogi` Rust 重写 Logitech Options+，Local-first 派再赢一城
> - `cursor/plugins` 正式仓库上线，Cursor 从 IDE 走向平台化
> - `mahlernim/google-timeline-visualizer` 一个周末副项目 +1,040⭐——数据主权情绪未减

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [mattpocock/skills](https://github.com/mattpocock/skills) | 工程师个人 Skills 集合 | Shell | 229,345 | +3,368 | 19,602 |
| 2 | [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) | Rust 重写 Logitech Options+ | Rust | 12,847 | +1,372 | 349 |
| 3 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | AI 一键生成短视频 | Python | 113,852 | +1,187 | 17,273 |
| 4 | [mahlernim/google-timeline-visualizer](https://github.com/mahlernim/google-timeline-visualizer) | Google 时间线可视化 | Kotlin | 2,195 | +1,040 | 251 |
| 5 | [santifer/career-ops](https://github.com/santifer/career-ops) | 开源 AI 求职工具 | JavaScript | 67,410 | +918 | 12,867 |
| 6 | [modular/modular](https://github.com/modular/modular) | MAX + Mojo 平台 | Mojo | 28,670 | +905 | 3,053 |
| 7 | [obra/superpowers](https://github.com/obra/superpowers) | Agent Skill 框架 | Shell | 275,625 | +789 | 24,642 |
| 8 | [cursor/plugins](https://github.com/cursor/plugins) | Cursor 插件规范 | TypeScript | 4,377 | +391 | 366 |
| 9 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Agent harness 框架 | JavaScript | 241,767 | +348 | 36,652 |
| 10 | [PostHog/posthog](https://github.com/PostHog/posthog) | AI 可观测 + 分析 | Python | 38,274 | +334 | 3,232 |
| 11 | [apache/maka](https://github.com/apache/maka) | Apache 本地 AI Agent | TypeScript | 1,997 | +141 | 240 |
| 12 | [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 多智能体自治工作流 | TypeScript | 68,624 | +140 | 8,241 |
| 13 | [microsoft/TypeScript](https://github.com/microsoft/TypeScript) | TypeScript 原地 Go 重写 | Go | 110,369 | +65 | 13,740 |
| 14 | [TryGhost/Ghost](https://github.com/TryGhost/Ghost) | 独立发布平台 | JavaScript | 54,863 | +32 | 11,903 |
| 15 | [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf) | Google Protobuf | C++ | 71,760 | +4 | 16,236 |

---

## 重点项目点评

### 🥇 [mattpocock/skills](https://github.com/mattpocock/skills) — 今日榜首，+3,368⭐

**"我个人的 .agents 目录"竟然成了一个 22 万星的仓库。**

TypeScript 布道者 Matt Pocock 把自己在 Claude Code / Cursor 中日常使用的 Skills（脚本、系统提示、agent 指南、README 模板）打包公开，标题即价值——"Skills for Real Engineers"。截至今天单日新增 3,368 颗星，说明"agent skill 分享"已经从概念阶段进入"我要抄一份"的实操阶段。

这个仓库的爆发也再次印证近两周 HN/Reddit 的共识：**当 LLM 已经足够强，工程师的差异化不再是"会用哪个模型"，而是"我的私人 workflow 目录里存了什么"**。Skills 相当于 2005 年的 dotfiles、2015 年的 dockerfile ——每个人都会有一份，但公开的价值是范式教育而非直接复用。

与 #7 `obra/superpowers` 组合来看，Agent Skill 生态已经形成清晰分层：Superpowers 提供"框架/协议"，个人 skills 仓库负责"内容库"，Cursor Plugins 负责"IDE 分发"。

---

### 🥈 [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) — +1,372⭐

**Rust + Local-first + 抵制官方臃肿——2026 年最好卖的组合。**

Logitech Options+ 因为频繁 Bug、后台常驻、账号绑定和体积（>500MB）被极客社区骂了两年。中国开发者 AprilNEA 用 Rust 重写了一个原生、本地优先、无账号绑定的替代品——支持所有主流 MX/Craft 系列外设，安装包不到 15MB。

它爆红的原因不完全是技术，更是情绪：这是继 `oh-my-posh` → `Zed` → `Ghostty` → `Warp` 之后又一次"用 Rust 把厂商官方软件重写一遍"的社区叙事。当 `MoneyPrinterTurbo` 靠 AI 快速做视频、`google-timeline-visualizer` 靠可视化个人数据登顶时，本项目代表的是另一条线——**"取回自己设备的控制权"**。

---

### 🥉 [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) — +1,187⭐

**AI 视频工厂化，已经是 GitHub 上"暗黑刚需"的常青树。**

MoneyPrinterTurbo 是从 2024 年就开始崛起的国产项目，围绕"输入关键词/主题 → 自动生成脚本 → TTS + 字幕 + 素材拼接 → 输出短视频"这条流水线不断迭代。今天再度进入前 3，说明进入 2026 年下半年，**中小商家/自媒体对"零人力短视频"的需求依然强劲**——特别是在 TikTok、YouTube Shorts 的算法红利仍在的市场。

这类项目往往被主流媒体嫌弃"低质量内容工厂"，但从生态角度看它极具指标意义：它揭示了 GPT-5.6 Luna 免费化 + 便宜 TTS + 中国 CDN 素材库这三条曲线交汇后的经济学——单条视频生产成本已经跌破 0.1 美元。这是"AI-first UGC 平台"下一波变量的原材料。

---

### 🎨 [cursor/plugins](https://github.com/cursor/plugins) — +391⭐

**Cursor 正式承认自己不再只是"更好的 VS Code"。**

新仓库同时包含插件规范文档、官方插件源码、以及一系列示例（Anthropic Skills、Notion Sync、Sentry Integration 等）。这标志 Cursor 从"AI-first 编辑器"迈向"AI-first 平台" —— 类似 VS Code 于 2016 年发布 extension API 的时刻。

配合近期 Cursor Composer 的自动化能力、Team Rules 的团队级 skill 分发，Cursor 显然想在开发者工具市场建一个 App Store。对独立开发者而言，这是继 VS Code Marketplace、JetBrains Plugin Repo 之后的又一个分发入口，值得押注。

---

### 🧭 [mahlernim/google-timeline-visualizer](https://github.com/mahlernim/google-timeline-visualizer) — +1,040⭐

**一个周末副项目提醒我们：数据主权情绪还没消退。**

作者用 Kotlin/Compose 写了个跨平台桌面 App，把 Google Timeline 导出的 JSON 做成漂亮的年度旅行可视化。功能很小，但踩中了两个当前情绪：（1）Google 逐步收紧 Timeline 数据的访问和保留策略，很多用户第一次意识到"我这些年的位置数据都要靠自己保存"；（2）AI 时代人们再度关心"我这一年活成了什么样"的量化叙事。

这类"小副项目大流量"的模式（Wrapped、Year in Review、Location Story）已经成了 GitHub Trending 上稳定出现的模板，任何本地数据都可以做一遍。

---

## 生态观察

- **Agent Skills 已成显学**：榜单 15 名里，与"Skills / Agent framework / plugin"直接相关的有 5 个（#1, #7, #8, #9, #12），另有 1 个 Apache 官方项目（#11 Maka）跟进。这不再是"某个大厂在推"，而是全社区的标准化竞赛。
- **Local-first 与 Rust 依然强势**：`OpenLogi`（Rust 重写 Logitech）、`Apache Maka`（append-only 本地 workspace）、`Ghost` 稳定在榜，说明"离线可控 + 数据自留"的产品线在 2026 年下半年仍有增量。
- **Cursor vs. VS Code 的平台之争白热化**：官方 `plugins` 仓库上线意味着 Cursor 正式打响生态战。VS Code 需要在"AI Agent 编排" hooks 上追上，否则将失去一批 power user。
- **Mojo 稳步渗透**：`modular/modular` 单日 +905，虽然 Mojo 至今仍无杀手级应用，但榜单的存在性证明"高性能 AI 计算语言"仍是长跑赛道。
- **副项目回潮**：`google-timeline-visualizer` 的成功再次说明"个人数据 + 简单可视化 + 好看的截图"是 GitHub 增长的经典打法，尤其在 X/Twitter 上传播极快。

一句话总结今日的 trending：**"Agents 是生产力，Local-first 是主权，副项目是情绪出口——三种 GitHub 主流叙事，今天一次性都在榜上。"**
