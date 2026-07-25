# GitHub Trending 每日热榜 · 2026-07-26

## 今日焦点

> **Block 开源"人机共域"Buzz 登顶 · 阿里 open-code-review 打出 1/9 token 精度反击 · Agent 专用浏览器 ego-lite 冲上第三 · Claude Skills 生态两连击（mattpocock/skills、obra/superpowers）· Bitchat 因 Radicle 上线再度爆红**
>
> - `block/buzz` +2,506⭐：Block（Square 母公司）开源的"人 + AI Agent"协同 Relay，主打 Nostr 事件流 + 全审计。
> - `alibaba/open-code-review` +439⭐：阿里开源 Code Review CLI，把 LLM Agent 与确定性流水线拼在一起，F1 高于 Claude Code、耗 1/9 tokens。
> - `citrolabs/ego-lite` +986⭐：给 AI Agent 用的独立浏览器，共享 Chrome 登录态，代码化控制而非命令化。
> - `mattpocock/skills` +1,743⭐、`obra/superpowers` +507⭐：Claude Skills 生态两大目录级仓库继续吸量。
> - `permissionlesstech/bitchat` +1,695⭐：与今日 HN 热点同频（Bitchat now on Radicle）——去中心 P2P 通讯回潮。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [block/buzz](https://github.com/block/buzz) | 人+AI Agent 共域 Relay 平台，Nostr 事件全审计 | Rust | 11,811 | +2,506⭐ | 938 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 面向工程师的 Skills 目录，与 Claude Code/Codex 联动 | Shell | 188,176 | +1,743⭐ | 16,170 |
| 3 | [permissionlesstech/bitchat](https://github.com/permissionlesstech/bitchat) | 无网蓝牙 Mesh 聊天，IRC 味的去中心通讯 | Swift | 28,653 | +1,695⭐ | 4,267 |
| 4 | [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | 面向 Agent 的浏览器，共享 Chrome 态、代码化交互 | JavaScript | 3,519 | +986⭐ | 174 |
| 5 | [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Claude Skills 生态精选清单 | Python | 70,548 | +574⭐ | 7,937 |
| 6 | [obra/superpowers](https://github.com/obra/superpowers) | Agentic Skills 框架与开发方法论 | Shell | 261,064 | +507⭐ | 23,299 |
| 7 | [Automattic/harper](https://github.com/Automattic/harper) | 离线优先、隐私优先的语法检查器 | Rust | 13,395 | +503⭐ | 506 |
| 8 | [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | Agent + 确定性流水线的代码评审 CLI | Go | 12,909 | +439⭐ | 885 |
| 9 | [CoreBunch/Instatic](https://github.com/CoreBunch/Instatic) | Webflow / Framer 的开源替代 | TypeScript | 5,023 | +424⭐ | 469 |
| 10 | [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms) | LLM 编程实战教程系列 | Jupyter Notebook | 45,338 | +405⭐ | 5,414 |
| 11 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Agent 性能优化系统，含 Skills 与长时记忆 | JavaScript | 233,277 | +364⭐ | 35,566 |
| 12 | [Pumpkin-MC/Pumpkin](https://github.com/Pumpkin-MC/Pumpkin) | Rust 实现的高性能 Minecraft 服务器 | Rust | 9,690 | +357⭐ | 654 |
| 13 | [palmier-io/palmier-pro](https://github.com/palmier-io/palmier-pro) | 面向 AI 工作流的 macOS 视频编辑器 | Swift | 12,188 | +346⭐ | 894 |
| 14 | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) | 金融市场"语言"基础模型 | Python | 33,768 | +319⭐ | 5,702 |
| 15 | [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | Anthropic 官方 Claude 使用笔记本 | Jupyter Notebook | 49,856 | +144⭐ | 5,895 |

---

## 重点项目点评

### 🥇 [block/buzz](https://github.com/block/buzz) — 今日榜首，+2,506⭐

**Block 把"人 + Agent 协作 Workspace"当作基础设施发布**

Buzz 是 Block（原 Square）开源的 Rust workspace 平台：每一条消息、每一次 workflow 触发、每一段 code review、每一次 git 事件，都是一个签名过的 Nostr 事件，写进同一份可审计事件流。技术形态是 Nostr Relay + PostgreSQL / Redis / S3，产品形态是"聊天 + 代码托管 + CI Dashboard + Bot"合一。

它的核心主张是：**Agent 不应该是插件，而应该是团队成员**——每个 Agent 拥有独立密钥、独立事件签名与独立审计线，权限和历史与人类一视同仁。这与今天头版的 OpenAI Presence / Fly.io Sprites 是同一波"给 Agent 建单独身份和运行时"的浪潮，只是 Block 从更底层的通讯与审计出发。

选 Nostr 作为骨架很聪明：既避开了 Slack/Teams 这种封闭协议锁定，又天然带"可自持中继"、跨组织可路由的属性。对企业买家来说，"AI 可审计"接下来会变成硬性要求，而 Buzz 是第一份足够简单、可跑起来的开源答案。

---

### 🥈 [alibaba/open-code-review](https://github.com/alibaba/open-code-review) — +439⭐

**用"确定性流水线 + Agent 决策"打出高精度、低成本组合拳**

阿里内部孵化后的开源版本，核心思想是把 code review 拆成两半：**确定性侧** 做 file 选择、bundling、rule matching、position 校准这些"数据工程活"；**Agent 侧** 只做"要不要报"、"报到哪一行"这类判断。官方给出的对比是相同底模下，F1 高于 Claude Code，token 消耗约为 **1/9**。

这条路线其实在打脸最近半年 "all-agent, minimal-scaffold" 的乐观论：**大模型再强，也顶不住上万行 diff 的 context/position 抖动**；把重复、可枚举的工程决策交给确定性流水线，Agent 只负责最上层判断，是当下最实用的落地范式。今天头版 Anthropic 的 context engineering 新规也在说类似的话——"接口自解释、Progressive disclosure"，Buzz 与 Presence 都是同一个 lineage。

对国内团队还有一个额外意义：**它是阿里第一次把"可复现、可对比"的评测放进 README**，与"云厂商开源 = 玩具"的刻板印象拉开距离。

---

### 🥉 [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) — +986⭐

**Agent 需要自己的浏览器：不再靠 CLI，而靠可执行 JS 直接控页面**

ego lite 的产品定位一句话讲清：**给 Agent 用的浏览器**，让 Claude Code / Codex 之类的 Agent 在里面开各自的 Space、共享你 Chrome 的登录态、cookies、扩展，同时不跟你正在浏览的 tab 打架。技术亮点是把交互从"点击-输入命令"改成"Agent 写一段 JS，一次性在页面里跑完"，token 消耗与准确率同时改善。

这是继 Anthropic 的 Computer Use、Meta Muse Spark 1.1 之后，第三种"Agent 与真实 GUI 交互"的思路：**不建虚拟机、不做通用 vision，而是把浏览器本身改造成 Agent-first 环境**。它避免了 headless 浏览器最痛的"登录态难同步"问题，也给企业留了"Agent 权限沙盒"的钩子。

3.5k star 的体量还小，但趋势是明确的——**当所有大模型都在讲 Agent 能力时，工具链侧就会开始出现"Agent 优先"的重写版本**（浏览器、终端、编辑器都在里面）。ego-lite 是这一波第一个跑出来的。

---

### 🧠 [mattpocock/skills](https://github.com/mattpocock/skills) & [obra/superpowers](https://github.com/obra/superpowers) — +1,743⭐ / +507⭐

**Claude Skills 生态在"内容层"迅速被两个仓库垄断**

两者是 Claude Skills 生态里最主流的"目录 + 方法论"仓库：mattpocock/skills 从 TypeScript 教育者视角组织工程师常用 skill；obra/superpowers 更偏方法论，把 skill 与"Agent 开发流程"打成整体。它们跟 [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) 一起，在今天的榜单里包办了三席，说明 **Claude Skills 已经开始产生自己的 npm/package.json 生态位**。

值得留意的信号是：Anthropic 今天官方博客把 CLAUDE.md 从"要写详实"改成"要轻，把细节交给 Skills"，进一步把 Skills 抬到了"prompt 工程新一层"的位置。可以预见接下来会出现 **Skills 市场、评测、依赖管理** 之类的元项目，github trending 上的 skills 类仓库还会继续吃流量。

对开发者的实用建议：现在收藏这两个仓库 = 收藏一份"业界共识 skill 清单"，比自己从零试要省很多。

---

### 🌐 [permissionlesstech/bitchat](https://github.com/permissionlesstech/bitchat) — +1,695⭐

**去中心通讯回潮：从蓝牙 Mesh 走进 Radicle 代码站**

Bitchat 因今天 HN 头版 "Bitchat is now on Radicle" 而爆量：项目本体是靠 iOS 蓝牙 Mesh + 无网络的去中心聊天，气质像"IRC + 蓝牙"。这次搬到 Radicle（P2P 版 GitHub），意味着 **既没有中心服务器、也没有中心代码托管**，是一种"从传输层到治理层都是 P2P"的 end-to-end 姿态。

它的高点亮不完全来自使用价值——真实场景下蓝牙 Mesh 的距离和电量约束不小——而来自 **"离开平台"的姿态**。今天 HN 的 Android ADB 收紧、Debian LLM 全体投票，与 Bitchat 的爆红本质上是同一个母题：**社区在寻找"平台不能剪掉我"** 的技术栈。

从 GitHub 侧看，未来 6 个月内 Radicle 之类的 P2P 代码托管值得多留一眼——如果 GitHub 因 AI 训练数据许可或政策管控在开发者中出现新一轮信任裂缝，Radicle 就是替代路径的起点。

---

## 生态观察

- **Agent 基础设施集中爆发**：Buzz（Relay）、ego-lite（浏览器）、mattpocock/skills（能力包）、alibaba/open-code-review（工程侧 Agent）——今天 15 条里有 6 条是"给 Agent 用的东西"，Agent 已经从"应用层"沉降到"基础设施层"。
- **确定性 + Agent 的混合流派抬头**：open-code-review 直接用数据佐证"Agent 少做决策 + 流水线做多"的组合能同时提高精度和节省 token；这与 Anthropic 今天官方给出的 context engineering 新规、Presence 的"人工审批 + Agent 建议"高度一致，说明业界对"纯 Agent 派"已经开始降温。
- **Claude Skills 已进入生态层**：skills、superpowers、awesome-claude-skills 三仓一起吸量；Anthropic 官方博客也在推 Skills 优先，接下来会出现类 npm 的分发/评测/依赖管理项目。
- **去中心浪潮借 P2P 代码托管抬头**：Bitchat 上 Radicle 意味着一种"平台完全绕开"的示范；配合今天 HN 上 Android/Debian 的自由权讨论，形成一致的"社区找退路"氛围。
- **金融、创作、游戏三条支线仍在活**：Kronos（金融基础模型）、palmier-pro（Mac 视频编辑）、Pumpkin（Minecraft 服务器）稳定挤进榜单——AI 主导的日子里，专业细分领域也在借 Rust / Swift 高性能语言给出自己的答案。
