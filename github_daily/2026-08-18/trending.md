# GitHub Trending 每日热榜 · 2026-08-18

## 今日焦点

> **AI 视频工厂 · AI 代理内存 · AI 渗透测试 · Rust 交易系统 · 苹果本地推理**
>
> - `harry0703/MoneyPrinterTurbo` +1,275⭐：AI 短视频流水线连续两天冲榜第一，产品化极强。
> - `cordiverse/cordis` +959⭐：TypeScript 时空组合元框架，一天涨 17%，最快"暗马"项目。
> - `usestrix/strix` +656⭐：开源 AI 渗透测试工具，把 Wiz 揭露的"AI 代理会写漏洞"变成"AI 代理会找漏洞"。
> - `akitaonrails/ai-memory` +207⭐：给 Claude Code / Cursor / Codex 等 CLI 做跨供应商长期记忆。
> - `AlexsJones/llmfit` +239⭐：一条命令挑出你显卡跑得动的 LLM，本地推理选型工具火起来了。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | 关键词一键生成高清短视频的 AI 流水线 | Python | 105,904 | +1,275⭐ | 16,098 |
| 2 | [cordiverse/cordis](https://github.com/cordiverse/cordis) | 时空可组合性元框架 | TypeScript | 5,548 | +959⭐ | 294 |
| 3 | [usestrix/strix](https://github.com/usestrix/strix) | 开源 AI 渗透测试代理 | Python | 54,093 | +656⭐ | 5,791 |
| 4 | [immich-app/immich](https://github.com/immich-app/immich) | 自托管高性能照片/视频管理 | TypeScript | 111,105 | +337⭐ | 6,574 |
| 5 | [agalwood/Motrix](https://github.com/agalwood/Motrix) | 全功能下载管理器 | TypeScript | 53,026 | +295⭐ | 4,926 |
| 6 | [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit) | 一条命令找到"跑得动"的本地 LLM | Rust | 32,223 | +239⭐ | 1,997 |
| 7 | [vinta/awesome-python](https://github.com/vinta/awesome-python) | 权威 Python 工具/库合集 | Python | 314,497 | +226⭐ | 28,528 |
| 8 | [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) | Coding Agent 跨厂商长期记忆 | Rust | 1,996 | +207⭐ | 192 |
| 9 | [mukul975/Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) | 817 个 Claude Skills 结构化安全技能 | Python | 28,372 | +156⭐ | 3,446 |
| 10 | [santifer/career-ops](https://github.com/santifer/career-ops) | AI 找工作/投简历自动化 | JavaScript | 64,575 | +147⭐ | 12,650 |
| 11 | [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) | 生产级 Rust 交易引擎 | Rust | 25,878 | +115⭐ | 3,371 |
| 12 | [jundot/omlx](https://github.com/jundot/omlx) | Apple Silicon 上带 SSD 缓存的连续批处理 LLM Server | Python | 18,966 | +96⭐ | 1,644 |
| 13 | [openai/whisper](https://github.com/openai/whisper) | 多语种鲁棒语音识别 | Python | 107,469 | +89⭐ | 13,053 |
| 14 | [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | Stable Diffusion 全家桶 WebUI | Python | 164,550 | +31⭐ | 30,553 |
| 15 | [mickael-kerjean/filestash](https://github.com/mickael-kerjean/filestash) | 万能文件存储客户端 | Go | 14,501 | +17⭐ | 1,002 |

---

## 重点项目点评

### 🥇 [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) — 今日榜首，+1,275⭐

**"AI 短视频流水线"从玩具进入十万星俱乐部**

MoneyPrinterTurbo 是一条"关键词进、成品竖屏视频出"的完整流水线：脚本生成、素材匹配（Pexels / 本地库）、字幕对齐、TTS、BGM 混音、导出全部由 LLM + 开源模型串起来。它今天以 1,275 颗新星登顶，累计冲破 10.5 万，Fork 数已达 1.6 万——按 Fork/Star 比例是当前榜单最"被真正使用"的项目之一。

它今天再度冲榜的原因和 8 月中旬 Higgsfield / Sora 系列消费端 AI 视频公司的暴涨完全同频：**"个人可运营"式内容工厂正在成为一种普遍生活方式**，无论是 TikTok 混剪、YouTube Shorts 还是国内的抖音号。MoneyPrinterTurbo 的价值在于它给了非程序员一个"docker compose up 就能开工"的完整包，比商业 SaaS 更贴合"批量、匿名、成本敏感"的长尾创作者。

有意思的是它并没有集成任何自研模型——所有能力都是把主流 API/开源模型拼装起来，说明 2026 年真正稀缺的不是能力，而是"最后一公里的产品化能力"。

---

### 🥈 [cordiverse/cordis](https://github.com/cordiverse/cordis) — +959⭐

**"时空可组合性"元框架，一天涨 17%**

Cordis 是一个 TypeScript 编写的元框架，标榜"Spatiotemporal Composability"——把插件（Plugin）、生命周期（Lifecycle）、依赖注入（DI）和事件总线（Bus）四个基础抽象组合成一个可以在 Node、Bun、Deno、浏览器多环境跑的运行时。它今天从 5.5k 起步一次涨 959 颗星，是榜单里增长率最快（+17%）的项目。

背景是：Cordis 原本是国内知名聊天机器人框架 Koishi 的运行时内核，作者最近把它独立出来发新版并开始面向"AI Agent Runtime"营销——正好戳中当下"我要一个能装插件、能热更新、能跨语言绑定、能被 LLM 调度"的开发者痛点。TypeScript 生态里目前缺乏一个和 Elixir/OTP 一样成熟的"运行时抽象"，Cordis 想抢这块空位。

对国内开发者而言，这是继 KoishiJS、Cordis Console 之后，中文开源作者一次难得的"框架层"输出，如果它能被 Copilot Chat / Roo Code / Cline 这类 Agent 平台接纳成插件运行时，价值会指数级放大。

---

### 🥉 [usestrix/strix](https://github.com/usestrix/strix) — +656⭐

**用 AI 代理反打 AI 应用的第一款开源工具**

Strix 是一个开源"AI 渗透测试代理"，输入一个网站/App/API，AI 会自主选择工具（如 nmap、sqlmap、Burp 等）执行侦查、指纹识别、漏洞验证，并生成可复现的报告。它累计 5.4 万星，今天再涨 656 颗，正好赶上昨晚 Wiz 披露"GitHub Copilot Autofix 打穿 Snowflake Jira"的热度——社区显然想要一款能对称"打回去"的攻击方模拟工具。

不同于 Metasploit 这种手动框架，Strix 的思路是"把 pentester 的经验固化成一组 LLM 可读的 skill 卡片"，然后让代理自主规划。这也是 GitHub 榜单里第 9 名 `Anthropic-Cybersecurity-Skills`（817 个 Claude Skills 结构化技能）今天大涨 156 颗星的同一线索：**AI 安全正在从"人类专家 + AI 辅助"变成"AI 代理 + 结构化知识包"**。

值得警惕的是，Strix 面世也意味着"低门槛自动化漏洞挖掘"进入野外——2026 年下半年，防守方需要重新评估自己 asset surface 的暴露程度。

---

### 🤖 [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) — +207⭐

**Coding Agent 跨供应商长期记忆的第一次靠谱尝试**

在 Claude Code、Cursor、Codex、Amp、Cline 之间切换是当下开发者的日常烦恼——每换一个 CLI，上下文和历史决策就全丢了。ai-memory 提供一个统一的 Rust 后端，把"这个项目里我们决定过什么"沉淀成结构化记忆（带版本、带 embedding、带 tag），任何遵循 MCP 协议的 Coding Agent 都能读写它。

它今天一天涨了 10% 的星，评论区最典型的一句话是："我不在乎哪个 Agent 更聪明，我在乎它记得我们上周的架构决定。"——这直接呼应了上周 Anthropic 官方推的 "Skills + Memory MCP" 组合。可以预见接下来几个月，"记忆层"会像去年的"上下文长度"一样成为 Coding Agent 之间的核心竞争维度。

---

### 🧪 [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit) — +239⭐

**"我的显卡能跑什么模型"这个日经问题终于有官方答案了**

llmfit 是一个 Rust CLI：给它一台机器（本地或远程），它会枚举本地 GPU/CPU/RAM 情况，然后从数百个开源模型（Llama、Qwen、Mistral、DeepSeek、Phi 等）里找出"能以合理时延跑起来"的组合，并推荐推理引擎（llama.cpp / vLLM / MLX / Ollama）。

它今天冲榜是因为大量开发者被 DeepSeek V4-Pro 官方 API 涨价 4-11 倍的消息（8 月 14 日 Caixin 报道）刺激到，开始重新评估"本地跑一个次一档模型是否更划算"。llmfit 恰好把这个决策从半天的 Excel 计算，压缩到 30 秒的命令行输出。

搭配榜单 12 名的 `jundot/omlx`（Apple Silicon 上带 SSD 缓存的连续批处理 LLM 推理服务器），今天榜单实际上给出了一整套"逃离云推理账单"的工具链雏形。

---

## 生态观察

今天的 GitHub Trending 呈现三条清晰主线：

**1. AI 代理进入"Skills + Memory + Runtime"阶段**：ai-memory、Anthropic-Cybersecurity-Skills、cordis 都是围绕"代理需要什么才能真正稳定长期工作"给出的答案——不再是更大的模型，而是更结构化的知识包 + 更持久的记忆 + 更专业的运行时。

**2. AI 内容工厂持续爆发**：MoneyPrinterTurbo（AI 视频）、career-ops（AI 找工作）、Whisper（语音）连续多天进入榜单，反映出"AI 已经从生产力工具下沉到生活方式工具"这一趋势。

**3. 本地推理反攻**：llmfit、omlx、以及 Rust 阵营的持续走强（nautilus_trader、llmfit、ai-memory 三个 Rust 项目同时上榜），呼应了 DeepSeek 涨价、云推理账单飙升带来的"本地/边缘/离线"回流。

**4. AI 安全成为独立赛道**：Strix 和 Anthropic-Cybersecurity-Skills 同日入榜，加上昨天 Wiz 披露的 Copilot Autofix 漏洞，表明"AI 找漏洞 vs AI 写漏洞"的攻防双方都开始产品化。

**一句话总结：** 今天的榜单像是一份"后大模型时代的开发者购物车"——**你需要一个 Skills 包、一段可迁移的 Memory、一个能跑得动的本地模型、和一个能同时应对攻防的安全代理。**
