# GitHub Trending 每日热榜 · 2026-08-29

## 今日焦点

> **Agent Skills 生态爆发 · Claude 官方插件目录冲榜 · 卫星模拟器出圈 · Tailscale 生态扩张 · 图像 prompt 工程化**
>
> - `tt-a1i/archify` 榜首，+4,561⭐，Agent-skill 架构图工具引爆
> - `K-Dense-AI/scientific-agent-skills` +720⭐，163 个验证过的科研 Agent 技能
> - `anthropics/claude-plugins-official` +457⭐，Claude 官方插件目录进入 TOP3
> - `bilawalsidhu/gods-eye-view` +3,398⭐，浏览器端卫星数据模拟器现象级传播
> - `calesthio/OpenMontage` +1,144⭐，开源"AI 视频剪辑 Agent"日增破千

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 生成可验证的架构图 Agent Skill | JavaScript | 27,170 | +4,561⭐ | 1,721 |
| 2 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 163 个已验证的科研 AI Agent 技能 | Python | 36,504 | +720⭐ | 3,473 |
| 3 | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 官方精选 Claude Code 扩展目录 | Python | 35,001 | +457⭐ | 3,935 |
| 4 | [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | 浏览器卫星模拟器（真实空间数据） | JavaScript | 10,969 | +3,398⭐ | 2,226 |
| 5 | [abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus) | 客户端代码知识图谱工具 | TypeScript | 46,145 | +189⭐ | 5,100 |
| 6 | [JetBrains/go-modern-guidelines](https://github.com/JetBrains/go-modern-guidelines) | 面向 AI 编码 Agent 的现代 Go 指南 | Go | 2,573 | +574⭐ | 78 |
| 7 | [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | 开源 Agent 视频剪辑系统 | Python | 53,255 | +1,144⭐ | 6,643 |
| 8 | [abi/screenshot-to-code](https://github.com/abi/screenshot-to-code) | 截图转 HTML/React 代码 | Python | 75,521 | +309⭐ | 9,217 |
| 9 | [cursor/plugins](https://github.com/cursor/plugins) | Cursor 插件规范与官方插件 | TypeScript | 5,938 | +257⭐ | 478 |
| 10 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | 工业级图像 prompt 工程模板 | JavaScript | 24,211 | +1,687⭐ | 2,393 |
| 11 | [tailscale/tailcat](https://github.com/tailscale/tailcat) | 基于 Tailscale 数据面的 netcat | Go | 2,622 | +986⭐ | 69 |
| 12 | [NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) | 逆向工程框架 | Java | 73,309 | +205⭐ | 8,012 |
| 13 | [swoole/typephp](https://github.com/swoole/typephp) | 编译 PHP 为原生二进制 | PHP | 801 | +188⭐ | 38 |
| 14 | [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi) | 统一 34 家免费 LLM 提供商入口 | TypeScript | 21,586 | +477⭐ | 3,057 |
| 15 | [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Chrome DevTools 的 MCP 集成 | TypeScript | 49,955 | +61⭐ | 3,502 |

---

## 重点项目点评

### 🥇 [tt-a1i/archify](https://github.com/tt-a1i/archify) — 今日榜首，+4,561⭐

**Agent Skill 生态第一个"现象级单品"**

archify 单日 +4,561⭐ 直接把总星数推过 2.7 万，是本月增速最快的项目之一。它本质上是一个 **Claude Code / Cursor 通用的 Agent Skill 包**：给 Agent 加上"看代码 → 生成 Mermaid 架构图 → 自我验证"的能力，重点在最后一步 —— 让 Agent 自己 review 图是否与代码一致，避免"编造依赖"这个老毛病。

它爆火的时机很关键：Anthropic 官方 Skills API 上线不到两个月，社区正处在"人人都想做第一个爆款 Skill"的阶段。archify 的成功公式其实很朴素 —— **场景刚需（架构图人人要）+ 反馈闭环（可以验证）+ 一键 npm 安装**。三者叠加击穿了传统 Agent 项目"演示很酷但落地难"的天花板。

后续值得关注的是：archify 是否会被 Anthropic 官方收编进 `claude-plugins-official`（今日 TOP3），如果收编成功，将成为 Skills 商业化的第一个案例。

---

### 🥈 [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) — +3,398⭐

**浏览器就能玩的"上帝视角"卫星系统，出圈到非技术圈**

gods-eye-view 是一个纯浏览器端的卫星模拟器，加载真实的空间轨道数据、地球自转、卫星星座（Starlink、Iridium、GPS）—— 完全无需服务器。作者用 Three.js + WebGPU 实现了 60 FPS 下同时渲染 8000+ 卫星轨道。

之所以能日增 3,398⭐，一半功劳来自 Twitter/X 上一条"用手机就能实时看到自己头顶飞过什么卫星"的 demo 视频，被 Marc Andreessen 等大 V 转发。这类"3D 可视化 + 真实世界数据"的开源项目正在成为 GitHub trending 的常客，反映出 **WebGPU + 大规模空间数据** 组合的成熟度。

对开发者的启示：不需要复杂算法，只需要把公开数据（NASA、Celestrak）用现代 Web 技术做漂亮的呈现，就有出圈机会。这条路线过去一年已经跑出 flightradar24、windy.com、nasa-eyes 的多个 clone。

---

### 🥉 [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) — +1,144⭐

**开源版 Runway/Descript：Agent 剪视频进入 5 万⭐俱乐部**

OpenMontage 是一个"agentic video production"系统 —— 用户给一个粗剪视频和目标（"剪成 60 秒 TikTok"），Agent 自动完成分镜识别、字幕、B-roll 插入、音乐匹配、节奏调整。核心模型链路是 Whisper V4 + LLaVA-Next + FFmpeg 编排。

总星数 5.3 万意味着这不是新项目 —— 但今日 +1,144⭐ 的原因是新版 v0.9 引入了"Skill-based 视频模板"，让用户可以像装插件一样加入"vlog 剪辑 skill"、"短视频 hook skill"。这直接对标了 Descript、Adobe Premiere AI 的商用功能。

在闭源视频 AI 平台涨价（Runway Gen-4 提价 30%）的背景下，OpenMontage 这类"本地可跑、可自定义"的方案在自媒体和小型内容团队里正在快速渗透。这是"Open-source undercutting SaaS"这条老赛道在视频领域的具体案例。

---

### 🔧 [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) — +457⭐

**官方插件目录不是 README，是 Anthropic 的生态战略**

anthropics/claude-plugins-official 表面上是一个"精选插件列表"，实质上是 Anthropic 官方对 Claude Code 生态的**中央化质量控制机制**。所有入选插件需要通过安全审计、性能测试、维护活跃度审查。类似 Homebrew Core 和 VS Code Marketplace 官方推荐的组合。

从今日排名可以看到，围绕 Claude 生态的项目集中爆发：archify（第 1）+ scientific-agent-skills（第 2）+ claude-plugins-official（第 3）连续占据榜首。这不是巧合，而是**开发者社区已经把"给 Agent 加能力"作为独立的商业化方向**在跑。相比之下 cursor/plugins（第 9）刚起步，规模差距明显。

值得关注的下一步：Anthropic 是否会在 9-10 月发布 Skill Marketplace（付费插件市场），如果落地，将复刻 iOS App Store 时代早期的黄金窗口。

---

### 🌐 [tailscale/tailcat](https://github.com/tailscale/tailcat) — +986⭐

**Tailscale 生态第一个"官方 CLI 明星"**

tailcat 是 Tailscale 官方发布的 netcat 替代品 —— 基于 Tailscale 数据面（tailnet）做点对点通讯，无需公网端口、无需 NAT 穿透配置。上线两天涨到 2.6k⭐，Tailscale 用户社区反应强烈：*"这就是我一直想要的 ssh 替代品的第一步。"*

它的意义在于 **Tailscale 正在从"VPN 替代品"演进为"P2P 网络原语平台"**。tailcat 是把 wireguard + tailnet 打包成开发者可以像 netcat 一样直接调用的原语。后续 Tailscale 官方 roadmap 可能出现 taillisten、tailproxy、tailrsync 等一系列"tail-" 前缀工具。

对企业运维圈的信号：Tailscale 的商业策略正在从"卖 VPN"转向"卖网络原语套件"，与 Cloudflare Tunnel、Ngrok 的竞争会更直接。

---

## 生态观察

**今日 GitHub trending 的三条主线：**

1. **Agent Skills 进入"应用商店"阶段。** archify、scientific-agent-skills、claude-plugins-official 三箭齐发，明确宣告"Claude Code Skills"已从技术概念走向可流通的资产。开发者社区正在复现 2008 年 iOS App Store 早期的 gold rush 场景 —— 一个 Skill 可以在 24 小时内涨 4,000+⭐。

2. **可视化 + 真实数据 成 GitHub 出圈捷径。** gods-eye-view（卫星）与本月早些时候的 airspacetoday、real-time-earthquake 一脉相承，反映 WebGPU 让浏览器端的复杂 3D 展示不再需要后端。这条赛道的门槛：**创意 + 公开数据 API + 现代 Web 技术**，对独立开发者极其友好。

3. **Tailscale 生态正在扩张为完整平台。** tailscale/tailcat 之后可以预期更多"tail-" 前缀工具。运维和开发者工具圈正在迎来"P2P 网络原语作为基础设施"的浪潮。

**冷却中的：** 大型 LLM 训练库、纯 RAG 项目、传统 LangChain 类框架在 trending 上的出现频率明显下降 —— 生态正在从"如何训模型/搭 RAG"转向"如何让 Agent 干活"。

**观察窗口：** 未来一个月，Skills 相关项目的爆发是否会带出付费 Skill 交易市场；archify 是否被 Anthropic 收编成官方案例；Cursor plugins 会否发布"官方精选目录"以对标 Anthropic。
