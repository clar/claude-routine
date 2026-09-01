# GitHub Trending 日报 · 2026-09-02

## 今日焦点

> **Claude Code 生态霸榜 · 小模型训练文化再起 · Agent 工具链 · 教育与多智能体 · 视频/PDF 自动化**
>
> - `THU-MAIC/OpenMAIC` **今日 +3,122⭐**，多智能体交互课堂，清华系团队把 LLM 教育场景做成开源基建。
> - `jingyaogong/minimind` **+1,005⭐**，"2 小时从零训练 64M 参数 LLM"再度点燃 HN + 中文技术圈。
> - `affaan-m/ECC` **+621⭐**、`Imbad0202/academic-research-skills` **+161⭐**、`K-Dense-AI/scientific-agent-skills` **+914⭐**、`handsomestWei/patent-disclosure-skill` **+502⭐**、`VoltAgent/awesome-design-md` **+487⭐** —— Claude Code Skills 生态一天六个仓库上榜，成为最强子文化。
> - `firecrawl/pdf-inspector` **+545⭐**：Rust 写的极速 PDF 抽取器，喂给 RAG 流水线的新标配。
> - `browser-use/video-use` **+509⭐**：把"用 Agent 剪视频"从 demo 变成正式项目，Browser Use 团队再落一子。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [Gitlawb/openclaude](https://github.com/Gitlawb/openclaude) | "runs anywhere. uses anything" —— 开源 Claude Code 兼容运行时 | TypeScript | 31,244 | +37 | 8,945 |
| 2 | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | 面向 Claude Code 的学术研究 Skills 包 | Python | 44,842 | +161 | 3,548 |
| 3 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | 开源多智能体交互课堂 (Multi-Agent Interactive Classroom) | TypeScript | 29,404 | +3,122 | 4,964 |
| 4 | [iv-org/invidious](https://github.com/iv-org/invidious) | 隐私向 YouTube 替代前端 | Crystal | 23,748 | +583 | 2,674 |
| 5 | [jingyaogong/minimind](https://github.com/jingyaogong/minimind) | 2 小时从零训练 64M 参数 LLM | Python | 57,007 | +1,005 | 7,413 |
| 6 | [3b1b/manim](https://github.com/3b1b/manim) | 数学解说视频动画引擎 | Python | 92,523 | +74 | 7,615 |
| 7 | [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) | Rust 高速 PDF 解析与抽取库 | Rust | 17,888 | +545 | 1,218 |
| 8 | [browser-use/video-use](https://github.com/browser-use/video-use) | 用编码 Agent 编辑视频 | Python | 22,887 | +509 | 2,810 |
| 9 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 165+ 已验证科研 Agent 技能集 | Python | 41,495 | +914 | 3,825 |
| 10 | [handsomestWei/patent-disclosure-skill](https://github.com/handsomestWei/patent-disclosure-skill) | 中文专利分析与撰写 Skill | Python | 6,674 | +502 | 759 |
| 11 | [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) | 面向 UI 代码生成的设计系统 Markdown 集合 | Mixed | 112,661 | +487 | 12,771 |
| 12 | [averygan/reclip](https://github.com/averygan/reclip) | 几乎任意站点视频下载器 | HTML | 7,610 | +21 | 1,313 |
| 13 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Claude Code 的 Agent 优化系统 | JavaScript | 245,733 | +621 | 37,085 |
| 14 | [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) | 面向 LLM 的开源网页爬虫 | Python | 80,823 | +179 | 8,354 |

---

## 重点项目点评

### 🥇 [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) — 今日榜首，+3,122⭐

**清华系推出的"多智能体交互课堂"，把 LLM 教育场景做成开源底座**

OpenMAIC (Open Multi-Agent Interactive Classroom) 由清华 MAIC 团队开源，用 LLM 模拟教师 + 学生 + 助教 + 评估者四类角色，支撑从课程编排、随堂问答、作业批改到个性化辅导的一整套教学循环。选用 TypeScript 而非 Python 的关键是"前端可视化课堂 + 后端可插拔模型" —— 用户可以直接对接 Claude、GPT-5.6、GLM、Qwen 等多家模型做 A/B。

单日 +3,122⭐ 的爆发跟三个动因合流：一是"AI + 教育"在国内进入新学期档口，二是清华 MAIC 之前发的"AI 助教让学生分数显著提升"论文 8 月底被 Nature 子刊接收，三是这是全球第一个把 multi-agent teaching 做成"开箱即用"的工程实现。评论区已经有海外大学团队讨论把它 fork 成本校版本。

对开发者的信号很清晰：多智能体框架 (AutoGen、CrewAI、LangGraph) 的下一个变现方向不是"通用 agent"，而是"具体行业的可编排角色系统"，教育是其中最容易被 top-down 采纳的场景。

---

### 🥈 [jingyaogong/minimind](https://github.com/jingyaogong/minimind) — +1,005⭐

**"2 小时训 64M 模型"文化的再一次回潮**

minimind 用极简 pytorch 实现，从 tokenizer、预训练、SFT、DPO 到 MoE 全流程一条龙，能在单卡 3090 上 2 小时训练出一个 64M 参数的中文迷你 LLM，直接可以聊天。项目本身已经有 57k 星，今天+1005 是因为作者更新了"小模型能力上限"实验：将模型放大到 300M，在数学题、代码补全等任务上给出了详细比对。

它今天再次爆火的原因和 HN 前排"1.5 小时训练小模型打过很多 LLM"是同一股风：**开发者对"必须用 GPU 农场"的叙事产生疲劳**，希望在自家硬件上重演 LLM 训练流程。minimind 的价值不在于打 benchmark，而在于把整条流水线做到"读代码即懂原理"，成为无数中文技术圈开发者入门 LLM 训练的第一课。

未来看，这类项目会继续与 llama.cpp、mlx-lm、SmolLM 之类的"边缘 LLM"生态互相强化 —— 云 API 越贵，"我自己训一个"的社区就越活跃。

---

### 🥉 [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) — +914⭐

**"165+ 已验证科研技能"，Claude Code Skills 走向学术专业化**

这个仓库把生物信息、材料模拟、文献计量、图像分析等 165 个科研常见任务，逐一封装成 Claude Code Skills（.claude/skills/xxx/SKILL.md 结构），每个都带 sample data + evals。它今天涨 +914⭐ 的一个直接推动力是 Anthropic 昨晚官方博客把它列为"科研场景 Skills 参考实现"。

值得关注的不只是这个仓库，而是它 + `academic-research-skills` + `patent-disclosure-skill` + `awesome-design-md` + `openclaude` + `ECC` 六个 Claude Code 生态项目**同一天上榜**。GitHub Trending 上一次出现这种"单一 CLI 生态霸榜"的情况，是 2023 年 LangChain 全盛期。信号非常明显：**Claude Code 已经从"编程助手"进化为"垂直行业 AI 工作流的分发渠道"**，每个专业领域都在孕育自己的 Skills 生态。

对开发者来说，短期机会点在于选一个自己熟悉的行业（法律、医疗、金融、K12 教育）把 SOP 封成一套 Skills 包发出来，几乎是 2024 年"开源 GPT prompt 集合"套利的翻版，但门槛更高、复用性更强。

---

### 🚀 [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) — +545⭐

**Rust 写的极速 PDF 抽取器，成为 RAG 流水线新的默认零件**

Firecrawl 团队去年因为把"给 LLM 用的网页抓取"做成商业化 SaaS 火起来，这次开源 pdf-inspector 是他们下一步 —— 用 Rust 实现的 PDF 解析器，能在毫秒级完成表格识别、图像抽取、结构化输出，直接吐 markdown/json 给下游 LLM 消费。今天 +545⭐ 主要来自 X 上多个 RAG 从业者对比 `pdfplumber`、`unstructured`、`docling` 后的"性能屠榜"截图。

这个方向的战场其实非常拥挤（IBM Docling、Marker、MinerU 都在竞争），但 pdf-inspector 的差异在"零 Python 依赖 + 单二进制部署 + WASM 分发"，特别适合塞进 edge agent 或 desktop 应用（比如 Codex 桌面版）里。当"AI 应用装机体积"成为 HN 讨论焦点（同日 Codex 打包 LibreOffice 被吐槽），Rust 极简依赖的抽取器就是一个天然的对症解法。

---

### 🤖 [browser-use/video-use](https://github.com/browser-use/video-use) — +509⭐

**Browser-Use 出品，用编码 Agent 剪视频，Agent 落地场景再扩一格**

Browser Use 团队去年靠 `browser-use` 把 "自然语言操控浏览器" 做成事实标准，这次新开源的 `video-use` 把同一套 Agent 范式搬到 DaVinci / ffmpeg / OpenCV 之上，让 Claude / GPT 用自然语言指挥剪辑：切段、字幕、转场、配乐。README 里演示了"给一段 45 分钟录像自动剪出 3 分钟高光合集"，社区第一天就有人用它做 podcast to short 的流水线。

它爆红的技术含义在于验证了一件事：**Browser Use 的 agent-tool 抽象是通用的**，只要把"目标应用的可编程 API"抽成同一套 tool schema，同一个 Claude/GPT 就能操控完全不同的软件栈。video-use 之后，可以预期 audio-use、cad-use、design-use 这种"XX-use"系列会成为 Agent 工具链的重要分支。

对开发者的启示：不要再做"从零起一个 Agent 框架"，而应该做"某个专业软件的 Agent 桥接层"。

---

## 生态观察

**Claude Code 生态大爆发**。一天之内 6 个 Claude Code 相关项目上榜（openclaude / academic-research-skills / scientific-agent-skills / patent-disclosure-skill / awesome-design-md / ECC），这是 GitHub Trending 极其罕见的"单一 CLI 主导日"。Skills、Subagents、CLAUDE.md 已经从"Anthropic 的实验特性"变成了社区通用词汇，未来 6 个月，会出现类似"npm for Claude Skills"的分发市场（open-claude 已经有这个雏形）。

**小模型训练文化持续升温**。minimind +1005⭐ 与 HN 上"1.5 小时训 44M 打过 LLM"同频。开发者们在用"自己训一个"的方式对冲"云端模型太贵、政策不稳、隐私不敢"的焦虑。

**多智能体从 demo 走向垂直**。OpenMAIC 是一个信号：多 Agent 不再是通用编排框架的赛道，而是"教育 / 医疗 / 客服 / 研发"这种具体场景的舞台化。CrewAI、AutoGen 需要做出行业模板才能守住阵地。

**"Agent-for-app"抽象层已成形**。Browser Use 的 video-use + Firecrawl 的 pdf-inspector 表明：新的商机不在于自研模型，而在于把常见工作流软件包装为 Agent 可调用的 tool schema。RAG 时代之后，Tool 层将成为下一个新兴生态。

**内容自主 / 反平台情绪延续**。invidious（YouTube 替代前端）+ reclip（视频下载）+ HN 上的 AnkiDroid/Aurora 事件，共同显示开发者对"平台围墙 + 平台审查 + 平台抽成"的抵触在升温。这条支线在 GitHub Trending 上会长期存在。
