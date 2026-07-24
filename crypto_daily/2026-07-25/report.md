# 加密日报 · 2026-07-25

## 今日焦点

> **BTC ETF 7 日连续流入终结 · Uniswap v4 首次合规化 · BitMEX 谢幕 · 韩国持牌收编 · Bridge 又双叒被打**
>
> - **BTC 跌破 $65,000**：现货 ETF 单日净流出 **$225M**，7 日 $999M 流入链条终结；ETH ETF 反向流入 **$26M**
> - **Uniswap v4 上线 Permissioned Pools**：与 Superstate、Securitize、Dowgo 合作，DEX 首次内嵌白名单资产合规钩子
> - **BitMEX 宣布 9 月 23 日关停**：曾经的合约巨鲸退出历史舞台，行业进入"完全合规化"新阶段
> - **韩国 Mirae Asset 收购 Korbit 97% 股权**：$1T 传统资管首次直接控股本地交易所
> - **Bitcoin Security Consortium 成立**：BlackRock、Coinbase、Galaxy、Anchorage 联手投 **$15M** 抵御量子威胁

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
| 1 | **BTC 现货 ETF 单日净流出 $225M，终结 7 日 $999M 流入** | 机构 | IBIT 主导流出，BTC 跌破 $65K |
| 2 | **Uniswap v4 上线 Permissioned Pools** | 技术 | 与 Superstate、Securitize、Dowgo 合作合规钩子 |
| 3 | **BitMEX 宣布 9 月 23 日全面停运** | 行业 | 老牌合约交易所退场 |
| 4 | **Mirae Asset 收购 Korbit 97% 股权** | 机构 | 韩国 $1T 资管首次控股交易所 |
| 5 | **Bitcoin Security Consortium 成立** | 技术 | BlackRock 等联手 $15M 抗量子 |
| 6 | **Lien Finance 被利用漏洞窃取 $542K USDC** | 安全 | 债券定价函数逻辑缺陷 |
| 7 | **Verus Bridge 二度被打，$7.54M 被盗** | 安全 | 与 5 月 $11.5M 攻击同一漏洞 |
| 8 | **AFX Trade Arbitrum 桥被盗 $24.15M** | 安全 | 官方向攻击者提出 30% 白帽赏金 |
| 9 | **Circle 与 Kakao、Toss Bank 达成合作** | 采用 | USDC 进入韩国支付轨道 |
| 10 | **Robinhood CEO Vlad Tenev 的 X 账号被黑** | 安全 | 发布 meme 币诈骗内容 |
| 11 | **Zama Confidential RFQ 上线以太坊主网** | 技术 | 全链上机密撮合，反 MEV |
| 12 | **日本 FSA 拟 2028 年前推出首只 BTC 现货 ETF** | 监管 | 亚洲 ETF 时间表逐步清晰 |

---

## 重点点评

### 🔑 1. BTC ETF 流入链条断裂 — 宏观逆风 vs 结构性买盘的第一次拉扯

