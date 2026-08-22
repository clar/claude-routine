# GitHub Trending 每日 · 2026-08-23

## 今日焦点

> **Agent Skills 生态井喷 · Claude Code 家族继续霸榜 · OpenAI Codex 冲上榜首 · TypeScript 迁 Go 加速 · Local-first 硬件工具反攻大厂 SaaS**
>
> - `openai/codex` +1,978⭐ 冲榜首，terminal 编程 Agent 再点火。
> - `mattpocock/skills` +2,684⭐ 今日星数最高，"Skills for Real Engineers"点燃全社区。
> - `obra/superpowers` +592⭐、`multica-ai/andrej-karpathy-skills` +379⭐ 双双上榜，Karpathy 系 CLAUDE.md 派系形成。
> - `AprilNEA/OpenLogi` +959⭐，Rust 写的 local-first Logi Options+ 替代品激起硬件党共鸣。
> - `microsoft/TypeScript` 主语言正式切 Go，第 10 万 star 后进入新维护范式。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [openai/codex](https://github.com/openai/codex) | 轻量级终端编程 Agent | Rust | 113,223 | +1,978 | 17,351 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 工程师版 Skills 集合 | Shell | 231,912 | +2,684 | 19,797 |
| 3 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Claude Code/Codex Agent 优化框架 | JavaScript | 242,153 | +428 | 36,699 |
| 4 | [obra/superpowers](https://github.com/obra/superpowers) | 通用 Agent Skill + 软件方法论 | Shell | 276,160 | +592 | 24,696 |
| 5 | [Wei-Shaw/sub2api](https://github.com/Wei-Shaw/sub2api) | Claude/OpenAI/Gemini/Grok 订阅转 API | Go | 38,773 | +264 | 8,037 |
| 6 | [makeplane/plane](https://github.com/makeplane/plane) | 开源 Jira/Linear/Monday 替代 | TypeScript | 57,197 | +263 | 5,440 |
| 7 | [n8n-io/n8n](https://github.com/n8n-io/n8n) | 带 AI 的自动化编排平台 | TypeScript | 201,790 | +202 | 60,300 |
| 8 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | Anthropic 官方终端 Agent | Python | 142,506 | +141 | 22,838 |
| 9 | [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) | Local-first Logi Options+ 替代 | Rust | 13,859 | +959 | 370 |
| 10 | [modular/modular](https://github.com/modular/modular) | Modular Platform（MAX & Mojo） | Mojo | 28,829 | +395 | 3,065 |
| 11 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | Karpathy 风格 CLAUDE.md | — | 205,270 | +379 | 21,006 |
| 12 | [mahlernim/google-timeline-visualizer](https://github.com/mahlernim/google-timeline-visualizer) | 可视化 Google 位置历史 | Kotlin | 2,553 | +441 | 299 |
| 13 | [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev) | SaaS/PaaS/IaaS 免费额度大全 | HTML | 133,871 | +915 | 14,026 |
| 14 | [microsoft/TypeScript](https://github.com/microsoft/TypeScript) | TypeScript 编译器 | Go | 110,527 | +163 | 13,746 |
| 15 | [cursor/plugins](https://github.com/cursor/plugins) | Cursor 插件规范与官方插件 | TypeScript | 4,647 | +286 | 380 |

---

## 重点项目点评

### 🥇 [mattpocock/skills](https://github.com/mattpocock/skills) — +2,684⭐

**"Real Engineers"版 Skills：Matt Pocock 把 TypeScript 培训方法论移植到 Agent Skill**

Matt Pocock（TypeScript 世界最活跃的教育家之一）把自己私人 `.agents/` 目录里的 Skills 全部开源，形成一个覆盖 code review、schema 设计、测试策略、性能调优等真实工程场景的 Skill 集合。这些不是玩具级 prompt，而是把 Matt 过去几年在 Total TypeScript 里教的原则**格式化成 Claude Skill 的机读结构**。

一个人的私域产品化能拿到今日榜首级的 +2,684 星，只可能是因为它踩中了一个新的社区共识：**"Skill = 高质量 SOP 的可执行封装"**。Matt 的仓库和 obra/superpowers、Karpathy skills 三足并立，标志着 Agent Skill 生态从"实验/娱乐"进入"专业教育者出品"阶段。

---

### 🥈 [openai/codex](https://github.com/openai/codex) — +1,978⭐

**Codex 二次爆发：OpenAI 用 Rust 重写的 terminal Agent 抢占 Claude Code 阵地**

OpenAI 官方 codex 仓库虽是老项目，但在 8/21 发布 v0.35（带 GPT-5.6 Sol 支持 + 全新 sub-agent hook）后星数猛涨。Rust 实现让它比 Anthropic 的 Python 版 Claude Code 更快启动、内存占用更低；同时 codex 集成的 MCP client 直接兼容 Anthropic MCP 生态，形成"OpenAI 主体 + Anthropic 生态"这一混合部署。

从榜单上看，**openai/codex vs anthropics/claude-code = 1,978 : 141**——一个 10:1 的星差表明：一旦有 Rust 更快的替代品，开发者会毫不犹豫迁移。Claude Code 团队需要在性能与插件生态上加速回应。

---

### 🥉 [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) — +959⭐

**Rust + local-first：一个"反 SaaS"的硬件工具突破**

Logitech Options+ 长期被硬件党吐槽启动慢、要求登录、无端上传。作者用 Rust 从零重写了一个 local-first 版本，直接解析鼠标/键盘 HID 协议，纯本地运行，无网络无登录。**+959 星**表明社区对"外设配置软件被 SaaS 化"的反感已经形成付费级别的关注。

这个仓库很像去年 `raycast-linux`、`hyprland` 崛起时的信号——**当大厂把简单的桌面工具塞进云端订阅时，Rust 社区就会用一个下午的时间把它开源掉。**

---

### 4️⃣ [Wei-Shaw/sub2api](https://github.com/Wei-Shaw/sub2api) — +264⭐

**订阅转 API 的合规灰产：单点接入 Claude Pro/Plus 的走钢丝**

sub2api 用 Go 写了一个统一转发层，把 Claude Pro/OpenAI Plus/Gemini Ultra 等**订阅账号变成 OpenAI 兼容 API**。对个人开发者极具吸引力：一个 20 美元/月的订阅可以跑本地脚本、代替 API pay-as-you-go。

但这类工具明显违反各家 ToS，且 Anthropic 最近开始对 IP 频率进行严格限速。它出现在 trending 上，说明**API 定价与订阅定价之间的差价已被开发者视为套利机会**——如果 Anthropic/OpenAI 不主动重设费率，类似项目还会继续冒头。

---

### 5️⃣ [microsoft/TypeScript](https://github.com/microsoft/TypeScript) — +163⭐（语言字段变 Go）

**编译器主语言正式改 Go：一次静默但深远的架构变更**

TypeScript 已经有 11 万+ star，今天忽然又上 trending，是因为仓库主语言从 TypeScript 变为 **Go**——微软推行的 native compiler port（tsc-native）已经把主编译器移植到 Go 完成，并已成为默认发布路径。此前预告的 10 倍编译速度提升终于落地。

对 JavaScript/TypeScript 社区来说，这意味着**编译器再也不能自举**。对 Go 社区来说，这是继 Docker、Kubernetes 之后又一个战略级"生态吸虹"。而 Rust 派（stc、oxc）需要重新思考自己的定位——微软已经用工程决策告诉大家："性能提升的方向选 Go，不选 Rust。"

---

## 生态观察

**今日榜单最强的信号只有一个词：Skills。** Top 15 里 `mattpocock/skills`、`obra/superpowers`、`multica-ai/andrej-karpathy-skills`、`affaan-m/ECC` 四个仓库都围绕"Claude Skill / Agent 编排"展开。这不再是几个爱好者的实验——Matt Pocock 与 Karpathy 系的方法论集合出现，说明**Skill 已经进入"专业方法论产品"阶段**。仓库的 star 曲线甚至比 6 月 MCP 元素爆发时更陡。

第二个观察是**"OpenAI 卷 Rust，Anthropic 守 Python"**。`openai/codex`（Rust）一天涨 1,978 星，`anthropics/claude-code`（Python）只涨 141——性能差距被开发者用脚投票。若 Anthropic 想继续拿住 CLI Agent 生态，Python 主线需要一次快速 Rust 化重构。

第三个观察是**local-first + 硬件工具的复兴**：`OpenLogi`、`google-timeline-visualizer` 都在证明——当用户对云服务疲惫时，"本地 + Rust/Kotlin"这一组合会持续获得高涨幅。这条线是 2026 下半年最容易被忽视但最有生命力的开源方向。
