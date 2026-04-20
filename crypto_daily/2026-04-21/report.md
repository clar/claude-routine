# 加密日报 · 2026-04-21

## 今日焦点

> **Kelp DAO 2.93 亿美元被盗冲击 LayerZero · BTC 在 7.5 万美元争夺 · 美伊紧张回潮 · XRP ETF AUM 破 10 亿 · SEC/CFTC 分类框架落地**
>
> - **Kelp DAO 被黑 2.93 亿美元**，两周内 DeFi 总损失突破 4.5 亿，市场质疑 LayerZero 跨链安全
> - **BTC 周一低开 $73,820 后反弹至 $75,242**，美伊周末紧张再起但 ETF 需求托底
> - **SEC 与 CFTC 联合发布代币分类框架**，airdrop/staking/wrapping 获得明确监管口径
> - **XRP ETF AUM 累计突破 10 亿美元**，CLARITY 法案本月底参议院银行委员会 markup
> - **Goldman Sachs 向 SEC 递交新比特币 ETF 申请**，Bitwise 预测 2026 年上市的加密 ETF 有望突破 100 只

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
| 1 | **Kelp DAO 遭跨链漏洞攻击损失 $293M，2026 年最大 DeFi 事故** | 安全 | ~116,500 rsETH 被盗，波及 Aave/Spark/Fluid 紧急冻结 |
| 2 | **BTC 周一低开 $73,820，盘中反弹至 $75,242（+1.9%）** | 行情 | 美伊紧张加码，ETF 资金面支撑 |
| 3 | **ETH 从 $2,263 低点回升至 $2,307** | 行情 | ETH/BTC 汇率触及 3 个月新高 |
| 4 | **SEC + CFTC 发布联合代币分类框架** | 监管 | 明确数字商品、数字证券、稳定币等五类划分 |
| 5 | **XRP ETF 总 AUM 首次突破 $1B，7 只 spot 产品在列** | 机构 | CLARITY 法案本月底 Senate Banking 标记 |
| 6 | **Goldman Sachs 递交新 BTC ETF 申请** | 机构 | 新通用上市标准生效后首批大行产品 |
| 7 | **最近两周 DeFi 45 个项目共损失 $450M** | 安全 | Kelp $293M + Drift $285M + Dango/Silo/CoW 等 |
| 8 | **Drift Protocol 4 月 1 日被盗 $285M，疑朝鲜 Lazarus 所为** | 安全 | 长期社工 + 预签名隐藏授权 |
| 9 | **BTC spot ETF 4 月 14 日单日净流入 $411.4M，IBIT 领涨** | 机构 | 连续负流入后出现 V 型反转 |
| 10 | **ETH spot ETF 4 月迄今累计 $187M 净流入，扭转 3 周外流** | 机构 | 2026 年以来单周最高纪录 |
| 11 | **Solana 冲至 $86.55（+6.3%），SOL ETF 4 月 17 日吸金 $13M** | 行情 | DeFi 量能回暖 |
| 12 | **Ethereum 预告 Glamsterdam 升级：更快 gas、更便宜的 DA** | 技术 | 预计下半年主网激活 |

---

## 重点点评

### 🔑 1. Kelp DAO $293M 被盗 — LayerZero 范式下"模块化安全"的系统性风险首次兑现

