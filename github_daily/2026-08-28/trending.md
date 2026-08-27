# GitHub Trending 每日速览 · 2026-08-28

## 今日焦点

> **AI Agent 生产化 · Claude 生态爆发 · 卫星可视化黑马 · Skills 复用范式 · AI 教育长期热**
>
> - `tt-a1i/archify` +4,260⭐ 单日榜首，AI 时代重新造轮子的架构图工具
> - `freestylefly/awesome-gpt-image-2` +2,093⭐ "Prompt as Code" 提示词工程化仓库继续吸金
> - `bilawalsidhu/gods-eye-view` +1,984⭐ 浏览器里的间谍卫星模拟器，硬核可视化爆款
> - `anthropics/claude-plugins-official` +290⭐ Anthropic 官方插件目录持续填充
> - `K-Dense-AI/scientific-agent-skills` +494⭐ 163 个可复用"科学家 agent 技能"打包发布

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 开源架构图/工作流图工具 | JavaScript | 22,953 | +4,260⭐ | 1,483 |
| 2 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | Prompt-as-Code 530+ 提示词库 | JavaScript | 22,955 | +2,093⭐ | 2,283 |
| 3 | [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | 浏览器版间谍卫星模拟器，真实数据 | JavaScript | 7,808 | +1,984⭐ | 1,782 |
| 4 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | "让 AI agent 像最懒的资深工程师" | JavaScript | 113,968 | +1,610⭐ | 6,234 |
| 5 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 首个开源 agentic 视频制作系统 | Python | 52,298 | +1,284⭐ | 6,552 |
| 6 | [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) | Obsidian + Claude 自组织第二大脑 | Python | 13,961 | +631⭐ | 1,423 |
| 7 | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | AI 工程基础教育资源 | Python | 50,134 | +547⭐ | 8,714 |
| 8 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 163 个已验证科研 agent 技能 | Python | 35,277 | +494⭐ | 3,394 |
| 9 | [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) | 前端设计+AI 工作流的 skills 集 | CSS | 11,303 | +413⭐ | 1,411 |
| 10 | [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines) | 教 AI 编码 agent 写现代 Go | Go | 2,050 | +314⭐ | 63 |
| 11 | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Anthropic 官方 Claude Code 插件目录 | Python | 34,664 | +290⭐ | 3,911 |
| 12 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 跨会话持久化上下文 for AI agent | JavaScript | 92,246 | +260⭐ | 8,108 |
| 13 | [marin-community/marin](https://github.com/marin-community/marin) | 开源基础模型开发框架 | Python | 2,685 | +255⭐ | 229 |
| 14 | [zedeus/nitter](https://github.com/zedeus/nitter) | Twitter 替代前端 | Nim | 13,846 | +63⭐ | 1,120 |
| 15 | [google/googletest](https://github.com/google/googletest) | Google 测试与 Mock 框架 | C++ | 39,029 | +4⭐ | 10,865 |

---

## 重点项目点评

### 🥇 [tt-a1i/archify](https://github.com/tt-a1i/archify) — 今日榜首，+4,260⭐

**AI 时代重新发明架构图工具，Mermaid / draw.io 面临挑战**

archify 主打"agent-native"架构图和工作流图工具——重点不是"再造 draw.io"，而是**内置 AI 生成 + AI 修改 + 版本化的完整闭环**。用户可以直接描述"帮我画一个 K8s + Redis + LangGraph 的微服务架构"，工具生成后还能继续用自然语言迭代（"把 Redis 换成 Postgres，加一条鉴权层"）。

它今天的爆发不是偶然：**2026 年架构图工具的赛道刚刚被 AI 重写**——过去两年 Mermaid 因为可版本化 + 文本友好占据程序员市场，draw.io 靠拖拽保留了产品经理市场。archify 用 AI 交互统一了这两个流量入口，且开源。评论区里最常出现的评价是"我把 draw.io 卸载了"。

从 Star / Fork 比（22.9k / 1.5k）来看，这是一个**"技术传播型"而不是"参与型"**的项目——大家看了很惊艳但还没到 fork 改造的深度，接下来 3 个月能否形成 plugin 生态是判断它是否能坐稳的关键。

---

### 🥈 [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) — +2,093⭐

**"Prompt as Code" 从 meme 变成主流工程范式**

这个仓库以 530+ 高质量 prompt 示例覆盖图像生成、修改、风格迁移、批量处理等场景，重点是**每一条 prompt 都可以像代码一样被 diff / review / 复用 / 版本化**。它的火爆反映的是一个更大的趋势：**多模态模型 API 化之后，prompt 工程从"艺术"过渡到"工程"**，需要专业的模板库、命名规范和测试机制。

值得注意的是仓库结构：不再是 markdown 罗列，而是按"输入 → 期望输出 → 模型版本 → 已知失败模式"四段式组织。这种"prompt 即测试用例"的组织方式很可能会被更多 awesome 类仓库继承。

如果你在做多模态产品或图像自动化工作流，这类高质量 prompt 库比调 API 参数更有价值——**它是把"能用"变成"稳定"的关键中间层**。

---

### 🥉 [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) — +1,984⭐

**硬核可视化在 GitHub 上永远吃香**

这是本周最"炫技"的项目：一个基于浏览器的间谍卫星模拟器，**数据是真实的**——包括 TLE 轨道参数、地面站覆盖范围、当前可见性、以及模拟的传感器分辨率。作者 Bilawal Sidhu 是前 Google 工程师，专门做地球空间可视化。

它爆发的原因不是"我需要一个卫星模拟器"，而是**"我居然可以在浏览器里跑这个"**——GitHub 上纯前端 + 真实航天数据 + 3D 可视化的项目一直是 Star 磁铁（想想 chartjs、three.js 的历史）。fork/star 比也说明大家更多是被震撼到收藏，实际魔改的人少。

这类项目对个人开发者的启示是：**"叙事 + 可视化 + 一个别人做不到的技术组合"是 GitHub 冷启动的最优公式**，比"再写一个 CLI 工具"回报高 10 倍。

---

### 🔧 No.4 · [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) — +494⭐

**"Skills 复用"正在成为 AI agent 生态的标准分发单元**

这个仓库把 163 个已验证的"科研 agent skill"打包发布——覆盖分子对接、序列比对、文献检索、实验设计、数据清洗等任务。每一个 skill 都是**独立可加载、有测试用例、有性能基线**的模块，可直接接入 Claude Code / OpenAI Agents / 自研 agent 框架。

这与前几天 Anthropic 官方推的 claude-plugins-official 是同一个方向：**Prompt 工程 → Tool 定义 → Skill 打包 → Marketplace** 的分发链路正在完整化。Skills 之于 agent，相当于 npm packages 之于 Node.js。

对个人开发者来说，这个趋势带来两件事：一是**"造轮子"的成本变低**——你的 agent 可以拉几十个 skill 拼装；二是**"发轮子"的分发机会出现**——一个好的 skill 可能像十年前的 npm 包一样迅速被大量项目 depend on。

---

### 🎬 No.5 · [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) — +1,284⭐

**首个开源"agentic 视频制作系统"，抢在 Adobe 之前定标准**

OpenMontage 的定位很直接：**从脚本或素材出发，让多个 agent 协作完成视频剪辑、字幕、配音、镜头选择、音效匹配**。它不是"AI 生成视频"（那是 Sora / WAN 的赛道），而是"AI 剪辑+组装真实素材"，这在企业内容营销、YouTuber 工作流、教育视频领域是刚需。

52.3k star 说明这个赛道积压了大量需求。Adobe Premiere / DaVinci 在 AI 集成上一直很保守，OpenMontage 抢占的是**"工作流原生 AI"**的位置。它的模块化设计（每个 agent 独立可替换）让公司可以只用它的编排层，把模型换成自家私有模型。

如果这个项目能形成活跃的 plugin 生态，2027 年很可能出现"开源 OpenMontage + 商业 SaaS 服务层"的组合，直接对标 Adobe 订阅制。

---

## 生态观察

**主线一：AI Agent 的分发单元正在标准化。** 今天上榜的 claude-plugins-official、scientific-agent-skills、garden-skills、claude-mem 都指向同一件事：**Skills / Plugins / 持久化上下文**正在成为 agent 生态的基础层。这意味着未来 6-12 个月会出现类似 npm/PyPI 规模的"agent skill marketplace"，谁能占住分发通道谁就有巨大话语权。

**主线二：Claude Code 生态的活跃度已超过其他 IDE-agent。** 今天 top 15 里有 4 个直接与 Claude 相关（官方插件、Obsidian 集成、持久化上下文、Claude Code plugin）。这不是随机现象——**Anthropic 通过 Claude Code + Skills + Plugins 的组合，成功把"IDE 场景"打造成了自己的生态护城河**，比"卖 API"更难被替代。

**主线三：图像 / 视频 / 图表工具进入 AI 原生重构期。** archify（图表）、awesome-gpt-image-2（图像）、OpenMontage（视频）三条头部项目共同表明：**传统"内容创作工具"赛道正在被 AI 重新洗牌**，开源+AI-native 的组合具备 2-3 年内颠覆商业工具的势能。

**主线四："AI 教 AI"这个元层次开始出现。** JetBrains/go-modern-guidelines 明确写"Help AI coding agents write modern Go"——**语言/框架文档正在开始按 AI 的阅读习惯而不是人类的阅读习惯组织**。未来的 API 文档、SDK 手册、编码规范，都会有独立的 "for-agent" 版本。这是个新赛道，也是新岗位。

---

*报告日期：2026-08-28（Asia/Shanghai）*
