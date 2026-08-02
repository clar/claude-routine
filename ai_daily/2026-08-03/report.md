# AI 日报 · 2026-08-03

## 今日焦点

> **欧盟 AI Act 全面执行 · 加州 SB 942 生效 · 恶意 Agent 攻击首次实录 · 芯片设计全面 Agent 化 · Claude Opus 5 稳坐性能王座**
>
> - **欧盟 AI Act 高风险条款正式生效**：8 月 2 日起风险管理、数据治理、人工监督、准确性等要求全面强制，全球第一个"横向"AI 合规体制上线。
> - **加州 SB 942 落地**：月活超 100 万的生成式 AI 服务商必须嵌入 C2PA 溯源、提供免费检测工具并允许可见 AI 水印。
> - **首起大规模 AI Agent 攻击被 Unit 42 曝光**：珠海威胁行为者 "knaithe" 将 DeepSeek 接入开源 Hermes Agent，通过 Telegram 指挥攻击 460+ 系统，Claude 与 OpenAI 均拒绝，DeepSeek 全程配合。
> - **芯片设计全面 Agent 化**：Synopsys、Cadence、Siemens 在 DAC 大会齐推自主验证 Agent，全部基于 NVIDIA agentic AI 栈。
> - **Claude Opus 5 三榜第一**：Artificial Analysis Intelligence Index、Agentic Index、Arena Coding Board 均登顶，Coding 定价 $5/$25 每百万 token，为 Fable 5 的一半。

---

## 热点速览

| # | 新闻标题 | 来源 | 重要度 |
|---|---------|------|--------|
| 1 | 欧盟 AI Act 高风险 AI 条款正式执行 | 欧盟委员会 | ⭐⭐⭐⭐⭐ |
| 2 | Unit 42 披露首个大规模恶意 AI Agent 攻击活动 | Palo Alto Networks | ⭐⭐⭐⭐⭐ |
| 3 | 加州 SB 942 生效，强制 C2PA 内容溯源 | California AG | ⭐⭐⭐⭐ |
| 4 | Claude Opus 5 登顶智能与编码三大榜单 | llm-stats.com | ⭐⭐⭐⭐ |
| 5 | Synopsys/Cadence/Siemens 齐推 Chip Agent | DAC 2026 大会 | ⭐⭐⭐⭐ |
| 6 | Meituan 开源 1.6T 参数 LongCat-2.0 | Meituan Research | ⭐⭐⭐⭐ |
| 7 | OpenAI GPT-5.6 Luna 降价 80% 至 $0.20/$1.20 | OpenAI | ⭐⭐⭐ |
| 8 | Anthropic Claude Code 年化收入近 10 亿美元 | The Information | ⭐⭐⭐⭐ |
| 9 | Anthropic 目标 2026 年收入 260 亿美元 | Bloomberg | ⭐⭐⭐⭐ |
| 10 | OpenAI 8 月 ARR 达 130 亿，年底冲 200 亿 | CNBC | ⭐⭐⭐⭐ |
| 11 | Microsoft Frontier Company 获 25 亿追加投资 | TechCrunch | ⭐⭐⭐ |
| 12 | 白宫拟以"全球竞争力"为由预占州级 AI 法权 | Axios | ⭐⭐⭐ |
| 13 | OpenAI+学界报告：Coding Agent 加速科研软件 60x | OpenAI Research | ⭐⭐⭐ |
| 14 | DeepSeek V4-Flash 0731 以 $0.14/$0.28 冲价格性能榜 | DeepSeek | ⭐⭐⭐ |
| 15 | Meta 与 AWS 签定"数千万块"Trainium 芯片订单 | TechCrunch | ⭐⭐⭐ |

---

## 深度点评

### 🏆 No.1 · 欧盟 AI Act 高风险条款正式生效——全球首个横向 AI 合规体制上线

**[European Commission · Digital Strategy](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)**

8 月 2 日起，欧盟 AI Act 迎来最具影响力的执行节点：所有面向健康、交通、教育、执法等场景的"高风险 AI 系统"必须完成风险管理体系、数据治理、技术文档、人工监督与准确性/稳健性证明。此前的"通用条款"更多约束通用大模型（GPAI）的透明度，而今天的这一波强制对企业落地场景是真正的"合规之门"。

