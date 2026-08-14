# GitHub Trending 每日报告 · 2026-08-15

## 今日焦点

> **Claude Code 生态爆发 · 端侧超小模型 · AI Agent 工作空间大集结**
>
> - `cathrynlavery/diagram-design` 面向 Claude Code 的编辑图表模板，一天 +3,651⭐ 直冲榜首。
> - `cactus-compute/needle` 14MB 端侧基础模型，手机/穿戴/家居/机器人通杀，+661⭐。
> - `semantica-agi/semantica` 面向可问责 AI 的图原生上下文基建，+1,183⭐ 昨夜杀出。
> - `holaboss-ai/holaOS` 开源 all-in-one AI Agent 工作台，+769⭐ 加入"agent OS"混战。
> - `github/spec-kit` 官方"规范驱动开发"工具包续热，累计 128K⭐，今日 +1,147⭐。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 29 种 Claude Code 编辑图表类型，纯 HTML+SVG | HTML | 17,141 | +3,651 | 1,018 |
| 2 | [cactus-compute/needle](https://github.com/cactus-compute/needle) | 14MB 端侧基础模型，覆盖手机/穿戴/家居/机器人 | Python | 5,571 | +661 | 369 |
| 3 | [megadose/holehe](https://github.com/megadose/holehe) | 用邮箱反查 Twitter/IG 等平台注册 | Python | 12,821 | +427 | 1,715 |
| 4 | [macro-inc/macro](https://github.com/macro-inc/macro) | 团队统一工作台：邮件/聊天/文档/任务/Agent/CRM | Rust | 3,008 | +435 | 303 |
| 5 | [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) | 自动化 OSINT 威胁情报与攻击面测绘 | Python | 20,920 | +292 | 3,339 |
| 6 | [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | 面向 AI Agent 的最快自动化浏览器 | JavaScript | 10,326 | +153 | 526 |
| 7 | [holaboss-ai/holaOS](https://github.com/holaboss-ai/holaOS) | 开源 all-in-one AI Agent 工作空间 | TypeScript | 7,251 | +769 | 635 |
| 8 | [github/spec-kit](https://github.com/github/spec-kit) | 规范驱动开发（Spec-Driven Development）工具包 | Python | 128,473 | +1,147 | 11,480 |
| 9 | [lightningpixel/modly](https://github.com/lightningpixel/modly) | 桌面端"图片/Prompt→3D 模型"本地 AI 生成 | TypeScript | 5,901 | +580 | 599 |
| 10 | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 检索+Agent 融合的开源 RAG 引擎 | Go | 88,386 | +474 | 10,381 |
| 11 | [cursor/plugins](https://github.com/cursor/plugins) | Cursor 插件规范与官方插件 | TypeScript | 2,801 | +69 | 227 |
| 12 | [deepseek-ai/awesome-deepseek-agent](https://github.com/deepseek-ai/awesome-deepseek-agent) | DeepSeek 官方 Agent 精选资源与实现 | Markdown | 5,678 | +203 | 689 |
| 13 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 面向可问责 AI 的图原生上下文与身份基建 | Python | 7,493 | +1,183 | 775 |
| 14 | [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) | 开源远程桌面，TeamViewer 替代 | Rust | 120,627 | +182 | 18,466 |
| 15 | [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | 开源 CapCut 剪辑替代 | TypeScript | 83,115 | +238 | 8,228 |

---

## 重点项目点评

### 🥇 [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) — 今日榜首，+3,651⭐

**Claude Code 用户社区第一次自发产出"设计资产库"。**

作者 Cathryn Lavery 是设计师背景，做的这件事非常"垂直"：29 套编辑级别的图表模板，全部是自包含的 HTML + SVG，直接给 Claude Code 当 skill/资产用——用户在编辑器里描述"要一个瀑布流对比图"或者"要一张 org chart"，Claude Code 就会调用这些模板返回可复用的图。首日 3,651 颗星，是 Claude Code 生态自 spec-kit 之后第二个"日新增破 3K"的仓库。

它为什么爆？因为它精准踩中了 Claude Code 用户的最大痛点：**代码生成早已成熟，但生成 "非代码的东西" 仍然靠 prompt 硬拼**。图表、幻灯片、图形化文档在 LLM 输出里最容易走样，一套"标准模板+官方风格"能让 90% 的可视化任务从"抛硬币"变成"选模板+微调"。

同时，它也是 Claude 生态商业模式的一次自然演进：先是 CLI（Claude Code），再是 skills / hooks，接下来一定会是"社区素材市场"——今天的 diagram-design 是雏形，未来六个月会看到 Slides、Report、Landing Page、Icon Set 的一整套"Claude 官方风"资产库。

---

### 🥈 [semantica-agi/semantica](https://github.com/semantica-agi/semantica) — +1,183⭐

**"图原生 + 可问责"，是不是下一代 RAG 的关键词？**

semantica 定位为"图原生的上下文与身份基础设施"——它不做 embedding 相似度这套 v1 RAG，而是把每一份数据、每一次访问、每一条生成结果绑定到一张知识图上，并且每一次 Agent 的写操作都要挂身份和权限（accountable AI）。这解决了当前 RAG 的三个真痛点：**长尾漂移**（同一实体出现在不同 chunk 反复被召回不一致）、**引用无法追溯**（LLM 输出的一段话背后是哪几条源）、**多 Agent 冲突**（Agent A 修改了 KG 中一节点，Agent B 不知道）。

一夜之间 +1,183⭐，动力主要来自两派：企业侧 AI 平台工程师被"合规级 provenance"打动，学术侧 knowledge-graph 老玩家看到"终于有人把 Neo4j 生态和 LLM Agent 缝起来了"。项目仍在早期（v0.4），但架构思路是当前市场缺失的一环——Palantir 的私有版本、微软 GraphRAG 的开源版本，semantica 想同时对标。

---

### 🥉 [cactus-compute/needle](https://github.com/cactus-compute/needle) — +661⭐

**14MB "基础模型" 上端侧，是不是新的 SLM 甜点位？**

needle 是一个仅 14MB 的基础模型（不到一张微信表情包大小），目标是在**手机/穿戴/智能家居/机器人**上直接跑通用推理，不依赖云。作者定义它为"foundation model"而不是"tiny task model"——同一模型能覆盖 wake-word 识别、文本槽位填充、简单意图分类、小规模对话，全部在 <100mW 功耗、<100ms latency 下完成。

它的技术底子来自 cactus 团队之前发布的 MoM (Mixture of Micromodels) 论文——先用一个 1.4B 教师蒸馏出 8 个 5MB 专家，再用一个 4MB 路由器动态选专家。**这个方向的意义**在于：当苹果 A18 / 高通 X Elite 已经能跑 8B 云模型的时候，硬件厂商更需要的是"完全免云端、完全免网络、完全免账户"的端侧智能——needle 就是这个赛道最激进的开源尝试之一，社区反应也可以理解。

---

### 🏅 [holaboss-ai/holaOS](https://github.com/holaboss-ai/holaOS) — +769⭐

**"AI Agent 操作系统"这个赛道从概念走进产品化。**

holaOS 把自己定位为"AI Agent 的工作空间"：一个跨工具、跨应用、跨浏览器的统一容器，Agent 可以在里面查邮件、开日历、跑爬虫、写 Notion、连 Slack。同类项目今年至少已经有六七个（AutoGen Studio、CrewAI Enterprise、Dify、n8n AI Kit……），holaOS 突围点在于**"开源 + all-in-one + TypeScript 全栈"**——用户不用像用 LangGraph 那样一层一层拼中间件，装完开箱即用。

有意思的是它和 `macro-inc/macro`（今日第 4，+435⭐）撞车了——macro 走 Rust 后端 + 团队协作，holaOS 走 TypeScript + 个人+小团队。这个赛道 6-12 个月内会出现"团队协作 OS"和"个人 Agent OS"的分叉，就像 2015 年的 Slack vs Notion。今天两个项目同榜，是分叉的起点。

---

### 🎯 [github/spec-kit](https://github.com/github/spec-kit) — +1,147⭐（累计 128K⭐）

**GitHub 官方 SDD 工具包持续膨胀，正在成为"AI 时代的 Rails"。**

spec-kit 已经不新了，但一天 +1,147 颗星、总星 128K 稳居头部，说明它在深度改变开发流程。Spec-Driven Development 的核心是把 "prompt-driven coding" 从艺术变成工程：让开发者先写规范 (`spec.md`)、再让 Copilot / Claude / Cursor / Aider 依据规范生成实现，同时把规范作为"永久性事实源" (source of truth) 跟着代码一起演化。

它的持续走强意味着两件事：一是 GitHub 正在把 Spec-Driven 变成官方推荐流程（对手 Cursor 也开始跟进），二是它逐步显性化"prompt as code"的仓库结构——`spec/`、`ADR/`、`skills/`、`AGENTS.md` 会成为下一代 repo 的标配子目录。对独立开发者的实际价值：`spec-kit init` 后一天，就能让一个大模型 agent 独立完成 60-70% 的 CRUD 类工作，交付质量比"直接对话生成"高出一个身位。

---

## 生态观察

**今天的 GitHub Trending 有三条主线：**

- **"Claude / Cursor 周边工业化"**：diagram-design、spec-kit、cursor/plugins、awesome-deepseek-agent 四个项目同日上榜——这已经不是"Claude 生态"或"Cursor 生态"，而是"AI Coding IDE 通用生态"。资产、规范、插件三件套第一次同天成规模，这是"AI Coding 编辑器"从工具走向平台的信号。
- **"端侧 SLM + 硬件下沉"**：needle 14MB 的 "foundation model on edge" 是本月最激进的一次端侧尝试；modly 桌面端本地生 3D、ego-lite 极速浏览器都在把 AI 计算从云端拉回本地。宏观看，"云侧超大模型 + 端侧超小模型"两极化格局在开源社区已成共识。
- **"AI Agent OS 大混战"**：holaOS、macro、semantica、ragflow 四个项目今天各自代表一个流派（个人 workspace、团队 workspace、accountable graph、RAG+agent 融合）。半年内会有两三个项目跑出来做成"AI 时代的 VS Code"，剩下大部分会被吞并或消失——现在正是最热闹但也最凶险的窗口。
