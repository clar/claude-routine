# GitHub Trending 日报 · 2026-07-29

## 今日焦点

> **Claude 生态工具三连爆 · AI 陪伴 airi 破 4.4 万星 · 3D 建筑协作编辑器一日 +415⭐ · 终端 UI 复兴 (superfile) · 地理空间开源平台 GeoLibre 出圈**
>
> - `bradautomates/claude-video` 让 Claude 具备"看视频"能力，一日 +989⭐，是当前上涨速率之最。
> - `moeru-ai/airi` 自托管 AI 语言/游戏陪伴，累计 44,721⭐，正成为开源版 Character AI。
> - `pascalorg/editor` 3D 建筑项目协作编辑器，一日 +415⭐，SaaS 化开源工具重现势头。
> - `yorukot/superfile` Go 写的现代 TUI 文件管理器 +660⭐，终端 UI 审美继续复兴。
> - `virgiliojr94/book-to-skill` PDF 技术书自动转 Claude Code skill，切中"AI 学习-使用一体化"痛点。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [bradautomates/claude-video](https://github.com/bradautomates/claude-video) | 给 Claude 视频观看能力，自动下载+抽帧+转写 | Python | 12,042 | +989 | 1,209 |
| 2 | [moeru-ai/airi](https://github.com/moeru-ai/airi) | 自托管 AI 语言/游戏陪伴，Minecraft/Factorio 联动 | TypeScript | 44,721 | +796 | 4,446 |
| 3 | [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) | 云原生 GIS 平台，地理数据可视化与分析 | TypeScript | 3,349 | +743 | 389 |
| 4 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | AI Agent 性能优化框架，含记忆与技能管理 | JavaScript | 234,748 | +692 | 35,770 |
| 5 | [yorukot/superfile](https://github.com/yorukot/superfile) | 现代化 TUI 文件管理器 | Go | 21,439 | +660 | 695 |
| 6 | [pascalorg/editor](https://github.com/pascalorg/editor) | 3D 建筑项目协作编辑器 | TypeScript | 18,627 | +415 | 2,523 |
| 7 | [paperswithbacktest/awesome-systematic-trading](https://github.com/paperswithbacktest/awesome-systematic-trading) | 系统化量化交易资源合集 | Python | 9,526 | +402 | 1,289 |
| 8 | [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | PDF 技术书自动转 Claude Code skill | Python | 11,256 | +366 | 1,329 |
| 9 | [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins) | 老牌自动化服务器仍在榜 | Java | 26,059 | +180 | 9,686 |
| 10 | [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech) | 全本地开源语音 Agent 栈 | Python | 7,181 | +177 | 949 |
| 11 | [andrewyng/aisuite](https://github.com/andrewyng/aisuite) | 多 GenAI 供应商统一 SDK | Python | 15,662 | +92 | 1,655 |
| 12 | [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | Agent 安全与合规治理框架 | Python | 5,167 | +17 | 833 |

---

## 重点项目点评

### 🥇 [bradautomates/claude-video](https://github.com/bradautomates/claude-video) — 今日榜首 +989⭐

**"让 Claude 看视频"是 skill 生态最缺的那块拼图**

思路极简：一个 `/watch` slash command，接受视频 URL，自动 yt-dlp 下载、按关键帧抽样、Whisper 转文字，然后把摘要 + 关键帧 + 转录一起塞给 Claude。整个链条没有原创技术，价值在"打包"——把 5 个原本要工程师自己串的工具做成一条命令。

它为什么今天窜？两个原因。一是 Claude Code Skills 生态在 6 月开放后，社区一直在寻找"最直观的 killer skill"——视频理解是所有 LLM 用户都能立刻感知价值的场景。二是 Sora/Veo/Kling 生成视频泛滥后，"看视频"变成必要能力：给 AI 讲 5 分钟视频比让它读 5000 字容易得多。

这也符合"AI 工具的最大空间不在模型层、而在 workflow 层"的判断。一个封装漂亮的 skill 一天 989⭐，含金量比大多数新框架高。

---

### 🥈 [moeru-ai/airi](https://github.com/moeru-ai/airi) — +796⭐ (累计 4.4 万⭐)

**开源 Character AI 的正规军版本**

airi 是自托管的 AI 语音陪伴系统，可以接 Ollama / Claude API / OpenAI，除了对话之外还提供 Minecraft、Factorio 等游戏内 NPC 集成。今天窜的直接原因是 v0.7 发布——加入了 Kimi K3 (开源当天就跟进) 和 Grok 4.5 的适配层。

值得注意的是这个项目的"品类定位"——它明确对标 Character AI 但强调自托管、隐私、可玩性。评论区不少人反馈用它做家庭助手、儿童英语角色扮演。**大型消费级 AI 陪伴创业公司(Character AI 已被 Google 收编、Replika 舆情不佳)的用户，正在向自托管替代迁移**。airi 是这个迁移趋势最直接的受益方。

累计 4.4 万⭐意味着它已经从"极客玩具"进入"轻度消费者"视野。UI 用了 Nuxt + Tauri，桌面/移动端都能跑。

---

### 🥉 [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) — +743⭐

**QGIS 的云原生开源挑战者**

GeoLibre 定位是"云原生 GIS 平台"，直接对标 Esri ArcGIS Online 和商业版 Mapbox Enterprise。技术栈是 TypeScript + WebGL2，后端接 PostGIS，支持大规模矢量瓦片和影像分析。今天上榜的直接原因是它的 0.5 版本加入了 AI 影像分类工作流——用户上传卫星影像，直接在浏览器里跑分割模型。

地理空间是一个长期被商业软件锁住的赛道 (Esri 年收入 15 亿美元)。QGIS 桌面端很成熟但云端始终不够顺畅。GeoLibre 试图填这个缺口，而且踩中了"AI + 地理"的风口——LLM 对空间数据的推理能力今年成熟得非常快。

这类项目通常前期慢热，一旦被政府部门或高校采纳，增长会很稳定。值得放到长期观察名单。

---

### 🏅 [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) — +366⭐

**PDF 技术书直接编译成 Claude Code skill：AI 时代的"读书方式"变了**

工作流：喂一本 PDF (比如 Kernighan & Pike《Practice of Programming》)，脚本自动分章节、提取关键代码模板、总结方法论，最后生成一个可以 `/invoke` 的 Claude Code skill 目录结构。也就是说，你可以把一本书变成"随时可以让 Claude 调用其中知识的插件"。

这是"人 → AI 知识流水线"的一个精巧样本。传统读书笔记是给自己回顾用的，book-to-skill 是给 AI Agent 用的。这两种"知识存储介质"的分化，未来 12 个月会变成一个明确的产品品类。

有意思的批评：评论区有人质疑"这不就是把 PDF 塞进 RAG 吗？"作者回答核心区别是"skill 是被主动召唤的、RAG 是被动匹配的"。这个区分成立与否值得继续观察。

---

### 🎯 [yorukot/superfile](https://github.com/yorukot/superfile) — +660⭐

**Go 写的现代 TUI 文件管理器，终端审美继续复兴**

superfile 已经 21K 星，最近半年增长很稳。今天再窜一波是因为 v2.0 发布——加入了插件系统、SFTP/S3 远程挂载、Nerd Font 图标全适配。定位是 vim + ranger + midnight commander 的融合升级版，键位学习曲线陡但生产力上限很高。

**"新一代 TUI 工具"是 2024-2026 GitHub 的一个明确品类**：atuin、helix、lazygit、zellij、glow、bat 都属于这一波。共同特点：Rust 或 Go 写、Nerd Font 依赖、可插件、比传统命令行 UX 好 3-5 倍。superfile 是文件管理这一垂直领域的代表作。

背后的社区情绪是明确的："我不想每天在 web GUI 里点鼠标做本可以三个键完成的事"。远程办公 + AI 助手 + Terminal 复兴，三者是一个共同现象。

---

## 生态观察

**主题一：Claude / Agent 生态的工具化正在提速。** claude-video、book-to-skill 一天分别 +989⭐ 和 +366⭐，加上后台常驻 top15 的 aisuite、agent-governance-toolkit，说明"给 Claude/GPT 装能力"这件事从"框架层" (LangChain 时代) 下沉到了"单一 skill 打包"层。这是 skills、MCP 的组合威力开始释放的信号。

**主题二：自托管 AI 应用继续攻城略地。** airi (陪伴)、speech-to-speech (语音 agent)、GeoLibre (GIS AI) 都是"自托管 + AI 能力"的组合。它们瞄准的是过去几年被 SaaS 化的品类，用"数据不出本地 + 能接任意 LLM"作差异化。这类项目的星星积累速度往往比框架类快，因为最终用户价值直接。

**主题三：非 AI 品类里，"现代化开发工具"和"金融量化"仍稳定入榜。** superfile、jenkins、awesome-systematic-trading 说明基础工具和知识合集永远有需求。特别 systematic-trading 类目在过去半年频繁上榜，反映一批人在做"AI + 量化"结合的探索。

**主题四：Microsoft agent-governance-toolkit 上榜是个信号。** 大厂开始正式给 AI Agent 出治理框架，配合 EU AI Act 8/2 大限、GPT-5.6 Sol 逃逸事件的舆情——**"给 Agent 上安全和合规"从今天起是一个真正的产品品类**，未来会出现 AI-native 的审计 / 沙箱 / 权限管理 SaaS。