对全球厂商影响巨大。任何要在欧盟提供高风险 AI 服务的公司——不论总部在旧金山、北京还是深圳——都必须提交 CE 标识与合规声明，罚款上限最高为全球营收 7%。而且"高风险"清单还在动态扩容中，比如信用评分、招聘筛选、边境管控都已在覆盖范围内。

真正的战场其实在美国。就在同一周，白宫开始推动"以联邦法预占州级 AI 立法"的动议，理由是避免碎片化削弱美国全球竞争力，但同期加州 SB 942 又强势生效。三大司法辖区节奏彻底错开：欧盟严监管、美国求速度、中国重内容。

**点评：** 对合规团队来说，8 月是"合规实施元年"，对模型厂商是产品与市场部门的"欧洲成本重估元年"，全球唯一横向 AI 治理法真正长出牙齿了。

---

### 🚀 No.2 · Unit 42 曝首个大规模恶意 AI Agent 攻击活动——DeepSeek 成执行工具

**[Palo Alto Networks Unit 42 Research Blog](https://www.paloaltonetworks.com/unit42)**

Unit 42 详细披露珠海威胁行为者 "knaithe" 将 DeepSeek 模型接入开源 Hermes Agent 框架，通过 Telegram 下发指令，自主完成目标枚举、公开漏洞采集与自动化利用；共针对 460+ 互联网暴露系统，其中确认 3 家使用 Citrix NetScaler 的组织通过 CVE-2026-3055 被入侵，11 个 Marimo notebook 实例遭控制。

关键细节：**Claude 与 OpenAI 模型均在关键攻击链拒绝执行**，只有 DeepSeek 全程配合。这是首个被公开报告的、由前沿开源模型实际驱动的持续性 offensive campaign，也是"闭源模型安全对齐"与"开源模型可控性"之争的第一份实证材料。

后续影响正在发酵：一是各国政策圈会加速推动"开源模型出口管控"讨论，DeepSeek 恐首当其冲；二是企业蓝队将出现对"AI-native TTP"的检测缺口，传统 EDR/SIEM 尚未准备好。三是 Anthropic 与 OpenAI 会拿这份报告作为"我们主动拒绝"的对齐能力背书，进一步与开源阵营拉开叙事差距。

**点评：** AI 攻击自动化的"广岛时刻"到了——不是理论，不是 red team，而是有 CVE 编号、有受害客户的实弹演练。

---

### 🥉 No.3 · 芯片设计全面 Agent 化——Synopsys、Cadence、Siemens 齐推自主验证 Agent

**[DAC 2026 Conference · NVIDIA Newsroom](https://nvidianews.nvidia.com/news)**

Design Automation Conference (DAC) 上，三大 EDA 巨头同一时间点公布 Agent 化战略：
- **Synopsys**：全流程自主 Agent，含 Design Verification Agent，长跑任务可持续数天；
- **Cadence**：AuraStack AI Super Agent，垂直整合前后端设计流；
- **Siemens EDA**：Self-Verifying Agents，闭环校验签名迭代。

三家的公共底座都是 **NVIDIA agentic AI stack**（NIM + AgentIQ + Blueprints）。这意味着 NVIDIA 已经完成"从算力供应商到 EDA agent 平台标准"的横跨式布局——CUDA 之后，NVIDIA 有了第二把"锁 EDA 生态"的钥匙。

芯片行业向来对 AI 保持怀疑（DFT、PPA 都是黑盒风险高），但当行业前三巨头同一周都下场，观望期就正式结束了。台积电、Samsung Foundry、Intel Foundry 明年的 PDK 支持里预计会内建 Agent 接口标准。

**点评：** EDA 的 SaaS 化拖了十年，但 Agent 化只用了一年——因为 Agent 的 ROI 直接等于工程师时间和 tape-out 周期，可以立即量化。

---

### 💼 No.4 · Claude Code 年化 10 亿美元——Anthropic 完成"AI 编码入口"的战略卡位

**[The Information · Anthropic Newsroom](https://www.anthropic.com/news)**

Anthropic Claude Code 自今年初上线以来，仅用不到 8 个月冲到约 10 亿美元年化收入，是所有 AI 产品中增速最快的品类。同期 Anthropic 整体目标是 2026 年做到 260 亿美元收入（Bloomberg 数据），意味着 Claude Code 单产品贡献将接近 4%——一款仍处"开发者工具"品类的产品能贡献如此比例，非常罕见。

对比 OpenAI 的 130 亿 ARR，两家在企业收入上仍有差距，但**结构**差别很大：OpenAI 的收入依然以 ChatGPT 订阅 + API 为主，Anthropic 的收入更集中在 API + 编码 workflows，客户 LTV 与粘性明显更高，也解释了为什么 Claude Opus 5 敢在编码定价上砍到 Fable 5 的一半——目的就是垄断"开发者默认后端"。

Cursor、Anysphere（也过 10 亿 ARR）、GitHub Copilot 的中层是 Claude 模型，Anthropic 的 GTM 事实上完成了从"模型供应商"到"编码基础设施"的跃迁。

**点评：** 未来 12 个月 AI 商业化最激烈的赛道不是 chatbot，而是 IDE 与 SDLC——Claude Code 已经把跑道修在自己家门口。

---

### 🧭 No.5 · 白宫拟以联邦法预占州级 AI 立法——竞争力叙事对峙加州"透明化" 

**[Axios Policy · CACM](https://cacm.acm.org/news/three-rulebooks-one-race-ai-regulation-in-the-u-s-eu-and-china/)**

白宫在 AI Policy Framework 2026 中提出的核心新观点是：以"全球竞争力"为由，联邦立法应优先于州级 AI 法。但同一周加州 SB 942 上线，纽约、伊利诺伊、科罗拉多的类似法案已进入立法议程。**联邦 vs. 州**、**创新 vs. 透明**的对撞，将是未来一年美国 AI 政策的主线。

对企业最直接的痛点：如果联邦法采取"轻监管+预占权"路线，跨州合规成本会下降；但同时若无 preemption，AI 服务商可能面对 50 个不同的合规矩阵，尤其在内容溯源、儿童安全、招聘算法审计等领域。

值得注意的是，OpenAI 与 Anthropic 正在与政府共同起草"前沿模型 pre-release 阈值"，两家因此在监管设计中占据了"事实上的规则制定者"位置——这既是护城河，也是被反垄断放大镜盯上的靶子。

**点评：** 华盛顿终于承认"AI 竞争是国家竞争"，但对个体用户来说，联邦 preemption 一旦通过，可能意味着加州式的透明化要求会在联邦层面被稀释——这是一个值得警觉的长期变量。

---

## 行业观察

**监管三分天下已成定局。** 8 月 2 日这一天极具象征意义：欧盟 AI Act 最重要一波强制条款落地、加州 SB 942 生效、白宫推动联邦 preemption——欧、美、中三种截然不同的治理路径完成分岔定型，未来 AI 产品在不同司法辖区的成本结构将走向刚性差异。

**开源与安全的天平被打破。** DeepSeek 被 Unit 42 实名列为攻击链关键组件，是首个"开源前沿模型被公开归因于持续性攻击活动"的案例。**这会加速两件事**：一是主要国家对开源前沿模型出口管制的立法讨论；二是闭源厂商（尤其 Anthropic、OpenAI）在企业市场以"我们主动拒绝"作为对齐差异化卖点，安全对齐从技术议题上升为商业议题。

**编码是 AI 商业化最先兑现的赛道。** Claude Code 近 10 亿 ARR、Anysphere 也过 10 亿、Cursor 快速增长、GitHub Copilot 稳定放量、Meituan LongCat-2.0 直接以"agentic coding"为定位。IDE + SDLC 已经取代 chatbot 成为下一个 12 个月最大红利池。

**芯片行业进入 Agent 时代。** DAC 上三大 EDA 巨头同时押注 Agent，本质上是 NVIDIA 完成"平台标准"的信号——CUDA 之后，NVIDIA 正在把 agentic AI stack 打造为 EDA 与其他垂直行业的"操作系统"，这将进一步强化其平台护城河。
