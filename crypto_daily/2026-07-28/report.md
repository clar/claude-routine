# 加密日报 · 2026-07-28

## 今日焦点

> **BTC 力守 $65K · ETH 反弹 4% · WEMIX 稳定币再遭 $6.25M 洗劫 · GENIUS Act 逾期未落地 · USDT 被完全逐出欧洲**
>
> - **BTC 稳在 $65,000、ETH 上探 $1,950**：总市值 $2.4T，等待 FOMC 决议与中东局势明朗
> - **WEMIX$ 稳定币被夺权，损失 $6.25M**：攻击者拿到合约管理员权限，链上强制关停
> - **美国 GENIUS Act 逾期未成规则**：六大机构错过 7/18 立法定期，稳定币仍处"空转"状态；SEC "Regulation Crypto" 首份系统性规则本月或落地
> - **USDT 被完全逐出 MiCA 合规交易所**：Coinbase / Kraken / Crypto.com 已完成 EEA 用户下架，$1,860 亿存量分流
> - **ETF 资金 7 日净流入之后单日回撤 $2.25 亿**：年度累计 -$50 亿，7 月改善 +$4.27 亿

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
| 1 | **BTC $65,333 高开、ETH $1,953 涨 4%** | 行情 | 中东停火 + 能源回落带动风险偏好回升 |
| 2 | **WEMIX 稳定币被夺权，$6.25M 蒸发** | 安全 | 攻击者拿到合约 admin，链上被迫暂停 |
| 3 | **美国 GENIUS Act 立法期限逾期** | 监管 | 六机构未在 7/18 前发布最终规则 |
| 4 | **SEC "Regulation Crypto" 首份系统性规则或本月发布** | 监管 | 提供开发者与早期融资临时豁免 |
| 5 | **USDT 完成 EEA 交易所下架** | 监管 | Tether 拒绝 MiCA 授权后被清出欧洲 |
| 6 | **AFX Trade / Verus 跨链桥被攻击，合计 $31.5M** | 安全 | 单周 DeFi 损失突破 $47M |
| 7 | **BTC ETF 昨日净流出约 $2.25 亿，7 日入流终结** | 机构 | 年度累计仍 -$50 亿 |
| 8 | **FOMC 本周议息，市场押注按兵不动** | 行情 | 押注下半年首降息推至 9-11 月 |
| 9 | **Circle 双合规策略见效，USDC 稳步扩张** | 生态 | 法国 e-money + 美国联邦信托并行 |
| 10 | **2026 全年 DeFi 攻击损失突破 $10 亿** | 安全 | 桥/预言机/私钥泄漏三大类 |
| 11 | **BitMart 宣布关停部分服务** | 行业 | 二线交易所继续整合 |
| 12 | **Worldcoin 触底反弹领涨 alt-L1** | 行情 | 亚洲盘热点 |

---

## 重点点评

### 🔑 1. WEMIX 稳定币夺权：链下 admin 密钥就是链上央行 — 中心化风险再破防