[CoinDesk 报道](https://www.coindesk.com/tech/2026/04/19/2026-s-biggest-crypto-exploit-kelp-dao-hit-for-usd292-million-with-wrapped-ether-stranded-across-20-chains) · [Bloomberg](https://www.bloomberg.com/news/articles/2026-04-19/crypto-hack-worth-290-million-triggers-defi-contagion-shock)

4 月 18-19 日，Kelp DAO 被从 LayerZero 桥接层抽走约 116,500 rsETH（约 $293M），wrapped ether 分布在 20 条链上，部分资产"被悬在半空无法赎回"。这不是一个合约 bug，而是**跨链验证配置的结构性漏洞**——LayerZero 的"DVN（去中心化验证网络）可由应用自选"模式下，Kelp 采用的组合被攻击者反向工程后绕过。

这次事故是 2026 年加密社区最应该警惕的事件。过去一年 restaking、LRT、跨链 DEX 一起把 LayerZero 捧成了事实标准，"模块化安全"成为叙事高地。但模块化的代价就是：每个协议都在**自选一组 DVN 配置**，等于每个协议都成了自己的安全审计方——而 DeFi 协议的 dev team 根本没这个能力。今天是 Kelp，明天完全可能是 Pendle、EtherFi、Renzo 中的任何一家。

更糟的传染效应已经出现：Aave、SparkLend、Fluid、Upshift 紧急冻结接受 rsETH 的借贷市场。整个 LRT → 借贷 → 稳定币循环的尾部风险被放大。叠加 4 月 1 日 Drift $285M（疑 DPRK Lazarus）+ 两周 45 个项目共 $450M 损失，"DeFi is dead"言论再次回潮。2026 Q2 能否阻止资金离场将取决于 LayerZero 团队 + LRT 发行方能否在两周内给出可信的修复 + 赔付方案。

---

### 🔑 2. SEC + CFTC 联合分类框架 — 十年监管模糊期正式结束

[SEC 新闻稿](https://www.sec.gov/newsroom/press-releases/2026-30-sec-clarifies-application-federal-securities-laws-crypto-assets)

SEC 3 月 17 日联合 CFTC 发布的代币分类解释，在本周正式进入具体执法阶段。文件第一次把加密资产清晰划为五类：**数字商品、数字收藏品、数字工具、稳定币、数字证券**，并对 airdrop、PoW 挖矿、PoS 质押、非证券代币的 wrapping 行为给出了明确的证券法适用意见。

从产业角度看，这是 2014 年以来第一次"**美国监管方有能力让大部分 DeFi 行为合规生存**"。过去 Coinbase、Uniswap、Lido 等核心玩家在 Howey 测试下长期游走灰色地带，今年终于获得明确标签——比如 PoS 质押被划为非证券行为，协议挖矿被视作服务费而非投资合同。与此搭配的 SEC 新通用上市标准（crypto ETP 可绕过完整 19b-4 流程）意味着 2026 年可能上 **100+ 只加密 ETF**。

但框架清晰也意味着执法有了抓手。Restaking、LRT、再质押衍生品这类 Kelp 模式的产品此后大概率需要主动向 SEC 提交分析，否则 8 月后的 enforcement 会非常难受。今年 Q2-Q3 会有一大批美国 DeFi 协议**被迫做出合规或离岸二选一**。

---

### 🔑 3. XRP ETF AUM 破 10 亿 + CLARITY 法案 — XRP 派终于守得云开

[The Block](https://www.theblock.co/post/383241/crypto-regulation-2026-sec-ambitious-agenda-empowered-cftc) · [Bitrue 分析](https://www.bitrue.com/blog/xrp-regulatory-status-april-2026-new-update-latest-regulation)

7 只 spot XRP ETF 累计 AUM 突破 $1B，CLARITY 法案即将在 4 月底进入参议院银行委员会 markup——该法案一旦通过将**联邦立法层面永久确认 XRP 的商品属性**，彻底终结 SEC vs. Ripple 十年缠斗。从市场结构看，XRP ETF 的速度比 ETH 还快：上市约四个月即破 10 亿，接下来如果 CLARITY 过参议院，XRP 很可能成为**美国基金行业第三个"机构标配加密资产"**。

背后更深的信号是：现在 Congress 真的在做加密市场结构立法，而不是只盯着稳定币或反洗钱。如果 CLARITY（市场结构）+ GENIUS（稳定币）+ 对应税收条款能在 2026 内全部落地，美国加密的合法性会回到 2014 年前的状态，但这次是**带 ETF、带交易所托管、带主流银行结算**的合法性。

风险点：CLARITY 的 markup 如果 4 月底受阻，或反对派提出 last-minute 修正（例如收紧 "decentralized enough" 标准），XRP 和所有被视为"非完全去中心化"的 L1（Near、Avax、Apt、Sui）估值会承压。

---

### 🔑 4. BTC 在 $75K 争夺 — 宏观地缘 vs. ETF 资金流的角力

[Yahoo Finance](https://finance.yahoo.com/personal-finance/investing/article/bitcoin-and-ethereum-price-today-monday-april-20-2026-prices-rising-this-morning-despite-us-iranian-tensions-115955954.html) · [Fortune](https://fortune.com/article/price-of-bitcoin-04-20-2026/)

美国周末扣押了一艘前往霍尔木兹海峡的伊朗货轮，周一 BTC 以 $73,820 低开（-2.5%），但 7:35 ET 已回升至 $75,242。ETH 同步从 $2,263 爬回 $2,307。过去一周本来靠 4 月 14 日美伊停火预期推升到 $77K+，周末这一事件让行情再度回归"停火是否真能持续"的摇摆。

但 ETF 资金面给出了明确信号：4 月 14 日 BTC spot ETF 单日净流入 $411.4M（IBIT 领涨），ETH spot ETF 4 月累计净流入 $187M（扭转前三周共 $308M 流出）。**机构侧在用地缘恐慌抄底**，这与散户盘情绪形成分化。

技术层面 $73K 是今年多次测试不破的支撑位，$77K 是近期阻力。如果本周美伊紧张进一步加码（伊朗报复 or 美方升级），下破 $72K 进入回调区域的概率会明显上升。反过来，如果地缘回稳叠加 CLARITY/XRP 利好，再冲 $80K 的资金面已经就位。

---

### 🔑 5. Ethereum 活跃度周环比 +41% + Glamsterdam 升级预告

[CoinDesk 报道](https://www.coindesk.com/markets/2026/04/14/ether-outpaces-bitcoin-as-etf-flows-split-and-ethereum-activity-jumps-41-on-week)

ETH/BTC 汇率本周触及 3 个月新高，主因是 Ethereum 链上活跃度周环比 +41%，L2 交易量、DEX 成交、稳定币结算全线回暖。叠加 Ethereum 预告 **Glamsterdam 升级**（目标更低 gas + 更便宜的 data availability），ETH 叙事重新拾起"以太坊是 DeFi 结算层"的身份。

但 Kelp 事故的背景下，L2 + LRT + restaking 的去信任叙事会遭遇短期怀疑。Glamsterdam 升级如能在年中前上线并稳定，对 ETH 估值来说是关键催化剂。反之，如果二次延期，加上 DeFi 事故接连发生，市场可能重回 2024 年的 "Ethereum 生态是不是在原地打转"的悲观评论中。

---

## 市场脉搏

- **BTC**: $75,242（+1.9%）· 支撑 $73K / 阻力 $77K
- **ETH**: $2,307（+1.9%）· ETH/BTC 3 月新高
- **SOL**: ~$86.55（+6.3%）· 周内最强主流币
- **XRP**: 7 只 spot ETF，AUM 累计 $1B+，CLARITY 4 月底 markup
- **ETF 资金面**: BTC 4/14 单日 +$411M / ETH 4 月累计 +$187M
- **链上动态**: Ethereum 活跃度周 +41%，LRT 板块因 Kelp 事件承压
- **黑客损失**: 两周 $450M，Kelp $293M 居首
- **宏观变量**: 美伊周末货轮扣押事件，霍尔木兹海峡风险再起
- **情绪指标**: 恐惧贪婪指数从上周 62（贪婪）回落至中性区间

下一周关键时点：CLARITY 参议院银行委员会 markup、LayerZero/Kelp 事故赔付方案、Glamsterdam 升级进度更新。

Sources:
- [CoinDesk — Kelp DAO $292M 事件](https://www.coindesk.com/tech/2026/04/19/2026-s-biggest-crypto-exploit-kelp-dao-hit-for-usd292-million-with-wrapped-ether-stranded-across-20-chains)
- [Bloomberg — $290M 黑客冲击 DeFi](https://www.bloomberg.com/news/articles/2026-04-19/crypto-hack-worth-290-million-triggers-defi-contagion-shock)
- [SEC 加密分类框架](https://www.sec.gov/newsroom/press-releases/2026-30-sec-clarifies-application-federal-securities-laws-crypto-assets)
- [The Block — 2026 加密监管](https://www.theblock.co/post/383241/crypto-regulation-2026-sec-ambitious-agenda-empowered-cftc)
- [Yahoo Finance — 4/20 行情](https://finance.yahoo.com/personal-finance/investing/article/bitcoin-and-ethereum-price-today-monday-april-20-2026-prices-rising-this-morning-despite-us-iranian-tensions-115955954.html)
- [CoinDesk — ETH 活跃度 +41%](https://www.coindesk.com/markets/2026/04/14/ether-outpaces-bitcoin-as-etf-flows-split-and-ethereum-activity-jumps-41-on-week)
- [TRM Labs — Drift 朝鲜黑客事件](https://www.trmlabs.com/resources/blog/north-korean-hackers-attack-drift-protocol-in-285-million-heist)
- [Bitrue — XRP 监管现状](https://www.bitrue.com/blog/xrp-regulatory-status-april-2026-new-update-latest-regulation)
