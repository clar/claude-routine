# 加密行业每日资讯 · 2026-08-06

## 今日焦点

> **BTC/ETH ETF 分化 · Glamsterdam 硬分叉倒计时 · Base 反超 Solana 机构资金 · MiCA 淘汰 USDT · DeFi 桥事件全年破 8.4 亿**
>
> - **BTC 徘徊 $64,137，ETH $1,880**，两条 ETF 曲线走出分歧：BTC 现货 ETF 净流入 $170M，ETH 现货 ETF 反而净流出 $11.4M。
> - **Ethereum Glamsterdam 硬分叉锁定 8 月底激活窗口**，执行效率 + PBS 协议层化两条主线上桌。
> - **Base 在托管 DeFi 资产上以 $1.6B 反超 Solana**，Coinbase 系 L2 成为机构资本首选层。
> - **MiCA 下架 USDT，Circle 抢下欧盟牌照**，稳定币格局进入"美系吃欧系市场"阶段。
> - **2026 年 DeFi 累计被盗 $840M**（同比 +70%），跨链桥 + 社工攻击是全年主线。

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
| 1 | **BTC 现货 ETF 单日净流入 $170M，BlackRock IBIT 独占 $111M** | 机构 | 8/4 反弹后连续两日净流入 |
| 2 | **ETH 现货 ETF 单日净流出 $11.4M，BTC/ETH ETF 走势分化** | 机构 | 7-8 月 ETH ETF 反超 BTC 净流入 |
| 3 | **Ethereum Glamsterdam 硬分叉锁定 8 月末激活窗口** | 技术 | PBS 协议层化 + 执行效率 |
| 4 | **Base 在托管 DeFi 资产 $1.6B 上反超 Solana** | 生态 | 机构资本流向 Coinbase 系 L2 |
| 5 | **BTC 报价 $64,137、ETH $1,880，全市场市值 $2.27T** | 行情 | 24h +0.7%，成交 $522 亿 |
| 6 | **Cysic 单日 +93% 领涨山寨** | 行情 | ZK-alt 情绪回暖 |
| 7 | **MiCA 下架 USDT，Circle 拿下欧元法国 EMI 牌照** | 监管 | 稳定币欧美分野正式成型 |
| 8 | **稳定币日交易额从 $1T → $4T（GENIUS 通过后）** | 生态 | 单月市值 $322.6B |
| 9 | **Solana 治理提案 SIMD-0550 首轮通过（通胀衰减翻倍）** | 生态 | 65.16M SOL 支持 |
| 10 | **2026 年 DeFi 累计损失 $840M，KelpDAO 桥事件 $292M 居首** | 安全 | 76% 被 Chainalysis 归因 Lazarus |
| 11 | **Trump "重开霍尔木兹" 表态推升风险资产** | 行情 | 加密圈作为风险偏好晴雨表 |
| 12 | **SEC 通用上市标准落地，Solana staking ETF 首月 AUM $1B** | 监管 | ETF 品类从 BTC/ETH 扩展 |

---

## 重点点评

### 🔑 1. BTC / ETH ETF 走势分化 —— 从"齐涨"到"选边"

BTC 现货 ETF 在 8 月 4 日单日净流入 $170.1M，BlackRock IBIT 独吃 $111.4M、Fidelity FBTC $33.4M，前一日 -$265.4M 的失血被一举补回；同一天 ETH 现货 ETF 却净流出 $11.4M（约 5,805 ETH）。数字虽小，方向变化才是关键：过去 4 周 ETH 现货 ETF 曾创下月度 $3.87B 的净流入、首次反超 BTC，如今出现流出说明轮动结束、机构资金重新分档配置。

背后是两条不同叙事：BTC 依旧被摩根、贝莱德按 "货币-非主权储备" 的框架配置，季调节奏；ETH 则被视为 " staking + 稳定币结算轨" 的 real-yield 资产，情绪跟着 Glamsterdam 硬分叉、L2 采用度、稳定币立法节奏波动。8 月 4 日的分化更像是把两个类别彻底切开——投资人不再买 "crypto ETF 一篮子"，而是选边。

值得留意的是，BTC ETF 全年最小月度净流入的观察在 7 月 30 日就已出现，说明"BTC ETF 单向流入"这一惯性今年不再稳定；下一步观察点是 8 月 15 日前后的美元流动性/CPI 数据窗口。

---

### 🔑 2. Ethereum Glamsterdam 硬分叉 —— PBS 首次进入协议层

Ethereum 核心开发者已将 Glamsterdam 主网激活的内部目标锁定在 8 月末（Slot 时间窗口 8/25–8/31 之间），最大变化有两点：一是 Proposer-Builder Separation (PBS) 首次从 MEV-Boost 的"共识外中继"移入协议层，成为 in-protocol PBS；二是 EIP 组合针对执行层做批量优化，预计 EL 性能提升 12–18%。

对 L2 生态、MEV 供应商、staking 服务的影响都是结构性的：Flashbots 等 relay 商角色将被重新划分，Titan、bloXroute 需要重构商业模式；staking pool 的收益构成里 MEV 部分变得更透明可分配。这也是 EF 治理层准备了 18 个月的"清理 MEV 卫生"关键动作。

