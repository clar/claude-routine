# GitHub Trending 每日热榜 · 2026-08-26

## 今日焦点

> **GPT-Image2 提示词工程 · Claude 插件生态爆发 · Codex Rust agent · 本地优先 AI 二脑 · Karpathy 单文件 CLAUDE.md**
>
> - `freestylefly/awesome-gpt-image-2` +1,698⭐ — GPT-Image2 逆向工程库以"Prompt as Code"形式爆红榜首，530+ 案例把图像生成推向工业化模板战。
> - `anthropics/claude-plugins-community` +350⭐ + `claude-plugins-official` +47⭐ — Claude 官方 + 社区插件市场同框上榜，Anthropic 生态从 IDE 扩到工作流插件层。
> - `openai/codex` +1,183⭐ — OpenAI 官方 Rust 终端 agent 持续吸星，与 Claude Code 争夺 CLI 编码 agent 心智。
> - `apache/maka` +538⭐ — Apache Incubating 项目主打"local-first agent workspace"，本地优先 agent 框架有了顶级基金会背书。
> - `multica-ai/andrej-karpathy-skills` +828⭐ — 单文件 `CLAUDE.md` 就能提升 Claude Code 行为，Karpathy 效应把"配置最简主义"推上 20 万⭐。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | GPT-Image2 工业级提示词引擎 530+ 案例 | JavaScript | 17,540 | +1,698⭐ | 1,814 |
| 2 | [openai/codex](https://github.com/openai/codex) | OpenAI 官方终端编码 agent (Rust) | Rust | 118,060 | +1,183⭐ | 17,994 |
| 3 | [basecamp/omarchy](https://github.com/basecamp/omarchy) | DHH 主张的美化 Arch Linux 桌面套件 | Shell | 31,177 | +1,080⭐ | 3,171 |
| 4 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 让 AI agent 像"最懒的资深工程师"一样思考 | JavaScript | 110,916 | +944⭐ | 6,097 |
| 5 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | 单文件 `CLAUDE.md` 提升 Claude Code 行为 | Markdown | 207,158 | +828⭐ | 21,140 |
| 6 | [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) | Obsidian + Claude Code 自组织二脑 | Python | 12,670 | +810⭐ | 1,380 |
| 7 | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | 从零学 AI 工程的实战合集 | Python | 48,900 | +572⭐ | 8,559 |
| 8 | [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | 本地优先个人 AI 超智能 + 记忆层 | Rust | 37,736 | +541⭐ | 3,730 |
| 9 | [apache/maka](https://github.com/apache/maka) | Apache 孵化本地优先 agent 工作空间 | TypeScript | 3,297 | +538⭐ | 326 |
| 10 | [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) | Claude Cowork/Code 社区插件市场 | Python | 1,715 | +350⭐ | 176 |
| 11 | [marin-community/marin](https://github.com/marin-community/marin) | 开源基础模型研究框架 | Python | 2,076 | +277⭐ | 190 |
| 12 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 多 agent LLM 金融交易框架 | Python | 100,179 | +191⭐ | 19,346 |
| 13 | [asciimoo/hister](https://github.com/asciimoo/hister) | 自建个人搜索引擎 | Go | 2,747 | +166⭐ | 122 |
| 14 | [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | 100+ AI Agents / RAG 应用合集 | Python | 134,202 | +161⭐ | 19,740 |
| 15 | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Anthropic 官方 Claude 插件目录 | Python | 34,063 | +47⭐ | 3,869 |

---

## 重点项目点评

### 🥇 [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) — 今日榜首，+1,698⭐

**"Prompt as Code"把图像生成推入工业化提示词模板战**

这个仓库把 GPT-Image2 的 530+ 生产级案例做成结构化模板库：每个案例包含 prompt 原文、生成结果、参数注释、逆向拆解。它爆红的深层原因是**图像模型已经从"能不能生成"过渡到"能不能可控生成"**——GPT-Image2 相对上一代最大的差异是可复现性和风格一致性显著提升，这让"提示词模板化"第一次真正有工程价值。

社区反馈里最集中的评论是"节省了 3 个月摸索时间"——过去团队做 marketing 素材、UI 设计稿、电商产品图，往往要花几周调 prompt，现在可以直接从模板库 fork 修改。这也预示未来 12 个月**"图像模型的差异化会更依赖 prompt 工程库而非模型自身**"——就像 stable-diffusion-webui 之于 SD 生态一样。中文注释也让这个仓库在中英双语社区都获得关注。

---

### 🥈 [openai/codex](https://github.com/openai/codex) — +1,183⭐

**OpenAI 官方 Rust CLI agent 持续吸星，与 Claude Code 正面竞争**

Codex 已经稳定在 GitHub 编码 agent 类目的第二名（第一是 Claude Code 生态相关项目），今日 +1,183⭐ 得益于近期 GPT-5.3-Codex 模型 + Codex CLI 联动升级：新版本原生支持长时任务、多 sub-agent、审批策略，且 Rust 二进制启动时间只有 Node 版 CLI 的 1/5。仓库总星突破 11.8 万，Fork 1.8 万，说明它已经进入"每个 AI 工程师都要 clone 一次"的量级。

这一波关注度上升还有 OpenAI 8/26 宣布 o3 全面下线、GPT-5.6 Sol API 降价 20% 的连带效应——**降价 + Codex CLI 免费本地版**的组合，正在把"用 GPT 系模型做终端编码"的门槛压到最低。Anthropic 阵营的对策也很明显：Claude Code 官方插件目录 + 社区插件目录今日双双上榜，靠"插件市场"做差异化。

---

### 🥉 [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) — +828⭐

**一个 `CLAUDE.md` 文件涨到 20 万⭐：Karpathy 效应 + 配置极简主义**

这个仓库只包含**一个 markdown 文件**——按 Karpathy 风格提炼的 Claude Code 行为准则（写代码尽量简短、注释谨慎、拒绝过度抽象等），却已经达到 20.7 万⭐ + 2.1 万 Fork。今日 +828⭐ 主要来自 Karpathy 本人在 X 上再次转发导致的二次流量。

它的意义超出"一个配置模板"：它证明**Claude Code 生态已经形成"最佳实践社区"层**——不再只是"模型 + IDE"，而是叠加了"prompt 层、skill 层、CLAUDE.md 层"三层可复用组件。搭配今日同期上榜的 `AgriciDaniel/claude-obsidian`（Claude + Obsidian 二脑）和 Anthropic 的两个插件目录，可以清楚看到 Anthropic 的开发者生态战略在"从工具走向平台"的关键节点。

---

### 🧬 [apache/maka](https://github.com/apache/maka) — +538⭐

**Apache Incubating 收编 local-first agent，开源基金会加持第一次到位**

`apache/maka` 是 Apache Software Foundation 孵化的**本地优先 AI agent 工作空间**——用户数据、模型选择、工作流全在本机运行，可选接入云端 API 但默认离线。它今日爆火有两个原因：（1）Apache 品牌背书让企业 IT 部门第一次能名正言顺地把"local agent"写进采购清单；（2）它选择 TypeScript + 插件式架构，能兼容 llama.cpp / Ollama / MLX 等主流本地推理后端。

结合 Meta Muse Glimmer 30B、Apple M5 Ultra 512GB 统一内存等"本地跑大模型"新硬件条件，`apache/maka` 是**"local-first agent 平台"**这条赛道的第一个基金会级项目。可以预期未来 12 个月会出现更多"某某 + local agent"垂直组合。

---

### 🔌 [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) — +350⭐

**Anthropic 一口气公开两个插件市场：从 IDE 扩到"工作流平台"**

Claude Cowork 与 Claude Code 的社区插件市场今日正式对外开放，同期上榜的还有 Anthropic 官方管理的 `claude-plugins-official`。两个仓库的分工是：官方目录做"高质量精选"、社区目录做"任何人可提交"。这是 Anthropic 生态战略的第二段拐点——**从"CLI 编码工具"扩张到"工作流平台"**。

对比 OpenAI 生态的 ChatGPT Work / GPT Store，Anthropic 采取的路线更去中心化：插件是本地代码而非托管服务，用户完全控制运行环境。这套模式的杠杆点在于"能不能吸引第三方开发者贡献"——今日社区库 +350⭐、176 fork 的起步速度还算温和，但配合 Karpathy 效应和 skill 层生态，未来 3 个月可能出现类似 VS Code Marketplace 爆发式增长的窗口期。

---

## 生态观察

**今日主线是 "AI agent 平台化 + 本地优先运行"两条同时抬头：**

- **Claude 生态爆发**：今日 15 名中有 4 个直接与 Claude 相关（`claude-plugins-community`、`claude-plugins-official`、`claude-obsidian`、`karpathy-skills`），加上间接受益的 `ponytail`（AI agent 行为规范），Anthropic 的开发者社区正在形成"IDE + 插件 + skill + 二脑"多层堆栈。
- **OpenAI vs. Anthropic 编码 agent 对垒**：Codex 单日 +1,183⭐ 是继 GPT-5.3-Codex 发布后的持续放量，两大厂商在"终端 agent"这个战场几乎完全对称——都是 Rust CLI、都做长任务、都支持本地文件读写、都在推自己的模型。
- **本地优先浪潮**：`apache/maka`、`tinyhumansai/openhuman`、`asciimoo/hister`（自建搜索）、`AgriciDaniel/claude-obsidian`（本地知识库）四个方向的仓库同日上榜，配合硬件侧 Apple M5 Ultra 与 Meta Muse Glimmer 30B，"本地跑 AI"正在从极客爱好变成新的产品品类。
- **图像模型的第二曲线**：GPT-Image2 提示词库拿下今日榜首，说明"图像模型 + 结构化 prompt 库"正在成为独立生产赛道，可能孵化"图像 prompt SaaS"新品类。

**明日重点跟踪**：Codex 与 Claude Code 是否会出现互相开源核心组件的动作、`apache/maka` 是否会宣布合作硬件方（很可能是 Apple 或 Framework）、GPT-Image2 提示词模板是否会催生 SaaS 化 fork。
