# GitHub Trending 每日速览 · 2026-08-13

## 今日焦点

> **Claude Code 生态爆发 · Agent 工作台 SaaS 化 · 金融/图谱基础模型 · Rust 重写协作套件**
>
> - `cathrynlavery/diagram-design` **今日 +2,951⭐**，29 种编辑级图表模板专门为 Claude Code 优化，登顶榜首。
> - `msitarzewski/agency-agents` **+1,969⭐**，"完整 AI 代理公司"叙事继续吸粉，累积 14 万星。
> - `stablyai/orca` **+1,215⭐**，用自有订阅并行调度 Agent 舰队的 ADE 工具，多 Agent 编排赛道被引爆。
> - `semantica-agi/semantica` **+834⭐**，图谱原生的 AI 记忆基础设施，试图取代 RAG 向量库。
> - `macro-inc/macro` **+325⭐**，用 Rust 重写"团队协同套件"，正面撞 Slack/Notion/Linear。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 29 种编辑级图表模板，为 Claude Code 优化的 HTML+SVG 组件 | HTML | 10,091 | +2,951 | 660 |
| 2 | [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | 完整 AI 代理公司，覆盖前端到社区运营的专家 Agent | Shell | 144,528 | +1,969 | 23,414 |
| 3 | [stablyai/orca](https://github.com/stablyai/orca) | 用自有订阅并行调度 Agent 舰队的 ADE 工具 | TypeScript | 43,796 | +1,215 | 3,053 |
| 4 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 面向 AI 上下文与可问责性的图谱原生基础设施 | Python | 5,661 | +834 | 619 |
| 5 | [paperclipai/paperclip](https://github.com/paperclipai/paperclip) | 面向工作场景的 Agent 管理开源应用 | TypeScript | 77,687 | +573 | 14,296 |
| 6 | [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | NVIDIA NeMo 基础设施项目（新开源） | Rust | 788 | +370 | 82 |
| 7 | [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master) | AI 将文档转为原生 PPT，含形状/过渡/动画 | Python | 45,526 | +364 | 3,713 |
| 8 | [macro-inc/macro](https://github.com/macro-inc/macro) | 邮件/聊天/文档/任务/CRM/通话/Agent 一体化工作台 | Rust | 1,701 | +325 | 218 |
| 9 | [localsend/localsend](https://github.com/localsend/localsend) | 跨平台开源 AirDrop 替代 | Dart | 87,774 | +284 | 4,869 |
| 10 | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) | 面向金融市场语言的基础模型 | Python | 36,927 | +277 | 6,149 |
| 11 | [NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler) | 抖音/小红书/B 站等中文社交平台爬虫 | Python | 61,946 | +236 | 12,121 |
| 12 | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 结合检索与 Agent 能力的开源 RAG 引擎 | Go | 87,517 | +182 | 10,307 |
| 13 | [ZuodaoTech/everyone-can-use-english](https://github.com/ZuodaoTech/everyone-can-use-english) | "人人都能用英语"学习工具 | TypeScript | 36,048 | +53 | 5,027 |
| 14 | [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) | OSINT 威胁情报与攻击面自动化 | Python | 20,327 | +40 | 3,296 |
| 15 | [Lightricks/LTX-2](https://github.com/Lightricks/LTX-2) | LTX-2 音视频生成模型的推理与 LoRA 训练 | Python | 8,689 | +40 | 1,396 |

---

## 重点项目点评

### 🥇 [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) — 今日榜首，+2,951⭐

**为 Claude Code 定制的"编辑级"图表组件，把 Agent 输出的默认审美一次性拉满**

29 种自包含的 HTML + 内联 SVG 图表：金融时间线、组织架构、决策矩阵、对比象限、桑基图、层级树等，全部按"编辑设计"标准（对齐、留白、字重、灰度）预排。核心用法是**在 Claude Code / Cursor / Zed 里通过 skill 直接引用模板**——Agent 生成图表时不再自己"发明"糟糕的 CSS，而是从这 29 个模板里挑一个填数据。

它爆火的原因是精准踩中了当下最痛的一个断层：**LLM 已经能写内容，但图表审美始终糟糕**。作者把设计师能力"打包"成 Claude Code 可读的组件库，等于给所有做 report/deck/dashboard 的 Agent 团队做了"一键升级"。1 天暴涨 2951 星、评论区大量出现"整合到我们的 Claude Skill 里了"，说明这是**Claude Skill 生态里第一个真正跨用户的公共模板**。

对生态的启示很直白：**"Agent + 视觉规范"** 是下一波开源杠杆点。谁能把某类视觉/文档/交互的默认审美打包成一个 skill/prompt-pack，谁就能收获跨用户的复利式增长。

---

### 🥈 [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) — +1,969⭐

**"AI 代理公司"叙事继续吃红利，Shell 脚本封装 20+ 岗位**

仓库把一整个数字营销/开发代理机构（AI Agency）拆成 20+ 专家 Agent：前端、后端、UI/UX、SEO、内容、社区、销售、招聘等。每个岗位对应一个精心写好的 system prompt + Claude Code / Codex 兼容的运行脚本。总星数已到 **14.4 万**，是 GitHub 上"AI Agency 模板类"仓库的绝对头部。

它持续吸粉的原因不是技术含量高，而是**"叙事+可执行性"完美匹配**：小型工作室和 Solo Founder 可以照搬这套架构立刻组个"AI 公司"，甚至已经出现了整合了 Stripe/Slack/Notion 集成的 fork 版本。

底层信号是：**Agent 编排的"内容形态"正在从代码回到 prompt**。过去两年大家追求越来越复杂的框架（LangGraph、CrewAI、AutoGen），但今年最实用的仍然是"一堆精心设计的角色 prompt"——因为模型能力已经足够强，编排的关键不再是 flow，而是**角色定义清晰度**。

---

### 🥉 [stablyai/orca](https://github.com/stablyai/orca) — +1,215⭐

**"Agent Development Environment (ADE)"新赛道被点名**

Orca 是一个专门用来**并行调度 Claude Code / Codex / Gemini 等 Agent 舰队**的工作台，核心特性是"用你自己的订阅"（不代理 API，不吃你的 token 差价）。UI 上一个屏幕可以同时监控 4-8 个 Agent 并行任务，支持任务队列、失败重试、日志聚合、成本预算、branch worktree 隔离。

它的爆发暗示了一个正在成型的品类：**Agent Ops / Agent DevOps**。当每个开发者同时开 4-6 个 Claude Code 实例已经成为常态，"如何管理这些并行 Agent 的生命周期"就是一个新的工具层需求——类似 2018 年 Kubernetes 之于容器。目前竞品还有 Warp（做 Terminal 层）、Sourcegraph Cody Batch、以及不少自建脚本；Orca 用 4.4 万星的存量证明这个方向已经有真实用户。

对 Anthropic/OpenAI 来说也是一个信号：**API 使用形态从"单 session 对话"迁移到"多 session 并行"，价格结构、限流、审计需要重新设计**。

---

### 4️⃣ [semantica-agi/semantica](https://github.com/semantica-agi/semantica) — +834⭐

**图谱原生的 AI 记忆基础设施，把 RAG "向量-only"叙事推向拐点**

semantica 的立场明确：**RAG 用向量索引作为主索引是错的**。它主张用**知识图谱 + 时间线 + 可归责的证据链**作为 AI 系统的一等记忆结构，向量只作为辅助召回。仓库包含 graph store、时间戳查询、citation trace、可视化 UI 等组件，跟 Neo4j / TigerGraph 生态深度整合。

之所以在今天冲上前 5，是因为它踩在两件正在发生的事情上：（1）**Agent 的"记忆一致性"** 已经成为长任务的头号痛点，纯向量库回忆经常张冠李戴；（2）**AI 输出的可问责性（accountability / auditability）** 正在成为合规硬需求（欧盟 AI Act 8 月 2 日已开始执法）。图谱天然带 provenance，这是纯向量库怎么补都补不齐的短板。

**这个仓库值得所有做 Agent Memory 的团队关注**：接下来 12 个月很可能出现"向量 + 图谱 + 时间序列"三合一的混合记忆栈成为标配。

---

### 5️⃣ [macro-inc/macro](https://github.com/macro-inc/macro) — +325⭐

**Rust 从 0 重写的"团队协同一体化工作台"**

macro 把邮件、聊天、文档、任务、Agent、通话、CRM 全塞在同一个 Rust 应用里，本地优先、CRDT 同步，声称"一个 App 替换 Slack + Notion + Linear + Gmail + Hubspot"。虽然当前只有 1701 星，但**今日 +325⭐、fork 数已经 218**，说明工程社区对"用 Rust 写超集应用"这件事仍然有极高兴趣。

值得关注的两个技术点：（1）本地优先 + CRDT 意味着团队协同不再依赖服务端，跟 Automerge、Yjs 生态自然对接；（2）内嵌 Agent 意味着邮件/CRM 的自动化不再需要 Zapier 中间层，Agent 直接在客户端持续运行。

这类"超级 App"过去 3 年频繁失败（都因为在 5 个功能面前都比不上专业竞品），但 Rust + Agent 组合可能带来第一次真实机会：**Agent 弥补了功能深度不足，Rust 弥补了性能与本地体验的短板**。

---

## 生态观察

**主题一：Claude Code 生态开始出现"公共模板层"。** diagram-design 是第一个跨用户、跨团队的 Claude Skill 依赖库，证明 Claude Skill 这个格式的复利效应已经出现。接下来会看到更多细分类目（数据处理、财务表格、法律合同、UI 组件）被同样的方式打包。

**主题二：Agent 工作台（ADE）成为新工具品类。** Orca、Paperclip、Zed Delta、Cursor Composer 都在做类似的事：**并行管理多 Agent 的生命周期**。这是 API 消费形态从"单 session"到"多 session"过渡的必然产物，未来 3-6 个月会有多家创业公司拿 Series A。

**主题三：RAG 向量-only 时代面临范式挑战。** semantica、以及背后 Neo4j、TigerGraph、Zep 的持续发力，暗示图谱记忆将回到 Agent 架构的核心位置。**"混合记忆"** 会是 2027 年 Agent 架构的默认选项。

**主题四：Rust 在协作/生产力工具的地位继续上升。** macro 用 Rust 挑战 Slack/Notion，NVIDIA-NeMo Switchyard 也用 Rust。**"用 Rust 重写高频交互的桌面/协作应用"** 是今年最稳的生态方向之一。

**主题五：金融/垂直基础模型开始有认真的开源作品。** Kronos（金融市场语言基础模型）3.6 万星、活跃 fork——垂直领域的"专有基础模型"叙事继续升温，而且不再只是 fine-tune，而是从头训练。这是"通用 LLM 万能论"的第一批实质性反例。