**[Bitcoin ETFs Shed $225M – Crypto Times](https://www.cryptotimes.io/2026/07/24/bitcoin-etfs-shed-225m-to-snap-7-day-winning-streak-eth-etfs-gain-26m/)**

7 月 24 日现货 BTC ETF **单日净流出 $225.18M**（其中 BlackRock IBIT 独占绝大部分），是自 7 月 13 日以来首次单日净流出，也终结了此前 7 个交易日累计 $999M 的连续流入。同一天 BTC 一度跌破 $65,000、ETH 跌破 $1,860；表面上是"油价 + 关税→通胀预期→美债收益率上行→风险资产回撤"的教科书链条，但真正的信号是**BlackRock 首次表现出短线择时**——过去两年 IBIT 是"只买不卖"的锚定式资金，一旦这个假设动摇，市场对 ETF 结构性买盘的估值就得重新算。

对照面是 **ETH ETF 逆势流入 $26M**，且是连续 5 日净流入、无任何一只基金净流出。这几乎是 ETH ETF 上市两周年的一次"沉默胜利"：BTC-ETH 资金流第一次出现明显反向。放在 ETH/BTC 汇率处于周期低点（近日 [Bitcoin Foundation 数据](https://bitcoinfoundation.org/news/ethereum/ethereum-surpaces-bitcoin/)显示 ETH 兑 BTC 已接近 0.029）的背景下，机构开始"低吸 ETH、止盈 BTC"的板块轮动痕迹明显。

**观察点：（1）7/25 亚洲盘能否守 $64K 关键支撑；（2）IBIT 是否连续两日流出；（3）ETH ETF 若能延伸到 7 日连续流入，市场对"ETH beta 反弹"叙事的定价将快速上修。**

---

### 🔑 2. Uniswap v4 Permissioned Pools — DeFi 与合规资产的第一次官方握手

**[Uniswap v4 白名单钩子发布](https://www.cryptointegrat.com/p/crypto-news-july-24-2026)**

Uniswap Labs 宣布 v4 全面支持 **Permissioned Pools**：通过 Hook 标准，池创建者可以强制要求所有 taker 通过 Superstate / Securitize / Dowgo 等合规服务商完成 KYC 验证，才能进入池内交易。这意味着 **RWA、代币化国债、私募证券可以直接在 Uniswap 上流转**，不再需要独立部署合规 DEX（如 Ondo Sandclock、Backed）。

三重信号：**（1）Uniswap 从"抗监管象征"转向"合规运营层"**，与 v4 hooks 架构的设计初衷完全一致——协议层保留中性，合规逻辑外挂到 hook。**（2）Securitize / Superstate 成为 DeFi 的 KYC 网关**，一旦流量集中，会成为下一代"链上合规寡头"。**（3）传统资管的资金**——BlackRock BUIDL、Franklin BENJI、WisdomTree WTGXX——**理论上可以直接在 Uniswap 内部撮合**，DEX 与 TradFi 的边界第一次真正模糊。

**观察点：（1）v4 上线首月 Permissioned Pool 的 TVL；（2）BlackRock BUIDL 是否会主动接入；（3）美国 SEC 对"KYC-gated DEX"的执法姿态——若默许，将改写 DeFi 十年叙事。**

---

### 🔑 3. BitMEX 谢幕 — 合约时代的"CEX 三巨头"仅剩其一

**[BitMEX Shutdown – Cryptointegrat](https://www.cryptointegrat.com/p/crypto-news-july-24-2026)**

BitMEX 母公司 HDR Global Trading Limited 宣布：**9 月 23 日起全面停止运营**，为其 11 年历史画上句号。BitMEX 曾是加密永续合约的发明者、最大交易场所，其 XBT/USD 合约在 2020-2022 年一度占据全球衍生品交易量的 40% 以上。终结原因包括：Arthur Hayes 时代的美国司法部认罪协议后续影响、Binance / Bybit / OKX 的市场瓜分、以及缺少现货 + ETF 通道导致的机构失联。

真正意义在于：**BitMEX 的关停 + Binance 香港/欧盟持牌整改 + OKX 迪拜化 + Bybit 荷兰申请 MiCA**，构成 2026 年下半年 CEX 版图的正式重构——**"极客交易所"时代彻底结束，此后交易所的核心能力是牌照 + 银行接口 + ETF 通道**，而不再是极端杠杆和创新产品。

**观察点：（1）BitMEX 客户与 OI 会流向哪家，将极大改变永续合约资金费率分布；（2）"合规化"进一步压缩 CEX 的产品创新空间，DEX 与 RWA 平台可能吃下这块红利。**

---

### 🔑 4. 桥梁攻击三连击 — Cross-chain 安全模型仍未解决

**[AMBCrypto: Hackers' Day $35M+ Losses](https://ambcrypto.com/crypto-hacks-return-is-35m-in-exploits-the-start-of-another-defi-fud-cycle/) · [Coinpedia: Three Bridge Hacks](https://coinpedia.org/news/three-crypto-bridge-hacks-in-defi-vanish-35-6m-in-one-day/)**

24 小时内三起 Bridge 类攻击共计 **$35.5M+ 损失**：AFX Trade Arbitrum 桥 $24.15M、Verus Bridge $7.54M（与 5 月 $11.5M 攻击同一漏洞、二度失守）、B² Network $3.86M。加上今天 Lien Finance 的 $542K USDC 定价函数漏洞，本周 DeFi 已经跨过 $40M 单周损失。

这轮攻击最令人担心的是 **Verus 二次被攻击**——协议在 5 月已经知道漏洞，两个月未彻底修复即导致复发；反映出 DeFi 项目在人手 / 资金压力下**"临时补丁 vs 根本重构"的两难**。同时 AFX 首次采用 **"30% 白帽赏金 + 追责豁免"**协商策略，试图追回 70% 资金——这是过去半年 DeFi 攻击处置的标准化路径（类似 Nomad、Munchables 案例），但也让攻击者形成路径依赖：**攻击 → 谈赏金 → 无监管介入**。

**观察点：（1）AFX 谈判结果与后续保险赔付；（2）以太坊 L2 桥梁架构是否会集中回归 canonical bridge；（3）新一轮 DeFi FUD 是否影响 TVL 与 ETH gas fee，Q3 是否重演 2022 年 Nomad / Wormhole 后的持续下杀。**

---

### 🔑 5. Bitcoin Security Consortium 成立 — 机构第一次"内生"投入协议级安全

**[Cryptointegrat 综述](https://www.cryptointegrat.com/p/crypto-news-july-24-2026)**

BlackRock、Coinbase、Galaxy Digital、Anchorage 等联合发起 **Bitcoin Security Consortium**，承诺三年内投入 **$15M**，首要目标是**量子计算威胁下的 Bitcoin 迁移路径**（BIP-360 / BIP-361 / P2QRH 相关工作）。资金将用于资助 core dev、审计、量子抗性签名 (Falcon / Sphincs+ / Kyber) 的性能测试与部署工具。

这是历史性的一步——**过去 Bitcoin 协议演进由 Core 维护者、极客社区、少数矿池主导；机构从未参与协议级投入**。理由很简单：ETF 与企业 treasury（MicroStrategy、Metaplanet、Bhutan 政府）持有超 $200B 名义 BTC，如果 2030 年代量子算力真正到来，任何被动等待都是股东责任问题。$15M 相对 ETF AUM 是小数字，但**"机构开始 fund Bitcoin"** 这件事本身是范式转变。

**观察点：（1）Core dev 社区如何接受"机构资金 + 优先事项"；（2）第一个 P2QRH 迁移测试网时间表；（3）ETF 发行方是否会跟进撰写"量子抗性投资风险"新披露章节。**

---

### 🔑 6. Circle × Kakao/Toss + Mirae × Korbit — 韩国成为 2026 下半年最激烈的加密战场

**[Cryptointegrat: Circle Korea](https://www.cryptointegrat.com/p/crypto-news-july-24-2026)**

Circle 同日官宣与 **Kakao Group（韩国最大互联网平台）+ Toss Bank（新兴银行龙头）** 合作，共同探索 USDC 在韩国的支付轨道。仅数小时后传出 **Mirae Asset（韩国 $1T 传统资管）以 97% 股权收购 Korbit** ——这是**韩国传统金融巨头第一次直接控股本地加密交易所**。

背景是韩国 **VASP 2.0 法案**将于 8 月落地，允许"合格金融机构"运营加密业务、发行 KRW 稳定币；这直接吸引国际选手（Circle、Ripple、Coinbase）与本土 chaebol 财团（Mirae、Samsung Securities、KB 金融）同时行动。**韩国正在成为 2026 下半年除美国之外最重要的稳定币 + 现货交易战场**，主要因为它同时具备：高零售用户密度（人口 5000 万但持币率超 30%）+ 强牌照制度 + 财团深度参与。

**观察点：（1）Circle-Kakao 试点是否会推出 KRW-pegged USDC 变体；（2）Mirae 收购 Korbit 后，是否会推出面向个人投资者的 KRW-pegged 收益型稳定币；（3）韩国是否会成为 2027 年首个"稳定币主导零售支付"的先行案例。**

---

## 市场脉搏

| 资产 | 价格 (24 日收) | 24h 变化 | 备注 |
|------|---------------|---------|------|
| BTC | ~$64,300 | ▼ 1.6% | 现货 ETF 净流出 $225M |
| ETH | ~$1,860 | ▼ 2.9% | ETH ETF 反向净流入 $26M |
| ETH/BTC | ~0.0289 | 微跌 | 接近周期底部 |
| SOL | ~$135 | ▼ 3.1% | Meme 币交易量继续降温 |
| Global Mkt Cap | ~$2.3T | ▼ 2.2% | 稳定币供应量继续微增 |

- **关键支撑**：BTC $62,000 / $58,000（周线趋势线）；ETH $1,830 / $1,760
- **关键阻力**：BTC $66,000 / $68,500；ETH $1,935 / $2,000
- **衍生品**：BTC 永续资金费率短线转中性偏空 (~0.005%)；期权 25d put-call skew 略走阔，隐含波动率上行
- **宏观风险**：美债 10Y 收益率 4.55%（+7bp）、油价 WTI 反弹至 $87、伊朗-以色列局势升温 —— 三重因素同时压制风险资产
- **情绪指数**：Fear & Greed Index 报 **48（中性偏恐惧）**，从上周 58 明显回落

**一句话总结**：短线宏观利空对齐（yield 上行 + 地缘紧张 + BTC ETF 首次流出），但结构性利好持续兑现（Uniswap 合规、韩国机构入场、Bitcoin 抗量子基金）——**加密行业已从"周期驱动"进入"合规基建驱动"，短线波动无碍长线结构**。
