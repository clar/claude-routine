# AI Daily · 2026-04-23

## 今日焦点

> **OpenAI 工作区 Agent 上线 · Cursor 冲 500 亿估值 · Anthropic Glasswing 安全计划 · 企业 AI 从试点到部署 · Gemini 3 Deep Think 扩大开放**
>
> - **OpenAI 推出"工作区 Agent"**：Codex 内核，面向 Business/Enterprise/Edu，可跨人协作、在 Slack 里常驻
> - **Cursor 新一轮融资磋商**：$2B 规模，估值冲 $50B+，较 6 个月前几乎翻倍；SpaceX 被曝持 $60B 优先收购权
> - **Anthropic Project Glasswing**：Claude Mythos Preview 不走公开路线，$100M 算力授信给 50 家安全机构优先补洞
> - **Citi Sky 上线**：花旗财富部门用 Gemini Live + DeepMind 数字人技术把"AI 顾问"塞进客户服务
> - **Gemini 3 Deep Think 扩开放**：科研向推理模式对 Gemini API 开放部分企业与研究者名额

---

## 热点速览

| # | 新闻标题 | 来源 | 重要度 |
|---|---------|------|--------|
| 1 | OpenAI 发布 Codex 驱动的"工作区 Agent"，面向企业开放 | 9to5Mac / OpenAI | ⭐⭐⭐⭐⭐ |
| 2 | Cursor 在谈 $2B 新一轮融资，估值超 $50B | CNBC / TechCrunch | ⭐⭐⭐⭐⭐ |
| 3 | Anthropic 启动 Project Glasswing，Claude Mythos 限定输出给网安方 | red.anthropic.com / NBC News | ⭐⭐⭐⭐⭐ |
| 4 | Citi Wealth 推出 Citi Sky：Gemini Live + DeepMind 数字人 | Google Cloud Press | ⭐⭐⭐⭐ |
| 5 | SpaceX 披露对 Cursor 持 $60B 优先收购权 | TechCrunch | ⭐⭐⭐⭐ |
| 6 | Gemini 3 Deep Think 更新并开放科研 API | Google DeepMind | ⭐⭐⭐⭐ |
| 7 | Q1 2026 全球创投融资 $297B，AI 吸走 81% | Crunchbase | ⭐⭐⭐⭐ |
| 8 | Claude Opus 4.7 正式 GA，作为 Mythos 管控期的公开替代 | Anthropic | ⭐⭐⭐ |
| 9 | OpenAI 结算 $122B 融资，投后估值 $852B | OpenAI | ⭐⭐⭐ |
| 10 | Reliable Robotics $160M 融资推动航空自主 | Tech Startups | ⭐⭐⭐ |
| 11 | AcuityMD $80M C 轮，估值 $955M，主打 AI 医械销售 | Tech Startups | ⭐⭐⭐ |
| 12 | Meta 新推 AI 模型以追赶 OpenAI/Google | CNBC | ⭐⭐⭐ |

---

## 深度点评

### 🏆 No.1 · OpenAI 发布"工作区 Agent"，Codex 内核进入 ChatGPT 企业版

