# Crypto 日报 · 2026-07-30

## 今日焦点

> **BTC 守 6.4 万等 Fed · ETH ETF 单月吸金 93 亿 · SEC Regulation Crypto 7 月落地 · 桥安全再次爆雷 · 阿根廷银行接入 Circle**
>
> - **BTC $63,818，24h +1.04%；ETH $1,912，24h +2.38%** — Fed 议息决议之前市场谨慎回补
> - **7-8 月 ETH ETF 净流入 93 亿美元** — 以太坊现货 ETF 首次跑赢 BTC 品类月度流入
> - **SEC "Regulation Crypto" 三条规则 7 月正式进入 rulemaking 日程** — Atkins 时代第一份加密专项立法
> - **7 月 23 日 "黑客日" 累计损失 $35.55M** — AFX Trade + Verus 桥 + B² Network 同日被攻击
> - **Circle 与阿根廷两家银行集团合作发行比索稳定币** — 拉美美元化政策向"数字美元"扩展

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
| 1 | **BTC 守 $63,818，Fed 决议前市场谨慎** | 行情 | BTC +1.04%，ETH +2.38%，全球加密总市值回升至 $2.28T |
| 2 | **7-8 月 ETH 现货 ETF 净流入 $9.3B** | 机构 | 首次月度超过 BTC ETF 流入，机构轮动信号明确 |
| 3 | **SEC 将 Regulation Crypto 列入 7 月 rulemaking** | 监管 | 早期项目 12 个月内可豁免融资至 $75M；含"证券退出" safe harbor |
| 4 | **AFX Trade 因第三方桥漏洞损失 $24M** | 安全 | Arbitrum 上 5 位桥验证者私钥被盗 |
| 5 | **Verus-Ethereum 桥被攻击损失 $7.54M** | 安全 | 攻击者已转换为 3,916 ETH |
| 6 | **B² Network 同日遭袭** | 安全 | Bitcoin L2 生态首起主要事件 |
| 7 | **Circle × 阿根廷 Grupo BIND / Petersen 发行比索稳定币** | 采用 | 拉美银行集团首次直接接入 Circle 基础设施 |
| 8 | **Circle 在 Solana 增发 $500M USDC** | 生态 | USDC 结算重心继续向 Solana 迁移 |
| 9 | **上半年 USDC 占稳定币真实交易量约 70%** | 生态 | 反超 USDT，机构结算份额确立 |
| 10 | **SEC Release 33-11426：拟建统一 ETF 复杂产品框架** | 监管 | 涵盖预测市场、加密、杠杆、私募 |
| 11 | **恐惧贪婪指数 29，仍处"恐惧"区间** | 情绪 | Fed 决议前风险偏好压制 |
| 12 | **Across Solana 部署遭事件伪造攻击，零损失** | 安全 | 事件系统层缺陷已修复 |

---

## 重点点评

### 🔑 1. BTC 守 $63,818、ETH ETF 反超——机构轮动正在发生

Fed 决议前，加密市场没有出现常见的 pre-FOMC 抛压——BTC 24 小时上涨 1.04% 稳守 6.3-6.4 万区间，ETH 反而以 +2.38% 领跑。真正的信号来自资金面：7-8 月合计 93 亿美元净流入以太坊现货 ETF，这是自品类推出以来首次月度流入超越 BTC ETF。

驱动力有两个：一是 SEC 6 月发布的 Release 33-11426 拟为复杂 ETF 建立统一框架，让 ETH staking ETF 与其它衍生品类审批路径明朗；二是华尔街买方在"BTC 已定价、以 ETH 作为下一轮 alpha 载体"的叙事下开始配置。相较之下 BTC 主导率 56.3% 仍偏高，说明本轮以太坊反弹更多是配置轮动而非山寨行情启动。

**观察点**：如果 Fed 释放偏鸽信号，未来两周 ETH 有可能挑战 $2,050 前高；反之，$1,850 是短期关键支撑。

---

### 🔑 2. SEC "Regulation Crypto" 落地——Atkins 时代真正开始

SEC 把"Regulation Crypto"正式塞进 7 月 rulemaking 议程，这是新任主席 Paul Atkins 上任以来的第一份加密专项立法草案。三条核心内容：早期加密项目可在 12 个月内融资至 7500 万美元并暂时豁免证券注册；建立"证券退出" safe harbor——一旦项目方停止承担 managerial effort，代币可脱离证券状态；同步启动更清晰的做市与经纪商合规通道。

这份规则的关键意义是给"美国境内合规发币"提供第一条明确路径。过去五年美国合规 launch 只能走 Reg D / Reg A+，代币流动性受限；这套新框架让初创团队可以在国内做真正的 token sale，倒逼一部分本已迁出去的团队回流。对交易所是双刃剑——合规发币增加意味着新代币供给上升，短期不利币价，长期则让美国交易所获得更多首发利益。

**观察点**：正式 comment period 通常 60-90 天，最终落地可能要到 2026 Q4；期间 Atkins 会不会再出一份"稳定币利息"配套规则，是 DeFi 的关键变量。

---

### 🔑 3. "黑客日"再度证明桥不是被解决的问题——是结构性问题

7 月 23 日单日损失 3555 万美元，其中最大的一起来自 AFX Trade：攻击者获取了 5 个桥验证者的私钥，一次性提走 2415 万 USDC。同日 Verus-Ethereum 桥损失 754 万，B² Network（Bitcoin L2）也未能幸免。这已经是本年度第 X 次"跨链信息传递层被证明脆弱"的事件。

