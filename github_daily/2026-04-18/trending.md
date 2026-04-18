# GitHub 热门仓库日报 · 2026-04-18

## 今日焦点

> **AI Agent 自进化 · 方法论框架 · LLM 教育 · 文件安全 · AI 穿戴硬件**
>
> - `obra/superpowers` 今日新增最高，+1,713⭐，AI Agent 开发方法论框架，强制工程纪律
> - `google/magika` +956⭐，Google 开源的 AI 文件类型检测工具，已在 Gmail/Drive 规模部署
> - `Lordog/dive-into-llms` +944⭐，大语言模型实战教程持续高热，中文社区追捧
> - `lsdefine/GenericAgent` +845⭐，3000 行 Python 打造自进化 Agent，6x 降本
> - `BasedHardware/omi` +824⭐，开源 AI 穿戴设备平台，"帮你记住一切"

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | AI Agent 开发方法论与技能框架 | Shell | 157,750 | +1,713 | 13,720 |
| 2 | [google/magika](https://github.com/google/magika) | AI 驱动的文件内容类型检测 | Python | 15,453 | +956 | 849 |
| 3 | [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms) | 大语言模型编程实战教程 | Jupyter Notebook | 31,510 | +944 | 3,838 |
| 4 | [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent) | 自进化 Agent，低 Token 实现完整系统控制 | Python | 3,609 | +845 | 386 |
| 5 | [BasedHardware/omi](https://github.com/BasedHardware/omi) | AI 屏幕/语音感知穿戴助手 | Dart | 9,823 | +824 | 1,672 |
| 6 | [jamiepine/voicebox](https://github.com/jamiepine/voicebox) | 开源语音合成工作室 | TypeScript | 19,841 | +797 | 2,278 |
| 7 | [EvoMap/evolver](https://github.com/EvoMap/evolver) | GEP 驱动的 AI Agent 自进化引擎 | JavaScript | 4,229 | +737 | 417 |
| 8 | [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | 轻量级多 Agent 工作流框架 | Python | 21,803 | +625 | 3,488 |
| 9 | [SimoneAvogadro/android-reverse-engineering-skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) | Claude Code 安卓逆向工程技能 | Shell | 2,737 | +538 | 283 |
| 10 | [Donchitos/Claude-Code-Game-Studios](https://github.com/Donchitos/Claude-Code-Game-Studios) | 49 个 AI Agent + 72 工作流的游戏开发系统 | Shell | 11,773 | +311 | 1,716 |
| 11 | [z-lab/dflash](https://github.com/z-lab/dflash) | 块扩散加速推测解码 | Python | 1,802 | +287 | 119 |
| 12 | [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre) | AI 时代的开源 SRE Agent 工具包 | Python | 1,441 | +184 | 170 |
| 13 | [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | 为编码 Agent 提供 Chrome DevTools | TypeScript | 35,845 | +196 | 2,192 |
| 14 | [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | 全栈开发框架 | TypeScript | 9,432 | +227 | 1,776 |
| 15 | [lukilabs/craft-agents-oss](https://github.com/lukilabs/craft-agents-oss) | Agent 开发框架 | TypeScript | 4,292 | +110 | 635 |

---

## 重点项目点评

### 🥇 [obra/superpowers](https://github.com/obra/superpowers) — 今日榜首，+1,713⭐

**AI Agent 不是"替代"工程师，而是"学习成为"工程师**

在 AI 编程工具泛滥的今天，大多数人关注的是"Agent 能写多少代码"，而 Superpowers 关注的是"Agent 用什么方法写代码"。这个拥有 15.8 万星的框架（今日单日新增高达 1,713）并非一个模型或工具，而是一套强制执行工程纪律的**开发方法论**——要求 Agent 在动手之前先细化需求、制定计划、分解成 2-5 分钟的子任务，并全程遵循测试驱动开发（TDD）流程。

Superpowers 支持 Claude Code、OpenAI Codex、Cursor 等主流 AI 编程环境，其核心洞察是：AI Agent 的输出质量不取决于模型有多聪明，而取决于给它多规范的流程约束。框架通过"子 Agent 调度"实现并发开发，通过"证据优先"原则防止 Agent 自圆其说而非真正解决问题。

今日爆发式增长背后，折射出社区日益成熟的诉求：人们已经不满足于"AI 能写点代码"，开始追求"AI 写出生产级代码"。Superpowers 提供的，正是从玩具级 Agent 走向工程级 Agent 的那把钥匙。

---

### 🥈 [google/magika](https://github.com/google/magika) — +956⭐

**文件类型检测，Google 把这件"小事"做到了极致**

识别一个文件是 PDF、Python 脚本还是伪装成图片的恶意代码——这件事看似简单，实则暗藏玄机。传统方案依赖魔数（magic bytes）和文件扩展名，面对刻意混淆的文件束手无策。Google 开源的 Magika 用深度学习彻底重构了这个问题：**99% 准确率，5ms 延迟，模型只有几 MB**，支持 200+ 文件类型。

更有说服力的是它的生产验证背景——Magika 已在 Google Gmail、Drive 和 Safe Browsing 中大规模部署，同时被 VirusTotal 和 abuse.ch 采用用于安全扫描。2025 年 ICSE（国际软件工程会议）收录的相关研究进一步提升了其学术可信度。Python、Rust、JavaScript、Go 多语言支持，让它能无缝嵌入各类安全工具链。

在 AI 安全检测场景日益重要的当下，Magika 代表着"把 AI 能力封装成可靠基础设施"的工程哲学——小模型、精准任务、零妥协的可靠性。

---

### 🥉 [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent) — +845⭐

**3000 行代码，挑战百万 Token 怪圈**

大多数 Agent 框架越做越重：动辄需要 200K-1M 的上下文窗口，复杂的部署流程，高昂的 API 费用。GenericAgent 反其道而行之——3000 行 Python，9 个核心工具（浏览器、终端、文件、移动设备控制），30K Token 上下文预算，却能完成订餐、股票筛选、费用追踪等复杂日常任务，综合成本降低约 6 倍。

其核心创新是**"自进化"机制**：Agent 不需要预装技能，而是在每次完成任务后，自动将成功的执行路径"结晶"为可复用的技能，构建起个人专属技能树。这与 LLM 训练范式（预训练 + 微调）形成有趣的对照——GenericAgent 在推理阶段实现了一种轻量级的"在线学习"。

支持 Claude、Gemini 等主流 LLM 的后端，代码量极小意味着可审计、可 Fork、可定制。在 Agent 框架同质化的市场中，GenericAgent 用极简主义证明了：真正的智能来自设计，而非堆料。

---

### 🏅 [BasedHardware/omi](https://github.com/BasedHardware/omi) — +824⭐

**AI 穿戴设备：开源的"第二大脑"**

Omi 将 AI 助手从屏幕里解放出来，嵌入进日常生活。它能实时捕捉屏幕内容和周围对话，自动转录、生成摘要和行动项，并通过聊天界面回答"我之前看到过什么"——本质上是一个**持续运转的外部记忆系统**。平台支持 macOS、iOS/Android，以及 AI 项链和 Omi Glass 智能眼镜等自研硬件。

9.8k 星、完全开源、自研硬件生态，Omi 的野心远不止于一个转录工具。它代表着"具身 AI"（Embodied AI）的一个具体落地路径：不依赖专属设备的封闭生态，而是用开源软件栈 + 可选硬件，让用户自主选择 AI 介入日常生活的深度。

对于关注隐私的用户，开源意味着可以自部署、自审计——这在 AI 录音产品中是稀缺的差异化优势。随着 AI 穿戴硬件竞争加剧，Omi 的开源路线或许将成为对抗闭源巨头的有力武器。

---

## 生态观察

今日热榜呈现出几条清晰的主线：

**Agent 框架进入"方法论"竞争阶段。** 今日至少有 6 个项目直接与 Agent 开发相关（superpowers、GenericAgent、evolver、openai-agents-python、craft-agents-oss、opensre）。竞争焦点已从"能不能用"转向"怎么用得好"——Superpowers 的方法论框架登顶，标志着社区开始严肃对待 Agent 的工程质量问题。

**"自进化"成为高频概念。** GenericAgent 和 EvoMap/evolver 都以"自进化"为卖点，反映出开发者对"无需人工干预、持续学习"的 Agent 的强烈期待。这一趋势值得长期观察，其技术路径是否可持续仍有争议。

**LLM 教育热度不减。** Lordog/dive-into-llms 以 31.5k 总星、+944 今日新增持续高位，说明中文 LLM 学习资源的供需缺口依然显著。

**AI 安全工具悄然崛起。** google/magika 和 SimoneAvogadro/android-reverse-engineering-skill 双双入榜，AI 在安全领域的渗透正在加速，从文件检测到移动端逆向，传统安全工具链正在被 AI 重写。

**Claude 生态持续扩张。** 今日多个项目明确面向 Claude Code（android-reverse-engineering-skill、Claude-Code-Game-Studios），加上 superpowers 的多平台支持，Claude 正逐渐成为 AI 编程工具的第一公民。
