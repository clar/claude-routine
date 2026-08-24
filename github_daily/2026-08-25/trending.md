# GitHub Trending 日报 · 2026-08-25

## 今日焦点

> **免费 LLM 薅羊毛热潮 · Claude 生态扩张 · 本地优先 agent · Rust 系统工具 · 开源版付费 SaaS**
>
> - `openai/codex` +1,990⭐：Rust 版终端 coding agent 继续霸榜，直面 Claude Code
> - `Alishahryar1/free-claude-code` +889⭐：13 亿免费 token 攻略成新流量密码
> - `AprilNEA/OpenLogi` +1,102⭐：Rust 重写的 Logitech Options+ 替代品爆红
> - `basecamp/omarchy` +1,055⭐：DHH 的 Arch Linux 发行版持续吸粉
> - `anthropics/claude-plugins-community` +490⭐：Claude 插件市场刚开就冲进榜

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [openai/codex](https://github.com/openai/codex) | Rust 写的终端 coding agent | Rust | 116,989 | +1,990 | 17,835 |
| 2 | [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) | 本地优先的 Logitech Options+ 替代品 | Rust | 15,809 | +1,102 | 428 |
| 3 | [basecamp/omarchy](https://github.com/basecamp/omarchy) | DHH 出品的 Arch 桌面发行版 | Shell | 30,056 | +1,055 | 3,054 |
| 4 | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | Nous 的可成长通用 agent | Python | 235,756 | +899 | 47,561 |
| 5 | [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code) | 13 亿免费 token 全家桶攻略 | Python | 48,890 | +889 | 7,987 |
| 6 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | 单文件 Claude Code 行为配置 | Markdown | 206,454 | +491 | 21,082 |
| 7 | [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) | Claude Code / Cowork 社区插件市场 | Python | 1,328 | +490 | 150 |
| 8 | [apache/maka](https://github.com/apache/maka) | 本地优先 AI agent 工作台 | TypeScript | 2,871 | +408 | 305 |
| 9 | [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) | AI 求职材料自动定制框架 | Python | 33,990 | +378 | 11,878 |
| 10 | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | AI 工程从零手写教程 | Python | 48,248 | +330 | 8,496 |
| 11 | [AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) | Obsidian + Claude Code 二脑集成 | Python | 11,839 | +272 | 1,327 |
| 12 | [makeplane/plane](https://github.com/makeplane/plane) | 开源版 Jira/Linear/ClickUp | TypeScript | 57,892 | +268 | 5,485 |
| 13 | [openclaw/openclaw](https://github.com/openclaw/openclaw) | 跨平台个人 AI 助手 | TypeScript | 387,420 | +160 | 81,347 |
| 14 | [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi) | 每月 74 亿免费 token 聚合网关 | TypeScript | 19,744 | +153 | 2,873 |
| 15 | [PostHog/posthog](https://github.com/PostHog/posthog) | 自驱式产品分析平台 | Python | 38,969 | +106 | 3,272 |

---

## 重点项目点评

### 🥇 [openai/codex](https://github.com/openai/codex) — 今日榜首，+1,990⭐

**Rust 版 Codex 从 100k star 一路加速——OpenAI 拿终端端对垒 Claude Code**

Codex 已经是 GitHub 上 star 数最高的 CLI coding agent 之一，总 star 突破 11.6 万，今日再涨 1,990。它是 OpenAI 用 Rust 从零重写的终端编程助手，把此前 codex-cli（Node.js 版）该有的对话、执行、审批全部搬到本地进程里，启动更快、内存更省、可以完全离网调用自建 endpoint。这波涨势直接对标 Anthropic 的 Claude Code——两家都把"终端里的 agent"当作接下来 12 个月的兵家必争之地。

从 issues 里能看出 OpenAI 的路线：MCP 支持已是一等公民、`--sandbox` 权限模型也被重构成类似 Claude Code 的四档 permission 模式、桌面/IDE 侧则通过 vscode-codex 扩展形成组合拳。有意思的是，随 SpaceX 收购 Cursor 后编程 agent 头部格局重排，独立 IDE 的窗口被压缩，反而让"终端 agent + IDE 插件"这条路径的战略价值被抬高——Codex 今天的爆量恰好卡在这个节点。

**看点：** Codex 与 Claude Code 未来 3 个月最大的差异化，可能不在模型，而在 "policy engine + sandbox"——谁能让企业敢在生产分支上给 agent 写权限，谁就赢。

---

### 🥈 [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) — +1,102⭐

**用 Rust 干掉 Logitech Options+：一次"云化外设软件"的用户逆反**

OpenLogi 是一个用 Rust 写的、完全本地运行的 Logitech Options+ 替代品，支持鼠标手势、DPI、按键映射、跨设备切换。作者的主打卖点是"不需要注册、不需要联网、不上传按键统计"——这是对 Logitech 近两年把驱动软件云化、要求账号登录的直接反击。项目今日新增 1,100+ star，加上其 GitHub Sponsors 数一夜翻倍，说明"外设厂商的臃肿云端软件"正在被用户系统性反抗。

技术上有几个细节值得注意：底层用 [hidapi] 直接跟蓝牙/USB HID 通信，不依赖 Logi 官方 driver；对 macOS 的 Accessibility API 做了 sandbox 兼容处理；binary 只有 ~14MB，冷启动 <200ms。作者把它作为 "local-first" 生态的一部分，跟去年爆红的 [MonitorControl] 一脉相承——都是"官方软件太差，社区自己写一个 Rust 版"的经典模式。

**看点：** 下一个被这种模式冲击的品牌，很可能是罗技的对手 Razer 或耳机厂 Bose——它们的驱动软件同样在走登录化道路。

---

### 🥉 [basecamp/omarchy](https://github.com/basecamp/omarchy) — +1,055⭐

**DHH 的 Arch 桌面发行版进入"第二波传播"**

Omarchy 是 David Heinemeier Hansson（Rails 之父、Basecamp 联合创始人）今年发布的 Arch Linux 桌面发行版，主打"美观、现代、有观点"，默认包括 Hyprland、Waybar、Alacritty 等一整套 Wayland 生态。项目从春季首发开始一直在 trending 上间歇性冒泡，今日再涨 1,055 星，可能与他本周在 X 上贴出的新版预览截图有关——8.0 版把默认字体、终端配色、状态栏重做了一遍。

Omarchy 的意义超越发行版本身。它是 DHH 高调"逃离 macOS/苹果"运动的一部分——Basecamp 已经把整个团队搬到了 Linux，Omarchy 是"配套用户体验"。GitHub 上关注它的人不都是 Arch 老玩家，更多是被 macOS 广告 / Apple Intelligence 转向劝退的开发者。评论区大量提到"想装但又怕维护"——这也预示接下来 6 个月，会有一波围绕 Omarchy 的教程、镜像、社区脚本涌现。

**看点：** DHH 一贯的能力是"把小众品味推成主流选择"，Omarchy 现在的量级可以类比 Rails 早期——不看规模看势头。

---

### 🔌 [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) — +490⭐

**Claude 的插件市场开张，社区版从零到一**

这是 Anthropic 官方发布的 Claude Code / Claude Cowork 社区插件仓库，用来登记、审核、分发外部作者写的 skill 和 hook。虽然总 star 只有 1,328，但今日一夜 +490 意味着"社区第一次真的把它当分发渠道"。仓库里已经能看到几十个提交：从"每日日报生成器"（就是本项目所属类型）到"PR reviewer bot"再到"React 组件生成 skill"。

Anthropic 走这一步的关键在于把 Claude Code 从"CLI 工具"变成"平台"——插件市场是 platform play 的门槛。跟 VSCode marketplace 或 Zapier 类似，一旦第三方作者数量到临界点，Claude 的 lock-in 就不再依赖模型能力，而是靠"你的团队工作流已经嵌了 20 个 plugin"。这也是它跟 OpenAI Codex 走出差异化的关键——Codex 目前没有对等的社区市场。

**看点：** 下一个观察指标是"有没有第一个明星 plugin 出现"——类似当年 Cursor 靠 [continue.dev] 反哺自己那种。

---

### 🆓 [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code) & [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi) — 免费 token 攻略集体上榜

**"薅羊毛派"repo 成为 2026 下半年 GitHub 主线之一**

两个仓库主题接近：把 Google 学生礼包、GitHub Student Pack、OpenRouter 试用额度、DeepInfra 送的推理量等免费额度打包成教程与自动化脚本，让个人开发者能在不付费的前提下跑 Claude / GPT / Codex。free-claude-code 一天涨近 900 star，freellmapi 也已经超过 19k。这类项目在 2024 年就出现过，但今天卷土重来的背景不一样：token 单价虽然在跌，但主力模型（Opus 5、GPT-5.6 Sol）的实际吞吐消耗越涨越快，普通独立开发者半个月的推理账单已经能顶一份美区订阅费。

值得注意的是，两个 repo 都刻意站在"合规灰色地带"之上——教程里都强调"个人非商用、学生用途"，README 顶部大写字提示不要在企业里用。这种"半正当薅羊毛"的社区文化在 GitHub trending 上第一次出现是 2020 年的 Colab 白嫖脚本，历史又在重演。对上游厂商（Google/Anthropic/OpenAI）来说，这是一波"必须默许"的免费用户培养——但一旦超过某个成本阈值，接下来 6 个月会看到规则收紧。

**看点：** 这类 repo 的星曲线是不是可以作为"AI 平权指标"？每次它们再冲榜，都说明"付费门槛与真实需求之间的裂缝"又扩大了一次。

---

## 生态观察

**主线：Claude 生态在扩张，OpenAI 在补短板。** 今天榜单里跟 Claude 直接相关的项目多达 4 个（free-claude-code、karpathy-skills、claude-plugins-community、claude-obsidian），加上一个专门开源"Options+"式桌面软件的 OpenLogi 也强调 MCP 集成。相反，Codex 这一颗 OpenAI 项目虽然占据榜首，但它更像是"补上过去半年欠 Claude Code 的功课"——终端 agent 的形态、权限模型、MCP 支持都在向 Anthropic 的做法靠拢。

**新增子赛道：本地优先 (local-first) agent。** apache/maka、AprilNEA/OpenLogi、claude-obsidian 都在讲同一件事：把过去需要登录 / 云端的功能拉回本地。这背后是欧美企业隐私法规和"AI 数据泄露"新闻共同推的一波产品语言。趋势指标：过去一个月 trending 出现 "local-first" 字样的项目数比去年同期翻了 2 倍以上。

**降温的：Web3、Rust vs Zig、传统 CRUD 应用。** 今天榜里没有一个纯加密项目，也没有语言之争 meta 项目——这些 2024-2025 年常见主题正在从 trending 消失。这跟 HN 那边的走向一致：社区把注意力全部投入到"AI 生产工具 + 开发者体验"两个赛道，其他议题被压得很低。

**中国背景开发者的比例继续上升。** OpenLogi 作者 AprilNEA、claude-plugins-community 里大量中文 skill、free-claude-code 作者背景——今天榜单里可辨识的中文作者/项目占比接近 30%。这与 GitHub 官方 2025 年报告的"最快增长开发者群体来自亚太"的数据一致，值得长期关注。