值得注意的是攻击方式：不是智能合约本身漏洞，而是"验证者签名系统的运营性弱点"（key 管理不当、多签阈值太低、第三方托管服务被劫）。这说明桥的安全瓶颈已经从密码学层转到工程与治理层。行业出路只有两条：要么放弃 lock-and-mint 模型改用 native issuance（如原生 USDC）+ CCTP；要么把桥变成完全无信任的 zk 消息层。前者已在 Circle 与 Chainlink CCIP 上推进，后者仍需 2-3 年。

**观察点**：如果 Q3 内再有一次单笔损失 5000 万美元以上的桥攻击，各主流交易所是否会主动下架仍依赖多签桥的资产？答案将决定 lock-and-mint 桥的死亡时间表。

---

### 🔑 4. Circle 拉美攻略——比索稳定币是"数字美元"的侧翼

7 月 28 日，阿根廷 Grupo BIND 与 Grupo Petersen 两家大型银行集团宣布与 Circle 合作，通过其非银行牌照子公司发行比索锚定的合规稳定币，用于机构支付和财资管理。表面上是"本地货币稳定币"，实质上是 Circle 把它的 USDC 合规基础设施 API 化，允许其它法币在同一底层上发行。这个模式意味着 Circle 正在从"稳定币发行方"转型为"稳定币基础设施平台"。

背后逻辑很清楚：阿根廷通胀、外汇管制让企业对美元有天然需求，但完全美元化受政治阻力大；一条中间路是"合规比索稳定币 + 允许无缝兑换 USDC"。这让 Circle 得以在不与当地央行直接对抗的前提下让 USDC 事实上渗透。这是它相对 Tether 的核心差异化：Tether 依靠灰色地带的流通，Circle 依靠"逐国监管拿牌"。

**观察点**：如果这套 API 化模式成功，未来 12 个月里我们会看到墨西哥比索、巴西雷亚尔、越南盾以类似形式接入 Circle——事实上的"美元互联网"雏形。

---

### 🔑 5. USDC 交易量反超 USDT——但地缘政治可能重置这场比赛

数据显示 2026 上半年 USDC 占稳定币真实（去洗量）交易量约 70%，USDT 只有 25% 左右。这是自 2018 年以来第一次机构结算的天平明确倒向 USDC。同时 Circle 在 Solana 增发 5 亿 USDC，跟以太坊铸造节奏拉开距离——反映高频交易与 memecoin 生态对 Solana 上原生 USDC 的持续需求。

但这场胜利不是终局：Tether 依然在美元以外市场（俄罗斯、东南亚、非洲）拥有绝对份额；FCC 近期对中国硬件的封禁与美国"友岸"金融政策强化，意味着未来 12 个月可能有一场"稳定币阵营化"——USDC 属于西方合规轨道，USDT 属于开放/新兴市场轨道，两者不再是同一竞品而是不同市场的默认选项。

**观察点**：Circle IPO 后估值支撑 = 交易量 × 单笔手续费率；如果 SEC Regulation Crypto 允许稳定币直接付利息，那么 USDC 与货币基金的边界将崩塌，Circle 的商业模型会被迫升级。

---

## 市场脉搏

- **主要资产**：BTC $63,818（+1.04%）| ETH $1,912（+2.38%）| SOL 数据未收录 | 全球加密总市值 $2.28T（+0.9%）
- **BTC 主导率**：56.3%；**ETH 主导率**：10.2%
- **关键技术位**：BTC $65,000（近 5 日阻力）/ $62,500（30 日 EMA 支撑）；ETH $2,050 / $1,850
- **ETF 资金**：7-8 月 ETH 现货 ETF 累计净流入 $9.3B，首次月度超越 BTC ETF
- **情绪**：Fear & Greed Index 29（Fear 区间）；perp funding 中性偏低，无过度多头拥挤
- **宏观**：Fed 7 月利率决议是本周唯一的关键催化——市场隐含降息 25bp 概率约 60%

**一句话总结**：BTC 横盘等 Fed，ETH 有 ETF 承接资金，稳定币赛道向 Circle 倾斜，桥安全仍是行业年度伤口。

---

### Sources

- [Yahoo Finance — BTC/ETH July 29 2026](https://finance.yahoo.com/personal-finance/investing/article/bitcoin-and-ethereum-prices-today-wednesday-july-29-2026-crypto-investors-watching-the-fed-decision-closely-131641825.html)
- [The Block — Crypto ETFs 2026 outlook](https://www.theblock.co/post/383361/crypto-etfs-2026-regulatory-tailwinds-issuers-brace-crowded-year)
- [Coin Reporter — SEC Regulation Crypto](https://www.coinreporter.io/2026/07/sec-prepares-major-crypto-rule-proposals-for-july-signaling-regulatory-clarity/)
- [Crypto Times — Hackers Day AFX & Verus](https://www.cryptotimes.io/2026/07/23/cryptos-hackers-day-afx-trade-hit-for-24m-losses-reach-35-55m/)
- [Crypto Briefing — Circle mints $500M USDC on Solana](https://cryptobriefing.com/circle-mints-500m-usdc-solana-liquidity/)
- [Yahoo Finance — USDC pulls ahead of Tether](https://finance.yahoo.com/markets/crypto/articles/circle-usdc-pulls-ahead-tether-192600167.html)
