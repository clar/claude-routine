# GitHub Trending 每日热榜 · 2026-08-09

## 今日焦点

> **Agent Skills 生态井喷 · Coding Agent 自我进化 · Trading Agent 破 10 万星 · 数据主权/Durable Objects · 独立浏览器仍在坚持**
>
> - `PrimeIntellect-ai/prime-agent` **+2,483⭐**：自进化 RLM Coding Agent 单日暴涨，冲进榜首。
> - `mattpocock/skills` **+1,354⭐**：个人 agent skills 库累计 20.9 万星，"skill 作为可复用工程资产"格局成型。
> - `addyosmani/agent-skills` **+778⭐**：Google DevRel Addy Osmani 的生产级 agent skills，产业侧背书。
> - `google/skills` **+481⭐**：Google 官方 agent 能力仓库，进一步坐实"skills 是 Agent 时代新原语"。
> - `denoland/celld` **+432⭐**：Deno 团队开源自托管的分布式 Durable Objects，数据主权叙事的又一战场。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | 自进化 RLM Coding Agent | TypeScript | 8,760 | +2,483 | 807 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 个人级 Agent Skills 集合 | Shell | 209,941 | +1,354 | 18,138 |
| 3 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 生产级 Agent 工程 skills | JavaScript | 84,503 | +778 | 9,075 |
| 4 | [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) | 中国大中小学教材汇编 | Roff | 77,892 | +591 | 17,627 |
| 5 | [google/skills](https://github.com/google/skills) | Google 官方 Agent 能力仓库 | Python | 16,696 | +481 | 1,354 |
| 6 | [goauthentik/authentik](https://github.com/goauthentik/authentik) | 开源统一认证平台 | Python | 23,952 | +467 | 1,836 |
| 7 | [denoland/celld](https://github.com/denoland/celld) | 自托管分布式 Durable Objects | Rust | 2,533 | +432 | 71 |
| 8 | [bannedbook/fanqiang](https://github.com/bannedbook/fanqiang) | 科学上网工具汇编 | Kotlin | 49,856 | +161 | 8,252 |
| 9 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 多 Agent LLM 金融交易框架 | Python | 96,433 | +126 | 18,647 |
| 10 | [google/guava](https://github.com/google/guava) | Google Java 核心库 | Java | 51,841 | +93 | 11,180 |
| 11 | [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird) | 完全独立自研浏览器 | C++ | 64,967 | +79 | 3,104 |
| 12 | [litu54/DevOps-Interview-Guide](https://github.com/litu54/DevOps-Interview-Guide) | DevOps 面试题库 | Markdown | 688 | +59 | 879 |

---

## 重点项目点评

### 🥇 [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) — 今日榜首，+2,483⭐

**"self-improving RLM agent"这个 buzzword 终于有了可跑通的开源实现**

Prime Intellect 是过去一年最活跃的去中心化 AI 训练团队之一。今天登顶的 prime-agent 不是又一个 wrapper——它把 **RLM（Reinforcement Learning from Model）** 与 Coding Agent 直接拼在一起：agent 在长任务里执行→评估→回写训练数据→自更新，形成"自进化循环"。Repo 现有 8760 星，其中今天暴增 2483 星，是标准的"社区当日发现现象级项目"信号。

它踩中了 2026 年最热的两个痛点：
1. **长任务可靠性**：普通 tool-use agent 在 20 step 后就迷路，RLM 通过在线微调把成功率往上拉；
2. **可复现的自主进化**：过去 self-improve 主要在闭源公司里跑，Prime Intellect 直接开源了完整训练管线。

这对开源 Agent 生态是里程碑事件——预计接下来两周会有大量 fork 和衍生框架。

---

### 🥈 [mattpocock/skills](https://github.com/mattpocock/skills) — +1,354⭐

**Agent Skills 已经从"目录"变成"资产"**

Matt Pocock 的个人 skills 仓库累计 20.9 万星，今日再增 1354。它其实是他自己给 Claude/Codex/Cursor 等 Agent 用的**技能库**：一整套 markdown-based prompt + shell tools + workflow 模板，覆盖 TypeScript 教学、React 重构、Prisma 调试等。有意思的是，同榜前 10 出现了 **3 个不同风格的 skills 仓库**（Matt 个人的、Addy 的生产级、Google 官方的），意味着"skill 作为 agent 可复用资产"已经形成分层生态。

它本质上是**新一代 dotfiles**——过去开发者靠 dotfiles 定义环境，现在 Agent 靠 skills 定义"我能干什么"。对开源社区的含义是：**skills 会成为 GitHub 上第一批被大规模 fork/star 的"非代码"资产**，跟 awesome-lists 类似但更实用。

---

### 🥉 [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) — +778⭐

**Google DevRel 亲自站台，坐实"agent skills"是 Google 新一代战略叙事**

Addy Osmani（Google Chrome 团队工程负责人、前端布道师）的 agent-skills 仓库标题直接写着 "Production-grade engineering skills for AI coding agents"。这不是随手 side project——同一天 `google/skills` 也进入 top 5，标志着 **Google 正在系统地把 agent skills 作为一层平台叙事推向开发者社区**。

对照 Anthropic 的 Skills、OpenAI 的 GPTs Actions、Cursor 的 Rules，2026 年 H2 的共识正在收敛：**每家 Agent 平台都需要一个"可移植技能层"**，而 Google 押注 GitHub-native 的 markdown skills 生态。谁的 skill 格式最终成为事实标准，将决定下一代 Agent 供应商的话语权。

---

### 🌐 No.4 · [denoland/celld](https://github.com/denoland/celld) — +432⭐

**Deno 团队开源自托管 Durable Objects，数据主权浪潮进入 stateful 层**

Cloudflare 的 Durable Objects 是 edge stateful 的样板，但一直只能跑在 Cloudflare 上。今天 Deno 团队开源的 **celld** 是"自托管、分布式 Durable Objects"，把这套模型带到任何 Kubernetes / bare metal 环境里。Rust 实现，2500 星只花了 24 小时。

结合今天 HN 上的 Fastmail 欧盟数据区、AI Act 强制执行，可以看到一条清晰的主线：**基础设施层正在被"数据主权 + 自托管"重新定义**。celld 是 stateful 层的关键补齐——过去自托管方案对 stateful 应用总是妥协很多，Deno 的这一步会让 EU/亚洲开发者更愿意脱离美西厂商。

---

### 📈 No.5 · [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) — +126⭐（累计破 96k⭐）

**多 Agent LLM 交易框架逼近 10 万星，量化圈开始"标配化"使用**

TradingAgents 在今年年初就火过一轮，今天新增 126 星把总数推到 96,433，很快会破 10 万——这是**开源金融 Agent 里第一个进入十万星俱乐部的项目**。它用多 Agent 分工模拟真实投研团队（研究员、策略师、风控、执行），每个 Agent 都是独立 LLM 会话，最后由 orchestrator 汇总。

它的持续走热说明两件事：
1. **量化圈已经开始把 LLM Agent 当作真实生产工具**，而不是玩具；
2. **多 Agent 分工范式**在具备清晰 role separation 的领域（交易、法务、医学诊断）里比"单 super-agent"效果更稳定。

TradingAgents 的仓库结构也在被大量后续项目当作参考模板——包括今天的 prime-agent 里都能看到影子。

---

## 生态观察

今日 GitHub Trending 的三条主线：

1. **Agent Skills = 新原语**：Top 10 里挤进 3 个 skills 仓库（mattpocock、addyosmani、google/skills），说明"skill 作为可复用资产"已经从概念进入基础设施阶段。可以类比过去的 **npm packages / helm charts / vscode extensions**，未来 12 个月会诞生"skills marketplace"级别的项目。

2. **Self-improving Coding Agent 进入开源阶段**：prime-agent 单日 +2,483 是一个明确信号，社区终于有了可复现的 RLM Agent 训练管线。预计接下来 30 天会出现大量衍生实现，Anthropic/OpenAI 的闭源自进化 agent 会面临直接对比。

3. **数据主权浪潮渗透到 stateful 层**：celld 的出现补齐了自托管场景的最后一块拼图。结合 goauthentik 依然稳定登榜，可以看到"open-source self-hosted stack"是 2026 年最稳定的一条增长曲线。

其他信号：Ladybird 独立浏览器保持稳定日新增（79⭐），说明"不依赖 Chromium/Blink"的诉求持续存在但没有爆炸增长；ChinaTextbook 稳定进入 top 5，反映开源教材资源的长期需求；DevOps 面试题继续是热门，说明就业市场对基础设施岗位的关注度不减。
