# GitHub Trending 每日热榜 · 2026-08-14

## 今日焦点

> **AI Agent Skills 生态爆发 · 端侧小模型进入 45M 参数时代 · Rust 主导下一代协作栈 · NVIDIA 官方进场 LLM Router · 图数据库回潮做 AI 治理**
>
> - `cathrynlavery/diagram-design` 单日暴涨 +4,504⭐，把 "Claude Code 出图" 一次做成一个 Skill 集，成为 Skills 生态第一个爆款作者项目。
> - `cactus-compute/needle` 端侧模型 45M 参数、14MB 单文件、28MB RAM 就跑，向 250MB 级 Gemma/Apple FM 发起 5–70× 尺寸挑战。
> - `macro-inc/macro` Rust 全栈"团队 OS"日增 +1,180⭐，AGPLv3 开源，把 email/chat/docs/tasks/CRM/agent 揉进一张双向图。
> - `NVIDIA-NeMo/Switchyard` NVIDIA 官方下场做 LLM Router，Rust 实现、OpenAI/Anthropic 双协议互译。
> - `anthropics/skills`、`kepano/obsidian-skills`、`msitarzewski/agency-agents` 三大 Skills/Agent 仓库同时挂榜——Skills 变成 2026 下半年真正的开源货币。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 29 种编辑级图表 Skill，专为 Claude Code 打造 | HTML | 14,260 | +4,504 | 857 |
| 2 | [macro-inc/macro](https://github.com/macro-inc/macro) | Rust 全栈团队 OS：邮件/聊天/文档/CRM/Agent | Rust | 2,569 | +1,180 | 276 |
| 3 | [cactus-compute/needle](https://github.com/cactus-compute/needle) | 45M 参数端侧基础模型，14MB 单文件 | Python | 4,920 | +768 | 332 |
| 4 | [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | 完整的 AI Agency 系统，覆盖多种垂直职位 | Shell | 145,162 | +762 | 23,483 |
| 5 | [semantica-agi/semantica](https://github.com/semantica-agi/semantica) | 图原生 AI 基础设施：可解释 + 可审计 | Python | 6,577 | +727 | 692 |
| 6 | [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) | 用 CLI/开放格式操作 Obsidian 的 Agent Skills | Multiple | 45,675 | +411 | 3,295 |
| 7 | [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | Rust LLM 流量路由，跨模型/厂商保持兼容 | Rust | 1,185 | +408 | 106 |
| 8 | [anthropics/skills](https://github.com/anthropics/skills) | 官方 Agent Skills 公共资源库 | Python | 168,985 | +383 | 20,129 |
| 9 | [holaboss-ai/holaOS](https://github.com/holaboss-ai/holaOS) | 开源 AI Agent 工作空间，100+ 集成 | TypeScript | 6,544 | +380 | 598 |
| 10 | [unslothai/unsloth](https://github.com/unslothai/unsloth) | 本地跑 & 训练 LLM/Diffusion 的 UI | Python | 71,019 | +354 | 6,404 |
| 11 | [smicallef/spiderfoot](https://github.com/smicallef/spiderfoot) | 自动化 OSINT 情报收集平台 | Python | 20,646 | +278 | 3,313 |
| 12 | [3b1b/manim](https://github.com/3b1b/manim) | 3Blue1Brown 的数学动画库 | Python | 90,834 | +204 | 7,529 |
| 13 | [Lightricks/LTX-2](https://github.com/Lightricks/LTX-2) | 音视频联合生成模型官方包 | Python | 8,898 | +201 | 1,405 |
| 14 | [altic-dev/FluidVoice](https://github.com/altic-dev/FluidVoice) | macOS 端侧听写+AI 润色 | Swift | 9,828 | +187 | 662 |
| 15 | [megadose/holehe](https://github.com/megadose/holehe) | 通过邮箱查询多平台账号 | Python | 12,392 | +166 | 1,667 |

---

## 重点项目点评

### 🥇 [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) — 今日榜首，+4,504⭐

**"给 Claude Code 装的 29 种出图 Skill"，一战确立 Skills 生态的美学话语权**

自 Anthropic 8 月正式把 Agent Skills 变成 Claude Code 一等公民以来，社区大多数 Skills 都在解决"跑什么工具"、"接哪个 API"这类工程问题。cathrynlavery 直接把方向拧到"审美"——29 种编辑级图表（架构图、时序图、E-R、Gantt、四象限、雷达图……）打包成 Claude/Codex/Pi 共用的 Skills，自带 WCAG AA 对比度校验、自动从公司主页抽色、直接导出 PNG/SVG，把"AI 出图 = Mermaid 塑料风"这个刻板印象一次改写。

这是 Skills 生态第一个纯创作者身份、日增四千星的现象级项目，意味着 Skills 已经从"厂商内容"进入"社区明星"阶段。同一天 [anthropics/skills](https://github.com/anthropics/skills)（+383）与 [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills)（+411）同榜，说明 Skills 已经成为跨模型（Claude/Codex/Pi）都能复用的开源"通用货币"——很像 2023 年 langchain-tools、2024 年 MCP servers 那种拐点感。

---

### 🥈 [macro-inc/macro](https://github.com/macro-inc/macro) — +1,180⭐

**Rust 全栈重做"团队 OS"，AGPLv3 直击 Slack + Linear + Notion + HubSpot**

Macro 用 SolidJS 前端 + Rust 后端（167 个 crate、42 个可部署服务），把邮件、聊天、文档、任务、CRM、通话、Agent 装进一张 CRDT 双向图。差异点不是"另一个 Notion"，而是三点：一、Rust 全栈使得桌面/浏览器/移动端体验能真的做到"instant"；二、AGPLv3 开源+自托管商业化，直接跟 Notion/Linear 的封闭态度对冲；三、Agent 一等公民——email 里的对话、任务的状态、CRM 里的 deal 通过统一 graph 共享上下文，Agent 不需要人手动 wiring。

在 SaaS 采购预算被 AI 抢走的 2026，"用一个开源 workspace 换掉 4 家 SaaS"的叙事第一次有了工程扎实的候选者。macro-inc 的 GitHub 上一次现身还在 3 月，这周直接从谷底冲上第 2 名，说明 Rust + AGPL + Agent 三个热词叠加 + 真跑得动的代码，仍然是 GitHub 冲榜最稳的组合。

---

### 🥉 [cactus-compute/needle](https://github.com/cactus-compute/needle) — +768⭐

**端侧模型的"再小一档"：45M 参数、14MB 单文件、28MB RAM**

Needle 2 把端侧基础模型压到了新的物理下限：45M 参数、14MB 单文件、28MB RAM 就能推理。架构上叠了 Hadamard MLP + 分组查询注意力 + engram KV 记忆 + CQ2-bit 量化 + tool schema 编译成 byte-level grammar，官方对标 FunctionGemma 270M、LFM2.5 230M、Apple FM，尺寸小 5–70× 而在 tool calling / device control / structured extraction 上"trades wins"。

这个方向解决的是 Apple Intelligence、Pixel Gemini Nano 目前 250–500MB 级别模型的现实矛盾：wearable / 智能家居 / 车机场景根本不给你 512MB。Needle 把"foundation 模型"做进 wearable 硬件预算里，是继上月 Meta Muse Glimmer 开源之后另一个方向——不是把模型做大，而是把 sensor 场景做进模型。今天冲榜再次证明：端侧 SLM 是 2026 下半年最被低估的一条赛道。

---

### 🚀 [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) — +408⭐

**NVIDIA 官方进场做 LLM Router，用 Rust 而不是 Python**

Switchyard 是 NVIDIA-NeMo 组织下的 Rust 实现 LLM 路由器：OpenAI Chat / Anthropic Messages / OpenAI Responses 三种协议双向翻译，随机、LLM-分类、信号驱动、自研算法四种路由策略，Prometheus 指标全套。放出的定位是 pre-alpha，但仓库出现在 nvidia-nemo/ 下就是一个明确信号：NVIDIA 不再满足于"卖卡+推 NeMo 训练"，正在把 inference 侧的"客户上游流量"抓在自己手里。

这一步的战略含义远大于代码：如果 Switchyard 未来成为 NVIDIA Inference Microservice (NIM) 的默认前置层，那么"Anthropic 客户流量入到 NVIDIA 家 → 再决定去哪家 GPU/推理后端"，等于用一层 Router 反向把 OpenRouter / LiteLLM 的市场变成 NVIDIA 生态的功能子集。Rust 选型也很说明问题——Python 版 Router 已经卷成一片红海（LiteLLM 独大），Rust 一层是想借"性能 + 内嵌 library 路径"另开赛道。

---

### 📈 [semantica-agi/semantica](https://github.com/semantica-agi/semantica) — +727⭐

**用图数据库反攻 RAG：给"要审计的 AI"配一层"要能解释的记忆"**

Semantica 反着 RAG 的思路：不是拿 embedding + top-k 拼凑上下文，而是重新把 W3C PROV-O、SHACL、Datalog、OWL 那套图谱基建搬回来，把每个事实、每条推理、每个决策都变成 first-class graph object，附带 provenance、时间、冲突检测。目标场景直接点名了金融、医疗、政府/国防、法律——都是 EU AI Act 8 月强合规窗口下最痛的行业。

这个项目冲上第 5 名的信号非常清晰：2026Q3 开始的合规执行期把 "AI 结果解释性" 从 nice-to-have 变成合同必备条款，而现有 LLM 栈几乎没有原生方案。Semantica 用 "LLM 无关的确定性图基建" 抢占了这个空白位——这也是为什么 GitHub 上做 knowledge graph 十年没火过、今年反而回潮的原因。

---

## 生态观察

- **Skills 生态正在跨越"厂商内容"到"社区明星"的拐点。** 今日榜单 Top 15 里三个 Skills/Agent 仓库同时挂榜（`anthropics/skills`、`kepano/obsidian-skills`、`cathrynlavery/diagram-design`），加上 `msitarzewski/agency-agents` 与 `holaboss-ai/holaOS`，Skills/Agent 结构占据榜单近 1/3。cathrynlavery 这种个人开发者仓单日 +4.5k⭐ 说明社区已经开始用 Skills 打造"作者品牌"，跟 2020 年的 Awesome-list、2023 年的 Copilot Extensions 是同一个曲线的第 3 章。
- **Rust 在协作/基础设施赛道正在悄悄接管中间层。** `macro-inc/macro` 拿下第 2、NVIDIA `Switchyard` 冲进第 7——两个"下一代协作 + 下一代推理路由"都用 Rust。Python 依然是 AI 模型层的主场，但基础设施与终端应用层的默认语言正在向 Rust 迁移。
- **端侧模型开始按"MB 级"竞争。** Cactus Needle 把 45M 参数塞进 14MB 单文件，直接把 250M 参数的 Gemma/Apple FM 定义成"上一代大端侧模型"；同一天 macOS 端侧 dictation `FluidVoice` 也进榜。2026 下半年的端侧焦点已经从"Apple Intelligence 有没有用"跳到"能不能在 wearable/机器人上跑"。
- **合规驱动的老基建回潮。** Semantica 冲上第 5、macro 用 CRDT + AGPLv3 冲上第 2、Nine PBS 数据归属的讨论在 HN 同日刷屏，"数据/事实归属谁"这个老议题在 EU AI Act 生效之后被重新点燃。开源基建生态正在集体转向"能审计、能自托管、能解释"这三个词。
- **OSINT/取证工具持续在榜。** `spiderfoot` (+278) 和 `holehe` (+166) 常年冲榜，佐证 2026 年个人/企业风险面扩张仍在推动安全侧的工具需求。

---

_报告生成于 2026-08-14 (UTC+8)_
