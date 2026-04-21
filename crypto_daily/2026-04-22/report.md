# 加密货币每日速报 · 2026-04-22

## 今日焦点

> **Kelp DAO 余波 · 银行质疑区块链 · ETF 资金回流 · MiCA 最后冲刺 · 中东地缘风险交易**
>
> - **Jefferies 警告**：Kelp DAO $292M 漏洞或让大银行重新评估区块链部署
> - **BTC 回踩 $76K**：Bitcoin 开盘 $75,854 → 盘中 $76,535，Ethereum 站上 $2,320
> - **Kelp 成 2026 年最大 DeFi 漏洞**：116,500 rsETH 被抽空，18% 流通量瞬间蒸发
> - **ETF 资金回流**：单日最高净流入 $471M，AUM 重上 $96.5B
> - **BIS 警告"监管套利"**：4 月 20 日日本演讲指稳定币缺乏全球协调

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
| 1 | **Jefferies 警告 Kelp DAO 漏洞将动摇银行区块链计划** | 行业 | 机构客户风控模型被迫重写 |
| 2 | **Kelp DAO 遭 $292M 跨链桥漏洞，成 2026 最大 DeFi 黑客事件** | 安全 | 116.5K rsETH 散落 20 条链 |
| 3 | **Circle 因 Drift 黑客 $280M 遭集体诉讼** | 监管 | USDC 实时冻结机制成为诉点 |
| 4 | **Drift 获 Tether $147M 救助，换用 USDT 结算层** | 生态 | Tether 趁势扩大地盘 |
| 5 | **BTC 升至 $76,535，ETH 报 $2,322，双双上涨 2%+** | 行情 | 中东停火乐观情绪推动反弹 |
| 6 | **Morgan Stanley 推出 MSBT 比特币 ETF，首周 $14.9M** | 机构 | 传统 wirehouse 第二个入场 |
| 7 | **BlackRock IBIT 4 月 17 日单日流入 $284M** | 机构 | 继续主导 Bitcoin ETF 份额 |
| 8 | **BIS 总经理警告稳定币面临"监管严重碎片化"** | 监管 | 4 月 20 日日本演讲 |
| 9 | **MiCA 7 月 1 日全面生效倒计时** | 监管 | Circle 游说降低欧元稳定币门槛 |
| 10 | **朝鲜 Lazarus 集团策划 Drift 攻击 6 个月** | 安全 | 从社工转向基础设施结构性漏洞 |
| 11 | **54,000 个假稳定币冒充 USDC/USDT 诈骗** | 安全 | Cybernews 调查披露规模 |
| 12 | **GENIUS Act 配套规则 6 月进入意见征询期** | 监管 | FDIC/Treasury/FinCEN 联动推进 |

---

## 重点点评

### 🔑 1. Jefferies 警告银行重新评估区块链 — 机构信任首次出现系统性动摇

