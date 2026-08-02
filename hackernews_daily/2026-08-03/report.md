# Hacker News 日报 · 2026-08-03

## 今日焦点

> **Karpathy 的 SVG 鹈鹕 · EU 硬件级年龄验证 · F* 证明语言 · macOS-on-Linux Kakehashi · eBay 骚扰案 5600 万赔偿**
>
> - **Karpathy's Pelican** 355分 · 277评：Karpathy 用一张 SVG 鹈鹕梗图重启 HN 对"模型创造力评测"的讨论。
> - **EU Age Verification 强制硬件绑定证明** 62分 · 26评：欧盟年龄验证方案要求 device attestation，Linux 阵营炸锅。
> - **F\* proof-oriented language** 136分 · 60评：老牌形式化验证语言重回视野，讨论 AI Coding 时代形式化的复兴。
> - **Show HN: Kakehashi** 142分 · 36评：Linux ARM 上跑 macOS 二进制的实验用户态实现。
> - **eBay 骚扰案：5600 万美元和解** 119分 · 49评：企业内部"信息安全"如何变成对个人的骚扰。

---

## 今日热榜总览

| 排名 | 标题 | 描述 | 分数 | 评论数 |
|------|------|------|------|--------|
| 1 | [Karpathy's Pelican](https://news.ycombinator.com/item?id=49140998) | Karpathy 玩梗 SVG 生成 | 355 | 277 |
| 2 | [Meshdiff – client-side STL 对比](https://news.ycombinator.com/item?id=49143479) | 浏览器端 3D 模型 diff | 167 | 17 |
| 3 | [Show HN: Kakehashi macOS on Linux ARM](https://news.ycombinator.com/item?id=49145937) | 用户态运行 macOS 二进制 | 142 | 36 |
| 4 | [Twenty Years of RISC OS Open](https://news.ycombinator.com/item?id=49143967) | 老 OS 开源二十年回顾 | 142 | 25 |
| 5 | [F* proof-oriented language](https://news.ycombinator.com/item?id=49143925) | 形式化证明语言重启 | 136 | 60 |
| 6 | ['Crush this lady': eBay 骚扰赔 5600 万](https://news.ycombinator.com/item?id=49147435) | 大厂 OSINT 变武器化 | 119 | 49 |
| 7 | [Fasttracker II clone in C using SDL2](https://news.ycombinator.com/item?id=49094151) | 追星族 tracker 重制 | 108 | 36 |
| 8 | [Developers 与工具的信任问题](https://news.ycombinator.com/item?id=49097961) | 工具即信任的具象 | 106 | 51 |
| 9 | [Note-Taking and PKM](https://news.ycombinator.com/item?id=49084324) | 反 PKM 的清醒之作 | 82 | 23 |
| 10 | [手绘时代的公交票设计](https://news.ycombinator.com/item?id=49123003) | 平面设计怀旧长文 | 83 | 27 |
| 11 | [Show HN: NixOS-DGX-Spark](https://news.ycombinator.com/item?id=49146267) | Nix 跑上 DGX Spark | 78 | 21 |
| 12 | [TP-Link TL-841N 根提取](https://news.ycombinator.com/item?id=49145883) | 家用路由拆机固件反编 | 72 | 13 |
| 13 | [Habsburg 下巴 SVG 蛙生成器](https://news.ycombinator.com/item?id=49147622) | AI meme 蛙类版 | 65 | 38 |
| 14 | [EU 年龄验证强制硬件绑定](https://news.ycombinator.com/item?id=49148128) | 装置证明 = 硬绑定隐私风险 | 62 | 26 |
| 15 | [SSH 蜜罐凭证收集报告](https://news.ycombinator.com/item?id=49146605) | 蜜罐实录 SSH 攻击链 | 31 | 24 |
| 16 | [Show HN: Framework 12 木门声效](https://news.ycombinator.com/item?id=49148048) | 硬件 hack + 恶趣味 | 21 | 2 |
| 17 | [FamilyWild X11 跨主机共享](https://news.ycombinator.com/item?id=49147978) | 老 X 协议家庭部署 | 17 | 5 |
| 18 | [Read the Novels](https://news.ycombinator.com/item?id=49129676) | 反刷屏思考型长文 | 12 | 0 |
| 19 | [Schmitt Trigger 迟滞设计](https://news.ycombinator.com/item?id=49111194) | 老经典模电小科普 | 12 | 7 |
| 20 | [TinyNES 评测](https://news.ycombinator.com/item?id=49147760) | 极小型 NES 复刻机 | 9 | 0 |

---

## 重点讨论点评

### 🥇 [Karpathy's Pelican](https://news.ycombinator.com/item?id=49140998) — 355分 · 277评

**Karpathy 又扔了一个"评测创造力"的梗，评论区吵翻天**

Andrej Karpathy 在 X 上发了一张 AI 生成的 SVG 鹈鹕，配上简单一句注释"看模型能不能画一只像样的鹈鹕"。这个"SVG 动物创造力测试"跟 Simon Willison 长期做的"SVG pelican 打分"是同一血脉，本质是**低带宽评测框架**——不能像 MMLU 那样刷分，但一眼能看出模型"审美"和"空间理解"。

评论区分裂成两派：一派认为这就是玩梗（"pelican benchmarks 又来了"），另一派认真讨论 SVG 生成对模型的意义——因为 SVG 需要模型同时"理解语义 + 生成结构化代码 + 保持视觉一致性"，是极少数把语言、代码、图像三种能力打包考核的任务。有人甚至提出：SVG 打分 + human eval 可能是评测 Claude Opus 5、Fable 5 差异的最锐利视角。

> *热门评论摘要：* 有资深研究者指出 SVG 评测唯一的问题是"没有客观 ground truth"，但反驳说"benchmark 只要能让不同模型在盲测中被人排出稳定次序就已经赢了 90% 的 leaderboard"。

---

### 🥈 [EU Age Verification Project Mandates Hardware-Bound Attestation](https://news.ycombinator.com/item?id=49148128) — 62分 · 26评

**Linux 阵营的"数字身份 vs. 用户主权"之争**

欧盟推动的年龄验证项目要求 device attestation：想访问受年龄限制的服务，用户设备必须能证明其硬件、启动链、内核未被篡改。对 Windows/macOS/iOS/Android 用户来说影响不大，因为都已经有 Secure Boot、Secure Enclave、Play Integrity 等基础设施；但对 Linux 桌面用户（尤其自编内核者）来说，这几乎等于"从主流互联网被驱逐"。

评论区快速上升到哲学层：**这不是年龄验证问题，是把"设备身份"作为默认信任基石**——一旦通过，之后所有反爬虫、反 DDoS、支付风控都会跟进要求 attestation，Linux 桌面在互联网上的边缘化就成了系统性问题。也有评论提到 Google 的 Web Environment Integrity 提案曾因舆论反对搁置，但欧盟此次是"以监管形式"倒逼落地，抵抗力度会小得多。

> *热门评论摘要：* 一位维护 Fedora 的资深用户直言"这不是保护未成年，这是给硬件厂商颁发通行证——五年后想在互联网上以 root 身份跑东西的人会像现在跑 XP 的人一样稀有"。

---

### 🥉 [F\*: A general-purpose proof-oriented programming language](https://news.ycombinator.com/item?id=49143925) — 136分 · 60评

**AI Coding 时代重回形式化验证：F\* 的第二春**

F\* 是微软研究院 + INRIA 开发的证明导向语言，用 SMT 求解 + tactics 完成程序性质验证；老朋友 HACL\* 加密库、EverParse、miTLS 都是它的成品。今天它重新登上 HN 首页，背后是一个越来越强的趋势：**AI Coding 生成的代码越来越"看起来对"，人类审查越来越难，形式化证明因此从"学术玩具"上升为"工业必需"**。

评论区讨论最激烈的是"Coding agent + F\* 是不是终极答案"——观点是：让 agent 生成实现，让 F\* 或 Lean/Coq 生成规范，人类只在类型/规范层审阅。有 InfoSec 老兵反驳"90% 的商业代码根本不值得写规范"。但支持派立即回击：Cursor、Claude Code、Codex 现在每天 push 的代码量已经是人类审查带宽的 10 倍以上，SMT-backed 验证是唯一能匹配这个速度的机械化护栏。

> *热门评论摘要：* 一位来自 Cardano 项目的评论者提到他们已经在关键部件用 F\* 做规范化，"agent 敢 push、我们敢 review 的边界完全被 F\* 决定"。

---

### 🎯 No.4 · [Show HN: Kakehashi – macOS binaries on Linux ARM](https://news.ycombinator.com/item?id=49145937) — 142分 · 36评

**开发者对"macOS 生态锁定"的又一次抵抗**

Kakehashi 是完全用户态的 macOS 二进制运行器（类似 Darling），专攻 Apple Silicon 家族的 Linux ARM 目标（如 Asahi、Ampere Altra）。作者说明白：目标不是运行 Xcode、Final Cut，而是让开发者能在 CI/Server 上直接跑 macOS 二进制，规避"必须买 Mac mini 才能构建/测试"的老痛点。

HN 上评论普遍支持，讨论集中在几个方向：**沙箱、代码签名、mach-o 加载、entitlements 兼容**——这些是 Darling 十年没解决的死结。Kakehashi 用"专注 CLI 二进制 + 依赖 Rosetta 中间层"作为妥协，被认为是"很务实"的路线选择。

> *热门评论摘要：* 有 Asahi Linux 开发者留言："能在 ARM Linux 上跑 iOS/macOS 的构建工具链是 CI 成本的救命稻草，希望能扛住苹果法务的 CDS 追杀。"

---

### 💼 No.5 · ['Crush this lady': eBay Harassment $56M Payout](https://news.ycombinator.com/item?id=49147435) — 119分 · 49评

**大厂"信息安全部"变私人复仇队的最后一章**

FT 长文复盘 2019 年 eBay 高管授意员工在网上骚扰批评公司的博主夫妇——寄血蟑螂、活蜘蛛、猪面具面罩、深夜跟踪，最终以联邦刑事定罪 + 5600 万美元民事和解收场。文章的价值不在旧事重提，而在把整个链条拆到"公司内部合规架构、执法能力、财务处罚天花板、董事会连带责任"的每个环节。

HN 讨论集中在**大厂内部"OSINT / 情报部门"扩张的合理边界**：当反欺诈、反假货、反爬虫等业务合法地需要 OSINT 能力时，这套能力和武器化只差一步（一个高管 email）。评论中有人提到 Meta、Google、Amazon 都设有类似的 corporate intelligence 部门，唯一的护栏是"文化 + 内审"，一旦 CEO 越界就再无制动。

> *热门评论摘要：* 一位前 GRC 律师留言："5600 万在 eBay 财报里是四舍五入，但真正让此案有意义的是 7 名员工被联邦定罪——只有 personal liability 才能让 corporate intelligence 部门的员工敢对高管说不。"

---

## 社区脉搏

**今天的 HN 主线可以用一个词总结：hackerspace 复古 + 严肃系统议题双开花。** Karpathy 的鹈鹕梗、Habsburg 蛙生成器、Framework 12 木门声效、FastTracker II 复刻构成了"HN 该有的极客娱乐"侧；而 F\* 的 AI 编码时代复兴、EU 硬件 attestation、eBay 骚扰案、SSH 蜜罐则代表"严肃系统议题"侧——两条线索平行推进。

**AI 相关帖子从"模型发布"转向"评测方法学与工程护栏"。** 今天 AI 板块里没有新的 SOTA 发布，但两大讨论都很深：一是 Karpathy 的低带宽评测能否成为主流，二是形式化证明能否成为 AI Coding 的护栏。这是从"哪个模型分数高"到"我们怎么信任它"的重要拐点。

**Linux 桌面 vs. 现代 web 的对撞感越来越强。** EU 硬件 attestation 的贴子只有 62 分，但 26 条评论都很激烈——这是长期议题的短期缩影，值得下周继续追。

**Show HN 数量偏低但质量高。** Kakehashi、Meshdiff、NixOS-DGX-Spark、Creakwork12——从跨平台运行时到浏览器端 3D diff，从 GPU HPC 到硬件恶搞，覆盖面很广，是 HN 传统"个人项目 + 高完成度"的典型日。
