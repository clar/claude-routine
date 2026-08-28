# AI 每日资讯 · 2026-08-29

## 今日焦点

> **OpenAI 自研芯片破局 · Salesforce×Anthropic 深度绑定 · Nvidia $96B 季报重构估值 · 推理价格战再降 80% · Anthropic 法律战胜五角大楼**
>
> - **OpenAI 首款自研推理芯片"Jalapeño"流片成功** —— 与 Broadcom 合作 16 个月完成，采用 TSMC N3P，700W 达 13.4 PFLOPs MXFP4，单用户 1400 tok/s（GPT-OSS）
> - **Salesforce 与 Anthropic 联合推出 Claudeforce** —— Claude 成为 Agentforce/Slack 默认推理模型，Claude Code ARR 已近 10 亿美元
> - **Nvidia 二季度 $96.2B 营收** —— 同比 +106%，Blackwell Ultra 大规模出货但暂停部分云融资交易
> - **OpenAI GPT-5.6 Luna 输入 token 价格降至 $0.20/M** —— 一次 80% 降幅，ChatGPT 周活突破 10 亿
> - **联邦法官裁定五角大楼不得将 Anthropic 列入黑名单** —— AI 公司维护安全边界的法律先例被确立

---

## 热点速览

| # | 新闻标题 | 来源 | 重要度 |
|---|---------|------|--------|
| 1 | OpenAI 首款自研推理芯片 Jalapeño 与 Broadcom 联合流片 | Tech Startups | ⭐⭐⭐⭐⭐ |
| 2 | Salesforce × Anthropic 推出 Claudeforce，Claude 默认接管 Agentforce | Tech Startups | ⭐⭐⭐⭐⭐ |
| 3 | Nvidia FY26 Q2 营收 $96.2B，同比 +106% | Intellectia | ⭐⭐⭐⭐⭐ |
| 4 | OpenAI GPT-5.6 Luna 输入价格 80% 直降至 $0.20/M tokens | AI News Recap | ⭐⭐⭐⭐ |
| 5 | ChatGPT 周活跃用户突破 10 亿大关 | AI News Recap | ⭐⭐⭐⭐ |
| 6 | 联邦法官：五角大楼不得因安全立场将 Anthropic 列入黑名单 | AI News Recap | ⭐⭐⭐⭐ |
| 7 | Anthropic 锁定 $71B 长期算力承诺 | Bloomberg | ⭐⭐⭐⭐ |
| 8 | Google DeepMind 大换血：Hassabis 转任董事长，Jeff Dean 离职创办 Discovery Loop | Build Fast with AI | ⭐⭐⭐⭐ |
| 9 | Claude Code ARR 逼近 10 亿美元，编程赛道白热化 | Tech Startups | ⭐⭐⭐⭐ |
| 10 | Fireworks AI 完成 $1.505B D 轮融资 | Blog.mean.ceo | ⭐⭐⭐⭐ |
| 11 | Together AI 完成 $800M C 轮，Aramco/Nvidia/Salesforce 领投 | Blog.mean.ceo | ⭐⭐⭐ |
| 12 | 欧盟 AI 法案透明度条款 8/2 正式实施 | 欧盟委员会 | ⭐⭐⭐⭐ |
| 13 | A16Z 首只硬件基础设施基金 Machine Age 募资 $1.1B | Tech Startups | ⭐⭐⭐ |
| 14 | Google 发布 Gemini 3.5 Transcribe 语音端点 | AI News | ⭐⭐⭐ |
| 15 | Google A2A 协议加入 Linux 基金会 Agentic AI Foundation | Tech Startups | ⭐⭐⭐ |

---

## 深度点评

### 🏆 No.1 · OpenAI Jalapeño 芯片流片：芯片自主化的信号弹

