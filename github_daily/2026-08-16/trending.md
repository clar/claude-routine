# GitHub Trending 日报 · 2026-08-16

## 今日焦点

> **Claude Code 生态扩张 · 边缘小模型 · AI Agent 原生工具 · 规格驱动开发 · 本地训练民主化**
>
> - `cathrynlavery/diagram-design` 一天 +1,619⭐，29 种"给 Claude Code 用的编辑级图表模板"，Claude Code 生态开始沉淀设计资产。
> - `cordiverse/cordis` 一天 +616⭐，从 3.4K 冲上 4K，TypeScript "时空可组合"元框架成为架构党新宠。
> - `cactus-compute/needle` +551⭐，14MB 基础模型专攻手机/穿戴/机器人的极端边缘部署。
> - `citrolabs/ego-lite` +546⭐，为 Codex / Claude Code 共享登录态而生的"Agent 专用浏览器"，绕开自动化被反爬风险。
> - `github/spec-kit` +901⭐，GitHub 官方推 Spec-Driven Development，"先写规格再让 AI 写代码"进入官方工作流。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [public-apis/public-apis](https://github.com/public-apis/public-apis) | 免费 API 集合的常青长青库 | Python | 460,104 | +2,476 | 50,850 |
| 2 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 29 种给 Claude Code 用的自包含 HTML+SVG 编辑级图表 | HTML | 18,550 | +1,619 | 1,114 |
| 3 | [github/spec-kit](https://github.com/github/spec-kit) | GitHub 官方 Spec-Driven Development 工具包 | Python | 129,160 | +901 | 11,548 |
| 4 | [cordiverse/cordis](https://github.com/cordiverse/cordis) | "时空可组合"的 TS 元框架 | TypeScript | 4,030 | +616 | 198 |
| 5 | [ToolJet/ToolJet](https://github.com/ToolJet/ToolJet) | 开源内部工具与 AI Agent 平台 | JavaScript | 39,496 | +553 | 5,292 |
| 6 | [cactus-compute/needle](https://github.com/cactus-compute/needle) | 14MB 边缘基础模型（手机/穿戴/机器人） | Python | 6,041 | +551 | 402 |
| 7 | [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | 为 AI Agent 共享登录态的浏览器 | JavaScript | 10,927 | +546 | 556 |
| 8 | [unslothai/unsloth](https://github.com/unslothai/unsloth) | 本地跑训 LLM/扩散模型 UI，覆盖 Qwen3.8/Kimi K3/DeepSeek-V4 | Python | 72,014 | +435 | 6,492 |
| 9 | [megadose/holehe](https://github.com/megadose/holehe) | 邮箱在各社交平台注册情况检测 | Python | 13,100 | +389 | 1,742 |
| 10 | [MakazhanAlpamys/Soup](https://github.com/MakazhanAlpamys/Soup) | YAML 微调 LLM，层流训练可让 8B 跑在 4GB 显卡 | Python | 1,626 | +303 | 261 |
| 11 | [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice) | macOS 端侧听写，Wispr Flow 的本地替代 | Swift | 10,306 | +165 | 697 |
| 12 | [cursor/plugins](https://github.com/cursor/plugins) | Cursor 插件规范与官方插件 | TypeScript | 2,941 | +152 | 232 |
| 13 | [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) | 让一切软件变成 Agent-Native 的 CLI 框架 | Python | 47,323 | +100 | 4,391 |

---

## 重点项目点评

### 🥇 [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) — 今日榜首（可增速指标）· +1,619⭐

**给 Claude Code 用的 "editorial diagrams"，标志着 AI 编码工具正在长出真正的设计资产层**

29 种编辑级图表类型——decision tree、mechanism diagram、branch diagram、network topology 等——全部以自包含 HTML + inline SVG 交付，主题感和信息密度对齐 Bloomberg / NYT 图表风格。它不是一个组件库，而是**给 LLM 消费的"图形语法说明书"**：每种图表都有完整例子、颜色 token、暗色模式适配和无外部依赖的约束，让 Claude Code 之类的 AI 一次生成就可用。

它成为今天最大增速项是有原因的：Claude Code 的用户开始意识到自己在**批量输出方案文档**时都需要图，但 LLM 直生 Mermaid 又太丑，直生 D3 又太贵。这个仓库正好卡在中间层——"漂亮 + 单文件 + 可复制"。这暗示着 AI 编码工具的第二阶段来了：**从"生成代码"过渡到"生成成品制品"**，中间需要一整套 AI-friendly 的设计素材沉淀。

未来 30 天可以观察：类似的"AI-native 设计资产"仓库会不会形成一个 category——PPT 模板、报告 layout、数据可视化 preset、图标集，都会出现"Claude Code 版本"的重制品。

---

### 🥈 [cactus-compute/needle](https://github.com/cactus-compute/needle) — +551⭐

**14MB 的基础模型：把 LLM 塞进手表、耳机和机器人**

Needle 只有 14MB，专门为极端边缘设备设计——手机、可穿戴、智能家居、机器人。它不是"缩水版通用助手"，而是把工程重心放在小型指令跟随、传感器上下文融合、低功耗持续在线。同类项目通常需要 100MB+ 甚至 500MB，才能保留可用的自然语言能力。

它今天冲上榜是因为**边缘 AI 从"演示"进入"部署"阶段**。上半年苹果和高通的芯片 NPU 算力翻倍，让 100M 参数级模型可以在 <100ms 完成一次 turn。真正的瓶颈变成了权重占用的存储空间与冷启动时间。14MB 意味着可以做到"永久驻内存 + 秒级冷启动"，进而实现 always-on 语音指令、传感器解释这些新交互。

生态含义：Needle 与 Meta 的 Llama-Nano、Google 的 Gemini Nano 2 组成一组"手机/穿戴级"竞品。开源阵营首次拿到能与硅谷大厂对齐的极小尺寸方案。

---

### 🥉 [github/spec-kit](https://github.com/github/spec-kit) — +901⭐

**"Spec-Driven Development"从推特话题变成 GitHub 官方工作流**

GitHub 官方发布了 Spec-Driven Development（SDD）工具包，把"先写规范→AI 生成实现→AI 生成测试"这一 pattern 变成 CLI 化的工程流程。核心不是新概念——这套东西五年前叫 BDD/DSL 都试过——但这次不同的是**LLM 让"完整规格 → 完整实现"第一次真正跑得通**。

它冲榜是因为 2026 年 AI 编码进入了一个尴尬的中期：Cursor / Claude Code 让每个开发者的产量翻倍，但也带来了"AI 写出来的代码 review 不动"的问题。SDD 提供的答案是——**把 review 环节前置到规格层**。人负责的是"写清楚要什么"，AI 负责"精确实现 + 出测试"，两方都用规格文档作为唯一契约。

生态含义：官方入场意味着未来 6 个月会有一批 SDD 生态项目——linters、IDE 插件、CI check——这将进一步固化"设计文档 = 可执行契约"的行业习惯。

---

### 🚀 [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) — +546⭐

**"给 Agent 用的浏览器" —— 反反爬时代的关键基建**

ego-lite 定位是"最快的浏览器，专门给 AI Agent 用"。它解决的痛点非常具体：Codex / Claude Code 需要访问用户已登录的服务（GitHub、Notion、内部管理后台）去做自动化，但正常 Playwright/Chromium 会触发反机器人策略；同时用户不想让 Agent 直接接管自己的主浏览器。

它的方案是**独立进程 + 共享 cookie/state**——用户先登录一次，Agent 在这个隔离浏览器里以"你的账号"活动，但不会打扰你正常刷网页。这个模式过去存在于零散的 dev tools 里，现在被打包成了 Agent-first 的产品形态。

生态含义：**"AI Agent 原生的软件"** 正在从"用现成软件的 API"变成"重写一个专为 Agent 优化的软件"。浏览器只是第一个——接下来会看到 Agent 原生的 IDE、Agent 原生的邮箱客户端、Agent 原生的终端。

---

### 🧬 [cordiverse/cordis](https://github.com/cordiverse/cordis) — +616⭐

**"时空可组合"的 TS 元框架：面向 Agent 时代的架构实验**

Cordis 自称是"Meta-Framework of Spatiotemporal Composability"——把一个应用拆成可以在不同上下文（浏览器/边缘/服务端）、不同时间（同步/异步/事件驱动）之间自由组合的服务单元。这套想法在传统前端里过于抽象没人买账，但在 Agent 编排场景里恰好合适——Agent 需要"在浏览器里执行一段、在服务端存一段、在事件到来时被唤醒"。

它今天从 3.4K 冲到 4K 的增速，反映的是**Agent 后端框架的空白已经被工程社区意识到**。LangChain 太重、Vercel AI SDK 太简单、Temporal 太企业化，中间需要一个"给独立开发者的 Agent 原生服务架构"，Cordis 卡在这个位置。

风险：TS 生态每 6 个月出一个"新元框架"，多数活不过一年。它能不能站住，取决于能否在下个季度接入一个真实的 Agent 产品案例（比如 open-source Cursor 替代或 Claude Code 的插件生态）。

---

## 生态观察

今天最鲜明的一根主线是 **Claude Code / Codex 周边生态开始批量成型**——`diagram-design`（AI-native 设计素材）、`ego-lite`（Agent 专用浏览器）、`cursor/plugins`（Cursor 插件规范）、`spec-kit`（规格驱动）、甚至 `cordis`（Agent 原生架构）都在为"AI 编码 Agent 的日常工作流"补齐配套。这类似 2010 年 iOS 应用生态爆发前的**中间件冷启动阶段**。

第二根主线是**模型部署的两个极端在同时被推**：`unsloth` / `Soup` 让本地训练大模型的门槛掉到 4GB 显存以下；`needle` 让推理下沉到 14MB。传统"云端大模型 + 边缘小模型"的二分法正在被替换成"任何设备都能既训又推"的均衡分布。

冷门信号：`megadose/holehe` 这种老 OSINT 工具再次上榜，间接反映**AI 时代对身份验证与账号发现类工具的需求正在被重新发现**——Agent 自动化任务需要判断"这个邮箱在哪些平台注册过"来做后续操作。安全工具正在被 AI 场景重新拉回主流视野。

未来 7 天最值得盯的是"Claude Code 生态"周边——如果继续每天出一到两个 +500⭐ 的新仓库，说明这个生态位已经稳固；如果热度衰减，则可能被 Cursor / Codex 生态收编。