**[9to5Mac — OpenAI updates ChatGPT with Codex-powered "workspace agents"](https://9to5mac.com/2026/04/22/openai-updates-chatgpt-with-codex-powered-workspace-agents-for-teams/)**

在今年 OpenAI launch week 的第二天，workspace agents 正式登场。定位是"GPTs 的进化形态"，但动力总成换成了 Codex——也就是可以写代码、跑浏览器、常驻云端的那一套。组织内员工可以**共建一个 Agent、共享运行**，既能在 ChatGPT 里调用，也能在 Slack 里常驻。面向 Business / Enterprise / Edu / Teachers 四个档位的 plan 开放研究预览。

这件事最关键的细节是"共享"二字。过去 GPTs 本质是个人的 prompt 封装，可以分发但没有共享运行状态。workspace agent 改成云端持久运行，意味着 Agent 的产出、权限、审计都能纳入企业 IT 管控范畴——这是**把 Agent 从"个人效率玩具"升级成"部门级软件资产"**的关键一步。

配合几天前（4 月 16 日）Codex Desktop 加上 90+ 插件、macOS 计算机控制、in-app 浏览器、持久化记忆等能力，OpenAI 已经搭起了一个完整的"企业 Agent 栈"。Salesforce、Microsoft Copilot、Glean 这些玩家会直接受到冲击，因为 OpenAI 绕过了这些产品的流量入口，直接在 ChatGPT 这个月活已破十亿的应用里生成 Agent。

**点评：** 2026 年的"企业 AI 之战"，战场不再是谁的模型最好，而是谁能把 Agent 嵌入最多的组织流程——OpenAI 这一枪已经贴着 Microsoft Copilot 的后腰打。

---

### 🚀 No.2 · Cursor 新一轮 $2B 融资，估值直冲 $50B+

**[CNBC — AI startup Cursor in talks to raise $2 billion at $50 billion valuation](https://www.cnbc.com/2026/04/19/cursor-ai-2-billion-funding-round.html)**

Cursor 的估值在 6 个月内从 $29.3B 翻到 $50B+，领投仍是老朋友 Thrive 和 a16z，Battery Ventures 作为新老板入场，Nvidia 战略支票同步上桌。配合 [TechCrunch 披露](https://techcrunch.com/2026/04/21/spacex-is-working-with-cursor-and-has-an-option-to-buy-the-startup-for-60-billion/) SpaceX 手握一份 $60B 的优先收购权，这家公司实际上已经进入"半上市节奏"。

值得关注的是，在 Claude Code、Cline、Codex Desktop、Windsurf 等竞品密集更新的背景下，Cursor 仍然能拿到这种估值倍数，说明**企业侧对 AI 代码助手的采购已经从"POC"跨进"人头制标配"**阶段。它的护城河不是模型，而是编辑器级别的上下文控制、团队计费、审计这三件套——这些恰恰是纯 Agent 工具难以短期复制的。

和 No.1 形成有趣对照的是：OpenAI 用 workspace agent 从 ChatGPT 一侧向 IDE 渗透，Cursor 则从 IDE 一侧向工作流渗透，两者的下半场一定会在"企业代码 + 任务 Agent"这块正面撞车。

**点评：** Cursor 估值不是泡沫，是市场在为"企业 SaaS 人头制 AI 工具"先定一个锚——50B 只是起点，真正的天花板取决于谁能先抢到 Fortune 500 的部署标准。

---

### 🥉 No.3 · Anthropic Project Glasswing：Mythos 不公开发布，只给网安方

**[Anthropic — Claude Mythos Preview](https://red.anthropic.com/2026/mythos-preview/)** · **[NBC News 报道](https://www.nbcnews.com/tech/security/anthropic-project-glasswing-mythos-preview-claude-gets-limited-release-rcna267234)**

Mythos Preview 的能力画风和前代差异显著：它在过去几周里**挖出了主流操作系统和主流浏览器中"数千"个 zero-day**。Anthropic 的结论是——这种能力已经越过了"可以直接上架 API"的安全红线。于是他们选择了一个非常激进的发布形式：Project Glasswing，**不面向公众开放，但给约 50 家关键基础设施和软件厂商（及一部分政府机构）约 $100M 的算力信用额度**，优先去为全球重要软件栈打补丁。

这是目前为止主流前沿模型里最接近"有条件锁定"的一次。它既回避了 EU AI Act 下 frontier model 的对外责任边界，也避免了把攻击性能力直接给到红队之外的用户。Anthropic 同步放出了 Claude Opus 4.7 GA 作为公开替代，等于用一个"强模型，但不到 Mythos 水平"的版本填补商业缺口。

这件事对行业的真正意义：**"模型能力大过发布门槛"开始成为常态**。从此 GPT-6 / Gemini 4 / Mythos 等一批模型大概率都会以"部分能力受限开放 + 分层许可"方式面世，而不是统一 API 发布。这一结构改变了未来 12 个月生态位——做 AI 安全、做独立第三方模型审计、做受限 API 网关的公司，价值会快速重估。

**点评：** Anthropic 这一手既是安全策略也是政治策略，等于拿一次"现实威胁展示"把"前沿模型监管 = 自愿 + 白名单"这套方案钉进了行业默认选项里。

---

### 🥉 No.4 · Citi Sky 上线：企业级 AI 进入"数字同事"阶段

**[Google Cloud Press — Citi Wealth Unveils Citi Sky](https://www.googlecloudpresscorner.com/2026-04-22-Citi-Wealth-Unveils-Citi-Sky-An-AI-Powered-Member-of-the-Citi-Wealth-Team,-Built-Using-Google-Cloud-and-Google-DeepMind-Technologies)**

Citi Wealth 不是做聊天机器人，而是把 Gemini Live API + DeepMind 实时数字人合成为"一位 7×24 的财富团队成员"——会面对面视频、语音低延迟、多模态调研入口直连内部研究系统。官方口径是"reshape 客户与顾问的交互方式"，但实际意义更硬核：**私行客户以后和团队的第一次接触，可能已经不是人类**。

这是金融业最敏感的一种部署方式能公开落地，说明两件事：一是 Gemini 的低延迟推理 + 数字人管线已经经得起合规审查（客户身份、回放、审计都做得通），二是企业客户开始愿意让 AI 承担"身份角色"，而不只是"工具角色"。

对 Google 而言，这是把 Gemini 挤进企业核心客户关系触点的一次示范；对 Anthropic 和 OpenAI 来说，提醒它们：**企业 AI 不是"部署一个模型"，而是"替换一个岗位形象"**——谁先把数字人、语音、知识库、合规这四件事打通，谁吃下核心金融/医疗/法律客户。

**点评：** 花旗此举暗示金融零售的前台正在 AI 化，而不是单纯的"效率提升"——顾问团队规模会先膨胀再压缩，真正受益的是掌握多模态 + 合规栈的大模型厂商。

---

### 🥉 No.5 · Q1 2026 全球创投 $297B，AI 吸走 81%

**[Crunchbase — Q1 2026 Shatters Venture Funding Records](https://news.crunchbase.com/venture/record-breaking-funding-ai-global-q1-2026/)**

单季度全球 VC 投资总额刷新历史纪录至 $297B，其中 AI 占 $242B（81%）。史上五大 VC 单笔中有四笔在这个季度完成：OpenAI $122B、Anthropic $30B、xAI $20B、Waymo $16B。另外 SpaceX 以 $250B 完成对 xAI 的收购，形成估值 $1.25T 的垂直整合体。

这个数据水平已经超过 2021 dot-com 末期的狂热度。值得注意的是**非顶级大模型公司的份额在被挤压**——Q1 里剩下约 19% 的非 AI 资金被稀释在大量种子/早期创业公司里，中位融资额反而下滑。IPO 管线也开始排队：SpaceX/xAI 目标 6 月以 $1.75T 上市，OpenAI 瞄准 Q4 接近 $1T。

但风险同样清晰：这种"少数几家吸金、其余受挤压"的格局，让中小 AI 应用公司 2026 下半年融资压力极大；二级市场对 AI ETF 估值的敏感度也在上升。

**点评：** 资本市场现在只相信三类 AI 故事——模型巨头、基础设施（GPU/云）、以及能证明 ARR 上千万美金的企业 SaaS——其他的请准备好现金流撑住至少 18 个月。

---

## 行业观察

今天的信号非常集中：**AI 产业进入"部署年"**。

- **OpenAI / Anthropic 各自收紧边界**：OpenAI 用 workspace agent 把自己嵌进企业员工流程；Anthropic 用 Glasswing 把前沿能力限定在风险可控的白名单。两者都不再追求"最大化对外开放"，而是在定义"我愿意为哪种部署承担责任"。
- **IDE / 开发者工具成为红海**：Cursor $50B + SpaceX $60B 优先收购权 + OpenAI workspace agent + Codex Desktop 更新 + Claude Code 上下文工程生态——这条赛道的整合大概率在 2026 下半年发生，最大变量是微软会不会亲自下场。
- **企业 AI 从试点进入常驻**：Citi Sky 这样的"AI 同事"会很快成为财富、保险、法律、医疗行业的标配姿势，驱动多模态 + 合规 + 数字人的三件套供应商估值重估。
- **资本极度集中**：AI 独角兽 Q1 吸走 81% 的 VC，这既是泡沫信号也是寡头化信号，中小应用层团队需要在 2026 下半年准备现金流防御策略。

一句话总结：**模型层继续军备竞赛，但真正的新故事在"Agent 部署层"和"企业嵌入层"——这两个位置今年下半年会迎来第一轮大规模整合。**