**[Tech Startups](https://techstartups.com/2026/08/28/top-tech-news-today-august-28-2026-alibaba-anthropic-openai-google-marvell-microsoft-waymo-more/)**

OpenAI 正式宣布首款自研推理芯片 **Jalapeño**，与 Broadcom 合作从设计到流片仅耗时 16 个月，采用 TSMC N3P 工艺。关键指标：700W 功耗下达到 13.4 PFLOPs 的 MXFP4 算力，DeepSeek R1 上跑到 700+ tok/s/user，GPT-OSS 达到约 1,400 tok/s/user。

这颗芯片的意义远超技术参数本身：它是 OpenAI 摆脱对 Nvidia 单一依赖的第一步，也验证了 Broadcom 作为"AI 时代第二 fab-less 设计伙伴"的价值链地位。16 个月的时间线在业界属于极快 —— 相比之下，Google TPU、Amazon Trainium 早期版本均在 24 个月以上。这背后是 OpenAI 团队从 Google TPU 出走的 Richard Ho 等硬件老兵在推动。

对市场而言，需要关注三件事：一是 Nvidia 是否会因为超大客户去 GPU 化而出现估值重估；二是 OpenAI 是否会把这颗芯片的产能优先给自家推理服务，从而进一步压低价格；三是 Anthropic、Meta 会不会跟进"设计-流片-上线"节奏，加速自研化。

**点评：** 当 GPT 越来越像"应用软件"时，Jalapeño 揭示了背后正在建的是电力和硅两个层面的垂直帝国。Nvidia 依然强大，但云厂商 + AI Lab 联合推自研芯片的黄金时代已经开启。

---

### 🚀 No.2 · Salesforce × Anthropic 推出 Claudeforce：企业 AI 生态战定型

**[Tech Startups](https://techstartups.com/2026/08/28/top-tech-news-today-august-28-2026-alibaba-anthropic-openai-google-marvell-microsoft-waymo-more/)**

Salesforce 与 Anthropic 正式宣布 **Claudeforce** —— 一项将 Claude 深度嵌入整个 Salesforce 技术栈的战略合作。Claude 将作为 **Agentforce、Slack、开发者工具的默认推理模型**，配套发布 37 个预置销售技能，Pilot 客户已可接入，9 月进入公开 Beta。

同时爆料的一组数字更值得关注：Claude Code 上线以来 ARR 已接近 10 亿美元，这个数字比业界估算的还要高 2-3 倍。Salesforce 选择 Claude 而非 OpenAI 作为默认模型，是自 Bret Taylor 时代以来最重要的技术站队 —— 意味着 Salesforce 押注的是"具备真正 Agent 能力的模型"，而非仅通用聊天。

对 OpenAI 而言，这是一个明确的失分。TechCrunch 8 月 20 日报道 OpenAI 正在企业市场追赶 Anthropic，但 Anthropic 在 SaaS 巨头分销侧仍然握有明显优势 —— Amazon（AWS）、Salesforce、Slack、Zoom 一条线基本被锁定。

**点评：** 企业 AI 的胜负手不是"模型好"，而是"分销广"。Salesforce 一条线锁定 40 万企业客户，Anthropic 已经不再只是"Claude"，而是企业 AI 事实上的操作系统底层。

---

### 💰 No.3 · Nvidia 单季 $96.2B：AI 军备赛的现金分红机

**[Intellectia](https://intellectia.ai/blog/nvidia-q2-earnings-2026-analysis)**

Nvidia 财报周落地：FY26 Q2 营收 **$96.2 亿美元**（同比 +106%），远超华尔街 $93-95B 一致预期。数据中心业务继续贡献超过 85% 的营收，Blackwell Ultra 已在 Q2 内实现大规模出货 —— 训练速度较 Hopper 提升 4x，推理提升 30x。

但报告里隐藏着一个市场没注意的信号：**Nvidia 悄悄按下了针对小型 AI 云商的融资担保暂停键**。这个被称为 "cloud-financing deals" 的安排此前被用来帮 CoreWeave、Lambda 等 GPU 云玩家消化 Nvidia 库存。如今 Nvidia 转向紧盯超大客户（Hyperscaler + Anthropic + OpenAI），意味着二线 AI 云正在被主动挤出。

配合 OpenAI Jalapeño 落地的时间点，Nvidia 的战略画像清晰起来：不再"什么都赚"，而是把资源集中给能吃下 Blackwell Ultra 全生命周期产能的少数客户。所有想通过"堆 GPU 抽利润"的中间层公司，会面临越来越难的生存空间。

**点评：** $96B 的数字很漂亮，但更值得警惕的是"渠道收缩"。当 Nvidia 开始挑客户，AI 基础设施的洗牌就已经开始。

---

### ⚖️ No.4 · 联邦法官裁定：Pentagon 不得因安全立场封杀 Anthropic

**[AI News Recap](https://www.neuralbuddies.com/p/ai-news-recap-august-28-2026)**

一位联邦法官作出关键裁决：五角大楼不能因为 Anthropic 拒绝其某些用例（涉及杀伤性自主武器测试）就将其从供应商名单中除名。这份判决在 AI 圈的意义堪比过去互联网时代的"Section 230" —— 它首次以法院判决形式确认：**AI 公司有权坚守自身安全策略，即便与政府客户诉求冲突**。

背景：Anthropic 是唯一一家在 Usage Policy 中明确禁止部分军事用例的头部实验室。此前五角大楼将其列入"待观察"名单，暗示会影响 JWCC 后续合同。判决出台后，OpenAI、Google、Microsoft 三家都在争取"national-security contract 通道"的过程中，也必须重新掂量：政府合同 vs. 内部 AI 使用政策的合规平衡。

**点评：** 这是 2026 年最重要的 AI 治理判决之一 —— Safety-first 不再只是道德立场，而是可以在法庭上守得住的商业底线。Anthropic 的品牌溢价，正在获得法律层面的加固。

---

### 🏭 No.5 · Google DeepMind 换帅 + Anthropic $71B 算力锁单：巨头两条路

**[Build Fast with AI](https://www.buildfastwithai.com/blogs/ai-news-today-august-9-2026)**

本月早些时候的两条信号在 8 月末形成呼应：Google DeepMind 领导层大洗牌 —— Demis Hassabis 转任 Alphabet 首席科学家/董事长，CTO Koray Kavukcuoglu 接掌运营；同一日 Jeff Dean 离职创办 Discovery Loop，带走数位顶级研究员。而**同一天** Anthropic 宣布锁定 $71B 长期算力承诺。

这是"研发驱动"与"资本驱动"的经典分野时刻：
- Google 试图重整队形迎战 OpenAI/Anthropic 在模型迭代速度上的领先
- Anthropic 则选择用天量长约把未来 3 年的计算能力预付出去（相当于给自己的 $61.5B 估值再打一针强心剂）

搭配 Fireworks AI 15 亿 D 轮、Together AI 8 亿 C 轮，市场正在形成"模型 + 中间层推理平台"双寡头结构。而 Jeff Dean 出走创业则是另一个信号 —— 顶级研究员正加速离开大公司，AI 创业下一波"研究员系"独角兽正在形成。

**点评：** 巨头级 AI 已经进入"算力 = 时间"的博弈阶段。Google 的组织重构能不能变成模型层面的战斗力，是 Q4 前最大的看点。

---

## 行业观察

**今日主线：垂直整合 vs. 水平分工的第二次决战。** OpenAI 自研芯片、Anthropic 天量算力预付、Salesforce 深度绑定 Claude、Nvidia 挑客户 —— 每一个动作都在同一个方向：**基础设施 + 模型 + 分销的一体化**。这与 2000-2005 年互联网从"分层"走向"垂直生态"的路径几乎一致。

**结构性变化三条：**
1. **模型价格战全面开打。** GPT-5.6 Luna 输入降至 $0.20/M，一年前的 GPT-4 Turbo 是 $10/M，两年降 98%。推理越来越像电力，卖方开始考虑"打包销售"（Anthropic Bedrock、OpenAI Enterprise）而非按 token 卖。
2. **企业市场是分销之战，不是模型之战。** Salesforce 选 Claude、微软继续押 OpenAI、Google 自家 Workspace 力推 Gemini —— 决胜点在渠道，不在跑分。
3. **AI 治理判决化正在到来。** Anthropic 法律战胜利 + 欧盟 AI 法案 8/2 生效 + 白宫 AI 安全框架 —— 合规能力将成为 2027 年 AI 公司的核心壁垒之一。

**观察窗口：** Nvidia GTC 秋季场（10 月）会否公开回应 OpenAI Jalapeño；Google Gemini 3 Ultra 是否能在 10-11 月落地追赶；Anthropic 是否公开 Claude 4.5 时间表以对抗 GPT-5.6 Luna 的价格战。
