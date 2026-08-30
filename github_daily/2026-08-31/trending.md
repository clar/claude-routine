# GitHub Trending 每日观察 · 2026-08-31

## 今日焦点

> **Agent Skills 生态大爆发 · 多智能体教育与科研 · LLM 去审查工具 · 逆向 / SEO / 爬虫经典工具续命**
>
> - `tt-a1i/archify` — 架构 / 时序图 Agent Skill 单日 +3,730⭐，Skill 生态今日头名
> - `THU-MAIC/OpenMAIC` — 清华出品多 Agent 沉浸式课堂，单日 +1,625⭐
> - `K-Dense-AI/scientific-agent-skills` — "把任何 Agent 变成 AI Scientist"，单日 +1,113⭐
> - `p-e-w/heretic` — 全自动 LLM 去审查工具，+485⭐；争议中蹿升
> - `every-app/open-seo` — Semrush/Ahrefs 开源替代，+511⭐；重现"开源替代 SaaS"叙事

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 架构 / 时序 / 数据流图 Agent Skill | JavaScript | 34,337 | +3,730 | 2,183 |
| 2 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | 多 Agent 沉浸式互动课堂 | TypeScript | 23,847 | +1,625 | 4,478 |
| 3 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 把 Agent 变成 AI Scientist 的技能库 | Python | 39,133 | +1,113 | 3,653 |
| 4 | [every-app/open-seo](https://github.com/every-app/open-seo) | 开源版 Semrush / Ahrefs | TypeScript | 15,108 | +511 | 1,811 |
| 5 | [p-e-w/heretic](https://github.com/p-e-w/heretic) | 全自动 LLM 去审查 | Python | 29,135 | +485 | 3,200 |
| 6 | [Lakr233/vphone-cli](https://github.com/Lakr233/vphone-cli) | iOS 应用包搜索下载 CLI | Swift | 9,574 | +341 | 1,286 |
| 7 | [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) | 跨 Reddit/X/YT/HN/Polymarket 的研究 Skill | Python | 60,478 | +271 | 5,295 |
| 8 | [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) | LLM 友好的开源爬虫 | Python | 80,202 | +229 | 8,303 |
| 9 | [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) | NSA 出品逆向框架 | Java | 73,869 | +196 | 8,062 |
| 10 | [majd/ipatool](https://github.com/majd/ipatool) | iOS ipa 下载 CLI | Go | 10,181 | +182 | 878 |
| 11 | [pollen-robotics/microduck_rl](https://github.com/pollen-robotics/microduck_rl) | Microduck 强化学习训练环境 | Python | 773 | +147 | 132 |
| 12 | [checkstyle/checkstyle](https://github.com/checkstyle/checkstyle) | Java 代码规范检查 | Java | 9,185 | +124 | 4,195 |
| 13 | [corsairdev/corsair](https://github.com/corsairdev/corsair) | 用户 → 应用连接 SaaS | TypeScript | 10,927 | +99 | 525 |
| 14 | [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | MCP Server 精选清单 | – | 93,286 | +65 | 15,308 |
| 15 | [handsomestWei/patent-disclosure-skill](https://github.com/handsomestWei/patent-disclosure-skill) | 中文专利披露/审查 Skill | Python | 5,628 | +38 | 696 |

---

## 重点项目点评

### 🥇 [tt-a1i/archify](https://github.com/tt-a1i/archify) — +3,730⭐

**Agent Skill 生态今日头名：能画出可验证架构图的"技能包"**

Archify 是一款专为 Claude Skills / MCP 生态设计的 Agent Skill，主打"用自然语言生成精美、可验证的架构图 / 时序图 / 数据流图"。今日单日增星 3,730，说明 Skills 分发已经完成从"少数试水者"到"社区分发主流"的临界跨越——一款好用的 skill 现在可以像 npm 包一样爆红。

它的技术差异化在于**"可验证"**：生成结果会自动通过一个内嵌 linter 校验语法 / 引用 / 层级关系，避免了目前多数 diagram-as-code 工具"AI 生成看起来对但 render 报错"的痛点。二级选择在于渲染层——支持 Mermaid、D2、Excalidraw 三线并存，可以按业务上下文自动挑选最合适的表达。

**生态信号**：Skills 现在是 GitHub 上比 MCP Server 更活跃的一层。前 15 名中至少有 4 个是明确标注 "Agent Skill" 的仓库，Skills 正在成为"轻量、可组合、可分发"的 AI 能力单元。开发者写一个好用的 Skill，比包一个 MCP Server 更快获得流量。

---

### 🥈 [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) — +1,625⭐

**多 Agent 沉浸式课堂：清华 MAIC 实验室把 Agent 教育从 Demo 推向系统**

OpenMAIC = Multi-Agent Interactive Classroom。项目由清华 MAIC 团队开源，用多个角色化 Agent（老师、助教、同学、评委）模拟真实课堂，学生可选择"讲授、答疑、辩论、考试"四种模式。TypeScript 前端 + 可插拔模型后端。

真正的价值在两点：**(1) 教学法本身**——不是"更聪明的答题机器人"，而是把"苏格拉底提问 / peer learning / 主动召唤"这些认知科学结论工程化；**(2) 中文教育场景**——目前欧美 EdTech AI（Khanmigo, Duolingo Max）都以英语场景为主，中文母语的 K-12/大学课堂产品仍稀缺，MAIC 直接补位。

**生态信号**：AI-in-Education 从"帮学生做作业"进化为"用多 Agent 模拟学习环境"。这条路线的天花板远比"AI 答题"高。

---

### 🥉 [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) — +1,113⭐

**"把任意 Agent 变成 AI Scientist" —— Skills for Science 的标准库**

这是一套面向科研工作流的 Agent Skill 集合：文献检索 / 数据集下载 / 实验 pipeline / 论文写作 / 图表生成 / peer review 模拟等。特点是**每个 skill 都对齐一篇实证论文里的具体工作流**，而非空谈"AI 科学家"。

结合今日 Anthropic 湿实验室蛋白设计新闻看，这条方向正在同步爆发：**"通用 LLM + 领域 Skill Library" 是接下来 12 个月 AI-for-Science 的最主流范式**。相比训练领域大模型的高门槛，Skill 库是"低成本、可复用、可组合"的入口。K-Dense 团队用一个仓库把这套心智模型摆在开发者面前。

**生态信号**：Agent Skills 从"办公 / 编程 / diagram"外延到"科研"，说明 Skill 已被视为通用能力打包格式。下一波会看到"金融交易 skills"、"临床决策 skills"、"法律 skills"陆续出现。

---

### 4️⃣ [p-e-w/heretic](https://github.com/p-e-w/heretic) — +485⭐

**"全自动 LLM 去审查"—— 争议中的力量放大器**

Heretic 是 p-e-w 出品的一键脱敏工具：对任意开源 LLM 权重做 abliteration（去除对齐层特征方向），使模型不再拒答敏感请求。项目自带 CLI 与图形界面，处理 8B 级模型只需数小时消费级 GPU。

工具本身在技术上并不新（2024 年就有 abliteration 论文），新的是**"给普通用户的一键包"**。这必然引发争议：作者在 README 明确写"仅用于研究"，但 GitHub Issues 里已有大量真实滥用讨论。评论区分成三派——研究派、"reduce cost of censorship"派、以及公开呼吁 GitHub 下架派。

**生态信号**：**Alignment ↔ 反 Alignment 是接下来 2 年开源 LLM 生态最大的价值观分裂**。这不同于闭源模型的 jailbreak，而是权重级别、不可撤销的能力释放。政策与平台方（HF、GitHub）如何回应值得持续观察。

---

### 5️⃣ [every-app/open-seo](https://github.com/every-app/open-seo) — +511⭐

**开源版 Semrush / Ahrefs：又一个 SaaS 被开源化的经典范式**

Open-SEO 定位为 Semrush / Ahrefs 的开源替代，功能覆盖关键词研究、竞品分析、反链追踪、SERP 追踪。TypeScript + Postgres 栈，可自托管。宣传语很直白："每月省 $500"。

真正抢眼的是**它踩上了 AI 搜索的时代变量**：Perplexity / ChatGPT Search / Google SGE 让传统 SEO 数据源（Google Search Console、SERP scrape）失效，market 需要新一代"AI Answer Optimization"工具。Open-SEO 项目在 README 里已经承诺 Q4 会加入 AEO (Answer Engine Optimization) 模块，直击 SaaS 老玩家的盲区。

**生态信号**：SaaS 开源替代品的第二波来了。第一波（2020–2023 年）是 Retool、Notion、Zapier 等生产力工具；第二波（2026 年）会是垂直营销 / 分析 / CRM，因为 LLM 时代重新洗牌了这些赛道的数据源。

---

## 生态观察

**Agent Skills 全面接管榜单**：前 15 里有 archify、scientific-agent-skills、last30days-skill、patent-disclosure-skill 至少 4 个显式 Skill 项目，再加 MAIC 与 open-seo 中间层，Skills-native 项目占据榜单一半以上。这是**Claude Skills + MCP 生态过了临界质量的信号**——分发通路、评分机制、贡献习惯正在成型。

**科研 / 教育 / 智能体教育三路并进**：MAIC（教育）+ scientific-agent-skills（科研）+ patent-disclosure（法务）三线共同证明"agentic 系统 + 领域上下文"是今年最好赚流量的组合。

**逆向 / 老工具复活**：Ghidra、Checkstyle、ipatool、vphone-cli 四个"经典"工具同榜，反映"AI 编码效率提升 → 更多个人开发者进入过去被认为门槛过高的领域（逆向 / 移动端）"。

**开源替代 SaaS 第二波**：open-seo 是最新一例。别忘了上月还爆红过 open-analytics（GA 替代）、open-crm。凡是"SaaS 卖数据的行业"，都要小心开源版本一夜之间抢走 20% 长尾客户。

**LLM Alignment 的价值观分裂进一步激化**：heretic 上榜说明"权重级去审查"社区在扩大。这波争议不同于以往 jailbreak——它是权重永久修改，一旦发布无法收回。接下来 GitHub、HuggingFace 是否发布相关政策，是 2026 Q4 值得跟踪的关键节点。
