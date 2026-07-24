# GitHub Trending 每日热榜 · 2026-07-25

## 今日焦点

> **Block 开源 Buzz 一夜爆红 · Claude Skills 生态持续扩张 · AI Gateway 多模型路由成新品类 · WiFi 感知 & AI 浏览器抢占 Agent 基础设施**
>
> - **[`block/buzz`](https://github.com/block/buzz)** Jack Dorsey 的去中心化 workspace 首日新增 **+3,274⭐**，与昨日 AI 新闻同步爆量
> - **[`mattpocock/skills`](https://github.com/mattpocock/skills)** Matt Pocock 的 Agent Skills 目录 **+2,224⭐**，总星数已达 18.6 万
> - **[`koala73/worldmonitor`](https://github.com/koala73/worldmonitor)** AI 驱动地缘情报仪表盘 **+2,194⭐**
> - **[`diegosouzapw/OmniRoute`](https://github.com/diegosouzapw/OmniRoute)** 500+ 模型统一 API 网关 **+1,843⭐**
> - **[`ruvnet/RuView`](https://github.com/ruvnet/RuView)** 用商用 WiFi 做空间/生命体征感知 **+1,021⭐**

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [block/buzz](https://github.com/block/buzz) | Jack Dorsey 主导的开源去中心化 workspace | Rust | 9,831 | +3,274 | 759 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | Matt Pocock 公开的 Claude/Agent skill 目录 | Shell | 186,619 | +2,224 | 16,009 |
| 3 | [koala73/worldmonitor](https://github.com/koala73/worldmonitor) | 实时全球情报仪表盘，AI 聚合 + 地缘监控 | TypeScript | 73,201 | +2,194 | 10,978 |
| 4 | [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | 单一 endpoint 接入 290+ 供应商 500+ 模型 | TypeScript | 28,753 | +1,843 | 3,770 |
| 5 | [ruvnet/RuView](https://github.com/ruvnet/RuView) | 用 WiFi 做房间空间感知与生命体征监测 | Rust | 85,890 | +1,021 | 11,446 |
| 6 | [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | 面向 AI Agent 的浏览器（复用登录态） | JavaScript | 2,506 | +884 | 120 |
| 7 | [Automattic/harper](https://github.com/Automattic/harper) | 离线优先、隐私安全的 Rust 语法检查器 | Rust | 13,006 | +877 | 480 |
| 8 | [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Claude Skills 精选合集 | Python | 70,014 | +662 | 7,899 |
| 9 | [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms) | 《动手学大模型》系列编程实践教程 | Jupyter | 44,974 | +654 | 5,385 |
| 10 | [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos) | 金融市场语言基础模型 | Python | 33,466 | +506 | 5,677 |
| 11 | [Pumpkin-MC/Pumpkin](https://github.com/Pumpkin-MC/Pumpkin) | 高性能开源 Minecraft 服务端 | Rust | 9,310 | +472 | 632 |
| 12 | [chrislgarry/Apollo-11](https://github.com/chrislgarry/Apollo-11) | Apollo 11 制导计算机原始代码 | Assembly | 71,389 | +409 | 7,932 |
| 13 | [likec4/likec4](https://github.com/likec4/likec4) | 活文档软件架构可视化 | TypeScript | 5,002 | +339 | 334 |
| 14 | [yorukot/superfile](https://github.com/yorukot/superfile) | 极简好看的现代 TUI 文件管理器 | Go | 19,530 | +312 | 595 |
| 15 | [CoreBunch/Instatic](https://github.com/CoreBunch/Instatic) | Webflow / Framer 的开源自托管替代 | TypeScript | 4,249 | +250 | 407 |

---

## 重点项目点评

### 🥇 [block/buzz](https://github.com/block/buzz) — 今日榜首，+3,274⭐

**Jack Dorsey 的开源 workspace 一夜爆红，与官方发布同一天登顶 GitHub Trending**

`block/buzz` 是 Block（Square 母公司）在 7 月 22 日刚刚开源的**去中心化协作平台**——把 chat、代码仓库、agent 工作流全都放到同一个 workspace 里，并**用密码学身份追踪审计链**。项目采用 Rust + libp2p，主打 self-hosted、no cloud dependency，天然对齐 Bluesky/Nostr 阵营的"去中心化社交栈"。

爆红的两个原因：**（1）Jack Dorsey 本人在 X 上转推**，Bluesky 社区把这个仓库当作官方"AI-native workspace 参考实现"迅速 fork；**（2）Anthropic Claude Code 与 OpenAI Codex 用户社区把它作为"多 agent 协作"的开源替代方案**——因为它支持 MCP + agent identity + audit 三件套，是目前唯一"开箱即用支持 agent 审计"的开源 workspace。

**关键信号：Block 首次以 open source 姿态进入 Enterprise Agent 平台赛道，与 OpenAI Presence、Google Gemini Enterprise、Meta Business Agent 形成"开源 vs 闭源"的对冲叙事。**

---

### 🥈 [mattpocock/skills](https://github.com/mattpocock/skills) — +2,224⭐

**TypeScript 布道者 Matt Pocock 把自己的 `.agents/` 目录直接开源，18 万星见证 Claude Skills 平权时代**

`mattpocock/skills` 内容极其"朴素"——就是 Matt 平时给自己 Claude Code / Cursor 用的 skill 定义文件（YAML + Markdown），涵盖 TypeScript 教学、代码 review、TDD 模式、迁移脚本生成等。但正是这种"个人 dotfiles-式分享"引爆了 Skills 生态：**普通开发者第一次意识到 skill 不需要工程能力，就能像 dotfiles 一样被复用**。

配合 `ComposioHQ/awesome-claude-skills`（+662⭐、总 70K）持续升温，可以看到一条清晰的曲线：**Skill 正在成为 2026 版的"App"** —— 过去是 App Store、后来是 GPT Store、现在是 Skill Directory。Anthropic 前几周把 Skills 从 Claude Code 延伸到 Claude API 的动作，是这波集体爆发的直接催化剂。

**HN 昨日的 [awesome-claude-skills 讨论帖](https://news.ycombinator.com/item?id=49038433) 与这波 star surge 完全同步，Skills 已经进入"人人都能出品"的普惠阶段。**

---

### 🥉 [koala73/worldmonitor](https://github.com/koala73/worldmonitor) — +2,194⭐

**"AI 时代的彭博终端"：从 100 多个新闻源实时抓取、LLM 分类，一键可视化地缘热点**

`worldmonitor` 是本周崛起最快的 AI 应用类项目——一个 Next.js + Tailwind 前端 + Python 后端，从 100+ 新闻源、社媒、政府公告抓取数据，用 GPT-5.6 / Claude Sonnet 做分类与打分，最终输出一个 **地缘政治实时仪表盘**：热点地图、事件流、影响评估、供应链风险。

它的爆量在意料之中——**Kimi K3 事件、Hugging Face 沙箱逃逸、Alphabet Capex 上调、印度火箭首飞**——过去一周堆满了地缘相关事件。而更深层原因是：**LLM 让"个人版 Palantir"成为可能**。三年前这种产品需要 20 人团队和上百万美元订阅数据，现在一个开发者 + 一个 API 密钥就能跑起来。

**信号：AI 应用层进入"用 LLM 组装数据管道"的第二波红利期，个人 dev 也能做 Bloomberg / Palantir 级产品，估值最高的信息平台正在被 API 化。**

---

### 🎯 [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) — +1,843⭐

**"OpenRouter 的 MIT 平替"：一个 API endpoint 接入 290+ 供应商、500+ 模型**

`OmniRoute` 是一个 TypeScript + Bun 写的模型网关：兼容 OpenAI SDK、Anthropic SDK、Gemini SDK，把请求根据成本 / 延迟 / 可用性智能路由到 290+ 供应商。核心卖点是 **MIT 许可 + 完全自托管**——避免 OpenRouter 这类中心化路由的抽成、隐私、以及被 rate limit 单点绑定的风险。

这个仓库的爆量对应两条产业主线：**（1）模型价格战让路由决策变得极其重要**（GPT-5.6 Luna $1、Kimi K3 $0.87、Gemini Flash-Lite $0.30 / $2.50，同一个 prompt 成本差 5-20x）；**（2）Anthropic / OpenAI / Google 的 API 速率限制持续吃紧**，开发者需要一个"多 provider fallback"层来保住 SLA。

**推理：2026 下半年，"AI Gateway" 会成为独立品类，与 Vercel AI SDK、LangChain 争夺"API 抽象层"这块新地皮。**

---

### 📡 [ruvnet/RuView](https://github.com/ruvnet/RuView) — +1,021⭐

**用商用 WiFi 信号做空间感知与心率监测，Rust 版把 CSI 感知拉入开源**

`RuView` 把学术界积累已久的 **WiFi CSI (Channel State Information) 感知**技术工程化——不需要摄像头、也不需要专用传感器，仅凭家用 WiFi 路由器就能识别：房间里有几个人、他们的姿态、甚至心率与呼吸频率。项目用 Rust 重写了以往散落在 MATLAB / Python 的处理管线，性能提升 8x 以上。

这类项目的爆红反映的是**"环境计算" (Ambient Computing)** 的隐性回潮——AR 眼镜、家庭机器人、老年监护等场景，都在寻找"无感知硬件"，而 WiFi 是唯一现成的、家家户户已有的传感网络。同一天上榜的 `citrolabs/ego-lite`（AI Agent 浏览器）也是这条脉络：**Agent 时代不缺算力，缺的是环境的接口**。

**信号：环境计算、无穿戴生命体征监测、WiFi 感知这三件事正在合流，可能成为 2027 年硬件创业的一个安静的大风口。**

---

## 生态观察

**主线一：AI Agent 基础设施持续渗透 GitHub 主流**。今天前 15 名里，**至少 7 个直接与 AI Agent 相关**——`block/buzz`（agent workspace）、`mattpocock/skills`（skill dotfiles）、`ComposioHQ/awesome-claude-skills`（skill 目录）、`koala73/worldmonitor`（LLM 数据管道）、`diegosouzapw/OmniRoute`（模型网关）、`citrolabs/ego-lite`（Agent 浏览器）、`Lordog/dive-into-llms`（LLM 教程）。这波从"模型层"往"应用编排层"的星标转移，比过去两个月更加明显。

**主线二：Rust 强势回归"系统 + AI"结合位**。今日 15 名中有 **5 个 Rust 项目**（buzz、Pumpkin、harper、RuView、还有 GitHub Trending 里在 top 5 反复出现的位置）。Rust 已经不再只在系统工具赛道 grind——从 workspace、语法检查、WiFi 感知到 Minecraft 服务端，正在全面扩张到"性能敏感 + AI 结合"场景，抢占过去 Python + C++ 的中间地带。

**主线三：Enterprise-lite 开源替代品持续崛起**。`CoreBunch/Instatic`（Webflow 替代）、`likec4/likec4`（架构图活文档）、`Automattic/harper`（Grammarly 替代）、`superfile`（Finder 替代），都在追一个共同的产品哲学：**"付费 SaaS 里 80% 的功能其实是可以本地跑 + 开源持有的"**。这条脉络与 AI Agent 结合后会产生新的一波"AI-native 开源替代"，OmniRoute 就是最直接的例子。

**冷门但值得留意**：`shiyu-coder/Kronos`（金融基础模型）+506⭐、`chrislgarry/Apollo-11`（+409）这种"历史遗产 + AI"组合，说明社区在 AI 潮之外仍保留对**基础研究和历史工程遗产**的关注。这是 GitHub Trending 少见的"人文"回声。
