# GitHub Trending · 2026-07-31

## 今日焦点

> **Agent 生态 · 语音/多模态 · 开源替代 · 3D/建筑创作 · 系统化交易**
>
> - `different-ai/openwork` 号称 Claude Cowork 的开源替代，一天 +916⭐，Agent 平台之争白热化
> - `affaan-m/ECC` Agent harness 性能优化框架单日 +810⭐，成为 Fork 榜龙头
> - `huggingface/speech-to-speech` +627⭐，本地语音代理模式再度受关注
> - `paperswithbacktest/awesome-systematic-trading` +628⭐，量化开源资料库回潮
> - `pascalorg/editor` +617⭐，Web 3D 建筑协作工具打入前十

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [different-ai/openwork](https://github.com/different-ai/openwork) | Claude Cowork 的开源替代，基于 opencode | TypeScript | 18,673 | +916 | 1,904 |
| 2 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Agent harness 性能优化，含 skills/memory/安全 | JavaScript | 236,180 | +810 | 35,925 |
| 3 | [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | 为编码智能体准备的 Chrome DevTools MCP | TypeScript | 48,015 | +73 | 3,257 |
| 4 | [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) | 系统化交易库、策略与工具精选 | Python | 10,997 | +628 | 1,411 |
| 5 | [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech) | 用开源模型搭建本地语音智能体 | Python | 8,695 | +627 | 1,085 |
| 6 | [pascalorg/editor](https://github.com/pascalorg/editor) | 在线创建与分享 3D 建筑项目 | TypeScript | 20,072 | +617 | 2,619 |
| 7 | [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 跨平台主题研究并合成摘要的 Agent Skill | Python | 55,501 | +377 | 4,785 |
| 8 | [agavra/tuicr](https://github.com/agavra/tuicr) | 带 vim 键位的代码审查 TUI | Rust | 1,829 | +232 | 157 |
| 9 | [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 12 周 24 课，AI 入门教程 | Jupyter | 53,833 | +115 | 10,940 |
| 10 | [microsoft/PowerToys](https://github.com/microsoft/PowerToys) | Windows 生产力增强工具集 | C++ | 137,089 | +68 | 8,364 |
| 11 | [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins) | 自动化服务器 Jenkins | Java | 26,280 | +53 | 9,718 |
| 12 | [ansible/ansible](https://github.com/ansible/ansible) | 极简 IT 自动化平台 | Python | 69,862 | +20 | 24,248 |
| 13 | [WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys) | 基于 socket 的 WhatsApp Web TS/JS API | JavaScript | 10,420 | +12 | 3,249 |
| 14 | [dotnet/aspnetcore](https://github.com/dotnet/aspnetcore) | 跨平台 .NET Web 框架 | C# | 38,282 | +5 | 10,858 |

---

## 重点项目点评

### 🥇 [different-ai/openwork](https://github.com/different-ai/openwork) — 今日榜首，+916⭐

**Claude Cowork 一发布，社区就等到了它的开源版本**

Anthropic 的 Cowork 上线不到两周，`openwork` 以"开源替代"打出旗号，用 opencode 内核复刻了 Cowork 的会话协作、共享工作区、多人 Agent 编排等核心能力。README 中特别强调"可以对接任何 API 兼容 LLM"，即刻切断闭源依赖。

这种"闭源大厂出品—开源快速跟进"的节奏，是 2026 年 Agent 平台层的默认剧本：Cursor 之后有 Continue，Devin 之后有 OpenDevin，Cowork 之后现在有 openwork。真正的看点在于 openwork 是否能长成"Agent 会话协议"的事实标准——它选用的 opencode 上下游有 GitHub、Composio、LangChain 生态背书，起手就比一般 fork 项目更接近产品级。

对企业 IT 而言，这个仓库的重要意义在于：短期你终于能自己托管一套"Cowork 语义"的协作前端，中期你能借它验证内部 LLM 网关是否具备承接团队协作的能力。

---

### 🥈 [affaan-m/ECC](https://github.com/affaan-m/ECC) — +810⭐

**从"个人 harness"进化到"团队级 Agent 运行时"**

ECC（Extended Claude Code）作为 Claude Code 的 harness 增强层，此前主要在个体开发者小圈流传，今日一举登上第二。它把 skills、memory、安全三件事在同一个进程内做完，同时保留了 Claude Code 本体的插件与 MCP 兼容。Fork 数已经 35,925，这个量级说明大量团队在拿它当二次开发的地基。

看点是它宣称的"性能优化"——大幅减少 Agent 循环里对模型的重复调用，实测长链条任务 token 消耗下降接近 40%（README 提供了对比脚本）。在 2026 年"Agent 越跑越贵"的普遍焦虑下，任何能拿出可量化 token 削减的 harness 都会获得溢价关注。

值得关注的风险是 harness 层"套娃"过深带来的调试复杂度：ECC 本身还在快速迭代，若企业深度依赖，需要建立版本冻结与影子部署流程。

---

### 🥉 [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech) — +627⭐

**语音 Agent 的"本地 ChatGPT 时刻"越来越近**

HuggingFace 官方仓库把语音识别、LLM 推理、语音合成三段串成一个流水线模板，全流程可本地部署，支持 CPU-only 与 GPU 加速两条路径。README 附带了从 Whisper Large-V3 到 Kokoro TTS 的完整堆栈脚本。

今天登榜的直接触发点很可能是 Gemini Robotics 2、Figure Helix-02 的连锁"具身智能"叙事：一旦机器人硬件普及，客户端语音 Agent 就必须离线跑，云端调用因延迟与隐私都不再是首选。这个仓库虽然只是"胶水层"，但它把开源语音生态的最优组合固定下来，未来一年会是很多硬件公司 fork 的基础。

---

### 🎯 [pascalorg/editor](https://github.com/pascalorg/editor) — +617⭐

**3D 建筑创作的"Figma 时刻"**

pascalorg/editor 是一个基于 WebGL/three.js 的在线 3D 建筑设计工具，支持多人协作、组件市集、导出到 IFC / glTF。今天登榜与 AEC（建筑工程施工）圈子的一次开源迁移潮相关——数家中小事务所在 X 上宣布放弃订阅制 SaaS，转投这个自托管方案。

对开发者而言值得研究的是它的实时同步协议：CRDT + WebRTC + 3D scene diff，是当前 web 3D 协作里少见的完整开源实现，可以直接抠出来用于 CAD、游戏关卡编辑、VR 教育等场景。

---

### 🔎 [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) — +628⭐

**量化开源资料库的回潮，与本轮 AI 交易热度直接相关**

awesome-* 类精选清单在 2025 年后热度整体下滑，今日单日 +628⭐ 属于典型"外部事件催化"。近几日多家对冲基金披露"AI 驱动系统化策略"的入场公告，散户与开发者用 star 表明立场：想跟上机构叙事，先补齐开源工具链。

清单覆盖 Backtesting、执行、回测数据源、因子研究、GPU 加速、LLM 交易信号等分栏，尤其新增的 "LLM 策略" 分支，把 GPT/Claude 用作因子挖掘的项目集中收录，是这一波流量的核心入口。

---

## 生态观察

今日榜单的**Agent 权重**极高：Top 5 里就有 3 项直接与"Agent 编排 / 增强 / 语音 Agent"相关（openwork、ECC、speech-to-speech），再加上第 3 名 chrome-devtools-mcp、第 7 名 last30days-skill——半数入榜项目在讲同一件事：Agent 平台层的标准化竞争已经从模型层外溢到 harness/协议层。开源社区正在用最快速度复刻闭源大厂的每一个产品化尝试。

第二个信号是**"具体行业工具"的回归**：pascalorg/editor（建筑）、awesome-systematic-trading（量化）、Baileys（社交）三个垂直方向都进入前 15，且 star 增速可观。相较去年"通用 SaaS 复刻"占榜的模式，2026 年下半年的社区注意力在向"某个具体职业能立刻用起来"的项目倾斜。

传统巨型仓库（PowerToys、ansible、aspnetcore、jenkins）今日只是"惯性上榜"，单日 star 均在两位数，说明这类项目对榜单的贡献进入"背景辐射"状态；真正在争夺开发者时间的，是最上面那几行日增数百的新血。
