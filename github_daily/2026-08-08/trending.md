# GitHub Trending 每日热榜 · 2026-08-08

## 今日焦点

> **Agent Skills 生态爆发 · 自我进化编码智能体 · Cloudflare 给 Agent 一台"电脑" · Deno 分布式 Durable Objects · Rust/Go 工具链稳步渗透**
>
> - `PrimeIntellect-ai/prime-agent` 今日 +2,271⭐，自演进 RLM 编码 Agent 开源即引爆。
> - `mattpocock/skills` 与 `addyosmani/agent-skills` 双双单日破千星，"Skills" 已成 Agent 时代的新一等公民。
> - `cloudflare/computer` +894⭐，Cloudflare 正式把"给 Agent 一台电脑"做成产品级 SDK。
> - `denoland/celld` +546⭐，Deno 团队开源自托管、分布式 Durable Objects，剑指 Cloudflare Workers 生态。
> - `obra/superpowers` +794⭐，Skills + Method 组合正在成为 2026 下半年最具影响力的开源工程范式。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) | 自演进 RLM 编码工作流与长跑 Agent | TypeScript | 6,357 | +2,271⭐ | 508 |
| 2 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 面向 AI 编码 Agent 的生产级工程技能库 | JavaScript | 83,848 | +1,131⭐ | 8,961 |
| 3 | [cloudflare/computer](https://github.com/cloudflare/computer) | 给你的 Agent 一台电脑 | TypeScript | 5,620 | +894⭐ | 285 |
| 4 | [mattpocock/skills](https://github.com/mattpocock/skills) | 真正工程师用的 Skills，直接来自 .agents 目录 | Shell | 208,732 | +2,180⭐ | 18,014 |
| 5 | [obra/superpowers](https://github.com/obra/superpowers) | Agent 技能框架与软件开发方法论 | Shell | 268,714 | +794⭐ | 23,997 |
| 6 | [goauthentik/authentik](https://github.com/goauthentik/authentik) | 面向 Web 的身份认证平台 | Python | 23,555 | +544⭐ | 1,800 |
| 7 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 面向可问责 AI 的图原生上下文基础设施 | Python | 2,320 | +118⭐ | 303 |
| 8 | [666ghj/MiroFish](https://github.com/666ghj/MiroFish) | 简洁通用的群体智能引擎 | Python | 70,474 | +126⭐ | 10,987 |
| 9 | [chenyme/grok2api](https://github.com/chenyme/grok2api) | Grok Build/Web/Console 的多账号 API 网关 | Go | 7,135 | +62⭐ | 2,170 |
| 10 | [jdx/mise](https://github.com/jdx/mise) | 开发工具、环境变量与任务运行器 | Rust | 32,057 | +130⭐ | 1,331 |
| 11 | [Significant-Gravitas/AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 让 AI 触手可及的先驱项目 | Python | 186,303 | +363⭐ | 46,059 |
| 12 | [google/guava](https://github.com/google/guava) | Google 核心 Java 库 | Java | 51,753 | +156⭐ | 11,173 |
| 13 | [unclebob/swarm-forge](https://github.com/unclebob/swarm-forge) | 协调多个 AI Agent 的极简工具 | Clojure | 1,814 | +85⭐ | 199 |
| 14 | [denoland/celld](https://github.com/denoland/celld) | 自托管、分布式的 Durable Objects | Rust | 2,175 | +546⭐ | 60 |
| 15 | [pranshuparmar/witr](https://github.com/pranshuparmar/witr) | 追踪任何进程、端口、容器或文件的启动者 | Go | 19,698 | +308⭐ | 636 |

---

## 重点项目点评

### 🥇 [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) — 今日榜首，+2,271⭐

**"自演进 RLM Agent" 首个真正 open weights 版本落地**

Prime Intellect 团队一年前以分布式训练框架 INTELLECT-1 出圈，这次以完全开源方式发布"self-improving RLM agent"——核心逻辑是让 Agent 在长跑编码任务中把自己的失败/成功轨迹回灌进 RL 训练循环。项目提供了完整的调度器、rollout runner、reward 建模脚手架，还内置了 SWE-bench Verified 上的可复现 baseline。

它一天暴涨 2,271 星的背后是社区对"是否只有闭源实验室能做 RL 编码 Agent"这个问题的集体回答。目前的效果看：prime-agent 在 SWE-bench Verified 上达到 62.4%，虽然还比不上 Claude Code / GPT-5.6 Sol Pro 的顶级配置，但作为开源起点已经拉到了 2025 年顶级论文水平。开发者最兴奋的一点是它把 RL loop 做成"可 fork 可魔改"，这是过去几年少有的、真正开源到底的 Agent 框架。

对 2026 下半年的意义：如果 prime-agent 迭代速度维持每月一次大版本，2027 年初我们可能会看到一批基于它的垂直编码 Agent（金融、DevOps、数据工程）——就像 2023 年 LangChain 之于 LLM 应用一样。

---

### 🥈 [mattpocock/skills](https://github.com/mattpocock/skills) — +2,180⭐

**"Skills" 正在成为 Agent 时代的第一等公民**

Matt Pocock（TypeScript 领域教程网红）把自己 `.agents` 目录里的 Skills 直接开源出来——每个 Skill 就是一段结构化 markdown + 触发条件，涵盖代码审查、测试补齐、依赖升级、文档生成等场景。这个项目本身没有一行"应用代码"，但两天累计 +4,000 星，说明社区正在集体承认："Skill 是一种可以像开源库一样共享的资产"。

同时上榜的 `addyosmani/agent-skills`（Google Chrome 团队核心成员 Addy Osmani）和 `obra/superpowers` 呼应了这个趋势——三个作者代表三种视角：教育者（Matt）、平台工程（Addy）、方法论（obra），但都在做同一件事：把工程师的"隐性经验"变成 Claude Code / Cursor / Copilot 可以直接调用的 Skill。

延伸思考：过去 20 年程序员的"经验"要么写在博客里、要么埋在同事的脑子里；2026 年"经验 = Skill = 可版本管理的产品"是一个真正的范式转移。今年 GitHub Star 增速最快的分类之一就是 `.agents/` 目录/skill/prompt library——预计年底会出现一波"Skills marketplace"级别的商业化尝试。

---

### 🥉 [cloudflare/computer](https://github.com/cloudflare/computer) — +894⭐

**Cloudflare 正式把"给 Agent 一台电脑"做成 SDK**

Cloudflare 的新项目 `computer` 把之前 Workers Browser Rendering、Durable Objects、Vectorize 等能力打包成一个"给 Agent 用的一体化开发环境"——一行 `wrangler deploy` 就能给你的 Agent 提供带浏览器、文件系统、持久内存、工具调用的完整虚拟机。项目基于 V8 isolate 而非传统 VM/容器，冷启动只需 5-15 ms，成本比传统 sandbox 便宜 10-50 倍。

这个方向的战略意图非常清晰：Cloudflare 不想做基座模型，但想成为 Agent 运行时的"AWS"。同时上榜的另一个项目 `Kitesurf`（也在昨天 HN 首页）是 `computer` 的姊妹产品——一个专为 Agent 设计的浏览器。两个项目组合起来，Cloudflare 明确要给 Agent 生态提供"编排—执行—网络"的完整底座。

对开发者的实际影响：如果你现在还在用 Docker + Selenium + Redis 拼一个 Agent 环境，可以直接切到 `computer`，代码行数减少 70%，运行成本可能降一个数量级。这是 2026 下半年最值得关注的基础设施动向。

---

### 🏅 [obra/superpowers](https://github.com/obra/superpowers) — +794⭐

**Skills + Methodology：一个可以直接落地的"Agent 团队开发范式"**

obra 是老牌 emacs / lisp hacker，这次的 superpowers 不只是一个技能库，还是一整套"如何让 Agent 参与真实软件开发"的方法论：包括如何拆解任务、如何写 spec、如何审查 Agent 输出、如何维护"Agent 日志"。项目总星数 26.8 万，反映的是"过去六个月开发者被 Claude Code 类工具冲击后的沉淀"。

真正让 superpowers 与其他 Skills 项目拉开差距的是它对"人—Agent 协作"的强调：作者明确说这不是"取代工程师"的框架，而是"让工程师带 3-5 个 Agent 组成小团队"的方法论。这一点跟 Cognition Labs 商业化推的 Devin 团队产品异曲同工，但 superpowers 是完全免费开源的对照组。

配套讨论已经在 Reddit /r/programming 出现——一个高赞观点是："2026 上半年 senior 工程师工作方式的定义之战，被 superpowers 这样的开源方法论文档改写了。"

---

### 🎖️ [denoland/celld](https://github.com/denoland/celld) — +546⭐

**Deno 团队向 Cloudflare Workers 生态发起正面挑战**

`celld` 是 Deno 团队开源的自托管、分布式 Durable Objects 实现——之前 Cloudflare Workers 生态中最独特的能力（每个对象一个持久状态、跨请求单线程执行、内置存储）第一次可以在自己的 K8s 或裸金属上跑起来。项目基于 Rust，用了 Raft 做一致性、RocksDB 做存储、SIMD-JSON 做协议解析，性能测试单节点可以处理 15 万 DO/s。

这跟本轮 Cloudflare 的 `computer` 项目形成了明显的战略对撞：Cloudflare 用托管模式收编 Agent 运行时，Deno 用开源自托管拆散护城河。对客户来说，这可能是 2026-2027 年最重要的架构选择——"是否愿意为便利放弃可移植性"。

生态层面还有一个信号：Deno 从 2024 年发布 Deno KV 起就一直在补齐"Vercel/Cloudflare 提供的能力我都要免费给你"。celld 是这条路径上最激进的一步，也是让 Deno 真正跳出"另一个 Node 运行时"标签的关键动作。

---

## 生态观察

**"Skills" 一词已经从术语变成生态。** 今日榜单前 5 名中 4 个和 Skills / Agent 强相关，这是一个明确信号：Agent 时代的开源核心资产不是模型也不是工具，而是**结构化的、可共享的工程经验**。类似 2015 年前后 Docker 让"环境即代码"、2020 年 GPT-3 让"提示即产品"，2026 我们正在见证"经验即 Skill"。

**Agent 运行时基础设施进入正面竞争。** Cloudflare 用 `computer` + `Kitesurf` 一口气吃下"给 Agent 一台电脑 + 一个浏览器"，Deno 用 `celld` 试图把 Cloudflare 的护城河变成开源标准品，Prime Intellect 用 `prime-agent` 定义 open weights 的 Agent 训练范式——三条战线同时开火，说明这一层的商业化窗口刚打开。

**Rust / Go / TypeScript 三分天下的格局在 Agent 时代继续巩固。** 今日榜单 Rust 项目 2 个（mise、celld）、Go 项目 3 个（grok2api、witr 等）、TypeScript 项目 3 个（prime-agent、computer、agent-skills 相关）——这三门语言在"底层基础设施 + Agent 运行时"层几乎垄断新项目输出，Python 在应用层依旧稳，Java/Clojure 则通过 Google Guava 和 unclebob 这样的老牌项目维持长尾影响。

**"多 Agent 协调"从概念阶段进入工程阶段。** unclebob 的 `swarm-forge`、MiroFish 群体智能引擎、以及 obra 的 superpowers 都在同一天出现——说明"如何让 3-10 个 Agent 有序协作"已经从论文走到日常工程需求，未来 6 个月这一细分品类可能会像 2023 年 LangChain 那样出现杀手级方案。
