# GitHub Trending Daily · 2026-08-10

## 今日焦点

> **自进化 Agent · Skills 生态大扩张 · 法律/股票垂直 Agent · Trace 类系统工具 · 老牌 GUI 继续吸粉**
>
> - `PrimeIntellect-ai/prime-agent` 榜首爆红，+2,319⭐，把"自我改进"的 RLM 塞进编程 Agent
> - `msitarzewski/agency-agents` 单日 +932⭐，14 万星的"完整 AI 代理机构"元框架继续膨胀
> - `addyosmani/agent-skills` 与 `google/skills` 同日上榜，Skills 变成 Agent 生态的通用交易货币
> - `pranshuparmar/witr` +342⭐，把 Linux 溯源做成一条命令，系统工程师久违的新玩具
> - `harveyai/harvey-labs`、`ZhuLinsen/daily_stock_analysis` 分别代表法律与金融的垂直 Agent 涌现

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | 自进化 RLM 编码 Agent | TypeScript | 10,913 | +2,319 | 1,133 |
| 2 | [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | 完整 AI 代理机构（专家 Agent 集） | Shell | 140,594 | +932 | 22,973 |
| 3 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 面向 AI 编码 Agent 的工程 skills 库 | JavaScript | 85,086 | +670 | 9,154 |
| 4 | [google/skills](https://github.com/google/skills) | Google 产品/技术的官方 Agent Skills | Python | 17,192 | +532 | 1,390 |
| 5 | [pranshuparmar/witr](https://github.com/pranshuparmar/witr) | 一条命令追踪进程/端口/容器/文件来源 | Go | 20,588 | +342 | 725 |
| 6 | [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) | 模块化扩散模型 GUI（graph/nodes） | Python | 125,444 | +333 | 14,835 |
| 7 | [goauthentik/authentik](https://github.com/goauthentik/authentik) | 开源身份/认证平台 | Python | 24,244 | +312 | 1,856 |
| 8 | [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis) | LLM 驱动的多市场股票分析系统 | Python | 61,143 | +287 | 51,986 |
| 9 | [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | T3 系列 TypeScript 开发框架 | TypeScript | 17,624 | +208 | 4,006 |
| 10 | [google-deepmind/weathernext](https://github.com/google-deepmind/weathernext) | DeepMind 新一代气象预测模型 | Python | 7,055 | +105 | 936 |
| 11 | [harveyai/harvey-labs](https://github.com/harveyai/harvey-labs) | 法律工作 Agent 能力基准 | Python | 802 | +87 | 174 |
| 12 | [vitali87/code-graph-rag](https://github.com/vitali87/code-graph-rag) | Monorepo 知识图谱 RAG | Python | 2,950 | +59 | 519 |

---

## 重点项目点评

### 🥇 [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) — 今日榜首，+2,319⭐

**"自进化"从论文热词落到可跑代码**

Prime Intellect 端出的 prime-agent 直接冲上今日 GitHub 全站第一，单日新增 2,319 星。它把去中心化训练团队在过去半年里反复验证的 RLM (Reinforcement Learning from Model) 思路，落到编程 Agent 场景：Agent 在完成任务过程中生成 rollout 数据，回流到自研模型进行小步 fine-tune，再进入下一轮任务——一个可以被人观察、可以被回滚的"自改进闭环"。

它踩中了 8 月社区最兴奋的两个点：一是**"Agent 不只是调 API，而应该拥有自己的模型演化路径"**；二是**"闭环反馈的 evaluation 数据不再依赖公开 benchmark"**。在 Meta Muse Code 出问题、Anthropic/OpenAI 都强调 Agent 权限收缩的背景下，Prime Intellect 走的是另一条相反路径——**让 Agent 拥有自己的模型和演化数据集，同时把改进过程透明化。**

值得关注的是 prime-agent 是 TypeScript 而非 Python，配套的 orchestrator 也用 Node，这在"离线批处理 + 云推理"混合的 workflow 里选型上少见但合理——更贴近前端/工具生态。是否能维持这一势头，要看它接下来的 checkpoint 频率和评估协议是否够透明。

---

### 🥈 [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) — +932⭐

**"整个咨询公司塞进一个仓库"式的元框架**

14 万星量级的 agency-agents 继续加速，今日 +932。它做的是"整个 AI 代理机构"：一整套预配置的专家 Agent（产品经理、设计师、开发、市场、法务……）通过 Shell 脚本 + 配置文件编排，用户输入一个业务问题即可产出跨职能协作输出。仓库结构以 Shell 为主，方便与本地 CLI Agent（Claude Code / Cursor / Codex）挂钩。

它火的原因不是"新颖"而是"填空题的默认答案"。今年下半年独立开发者的普遍诉求已经从"给我一个 Agent"变成"给我一整套能协作的 Agent"，而这类元框架恰好允许用户在 5 分钟内跑起一个"迷你 AI 公司"。fork 数已超过 2.29 万，说明 remix 需求非常旺盛。

隐忧是**质量控制**——当仓库以模板 + 提示词为主时，每次上游更新都可能被下游的定制版本落下。历史上类似"awesome-*"型项目最终都会分化出若干品牌化 fork，agency-agents 已经出现这种苗头。

---

### 🥉 [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) & [google/skills](https://github.com/google/skills) — +670 / +532⭐

**Skills 变成 Agent 生态的通用交易货币**

Addy Osmani（Google Chrome DX 负责人）本人维护的 agent-skills 与 google/skills 同一天上榜，这不是巧合。**"Skill"作为 Agent 生态的最小可复用单元**，正在被 Anthropic（Claude Skills）、OpenAI（Custom Actions / Custom GPTs）、Cursor（Rules）、Cline、Continue 等主流 IDE/Agent 客户端不同程度地纳入或兼容。

Addy 的仓库聚焦"生产级工程 skill"：codebase 分析、依赖升级、性能审计、a11y 审查等——**它们的价值不在于替代通用 LLM 能力，而在于打包 domain-specific prompt + 参考文档 + 校验流程，让 Agent 有稳定可复现的产出**。而 google/skills 更聚焦官方场景：Firebase 部署、Chrome DevTools 调试、Angular 项目脚手架等。

两者今天同时爆发意味着 Skills 已经进入"官方 vs. 社区赛马"的下一阶段。开发者选择 Skill 库的核心指标将迅速变成：更新频率、单 Skill 的 CI 通过率、以及是否具备可移植性（跨 Claude / Cursor / Copilot / Codex）。

---

### 🔧 [pranshuparmar/witr](https://github.com/pranshuparmar/witr) — +342⭐

**"lsof + strace 时代结束了"级的 Trace 工具**

witr 用 Go 实现了一条命令追踪任意 Linux 对象（进程/端口/容器/文件）到它的来源。比起传统 `lsof` / `strace` / `bpftrace` 组合，它把"我看到一个奇怪的开销/连接/占用"到"我知道谁在什么时候用什么参数启动了它"的路径压到 30 秒内。

在容器 + K8s + sidecar + eBPF 常态化的今天，systems engineer 常常被"这条监听是谁开的？"这样的问题反复拷打。witr 借助内核最新的 audit/ftrace hooks + 一层 pretty printing，让排障从考古学变成简单查询。20K 星量级仓库能在一天 +342，说明它戳中的痛点是真实的。

它也代表了一波 systems tools 的复兴——`witr`、`atuin`、`glow`、`gum`……这些用 Go/Rust 写的、单一命令、开箱即用的现代 CLI 正在把 Unix 工具箱系统性刷新一遍。

---

### 📊 [google-deepmind/weathernext](https://github.com/google-deepmind/weathernext) — +105⭐

**AI 气象继续挤压传统数值预报**

DeepMind 推出的 weathernext 是 GraphCast / GenCast 之后又一次升级，重点在于 15 天预测的确定性/概率同框、以及消费级 GPU 可推理。它并不是最快涨星的项目，但它的意义在于**AI weather 已经从论文竞速跳到工程可复现阶段**——8 月刚有多家欧洲气象机构公开测试将 AI 模型纳入运行时管道。

对于任何需要预测型工作流的行业（航运、能源、农业、保险），weathernext 类项目的开放，等于把过去只在气象局内部才有的能力推给了 SaaS 玩家。

---

## 生态观察

**主线一：Agent 生态从"能跑"进入"能协作 + 能改自己"。** 今天前 5 名中有 4 个直接跟 Agent 相关（prime-agent 自改进、agency-agents 多 Agent、addyosmani/skills、google/skills）。Agent 的"最小复用单元 = Skill"已成事实标准，"多 Agent 协作"成为独立开发者最常见的产品化路径。

**主线二：垂直 Agent 涌现。** `harveyai/harvey-labs`（法律）和 `ZhuLinsen/daily_stock_analysis`（金融）同日上榜，昨天还没进榜的 domain-specific Agent 基准和 pipeline 项目开始被高频 star。垂直化是 Agent 商业化的现实路径。

**主线三：Systems / CLI tools 复兴。** witr 是今日代表；配合前两周 atuin、mise、rip 的持续热度，说明 Rust/Go 写的现代 CLI 正在系统性取代 Python 早期一代（httpie、httpstat、glances 等）。

**主线四：老牌基础设施持续吸粉。** ComfyUI（+333）、goauthentik（+312）证明"扩散模型 GUI"、"开源 auth"这些 2023 以来的稳赞项目并未减速——它们的用户群随着 AI 与 SaaS 底层需求而持续扩容。
