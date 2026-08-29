# GitHub Trending 每日观察 · 2026-08-30

## 今日焦点

> **Claude Skills 生态井喷 · Agent 自制工具链 · 科研 Agent 与视频 Agent 双爆发 · 隐私/侦查 Sim 类 App · 语言模型"去审查"工具重回榜单**
>
> - `tt-a1i/archify` +3,927⭐ 登顶：为 Agent 提供"可验证架构图"生成能力，一日暴涨说明"文档即工具"正在成为 Skill 的第一个真需求。
> - `K-Dense-AI/scientific-agent-skills` +1,604⭐：165 个覆盖生物、化学、药物发现的 Agent Skill，学术工作流被 Skill 化的信号明显。
> - `bilawalsidhu/gods-eye-view` +1,870⭐：浏览器里的"卫星情报模拟器"，配合 3D 地球实况可视化——GEOINT 类爱好者工具冲上前三。
> - `calesthio/OpenMontage` +809⭐：开源 agentic 视频制作系统，100+ 工具封装，Agent 应用向"重创作"侧扩张。
> - `p-e-w/heretic` +150⭐：LLM 完全自动"去审查"工具再度冲榜，与本周百家公司呼吁 AI 安全形成有趣对照。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 生成可验证的架构 / 工作流图的 Agent Skill | JavaScript | 30,881 | +3,927⭐ | 1,925 |
| 2 | [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | 浏览器内的 3D 卫星情报模拟器 | JavaScript | 12,549 | +1,870⭐ | 2,490 |
| 3 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 165 个科研（生物/化学/药物）Agent Skill 集 | Python | 37,898 | +1,604⭐ | 3,570 |
| 4 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | 多智能体互动教室，沉浸式学习 | TypeScript | 22,141 | +907⭐ | 4,297 |
| 5 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 开源 agentic 视频制作系统，100+ 工具 | Python | 54,025 | +809⭐ | 6,710 |
| 6 | [tailscale/tailcat](https://github.com/tailscale/tailcat) | Tailscale 数据面上的类 netcat 工具 | Go | 3,449 | +790⭐ | 102 |
| 7 | [abi/screenshot-to-code](https://github.com/abi/screenshot-to-code) | 截图转 HTML/Tailwind/React/Vue 代码 | Python | 76,015 | +558⭐ | 9,260 |
| 8 | [every-app/open-seo](https://github.com/every-app/open-seo) | 开源 Semrush/Ahrefs 替代 | TypeScript | 14,613 | +517⭐ | 1,755 |
| 9 | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | Anthropic 官方 Claude Code 插件目录 | Python | 35,379 | +356⭐ | 3,957 |
| 10 | [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines) | 让 AI Agent 写"现代 Go"的规范文档 | Go | 2,858 | +294⭐ | 81 |
| 11 | [p-e-w/heretic](https://github.com/p-e-w/heretic) | 语言模型自动"去审查"工具 | Python | 28,659 | +150⭐ | 3,157 |
| 12 | [google/googletest](https://github.com/google/googletest) | Google C++ 测试与 mock 框架 | C++ | 39,311 | +125⭐ | 10,877 |
| 13 | [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Claude Skills 与定制资源精选清单 | Python | 73,903 | +74⭐ | 8,469 |
| 14 | [Osmantic/ODS](https://github.com/Osmantic/ODS) | 把 PC/Mac/Linux 变 AI 服务器（LLM + Agent） | Python | 4,879 | +35⭐ | 741 |
| 15 | [bigskysoftware/htmx](https://github.com/bigskysoftware/htmx) | HTML 的"高能"工具库 | JavaScript | 49,101 | +32⭐ | 1,640 |

---

## 重点项目点评

### 🥇 [tt-a1i/archify](https://github.com/tt-a1i/archify) — 今日榜首，+3,927⭐

**"给 Agent 一支能画得对的笔"——第一款真正让开发者感到痛点被戳中的 Skill。**

Archify 的定位是 Agent Skill：给出对象后，它能自动生成**可自动验证的架构图和工作流图**——不是画得好看，而是能对着 codebase 做一致性校验，改代码 → 图跟着更新且失败会告警。它的一日暴涨说明两件事：一是"Claude Skills / Agent Skills" 类生态已经越过第一次"目录建立"阶段，进入**用户为具体痛点付费/收藏**的阶段；二是过去两周多家企业内部都在做"代码 → 架构图"的 Agent，社区版一出即被 star 潮包围。

对比同类项目（如 Mermaid Agent、diagrammer 系列），Archify 的差异化在于"验证"——不仅生成还检查回路。这跟本周 A2A 归入 Linux 基金会的趋势有隐含联系：**Skill 化的开发工作流**必然催生"规范化的文档产物"。Archify 是这个方向上第一个爆款。

---

### 🥈 [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) — +1,870⭐

**浏览器里的 GEOINT 沙盒，把"卫星视角"变成消费级玩具。**

这个项目把公开卫星轨迹、地面情报可视化叠加到 3D 地球上——用户可以模拟侦查视角、追踪特定区域的活动。作者标榜"教育与好奇心用途"，但显而易见的场景包括新闻调查（Bellingcat 式）、供应链分析、以及军事迷。它今天冲上第 2，与 Guardian 关于 DHS 1509 传票的报道形成有趣的舆论合流——**社区对"谁在监控谁"的兴趣正肉眼可见地上升**。

技术层面看点在 Cesium/Three.js 与卫星星历数据的组合，以及一个非常克制的 UI：没有堆功能，围绕"看得懂"做减法。这也是为什么一个纯前端项目能一天冲近 2K 星——好用比强大更重要。

---

### 🥉 [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) — +1,604⭐

**科研工作流的"Skill 目录学"。**

165 个覆盖生物、化学、药物发现的可复用 Skill，让 Agent 能直接跑 sequence alignment、docking、retrosynthesis 等经典科研流程。爆火有两条线：一是过去 2 周 Anthropic 官方 claude-plugins 目录、ComposioHQ awesome-claude-skills 的连续涨榜，形成了明显的"Skill 生态位"叙事；二是 8 月 Causaly × Syneos Health 等临床 Agent 合作接连宣布，让"研究员 + Agent Skill"这一路径从愿景变成落地话题。

对开发者的启示：**领域 Skill 集**开始压过"通用 Agent 框架"的关注度——垂直、可复用、能验证的小工具比"再造一个 LangChain"更值得投入。

---

### 🎬 [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) — +809⭐

**Agent 时代的开源视频剪辑。**

100+ 工具的封装组合（剪辑、字幕、色调、Bgm、镜头筛选等），主打"从原始素材到成片"的一次跑通。这是继开源 image gen、TTS 之后，Agent 生态第一次真正吃到"视频"这类**重编辑器 + 长任务链**的场景。之所以能进入 Top 5，是因为它填了一个空——闭源 CapCut / Descript / OpusClip 主宰的领域第一次有了可自托管、可编排的替代品。

也解释了 Gods-Eye-View、Archify 这类"重可视化"项目今天扎堆的原因：**当 Agent 能一次性输出 30 分钟成片、可验证图表或 3D 地球叠加时，"最终交付物"这一层的门槛正在被系统性拉低。**

---

### 🛡 [p-e-w/heretic](https://github.com/p-e-w/heretic) — +150⭐

**"完全自动化的模型去审查"重返榜单。**

Heretic 主打对开源大模型的自动化 abliteration（去除拒绝行为）流水线：给定权重，跑完得到一个"更愿意回答任何问题"的版本。它上一次高热是 2025 年秋，但今天重新登榜——恰好与本周 100+ 公司呼吁"AI 网络安全协同"和 Anthropic 判例形成鲜明反差。

这个共振有意思：一边是产业界把"安全边界"抬升到法律和采购条款层面；另一边是开源社区在**继续降低"打开门"的成本**。中长期看，这将是 2026–2027 年最大的政策 vs 生态张力之一——欧盟 AI Act 强制透明度已经开始执行，但对开源权重下发何时、以何种方式监管仍是空白，Heretic 这类工具会不断把这个空白顶到监管者面前。

---

## 生态观察

**Skill 化不再是概念，而是"目录学"进入商业化**：Anthropic 官方 claude-plugins、ComposioHQ awesome-claude-skills、K-Dense-AI 科研 skills、以及 Archify 这样单点爆款——三种形态（目录 / 精选 / 单品）齐飞，说明 Claude Skills 已经度过冷启动，开始出现"发行—发行—策展"的三层结构。

**"重交付物"Agent 起势**：视频（OpenMontage）、架构图（Archify）、3D 地理情报（Gods-Eye-View）都在今天进入 Top 5，反映一个共同信号：**Agent 的产品化门槛从"能对话"跳到了"能交付一个完整制品"**。谁能率先把 Skill/工具编排成"一次跑完的可交付项目"，谁就能拿到下一波用户。

**语言与运行环境层面**，JavaScript 与 Python 依然主导，但今天多了两个特别项：`JetBrains/go-modern-guidelines` 是首个明确"给 AI Agent 看的 Go 风格指南"，`tailscale/tailcat` 则展示了"Overlay 网络 + 经典 Unix 工具"的复兴思路。这两类"面向 Agent 的规范文档 + 老工具重造"很可能成为 2026 下半年的一个持续小趋势。

---

*报告生成时间：2026-08-30（Asia/Shanghai）*
