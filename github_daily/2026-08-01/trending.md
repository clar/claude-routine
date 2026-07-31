# GitHub Trending 每日热榜 · 2026-08-01

## 今日焦点

> **Skill 生态爆发 · Agent Harness 内战 · 逆向安全 skill pack · 系统化交易复兴 · MoE 部署工具**
>
> - `microsoft/AI-For-Beginners` **+1,592⭐**：微软 12 周 24 课的 AI 入门教程一夜刷屏，登顶新增。
> - `different-ai/openwork` **+796⭐**：Claude Cowork 与 Codex 的开源桌面替代，MCP 一键跨 agent 复用。
> - `paperswithbacktest/awesome-systematic-trading` **+765⭐**：策略、书籍、库、教程的量化交易大合集。
> - `mvanhorn/last30days-skill` **+660⭐**：多平台并行调研 Reddit/X/YouTube/HN/Polymarket 的 agent skill。
> - `zhaoxuya520/reverse-skill` **+612⭐**：安全研究 skill router，把逆向/渗透/CTF 打包成 agent 工作流。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ |
|------|------|------|------|--------|-----------|
| 1 | [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 12 周 24 节 AI 入门课程 | Jupyter | 55,263 | +1,592 |
| 2 | [different-ai/openwork](https://github.com/different-ai/openwork) | Claude Cowork 开源替代 | TypeScript | 19,461 | +796 |
| 3 | [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) | 系统化交易资源大集合 | Python | 11,716 | +765 |
| 4 | [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 多平台并行调研 skill | Python | 56,195 | +660 |
| 5 | [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | 逆向 / 渗透 / CTF skill 路由 | PowerShell | 10,651 | +612 |
| 6 | [1jehuang/jcode](https://github.com/1jehuang/jcode) | 极致内存高效的 coding harness | Rust | 14,588 | +468 |
| 7 | [agavra/tuicr](https://github.com/agavra/tuicr) | vim 风格 TUI 代码 review | Rust | 2,138 | +336 |
| 8 | [usekaneo/kaneo](https://github.com/usekaneo/kaneo) | 极简开源项目管理 | TypeScript | 5,032 | +188 |
| 9 | [chatwoot/chatwoot](https://github.com/chatwoot/chatwoot) | 开源客服工作台 | Ruby | 35,097 | +175 |
| 10 | [geo-tp/ESP32-Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate) | ESP32 硬件协议瑞士军刀 | C++ | 4,969 | +161 |
| 11 | [deepfakes/faceswap](https://github.com/deepfakes/faceswap) | 老牌换脸工具 | Python | 56,956 | +157 |
| 12 | [github/copilot-sdk](https://github.com/github/copilot-sdk) | Copilot Agent 多语言 SDK | Java | 10,127 | +7 |

---

## 重点项目点评

### 🥇 [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) — +1,592⭐

**免费 AI 教材再上头条：为什么一门老课程今天冲榜？**

微软这门"12 周 24 节课"的 AI 入门课程严格来说不是新项目，去年就以 5 万+ Star 稳居长期榜。今天一天涨 1,592 星，本质是 GitHub 榜单的"教材周期性回归"——每逢中美暑期结束、开学季启动前后，学生与 self-learner 会集中收藏免费系统课程。上一次类似跳涨发生在 2 月初春季学期启动。

内容层面它覆盖的领域仍具竞争力：符号 AI、神经网络、CV、NLP、强化学习都用 Notebook 形式展开，配 PyTorch/TensorFlow 双实现。相比之下，同类新课程往往过度聚焦"用 LLM 做应用"这一狭窄面向，而微软这门课把 AI 作为一门学科完整讲清楚，反而在 agent 时代显得稀缺。

对开发者的实用建议：如果只跟着做 12 周会略显臃肿，但把里面"神经网络内部机制"和"强化学习"两个模块单独抽出来学，性价比很高。

---

### 🥈 [different-ai/openwork](https://github.com/different-ai/openwork) — +796⭐

**Agent Harness 开源化第一枪：Claude Cowork 的直接对标**

openwork 定位极其明确：Claude Cowork + OpenAI Codex 的开源桌面替代。跨平台、TypeScript，通过 MCP 让同一份 skill / workflow 在 Claude Code、Cursor、ChatGPT 等 agent 里复用；带一个 "OpenWork Den" 管理面板，供组织内部发布 skill 与统一配置连接。

这条赛道昨天还只是内部实验，今天却拿到 796 星、总量 1.9 万，说明 Anthropic 推 Cowork 与 OpenAI 推 Codex Home 之后，社区对"闭源桌面 agent harness"的替代焦虑迅速兑现成实际项目。判断这个赛道会继续升温：一是 MCP 让"复用 skill"变得可标准化；二是企业内网部署有天然合规需求；三是 openwork 之外的 opencode、qm、jcode 同期都在长星，形成事实生态。

关注点：这类项目最大的风险不是产品体验，而是与 Cowork / Codex 的 skill 库同步节奏——如果 Anthropic 每 2 周更新 skill schema，开源侧疲于追赶会耗掉大量维护力。

---

### 🥉 [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) — +612⭐

**Skill 生态最"垂直"的代表：安全研究工作流打包**

reverse-skill 把逆向工程、APK 分析、二进制反编译、JS 解密、CTF、渗透测试等安全研究场景统一封装成 Claude Code / Cursor / Cline 可直接调用的 skill 集合。核心是 `MASTER-ROUTING.md` 决策梯 + `routing.md` 任务-技能矩阵，自动识别系统里装了 IDA Pro、Ghidra、radare2、Frida、BurpSuite 等哪些工具，选择合适的方法论。

这个项目今天冲榜的信号意义比它自身产品更重要：**skill 正在从"通用工作流"下沉到"垂直行业方法论"**。上周登顶的 `last30days-skill` 是"跨平台调研"通用类；今天的 reverse-skill 已经是狭窄的安全垂类；预期下个月会有法律尽调、医学文献综述、量化回测、生物信息学等垂直 skill 集合出现。谁能第一个建立"垂直 skill 市场"，就有机会成为下一个 npm 或 Docker Hub。

需要留意的是这类 skill pack 的合规性——把 CTF 与渗透方法论直接暴露给 agent 会加速攻防两侧的能力扩散，是接下来 6 个月安全社区的争议焦点。

---

### 4️⃣ [1jehuang/jcode](https://github.com/1jehuang/jcode) — +468⭐

**"最省内存的 coding harness"：Rust 拿回主场**

jcode 用 Rust 重写 coding agent harness，实测单会话 ~27.8MB 内存、10 并发会话 ~260MB，对比同类工具（Claude Code / opencode / cursor-agent 等）动辄 140–3000MB 显得极端节流。启动 14ms、首字响应 48ms，加上支持 Claude / OpenAI / Copilot / Gemini 等 25+ Provider、内建向量记忆与多 agent 协同。

它今天涨 468 星，反映一个真实痛点：现有 harness 大多用 Electron / Node，内存占用巨大且冷启动慢。开发者在同一台机器上跑 3–5 个 agent 会话很常见，用 jcode 可以把总占用压到 1/10。这是"agent harness 内战"里最实用主义的一支——不做花活，只做效率。

值得关注 jcode 的"自修改能力"：agent 可以直接改自身源码、重新构建并热重载。这是很少 harness 敢做的功能，一旦生态成型可能产生"我的 harness 每周自我进化"的社区玩法。

---

### 5️⃣ [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) — +765⭐

**量化交易资源再次翻红：宏观周期的直接读数**

一份典型的 awesome-* 列表，覆盖策略、库、书籍、博客、教程等系统化交易资源。上一次进入日榜前 5 是在 2025 Q1 加密回暖时期；今天以 765 星再度冲榜，与 crypto 市场近期波动、美股/A 股散户回流量化平台的时间节点吻合。

内容本身以经典 Python 量化库为主（backtrader、zipline-reloaded、vectorbt、nautilus_trader 等），也开始收录 LLM 辅助交易研究的新兴项目。对完全新手可能过重，但作为"从头系统化梳理量化生态"的入口它依然是最好的开源资源之一。

在 GitHub 语境下，这种非代码 awesome 列表能进入 Top 10 通常意味着一个更大的社区叙事在发酵——今天可能就是"AI 交易 agent"这一新故事推动了传统量化资源的翻新点击。

---

## 生态观察

**主线一：Skill 生态从"通用"下沉到"垂直"。** 今日 Top 5 里 3 个都是 skill 类项目（`last30days-skill`、`reverse-skill`、`openwork` 底层也是 skill 集散），且垂直度显著提升——从"帮我搜信息"到"帮我做逆向"。这印证了 Anthropic 提出 skill 规范 4 个月后，社区第二波爆发是"面向真实职业方法论"的沉淀，而不是又一个通用工具。

**主线二：Agent Harness 内战全面开打。** `openwork`（TS 桌面）+ `jcode`（Rust 极致省内存）+ `qm`（多人协同）+ `tuicr`（TUI 代码 review）在同一天进入 GitHub 与 HN 双榜，说明 Claude Code / Cursor / Codex 三家闭源方案的替代焦虑正在集中兑现。这个赛道的竞争维度非常分散：桌面 GUI、TUI、多人协同、内存效率、垂直用途——短期不会出现单一赢家。

**主线三：Rust 在开发者工具层继续吸血。** `jcode`（harness）、`tuicr`（review TUI）都是 Rust 项目，配合近月的 `zed`、`biome`、`fnm`、`ripgrep` 的持续榜位，Rust 已经确立"要写快、要省资源就上 Rust"的默认心智——这一趋势在 agent 工具层比在传统命令行工具层更明显，因为 agent 需要长期驻留 + 大量并发 IO。

**主线四：教育资源与 awesome 列表回潮。** 除了微软的 AI-For-Beginners，awesome-systematic-trading 也进 Top 5。这一模式说明 GitHub 榜单在被 agent 工具类"占领"数周后，社区正主动寻找"扎实、系统、可回看"的知识资产。可以预期下周还有更多老教程 / 老 awesome 列表随季节性冲榜。
