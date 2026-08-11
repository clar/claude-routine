# GitHub Trending 日报 · 2026-08-12

## 今日焦点

> **Agent skills 生态爆发 · 图 RAG 卷土重来 · 编排层重构 · 教育与创作垂类**
>
> - `msitarzewski/agency-agents` 拿下今日榜首（+971⭐），"专家智能体商店"叙事继续升温
> - `anthropics/skills` 单日 +468⭐，官方 skills 仓库长期霸榜说明生态标准正被巩固
> - `semantica-agi/semantica` 与 `vitali87/code-graph-rag` 双双上榜，图 RAG 与代码图数据库回到聚光灯
> - `stablyai/orca` 多设备并行 Agent 编排（+881⭐）——"多 agent + 多机器"的开发环境形态开始被真正试用
> - `HKUDS/DeepTutor`（+829⭐）与 `calesthio/OpenMontage`（+436⭐）代表 agent 垂类进入教育、内容制作赛道

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | 面向多样任务的专业 AI 专家智能体集合 | Shell | 143,091 | +971 | 23,261 |
| 2 | [stablyai/orca](https://github.com/stablyai/orca) | 跨设备并行编码 agent 的 ADE 编排环境 | TypeScript | 42,699 | +881 | 2,978 |
| 3 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 面向上下文感知 AI 的图基础设施 | Python | 4,827 | +884 | 522 |
| 4 | [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor) | 终身个性化辅导平台 | Python | 34,662 | +829 | 4,416 |
| 5 | [paperclipai/paperclip](https://github.com/paperclipai/paperclip) | 工作场所智能体管理开源应用 | TypeScript | 77,117 | +743 | 14,246 |
| 6 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 为 AI 编码智能体准备的工程能力包 | JavaScript | 86,195 | +571 | 9,263 |
| 7 | [anthropics/skills](https://github.com/anthropics/skills) | Anthropic 官方 agent skills 仓库 | Python | 168,082 | +468 | 20,028 |
| 8 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 开源 agent 化视频制作系统（700+ skills） | Python | 47,282 | +436 | 5,900 |
| 9 | [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) | 多语言代码库的知识图 RAG 系统 | Python | 3,790 | +339 | 560 |
| 10 | [jaywcjlove/awesome-mac](https://github.com/jaywcjlove/awesome-mac) | 高质量 macOS 软件精选清单 | Swift | 110,440 | +334 | 8,413 |
| 11 | [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | LLM 驱动的多市场股票分析 | Python | 62,087 | +317 | 52,418 |
| 12 | [3b1b/manim](https://github.com/3b1b/manim) | 数学解释视频的动画框架 | Python | 90,140 | +246 | 7,478 |
| 13 | [huggingface/transformers](https://github.com/huggingface/transformers) | 跨模态 SOTA 模型统一框架 | Python | 163,771 | +69 | 34,200 |
| 14 | [harveyai/harvey-labs](https://github.com/harveyai/harvey-labs) | 评估 agent 法律能力的基准 | Python | 1,067 | +24 | 195 |
| 15 | [nvm-sh/nvm](https://github.com/nvm-sh/nvm) | POSIX 兼容的 Node.js 版本管理器 | Shell | 94,471 | +18 | 10,353 |

---

## 重点项目点评

### 🥇 [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) — 今日榜首，+971⭐

**"专家智能体应用商店"从概念走向社区共识**

这个仓库把 100+ 个针对具体职能（法律、财务、产品、招聘、代码审查……）的 agent 提示词、工作流、工具接线打包成 Shell/JSON 模块，可以直接 clone 后挂到 Claude Code、Cursor、Aider 等 CLI 上运行。今天单日 +971 星、目标是"每个岗位都有一个可复用 agent"，本质上是把过去分散在博客与 gist 里的 prompt 工程做成了带版本控制的软件包。

它能跳到榜首有两个背景：其一，Anthropic 的官方 [`anthropics/skills`](https://github.com/anthropics/skills) 上周更新了 skills 加载协议，第三方 skills 开始有了统一入口；其二，Claude Code、Cursor、Codex CLI 的用户越来越多，工程师需要"开箱即用的 agent 套件"而不是自己写系统 prompt。这个 repo 拿下今日热度，说明"agent skills 商店"已经从个人项目升级为社区共识。

---

### 🥈 [stablyai/orca](https://github.com/stablyai/orca) — +881⭐

**多机器并行 agent 的"新型 IDE"雏形**

Orca 定位为 ADE（Agent Development Environment），核心能力是把多个 coding agent 分派到多台开发机 / 沙箱执行，然后集中回收结果与冲突解决。它不是又一个"聊天式 IDE"，而是尝试解决 2026 上半年真正的痛点——**当团队 daily 会跑 20+ 个并行 agent 任务，谁来当调度员？**

TypeScript 实现意味着它可以嵌进 VS Code / Cursor 生态，也可以脱离 IDE 独立跑。加上今天 Meta 开源 Muse Glimmer 让本地 agent 具备实用可能，Orca 这类多机器编排层是必然的下一步：单机 agent 是玩具，编排才是生产力。今日新增 881 星、fork 数不到 3000，说明它还处在早期扩散阶段，值得年内继续跟踪。

---

### 🥉 [semantica-agi/semantica](https://github.com/semantica-agi/semantica) — +884⭐

**图 RAG 的第二次爆发**

一年前 GraphRAG 曾短暂火过一波，随后被向量数据库压过。Semantica 这次带回来的思路不同：它不是"再造一个图数据库"，而是提供一层图基础设施来记录 agent 长期上下文、任务依赖、工具调用轨迹——本质是给 agent 装记忆网络。README 强调"context-aware"，配合 [`vitali87/code-graph-rag`](https://github.com/vitali87/code-graph-rag) 也进入今日榜，这暗示**代码/上下文图**正成为 agent memory 的默认底座。

背景是 2026 中期学界对 "agent memory" 的关注度飙升（如 mem0 的 State of Agent Memory 2026 报告），大家意识到向量近邻搜索无法胜任多跳/时序型查询。图结构 + LLM 抽取正在补足这块。今天两个图 RAG 项目同时爆红不是巧合，是问题域被承认后的自然扩散。

---

### 4️⃣ [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor) — +829⭐

**教育 agent 从"AI 家教 demo"走向平台**

港大数据科学实验室（HKUDS）已经在这条线做了两三年积累。DeepTutor 主打"lifelong personalized tutoring"——即长期跟踪一个学习者的错题、思维习惯，用 agent 持续调整教学策略。它把课程规划、题目生成、答疑对话、错题分析等 agent 组合成流水线，34k 星本身也说明社区对 AI 教育的期待远高于其他行业垂类。

值得注意的是它没有走"接 GPT API 快速上线"的取巧路线，而是把开源模型 fine-tune 与图状记忆结合，可以看作 semantica / code-graph-rag 系列在教育垂直落地的最真实案例。教育赛道 2026 下半年的一个信号：单点工具（写作助手、错题批改）正在被 agent 平台整合。

---

### 5️⃣ [paperclipai/paperclip](https://github.com/paperclipai/paperclip) — +743⭐

**"公司内部 agent 管理台"开始独立成品类**

Paperclip 定位是企业内部 agent 管理平台：谁能启动哪些 agent、调用哪些工具、消耗多少 token、结果如何审计。它把过去散落在 Zapier / n8n / 内部 IT 工单里的东西升级为"agent-first"的管理界面。77k 星与 TS 技术栈都指向它更接近 SaaS 产品的形态，而非底层框架。

这类项目跟 Anthropic 的 Skills 生态、Orca 的开发者编排面向不同用户——**Paperclip 是给 IT / RevOps 用的**。随着企业开始批量部署 agent，"发号施令 + 审计追责"层的市场需求会明显放大，今天 +743 星是一个先行信号。

---

## 生态观察

**主线只有一条：Agent skills / orchestration / memory 三件套。** 今日 top 5 中有 4 个直接命中 agent 生态；semantica 与 code-graph-rag 又把 memory 层搬回议程。可以说 2026 8 月的 GitHub trending 已经进入"agent 专业分工"阶段——skills 层做能力打包、orchestrator 层做多 agent 调度、memory 层做上下文与记忆——三条腿在被独立填充。

**旧宠仍在，但热度洗牌。** `huggingface/transformers` 只涨 69 星，`manim` 涨 246 星，`awesome-mac` 涨 334 星——传统"通用工具型"仓库继续输血却难再霸榜。这类项目的存在感被 agent 项目挤到腰部。

**垂直 agent 出圈。** DeepTutor（教育）、OpenMontage（视频制作）、harvey-labs（法律基准），加上榜边缘常见的 medical / finance / sales agents，说明"通用 agent"叙事之后的下一波是"垂直 agent + 领域评测"。观察点是这些垂类项目能不能自己撑起独立开发者社区，而不只是套壳 Claude Code。

**冷门但有信号：** `harveyai/harvey-labs` 只 1067 星，但作为法律 agent 基准第一次出现在 trending，说明"评估"这层还是空白，谁能做出被引用的评测标准，谁就能拿定行业话语权。