**[CoinDesk · 2026-04-21](https://www.coindesk.com/business/2026/04/21/crypto-s-massive-exploit-may-force-big-banks-to-rethink-their-blockchain-plans-jefferies-warns)**

投行 Jefferies 在 4 月 21 日的研报中直言：Kelp DAO $292M 漏洞可能迫使摩根大通、花旗、汇丰等正在推进区块链托管/结算试点的大银行"重新评估风险模型"。这是第一次有主流卖方分析师把 DeFi 漏洞事件直接关联到银行的合规/风控决策——过去两年"稳定币是银行的未来"叙事曾经一路狂奔，现在第一次遭遇机构投资者和合规官的质疑。

技术面看，Kelp 漏洞的致命点不是普通的智能合约 bug，而是**跨链桥 rsETH 在 20 条链上的信用传导失控**——这恰恰是银行最怕的"单点故障扩散到全网"场景。对金融业而言，"多链部署"从营销口号变成了操作风险。

接下来要看：(1) BIS/FSB 是否出具"银行 DLT 部署指引更新"；(2) 已经部署 Kinexys（摩根）、Onyx、Versana 的银行是否暂停新用例扩张；(3) Circle/Paxos 等发行方的机构合作节奏会不会放慢。

---

### 🔑 2. Kelp DAO $292M 漏洞 — LRT 赛道迎来第一次系统性清算

**[CoinDesk · 2026-04-19](https://www.coindesk.com/tech/2026/04/19/2026-s-biggest-crypto-exploit-kelp-dao-hit-for-usd292-million-with-wrapped-ether-stranded-across-20-chains) · [PYMNTS](https://www.pymnts.com/cryptocurrency/2026/kelp-dao-293-million-hack-largest-defi-theft-of-2026/)**

攻击者通过 LayerZero 桥从 Kelp 抽走 116,500 rsETH（约 18% 流通量），按当时价格约 $292M，瞬间超越 Drift 成为 2026 年最大 DeFi 盗窃案。更麻烦的是：被盗的 wrapped ETH 现在"散落在 20 条链"，即使追回也面临跨链状态一致性问题。

这是 Liquid Restaking Token (LRT) 赛道第一次遭遇真正规模化攻击。LRT 的核心卖点是"用一份 ETH 获得多重质押收益"，但其工程本质是"用复杂性换取 APY"。今天的事件把这层复杂性以最惨烈的方式暴露：任何一环（Kelp 智能合约、LayerZero 桥、下游 LP）被攻破，连带链条会把损失放大到整个生态。

**市场影响**：Ether.fi、Renzo、Puffer 等同类 LRT 项目 24h 内 TVL 流出明显；rsETH 脱钩，短暂最深折价 4.2%。Lazarus Group 的签名意味着后面几周可能还会有关联事件。

---

### 🔑 3. Drift 换用 USDT 结算 — Circle 的"中立发行方"人设第一次被撕开

**[CoinDesk · 2026-04-16](https://www.coindesk.com/business/2026/04/16/drift-gets-usd148-million-funding-from-tether-and-partners-as-it-replaces-circle-stablecoin-with-usdt-after-massive-exploit) · [Law360](https://www.law360.com/articles/2465764/circle-failed-to-freeze-280m-lost-in-april-1-hack-suit-says)**

Drift 在 4 月 1 日被黑 $280M，攻击者利用 Circle 的 CCTP 跨链协议把 $232M USDC 从 Solana 转移到 Ethereum。Circle CEO Jeremy Allaire 表态"只在执法指令下冻结钱包"，随即遭集体诉讼。现在 Drift 的回应是：**用 Tether $147M 救助款换掉 USDC，改用 USDT 作为结算层**。

这一事件把 Circle 长期经营的"受监管、合规、机构友好"人设撕了个口子——当黑客现场正在进行时，"等执法指令"的确是合规做法，但对受害项目来说就是"你眼睁睁看着钱被搬走"。Tether 则借机以速度与灵活性切入 DeFi 协议结算市场，进一步挤压 USDC 的增长空间。

**结构性启示**：稳定币已经不只是"哪个合规更好"的比较，而是"谁在危机时反应更快"的商业战争。Circle 如果不在 MiCA 压力下再次调整政策，将在 DeFi 协议侧持续失位。

---

### 🔑 4. BTC 重回 $76K — 中东地缘与 ETF 双轮推动

**[Fortune](https://fortune.com/article/price-of-bitcoin-04-21-2026/) · [Yahoo Finance](https://finance.yahoo.com/personal-finance/investing/article/bitcoin-and-ethereum-prices-today-tuesday-april-21-2026-prices-on-the-rise-this-morning-113401602.html)**

Bitcoin 4 月 21 日开盘 $75,854，盘中 $76,535；Ethereum 从 $2,314 升至 $2,322，BTC/ETH 分别上涨 2.7% 和 2.2%。从 10 月 6 日 $128,198 的历史高点看，BTC 已经深度回撤 40%，但过去一周在 $72K-$77K 区间形成窄幅震荡。

推动今日反弹的双因素：(1) 中东停火时间窗口临近，风险资产整体回暖；(2) ETF 单周流入 $786M（CoinShares），其中 BlackRock IBIT 独占 $612M。Morgan Stanley 的 MSBT 首周仅 $14.9M 显示 wirehouse 渠道增量有限，但象征意义巨大——传统财富管理架构开始正式接纳 BTC 配置。

**关键位**：下方 $72K 是 4 月以来的成本密集区，若失守可能打开到 $65K 的空间；上方 $82K 是中期反弹阻力。ETH/BTC 比值 0.0303，已跌至 2021 年以来最低，L1 轮动信号尚未出现。

---

### 🔑 5. MiCA 倒计时 vs BIS 警告"监管碎片化" — 稳定币全球分裂进行时

**[ESMA MiCA](https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica) · [WEEX 监管综述](https://www.weex.com/news/detail/crypto-regulation-news-2026-sec-cftc-framework-genius-act-and-mica-2-coming-695837)**

MiCA 全面生效进入最后 70 天倒计时（7 月 1 日），核心分歧仍未解决：Circle 等大型稳定币发行方 3 月 24 日向 ESMA 递交意见，要求放宽对欧元外稳定币（即 USDC）的结算门槛。4 月 20 日 BIS 总经理在东京公开演讲，直言"没有更强的国际协调，稳定币监管面临严重碎片化和有害的监管套利"——这话是对 MiCA/GENIUS/香港/新加坡各自为政的直接批评。

三大全球主要框架已经基本定型：**EU MiCA**（发行方需持牌、欧元限额）、**US GENIUS Act**（FDIC/Treasury/FinCEN 联合规则 6 月征询）、**亚洲双核**（香港 MiCA-类、日本更严）。共同点：全储备、可赎回、许可制。差异点：对"离岸美元稳定币"的容忍度——EU 最严、US 最宽、亚洲居中。

**对行业影响**：Tether 在监管套利中持续受益（注册在萨尔瓦多），Circle 被迫走合规深坑；下半年稳定币市场的份额战会是一场"合规成本 vs 市场覆盖"的博弈。

---

## 市场脉搏

| 资产 | 价格 | 24h 变动 |
|------|------|----------|
| BTC | $76,535 | +2.7% |
| ETH | $2,322 | +2.2% |
| ETH/BTC | 0.0303 | 多年新低 |
| BTC Spot ETF AUM | $96.5B | 月内新高 |
| 本月 Bitcoin ETF 净流入峰值 | $471M（4/6 单日） | 单日次高 |

**情绪与技术信号**：
- **恐惧与贪婪**：市场仍处"中性偏恐惧"，Kelp 事件短期压制 DeFi 情绪
- **永续资金费率**：BTC 永续呈低正值（0.005%/8h），多空平衡
- **关键技术位**：BTC 下方 $72K / 上方 $82K；ETH 下方 $2,200 / 上方 $2,550
- **宏观变量**：中东停火（周三到期）、美联储 5 月 FOMC 预期、MiCA 合规截止（7 月 1 日）

**今日主题**：**信任重估**——机构投资者、项目方、稳定币用户都在同时重新评估自己的对手方风险。从 Drift 到 Kelp，两周内 $572M 的损失让整个"银行-稳定币-DeFi"链条的可靠性叙事第一次出现结构性裂缝。短期看，这会让资金流向 CEX 与受监管产品；中期看，跨链桥与 LRT 架构会进入一轮残酷的优胜劣汰。

Sources:
- [CoinDesk: Jefferies 警告银行重估区块链](https://www.coindesk.com/business/2026/04/21/crypto-s-massive-exploit-may-force-big-banks-to-rethink-their-blockchain-plans-jefferies-warns)
- [CoinDesk: Kelp DAO $292M 漏洞](https://www.coindesk.com/tech/2026/04/19/2026-s-biggest-crypto-exploit-kelp-dao-hit-for-usd292-million-with-wrapped-ether-stranded-across-20-chains)
- [CoinDesk: Drift 换用 Tether](https://www.coindesk.com/business/2026/04/16/drift-gets-usd148-million-funding-from-tether-and-partners-as-it-replaces-circle-stablecoin-with-usdt-after-massive-exploit)
- [TheStreet: Circle 被集体诉讼](https://www.thestreet.com/crypto/markets/circle-slapped-with-class-action-lawsuit-over-2026s-largest-hack)
- [Yahoo Finance: BTC/ETH 价格 4/21](https://finance.yahoo.com/personal-finance/investing/article/bitcoin-and-ethereum-prices-today-tuesday-april-21-2026-prices-on-the-rise-this-morning-113401602.html)
- [Fortune: Bitcoin 价格 4/21](https://fortune.com/article/price-of-bitcoin-04-21-2026/)
- [BYDFi: Bitcoin ETF 4 月流入](https://www.bydfi.com/en/cointalk/bitcoin-etf-flows-news-april-2026-institutional-demand-rebound)
- [KuCoin: BlackRock IBIT $118M 流入](https://www.kucoin.com/blog/blackrock-drives-etf)
- [WEEX: 2026 全球加密监管综述](https://www.weex.com/news/detail/crypto-regulation-news-2026-sec-cftc-framework-genius-act-and-mica-2-coming-695837)
- [Gizmodo: 朝鲜 6 个月情报行动](https://gizmodo.com/crypto-project-details-alleged-6-month-north-korean-intel-op-behind-285-million-hack-2000741330)
