# GitHub 每日趋势报告 · 2026-08-04

## 今日焦点

> **AI Agent 生态大爆发 · DeepSeek 生态双雄登榜 · AirLLM 4GB 单卡跑 70B · Firecrawl 转攻 Rust PDF · Anthropic Claude Code 影响力持续外溢**
>
> - `lyogavin/airllm` 单张 4GB 显卡跑 70B 推理，**+1,081⭐** 冲上榜首
> - `esengine/DeepSeek-Reasonix` 与 `antirez/ds4` 两个 DeepSeek 生态项目同日热榜，说明 DS 开源阵营正在形成
> - `firecrawl/pdf-inspector` **+1,769⭐**，用 Rust 重写 PDF 解析在 AI 数据管道里成刚需
> - `TencentCloud/TencentDB-Agent-Memory` 团队级 Agent 记忆库出圈，**+1,091⭐**
> - `Alishahryar1/free-claude-code` 蹭 Claude Code 热度，Anthropic 生态的溢出效应清晰可见

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [lyogavin/airllm](https://github.com/lyogavin/airllm) | 单张 4GB GPU 运行 70B 推理 | Jupyter Notebook | 26,992 | +1,081 | 2,964 |
| 2 | [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | AI 驱动的安全研究技能路由器 | PowerShell | 15,620 | +2,442 | 2,206 |
| 3 | [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) | 高性能 Rust PDF 解析库 | Rust | 8,036 | +1,769 | 537 |
| 4 | [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | DeepSeek 原生终端 coding agent | Go | 29,869 | +877 | 1,918 |
| 5 | [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) | 团队级 AI Agent 记忆中枢 | TypeScript | 12,019 | +1,091 | 1,137 |
| 6 | [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | 12 周 24 课 AI 通识课程 | Jupyter Notebook | 60,656 | +1,902 | 11,827 |
| 7 | [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 21 课生成式 AI 入门 | Jupyter Notebook | 115,504 | +776 | 61,431 |
| 8 | [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | 大型系统设计经典教程 | Python | 360,475 | +323 | 57,525 |
| 9 | [antirez/ds4](https://github.com/antirez/ds4) | DeepSeek 本地推理引擎（Metal/CUDA/ROCm） | C | 20,334 | +385 | 1,798 |
| 10 | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) | 金融市场语言的基础模型 | Python | 35,806 | +217 | 5,960 |
| 11 | [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | 给 AI Agent 一双看全网的眼睛 | Python | 65,660 | +1,052 | 5,454 |
| 12 | [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code) | 免费访问 Claude Code 等工具 | Python | 44,015 | +291 | 7,266 |
| 13 | [iv-org/invidious](https://github.com/iv-org/invidious) | YouTube 替代前端 | Crystal | 22,251 | +403 | 2,479 |
| 14 | [livekit/agents](https://github.com/livekit/agents) | 实时语音 AI Agent 框架 | Python | 11,944 | +129 | 3,456 |
| 15 | [usekaneo/kaneo](https://github.com/usekaneo/kaneo) | 开源项目管理工具 | TypeScript | 6,820 | +663 | 551 |

---

## 重点项目点评

### 🥇 [lyogavin/airllm](https://github.com/lyogavin/airllm) — 今日榜首，+1,081⭐

**4GB 显卡跑 70B 模型：把 LLM 推理带回消费级 GPU**

AirLLM 通过**逐层加载 + KV cache offloading + 极致量化**，让 70B 参数模型可以在**只有 4GB 显存**的显卡（如 GTX 1050 Ti、集成显卡）上推理。原理是把每一层从磁盘/内存动态搬入显存计算完再释放，牺牲吞吐换显存占用——单 token 耗时几秒到十几秒，但结果是**你的老 ThinkPad 也能跑 Llama 70B**。

今天上榜说明两件事：（1）**社区仍在乎"能在自己电脑跑"这件事**，即便云 API 越来越便宜；（2）在 GPU 供给紧张的地区（中国、教育机构、研究个人），"用现有硬件榨出 70B 能力"是刚需。同一天登上 HN 首页（175 分）说明这不是刷榜，是真实需求信号。

---

### 🥈 [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) — +1,769⭐

**Firecrawl 把 PDF 解析这块拼图补上，AI 数据管道全栈 Rust 化**

Firecrawl 从最初的"AI 友好爬虫"，一路扩展到内容清洗、结构化提取，现在再抛出一个**用 Rust 从头写的 PDF 解析库**。相比传统的 Python 生态（PyMuPDF、pdfplumber），pdf-inspector 主打**单文件吞吐更高、内存占用更低、可作为 Rust 服务嵌入**。目标场景很明确：**RAG 系统与 Agent 抓取管道**——PDF 是绝大多数企业文档的原始格式，解析速度和结构保真度直接决定检索质量。

今日 +1,769⭐ 的力度说明社区对"Rust 重写 AI 数据基础设施"这条主线的兴趣不减。跟 AirLLM 一起看，一个共同点是：**AI 系统性能优化的下沉压力正在从模型层扩散到数据层**。

---

### 🥉 [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) — +2,442⭐

**PowerShell 写的"安全研究技能路由器"，一天涨 2,442⭐ 的黑马**

这是一个用 PowerShell 编排的 AI 驱动安全研究工具集，把常见的逆向、漏洞挖掘、payload 生成、静态分析工具做成"skill"，通过路由器自动挑选并调用。语言选 PowerShell 有点意外，但符合 Windows 侧红队/蓝队研究人员的工作习惯。**+2,442⭐ 是今日增速冠军**——说明 AI Agent × 安全研究这个交叉点正在被大量红队工程师主动关注。

需要注意的合规提醒：这类工具的用途高度依赖使用者身份，仓库内容主要面向授权安全研究和 CTF 场景。

---

### 🎯 [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) + [antirez/ds4](https://github.com/antirez/ds4) — DeepSeek 生态双雄

**DeepSeek 从"能替代 OpenAI"进入"催生独立生态"阶段**

Reasonix 是一个用 Go 写的 DeepSeek 原生 terminal coding agent（对标 Claude Code），ds4 则是 Redis 之父 antirez 亲手做的 DeepSeek 本地推理引擎（C 语言、支持 Metal/CUDA/ROCm）。两个项目同日进入 GitHub Trending 前 10，构成了一个非常清晰的信号：**DeepSeek 已经不再只是"云端便宜模型"，围绕它的应用侧与推理侧工具链都在快速搭起来**。

antirez 这一手尤其有意思——一个以 Redis / KV store 闻名的 legend 亲自下场写推理引擎，说明**"我要在自己电脑上跑 DS，而且我要写得比现有的开源方案更快"**已经成为 systems 圈的新兴趣点。这跟 llama.cpp 早年的势能是一样的。

---

### 🧠 [TencentCloud/TencentDB-Agent-Memory](https://github.com/TencentCloud/TencentDB-Agent-Memory) — +1,091⭐

**团队级 Agent 记忆库：把"个人 Agent 记忆"升级为"组织资产"**

腾讯云推出的 Agent-Memory 主打**跨团队复用的记忆资产管理**——一个团队跑过的 Agent 会话、总结出的 SOP、验证过的 tool call 序列可以被打包成"可复用 memory asset"，让新加入的 Agent 快速继承经验。这是继 Mem0、Zep、Letta 之后，中国云厂商在 Agent 记忆层的第一个正面回应，也是**"企业 Agent 生态从个人 pilot 走向组织级部署"**的典型信号。

+1,091⭐ 说明企业侧对这个方向的关注度非常高。可以预期未来 3-6 个月，阿里云、火山、字节都会跟进类似产品，Agent 记忆层将成为云厂商争夺的新战场。

---

## 生态观察

**AI Agent 主线不变，但焦点从"框架"转向"工具链 + 记忆 + 数据管道"。** 今日榜单里，纯 Agent 框架（LiveKit Agents 排 14）已经不再是话题中心，取而代之的是 **Agent 记忆（TencentDB-Agent-Memory）、Agent 数据源（Agent-Reach）、Agent 数据管道（pdf-inspector）、Agent 本地推理（AirLLM/ds4）**——生态正在从"能跑 Agent"进化到"跑好 Agent 需要的一切拼图"。

**DeepSeek 生态开始独立成势。** Reasonix（Go）+ ds4（C）+ 昨日的 V4-Flash-0731 定价，DS 阵营正在快速拉起一整套"从模型到工具"的开源栈。这是 2026 下半年最值得跟踪的开源势能之一。

**Rust 在 AI 基础设施里继续加码。** Firecrawl 的 pdf-inspector 是今日增速第二，Rust 在 AI 数据管道（爬虫、解析、向量索引、推理服务）里的份额还在扩大——Python 写业务、Rust 写基础设施 已经成为新范式。

**Claude Code 的溢出效应清晰。** `free-claude-code` 蹭热度上榜，Reasonix 直接对标 Claude Code——**Claude Code 已经成了"AI 编码工具"品类的默认参照物**，即便你不用 Anthropic，也逃不开它定义的产品形态。
