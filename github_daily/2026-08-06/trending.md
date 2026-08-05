# GitHub Trending 每日热榜 · 2026-08-06

## 今日焦点

> **Agent 生态爆炸 · 团队记忆共享 · PDF/文档 pipelining · DeepSeek 原生工具链 · 长跑 AI 系统**
>
> - `TencentCloud/TencentDB-Agent-Memory` 一日 +1,891⭐，**团队级 AI 记忆总线**正式登上主榜。
> - `firecrawl/pdf-inspector` 一日 +1,583⭐，Rust 重写的 PDF 智能提取器，用于 RAG 上游的 ETL。
> - `obra/superpowers` 冲入前十，agent skills 框架 267K⭐，已经是"给 Agent 装能力"的事实标准。
> - `cloudflare/computer` +796⭐，官方给 Agent 一个"电脑"运行环境，Computer-Use 类项目再度加热。
> - `huangruiteng/loopx` 从零冲上 2K⭐，"long-running agent teams + 目标持久化 + 配额感知"三件套。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | Agent 团队级记忆中枢 | TypeScript | 15,006 | +1,891 | 1,366 |
| 2 | [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) | Rust 版 PDF 智能解析 | Rust | 11,366 | +1,583 | 755 |
| 3 | [obra/superpowers](https://github.com/obra/superpowers) | Agent 技能框架方法论 | Shell | 267,268 | +931 | 23,878 |
| 4 | [lyogavin/airllm](https://github.com/lyogavin/airllm) | 4GB 显存跑 70B | Jupyter | 29,040 | +833 | 3,119 |
| 5 | [cloudflare/computer](https://github.com/cloudflare/computer) | 给 Agent 一个电脑 | TypeScript | 2,753 | +796 | 126 |
| 6 | [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | 终端里的 DeepSeek 编码 Agent | Go | 31,548 | +747 | 2,027 |
| 7 | [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | utility-first CSS 框架 | TypeScript | 96,829 | +408 | 5,546 |
| 8 | [uber/ADR](https://github.com/uber/ADR) | 企业 Agent 安全 & 可观测 | Python | 1,013 | +354 | 85 |
| 9 | [huangruiteng/loopx](https://github.com/huangruiteng/loopx) | 长跑 Agent 状态内核 | Python | 2,063 | +327 | 160 |
| 10 | [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | 系统设计面试宝典 | Python | 361,480 | +304 | 57,646 |
| 11 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 生产级 Agent 编码技能 | JavaScript | 81,954 | +203 | 8,819 |
| 12 | [vercel/next.js](https://github.com/vercel/next.js) | React 框架 | JavaScript | 141,531 | +144 | 31,679 |
| 13 | [roboflow/supervision](https://github.com/roboflow/supervision) | 通用 CV 工具集 | Python | 48,892 | +132 | 4,617 |

---

## 重点项目点评

### 🥇 [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) — 今日榜首，+1,891⭐

**腾讯云出手，做"AI Agent 的团队记忆总线"**

腾讯云开源的 TencentDB-Agent-Memory 把过去零散的 vector store / long-term memory / conversation history / code snippets 用一个统一的记忆图谱串起来——它不是给单个 Agent 用的 memory 插件，而是"整个组织跨 Agent、跨会话共享的记忆资产层"。文档里最核心的一块是 team-level namespace + memory RBAC + retention policy，明显是奔着"企业内多 Agent 部署"去的。TS 实现、TypeORM 兼容，接入 Claude Agent SDK / LangGraph / AutoGen 的三份 adapter 直接摆在 README 里。

这条项目今天冲榜的信号意义比其数字更重要：过去半年 Agent 圈的争夺焦点一直在 "planner / tool router / loop scheduler"，但真正让 Agent 团队规模化的瓶颈已经切到"共享记忆 + 权限 + 审计"。TencentDB-Agent-Memory 是国内厂第一家把这一层做成基础设施拿出来的，配套的还有一份《Agent Memory 分级白皮书》。

对比同榜的 `addyosmani/agent-skills`（Agent 技能库）+ `obra/superpowers`（Agent 技能框架方法论）+ `uber/ADR`（Agent 安全）三个项目，今天的 GitHub 热榜清晰地画出了"AI Agent 企业化"的四层轮廓：技能、记忆、安全、编排。

---

### 🥈 [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) — +1,583⭐

**Firecrawl 团队用 Rust 重写 PDF 解析，直接冲进 ETL 主战场**

Firecrawl 一贯以"能爬敢爬"著称，这次开源 pdf-inspector 是他们在 crawl → clean → index 全链路里补上的一块砖。README 的重点在于"分类 + 智能文本提取"：内嵌一组分类器判断"这一页是目录 / 表格 / 图注 / 正文"，再走对应的提取策略；对表格用 layout parsing + OCR fallback；对论文类 PDF 特别做了 reference 分离。Rust 实现意味着 CI-friendly、低内存、可以放进 serverless 函数。

RAG 落地的 pain point 从"selection of embedding model"到"selection of chunker"再到"pre-ETL 文档理解"逐层下沉，pdf-inspector 恰好切中这一波。Firecrawl 一天涨 1,583⭐、fork 上升到 755，说明有大量 pipeline 团队在评估把它当作 Unstructured / PDFPlumber 的替代——Rust + intelligent classification 的组合正在把这个赛道重写。

---

### 🥉 [obra/superpowers](https://github.com/obra/superpowers) — +931⭐

**Agent Skills 事实标准，star 数已经到 267K**

Jesse Vincent (Anthropic 的 obra) 的 superpowers 项目在今天再进一步，累计 267K⭐、Fork 近 24K，成为"Agent Skills as a spec"的事实标准。README 长期在讲的一句话是——skills 不是 prompt、不是 tool、不是 memory，而是"一组可组合的工作方法论"，配套的目录结构、命名约定和 progressive disclosure 已经被大量 Claude Code 用户和第三方模仿。

今天再上榜可能与它最新一次 v0.9 refactor 有关：把 SKILL.md 的加载语义从"启发式"改成"显式声明 triggers"，并给每一个 skill 加了 evals / measurement。这一步让 skills 从"社区约定"往"可测量、可迭代"迈了一大步。呼应了 `addyosmani/agent-skills` 和 `TencentDB-Agent-Memory` 的同期热度，反映出社区对"agent 能力的组织方式"从模型层进入方法论层。

---

### 🏅 [cloudflare/computer](https://github.com/cloudflare/computer) — +796⭐

**Cloudflare 把"给 Agent 一台电脑"做成了产品**

cloudflare/computer 是 Cloudflare 官方 repo，主打给 Agent 一个隔离的 headless Linux + 浏览器 + 文件系统环境，一行 API 即可 `computer.new()`，返回 SSH / VNC / DevTools 接口，直接对接 Anthropic Computer Use / OpenAI Computer Use。项目上线两天涨到 2.7K⭐，主要因为把过去人肉搭 Playwright + Docker + noVNC 的活儿封成了一个 edge-friendly 的托管环境。

这是 Cloudflare "Agent-native platform" 战略里的最新一块：过去半年他们已经推出了 Agents SDK、Workflows、Browser Rendering、Durable Objects for Agents，如今 computer 补上了"Agent 需要 GUI 操作时该跑在哪"这一环。对开发者而言，最直接的价值是"计费不再按 EC2 小时算，按 Agent 会话 tick 算"——把 Computer Use 的成本压到了 serverless 曲线上。

---

### 🎖️ [huangruiteng/loopx](https://github.com/huangruiteng/loopx) — +327⭐

**"长跑 Agent"三件套：goal 持久化 + quota 感知 + auto-wake**

loopx 是一个专注于"长跑 Agent team"的状态内核，把三件事做成一等公民：goal 持久化（Agent 不再从零 replan）、quota-aware scheduling（token / API 预算前置调度）、auto-wake（Agent 睡眠后能在事件到达时自动被唤醒并继续任务）。今天从冷启动直接冲到榜单第 9，说明社区对"多 Agent 长期运行"这一场景的痛点已经被聚焦。

跟同榜的 `superpowers`（横向能力）、`Agent-Memory`（纵向存储）互补：loopx 把"时间"这一维加了进来，Agent 不再只是一次对话或一次任务，而是可以持续几周甚至几月的持续工作单元。可以预见这一类"long-running orchestrator"在下半年会更多；类似 Prime Agent（HN 同日上榜）也在解同一个问题。

---

## 生态观察

**"Agent 企业化"闭环成型。** 今天前 5 的项目里有 4 个直接围绕 Agent 主题：`Agent-Memory`（记忆）、`superpowers`（技能）、`cloudflare/computer`（运行环境）、`loopx`（长时间调度），加上 `uber/ADR`（安全）+ `agent-skills`（能力库），构成了 2026 下半年"AI Agent 企业化"的完整拓扑：记忆 · 技能 · 运行时 · 编排 · 安全 · 审计。

**Rust + Go 在数据/工具链侧持续增长。** `firecrawl/pdf-inspector` (Rust)、`DeepSeek-Reasonix` (Go) 两个新工具直冲榜首附近，说明"底层数据处理和 Agent 运行时"更需要系统语言，Python 优势正在被压回"实验和 notebook"。

**大厂开源节奏加快，纯个人爆款正在减少。** 腾讯云、Cloudflare、Uber 今日同框上榜，与年初"社区小项目独领风骚"的画面对比明显——AI Agent 已经进入需要基础设施背书的阶段。

**经典项目仍在增长。** `system-design-primer`、`next.js`、`tailwindcss` 单日仍有几百⭐入账，说明 GitHub 的长尾效应对老牌头部依然强，社区在 AI 大潮里依然给"工程与前端基础"留了流量。