风险点是 Glamsterdam 涵盖的 EIP 数量多、审计与客户端多样性有限（Prysm/Lighthouse/Teku/Nimbus 是否同步跟上）——一旦部分客户端出现 fork，短期市场会大幅波动。9 月 Devcon 之前是敏感期。

---

### 🔑 3. Base 反超 Solana 机构资金 —— Coinbase 系 L2 的合规溢价

8 月 4 日的一份数据显示，Base 在 "受托管的 DeFi 资产（curated capital）" 规模上达到 $1.6B，正式反超 Solana，成为最大的机构 L2。这一维度比 TVL 更贴近资金结构：curated capital 特指经过 Anchorage / BitGo / Coinbase Custody 等托管方允许的 DeFi 头寸，主要来自 RIA、家办、部分对冲基金。

Base 反超的直接原因是 Coinbase 的多产品协同：cbBTC、cbETH、USDC 在 Base 上零 fee 跨转、Coinbase 主账户与 Base 钱包一键出入金、机构 API 支持链上 Prime Brokerage。合规 DeFi 的用户体验被压缩到与 CEX 相仿，这才让 curated capital 从 Solana / Arbitrum 迁出。

对 Solana 来说这不是坏消息：Alpenglow 上线在望、Solana staking ETF 首月 AUM 破 $1B，"高性能公链 + 消费应用"的另一条路径依然强劲。但这份数据揭示了：机构资金和用户流量是两个独立市场，2026 下半年 Base 与 Solana 将各自吃掉一半。

---

### 🔑 4. MiCA 淘汰 USDT，Circle 抢下欧洲入场券 —— 稳定币进入"合规溢价"阶段

Tether 至今未获 MiCA 授权，欧盟主流交易所（Coinbase、Binance、Kraken、Crypto.com）已在 2024 年底 – 2025 年 3 月完成 USDT 下架；Circle 通过法国 EMI 牌照获得 USDC 与 EURC 的欧盟通行证。美国侧，GENIUS 法案 2025 年 7 月落地，2026 上半年 OCC 已给 Circle、Paxos 等发出附条件 National Trust Bank 牌照；Tether 作为境外发行方仍在等待财政部对等性认定，5 月前未获批。

结果就是——2026 下半年的稳定币格局已不再是 "USDT 占市场 65%" 的老图：GENIUS 后的 30 天，稳定币日交易量从 $1T 冲上 $4T，市场规模 $322.6B，Circle 在合规市场吃下最大溢价，Ethena / PayPal USD / First Digital USD 拿下细分场景，USDT 逐步退回新兴市场与场外结算。

对国内从业者的启示：稳定币的下一阶段是 "合规发行 + 银行清算 + 链上分发" 的三层结构。谁能拿到国家级牌照 + 全球银行 API + 主流公链默认支持，谁就是下一个 Visa。

---

### 🔑 5. DeFi 全年被盗 $840M —— 桥 + 社工，攻击面已重构

CCN、altfins 汇总的数据显示，2026 年 5 个月内 DeFi 累计损失 $840M（+70% YoY）；两个最大案例是 4 月 1 日 Drift Protocol 的 $285M（六个月的社工获取 admin key）和 4 月 19 日 KelpDAO 的 $292M（跨链桥 verification 层漏洞被伪造签名）。Chainalysis 把 76% 的被盗量归因 Lazarus Group。

攻击面已经从"合约漏洞"扩到"运维体系 + 治理体系"：现在的头部案例不是 flash loan 或重入，而是 "attacker 花半年时间接近多签成员 / 妥协 RPC 节点 / 伪造治理提案"。这类攻击几乎无法用 audit 防住，需要企业级安全流程（HSM、operational segregation、on-chain anomaly detection）。

对协议方与 LP 的实际含义：桥依然是最脆弱的一环，2026 Q3–Q4 建议把跨链头寸控制在总仓位 15% 以内；治理型 token holder 需要意识到 "有权限的人" 在 2026 已经是首要目标。

---

## 市场脉搏

- **主要资产** — BTC $64,137（+0.98%）；ETH $1,880（+0.66%）；SOL 触及 $148 中枢；总市值 $2.27T（+0.7%）。
- **技术位** — BTC 短线关注 $63.5K 支撑与 $66K 阻力，破位方向决定 8 月上半月节奏；ETH 关键位在 $1,845 / $1,910。
- **衍生品** — BTC 永续 funding 维持在 0.008% / 8h（中性略偏多），CME 未平仓合约微升；ETH 永续 funding 转正，8/4 后连续两日多头付费。
- **情绪** — Fear & Greed Index 27，位于"极度恐惧"区间，与价格企稳并存，通常提示"底部区域拉锯"。
- **待观察** — 8/8 美国 7 月非农 & 失业率；8/15 CPI；月末 Glamsterdam 激活窗口；9 月 SEC 关于 Solana / XRP / ETH 期权 ETF 的一揽子决议。