**[Crypto Times 报道](https://www.cryptotimes.io/2026/07/27/wemix-hacked-again-6-25m-stablecoin-exploit-forces-network-shutdown/)**

7 月 26 日 09:17 UTC，一名攻击者取得 WEMIX$ 稳定币合约的管理员权限，直接调用 mint / 转移函数抽走约 **$6.25M**。链方紧急暂停节点、启动回滚讨论。这已是 WEMIX 18 个月内第二次事故——2025 年跨链桥被吸走 $6.1M 记忆犹新。

真正让人不安的是模式：**核心权限依然握在链下私钥手里**。号称"稳定币"的资产实质是"admin-mintable 记账凭证"。链侧再多的去中心化叙事，也弥补不了 EOA / 多签管理员这层暴露面。这类事件在 2026 已发生 4 起，直接为 SEC "Regulation Crypto" 拟议的"稳定币储备强制 attestation + 权限白名单"提供了教材。

对市场：短期利空 Play-to-Earn 生态里所有链原生稳定币；长期加速资金向 USDC、USDe 等合规储备型稳定币集中。

**观察：** 若 WEMIX 决定硬分叉回滚，将是 2016 The DAO 事件之后最大一次链原生"逆天改命"，值得关注监管反应。

---

### 🔑 2. GENIUS Act 逾期未落地：美国稳定币"合法但没规则"的空窗期还在延长

**[Crypto Briefing 分析](https://cryptobriefing.com/genius-act-mica-stablecoin-conflict/)** · **[KuCoin 简讯](https://www.kucoin.com/news/flash/genius-act-and-mica-create-stablecoin-compliance-challenges-for-global-firms)**

7 月 18 日是 GENIUS Act 授权六大联邦机构（Fed / OCC / FDIC / SEC / CFTC / Treasury）发布最终执行规则的法定期限。目前所有机构**均未按期落地**，仅完成征求意见环节（截止 6/9）。真正强制执行的窗口后移到 2027 年 1 月，中间 6 个月出现明显的"合规真空"。

这对美国稳定币玩家的现实影响是：**发行方拿不到明确的许可路径、储备结构无法定型、跨州经营继续走 state-by-state 拼图**。相反 MiCA 已经强制执行——Tether 因不申请 MiCA 授权，7 月完成全欧下架，USDT 在 EEA 市场无法交易；Circle 双牌照并行、在 EU 用 EMI、在美国推联邦信托，成为唯一两边都合规的头部发行方。

监管空档最直接的赢家是 **Circle 与合规友好的银行系稳定币候选（PayPal PYUSD、Ripple RLUSD、Sky/Nord 计划）**，输家是 Tether 在欧洲的接入渠道。

**观察：** 若 SEC "Regulation Crypto" 本月落地，可能补齐 GENIUS Act 遗留的 issuer registration 缺口；否则国会民主党可能在 8 月休会前推动追加立法议程。

---

### 🔑 3. ETF 单日流出终结 7 日入流：机构的"回归"是脆弱的

**[Bloomberg 分析](https://www.bloomberg.com/news/articles/2026-07-20/bitcoin-etfs-log-second-week-of-inflows-breaking-two-month-rout)** · **[CoinReporter](https://www.coinreporter.io/2026/07/spot-bitcoin-etfs-see-significant-outflows-after-inflow-streak/)**

美国现货 BTC ETF 在 7/14 - 7/23 连续 7 个交易日净流入，但随后连续两日各净流出 **$225M / $240M**，一举吃掉最近 7 日流入的一大半。年度累计仍是约 **-$50 亿**净流出，仅 7 月单月 +$4.27 亿部分修复。

这数据两个含义：**（1）机构不是"重新加仓"，而是在给对冲基金短线套利提供工具**——ETF 已成为可靠的隔夜可平仓头寸；**（2）真正的 sticky 资金还没回来**，退休金、家族办公室在等 FOMC + 大选后再决定分配。BlackRock IBIT 与 Fidelity FBTC 是流入主力，其他 ETF 只是被动跟随。

对现货：ETF 净流量与 BTC 24 小时价差相关性仍在 0.55 左右，短期定价权仍掌握在 ETF 组合手里；一旦本周 FOMC 释放意外鸽派，可能触发单周超 $10 亿的追补入流。

**观察：** 关注周五 SoSoValue 与 Farside 的净流量数据、以及本周 FOMC 会议记录用词是否出现 "quantitative tightening pace"。

---

### 🔑 4. USDT 全面退出 MiCA 市场：稳定币的"欧洲版图"重画

**[Interexy 深度](https://interexy.com/genius-act-vs-mica-the-2026-stablecoin-compliance-map-a-regulatory-deep-dive)**

7 月 1 日 MiCA 过渡期截止后，Coinbase、Kraken、Crypto.com 已陆续对 EEA 用户下架 USDT。**Tether 拒绝申请 MiCA 授权**，且 CoinGecko 显示 USDT 存量已达约 **$1,860 亿**，其中欧洲交易量份额约 6%，短期意味着 ~$110 亿名义交易量必须迁移到场外或换币。

USDC、EURC 已成为欧洲合规首选，Circle 借此把 EURC 市值继续拉升至阶段新高。二线合规稳定币（如 EURI、Society Générale 的 EURCV）也获得配置空间。对 DEX 生态：Uniswap / Curve 上欧洲用户主导的 USDT 交易对开始向 USDC 迁移，短期造成流动性再平衡摩擦。

**观察：** Tether 是否在 8 月给出"EU 专用稳定币"方案（例如新发一款符合 MiCA 的实体持牌品种），决定其欧洲市场是否彻底放弃。

---

### 🔑 5. 2026 DeFi 全年损失突破 $10 亿：桥、oracle、私钥依然是"三巨头"

**[Nardello & Co 综述](https://nardelloandco.com/passle-insights/102mqdj/290-million-defi-hack-exposes-systemic-security-risks-in-decentralized-finance/)** · **[Altfins 全清单](https://altfins.com/blog/defi-hacks-2026/)**

年内 DeFi 累计损失已破 **$10 亿**，2026 大概率超越 2022 成为史上第二"惨烈年"。仅 7 月 22-23 日 AFX Trade 与 Verus 桥被攻击就损失 $31.5M；WEMIX 事件后单周累计到 $47M。

三大结构性风险持续暴露：**跨链桥的托管/中继密钥**（AFX / Verus / Wormhole 系）、**oracle 与价格喂给的可操纵性**（月内 3 起）、**协议管理员私钥/多签失守**（WEMIX 属此类）。相比合约漏洞，这些"运维层"漏洞更难通过审计消除，且大部分损失最终没能追回。

监管层已经开始跟进：SEC "Regulation Crypto" 拟议要求 DeFi 前端提供者对可控密钥的托管方进行披露；EU DORA 已把重要 DeFi 服务纳入运营韧性监管范围。**保险产品迎来窗口**——Nexus Mutual、InsurAce 承保余额本月环比翻倍。

**观察：** 明日追踪：Verus 是否宣布补偿方案；WEMIX 是否推进硬分叉。

---

### 🔑 6. 中东停火 + FOMC 蓄势：加密与股权同频的两个宏观开关

**[Fortune](https://fortune.com/article/price-of-bitcoin-07-27-2026/)** · **[Motley Fool](https://www.fool.com/coverage/stock-market-today/2026/07/27/crypto-market-today-july-27-bitcoin-steadies-as-ahead-of-fed-meeting/)**

BTC 今早高开 $65,333、ETH 上探 $1,953，与美股共振——直接催化剂是美国宣布**暂停对伊朗军事目标空袭**、能源价格回落。这对通胀路径构成正面。市场共识：FOMC 本周按兵不动概率 92%（CME FedWatch），首次降息推迟到 9-11 月。

crypto 与 macro 的耦合度在 2026 达到近年高点：BTC 与纳指 30 日相关性 0.61、与美元指数 -0.44。这意味着**加密不再有独立行情**，短期方向由：(1) 中东局势演进（若空袭恢复，避险快速回落）；(2) FOMC 决议措辞；(3) 大选民调波动 三个宏观变量决定。

**观察：** 若中东停火巩固、原油向 $70 靠拢，风险资产同频上涨；若 FOMC 措辞偏鹰、点阵图下移程度不及预期，BTC 可能再度回踩 $62K 支撑。

---

## 市场脉搏

**主要资产快照（截至 7-27 收盘）**
- **BTC**：$64,850（+0.3% 24h，-4.1% 30d）
- **ETH**：$1,945（+1.6% 24h，+0.8% 30d）
- **SOL**：$156（+2.1% 24h）
- **总市值**：$2.4T（+1.2% 24h）
- **BTC 主导率**：58.3%
- **恐惧与贪婪指数**：42 (Fear)
- **BTC 永续资金费率**：0.008%（8h）中性
- **ETH ETF 日净流入**：+$32M

**关键点位**
- BTC 支撑 $62,500 / $60,000，阻力 $67,800 / $70,000
- ETH 支撑 $1,850，阻力 $2,050 / $2,200
- SOL 关注 $160 心理关口能否站稳

**明日追踪清单**
- FOMC 决议前置指标（10Y-2Y 息差、DXY 走势）
- WEMIX 硬分叉表决与 GS Caltex 官方声明
- SEC "Regulation Crypto" 草案落地时点
- USDC/USDT 稳定币供应剪刀差是否继续扩大

**资金面判断：** 大方向未变——BTC 在 $60K-$70K 大区间震荡，ETH 距 Pectra 后升级的技术面 catalyst 仍需 6-8 周孵化。近端交易更看宏观驱动、少看币种叙事。
