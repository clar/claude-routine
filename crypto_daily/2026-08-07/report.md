# 加密日报 · 2026-08-07

## 今日焦点

> **Circle Arc 主网 9/16 上线携大型金融机构入场 · Solana 慢速时代结束 · BTC ETF 三日 $626M 净流入 · Chainlink 香港代币化证券落地 · Hashdex 成首个关停的现货 BTC ETF**
>
> - **Circle 官宣 Arc 主网 9 月 16 日启动**，12 家创始验证节点包含 BlackRock / DTCC / Visa / Mastercard / Galaxy / ICE / Standard Chartered，USDC 作为原生 gas。
> - **Solana 测试网首次缩短出块时间**：400ms → 350ms，四步路径最终目标 200ms。
> - **BTC 现货 ETF 8 月连续三日净流入 $626M**，IBIT 单日吸金 $254.5M；ETH ETF 回归 +$60.86M。
> - **Chainlink 在港推出代币化证券框架**：CCIP + ACE 打通发行、结算、合规全栈。
> - **Hashdex 关闭旗下现货 BTC ETF**，AUM 仅 $14.7M——现货 BTC ETF 时代首个正式出清案例。

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
| 1 | **Circle 宣布 Arc 主网 9/16 上线，12 家金融巨头验证** | 生态 | USDC 作为原生 gas，BlackRock/DTCC/Visa/Mastercard 全在列 |
| 2 | **BTC ETF 8/5 净流入 $244M，三日累计 $626M** | 机构 | IBIT +$254.5M，8 月无 BTC ETF 卖出 |
| 3 | **Solana 测试网首次缩短 slot 时间 400→350ms** | 技术 | 四步路径最终目标 200ms |
| 4 | **Circle Q2 营收 $701M，USDC 流通量 $73.3B (+19%)** | 生态 | 链上交易量同比 +151% 至 $14.8T |
| 5 | **Mastercard 与 Borderless 启动稳定币支付试点** | 采用 | 覆盖 100+ 国家的跨境支付 |
| 6 | **ETH ETF 回归净流入 $60.86M，ETH/BTC 突破 9 年阻力** | 行情 | 分析师关注 $2,300 与 $3,000 关键位 |
| 7 | **Chainlink 香港推出代币化证券平台** | 采用 | CCIP + ACE 覆盖发行、结算、合规 |
| 8 | **Binance 起诉 RedotPay 创始人，索赔 $472.8M** | 行业 | 指控违约转移 47 万用户 |
| 9 | **Hashdex 关闭现货 BTC ETF (AUM $14.7M)** | 机构 | 首个正式出清的现货 BTC ETF |
| 10 | **Solana 生态：Hyperliquid 允许 HIP-3 部署者自定义费率** | 技术 | 90% 折扣至标准 3 倍范围可调 |
| 11 | **Strategy 关联钱包转出 1,030 BTC (~$66M)** | 行情 | 总持仓 842,138 BTC 仍在 $52.65B |
| 12 | **Yellow Card 完成 $40M 战略融资**（Sony/Polychain 领投） | 机构 | 累计融资超 $120M，专攻新兴市场稳定币 |
| 13 | **普京签署俄罗斯加密监管法** | 监管 | 首个正式的数字资产法律框架 |
| 14 | **Kraken xStocks 代币化股票获得代理投票权** | 采用 | Broadridge 打通治理参与链条 |
| 15 | **DefiLlama 上线 40+ 做市商性能排行榜** | 生态 | 与 Forgd 合作，首次机构级 LP 透明度 |

---

## 重点点评

### 🔑 1. Circle Arc 主网确认 9/16 上线，机构验证节点阵容前所未有 — **稳定币公链化的临界一击**

Circle 官宣 Arc 主网将于 9 月 16 日启动，创始验证节点名单：**BlackRock、DTCC、Visa、Mastercard、Galaxy、Global Payments、ICE、MoneyGram、SBI Group、Standard Chartered、Sumitomo Corporation** —— 12 家清一色顶级金融机构。USDC 是原生 gas token，这是稳定币首次成为一条主流公链的燃料，也是 Circle 从"稳定币发行方"跃升为"金融基础设施平台"的关键一步。

这条新闻的信号密度极高。第一，验证节点阵容本身就是**监管合规的天然背书**——纽交所母公司 ICE、DTCC（美国证券结算中心）出场意味着 Arc 从第一天起就是"美国监管友好"公链；BlackRock 兼容 IBIT / BUIDL / Arc 的战略越来越清晰。第二，USDC 作 gas token 是对 ETH-as-gas 模型的**结构性挑战**——机构用户不需要买 ETH 就能用链，这一步会显著降低传统金融进入门槛。第三，这背后是 GENIUS Act（2025 年 7 月通过的美国稳定币法案）+ SEC 主席 Paul Atkins 规则化监管的组合红利，Circle 抓住了政策窗口。

**接下来关注：**Arc 的 TPS 与终局性表现（能否比 Base 更接近传统清算体验）、以太坊/L2 生态的应对（尤其是 Base、Optimism 会不会推出 USDC gas 选项）、Tether 的反制动作。

---

### 🔑 2. Solana 测试网首次将 slot 时间缩短到 350ms — **公链性能竞争进入毫秒战**

Solana 在测试网正式启动了 slot 时间缩短，从 400ms 降到 350ms，官方公布**四步路径最终目标 200ms**。这是 Solana 主网自 2020 年上线以来第一次调整核心区块间隔，工程意义重大——slot 时间直接决定用户体验层面的"确认速度"，也决定了链上高频应用（DEX、支付、游戏）的可行边界。

放到今年公链竞争的大背景里看，这是 Solana 应对 Arc / Base / Berachain 竞争的**主动防守**：Arc 主网即将上线且验证节点全是机构，天然具备"合规优势"；Solana 的差异化只能建立在"性能到消费级 web2 体验"这一条上。200ms slot（对应实测确认约 400-600ms）已经能媲美 Visa 的授权响应时间，这才是 Solana 想去的位置。

风险点：缩短 slot 会显著抬升验证节点硬件要求（CPU、SSD IOPS、带宽），Solana 的"节点集中度"批评会加剧。四步路径实际能推到哪一步，最终看 Firedancer / Agave 客户端能否在 200ms 场景下保持 99% 网络参与率。

**接下来关注：**350ms 主网上线时点（预计 Q4）、Firedancer v1.0 稳定性数据、Sui 与 Aptos 的性能反击。

---

### 🔑 3. BTC ETF 三日累计净流入 $626M，ETH/BTC 突破 9 年阻力 — **机构资金结构性转向 ETH**

现货 BTC ETF 8 月 5 日净流入 $244.4M，为月内单日最高，三日累计 $626M；8 月至今**无 BTC ETF 出现净卖出**。IBIT 单日 +$254.5M 占绝对主导。同一天 ETH ETF 从前一日净流出反弹到 +$60.86M。更值得关注的是 ETH/BTC 汇率**测试了长达 9 年的历史阻力位**并出现向上突破迹象，分析师锁定 $2,300 与 $3,000 两个关键位。

三条数据串起来看，机构资金正在经历一次结构性再平衡：BTC 端保持稳态吸金（更多是被动配置需求），ETH 端资金显著加速——这与 Ethereum ETF 后 18 个月里几家发行方陆续获批 staking 收益、DeFi 敞口整合有关。BlackRock 在 Arc 主网创始验证节点中的位置，加上其 ETH ETF 与 BUIDL 的战略捆绑，正在形成一个"ETH-Arc-USDC-BUIDL"的机构闭环。

**接下来关注：**8 月剩余交易日的 ETF 流入是否延续、ETH/BTC 若突破 0.06 后的位置目标（技术派看 0.08）、CME 期货持仓变化。

---

### 🔑 4. Chainlink 香港落地代币化证券平台 — **RWA 的合规基础设施接入亚洲**

Chainlink 官宣在香港推出代币化证券框架，用 CCIP（跨链互操作协议）+ ACE（Automated Compliance Engine）为数字证券的发行、跨链清结算与合规控制提供全栈支持。香港作为亚洲 RWA 试验田近两年动作密集（HKMA 数字港元、代币化绿债），Chainlink 这次入场意味着**合规中间件层在亚洲市场找到了官方级切入点**。

结合 Circle Arc 主网的机构阵容、Kraken xStocks 获得代理投票权、Plume 用 $178M TVL 承接 195K 项 RWA 上链——RWA 赛道正在从"叙事阶段"进入"基础设施阶段"。三层清晰化：底层公链（Arc/Solana/以太坊 L2）、中间件（Chainlink CCIP/ACE、Kraken/Broadridge 投票接管）、应用（Plume、tokenized T-Bills）。Chainlink 用 CCIP 卡位了跨链发行这个最关键的中间层。

**接下来关注：**HKMA 是否给出正式监管沙盒授权、其他主流 RWA 平台（Ondo、Superstate）在港动作、Chainlink CCIP 与 Circle CCTP 的竞争演化。

---

### 🔑 5. Hashdex 关闭现货 BTC ETF — **一年半窗口期结束，出清潮开始**

Hashdex DEFI 现货 BTC ETF 因 AUM 仅 $14.7M 正式关闭，这是自 2024 年 1 月批复以来**第一个正式清盘的现货 BTC ETF**。放在同一天 IBIT 单日吸金 $254M 的对比里，行业分化的残酷面貌完全显现——2024 年批复的十几家 ETF 里，IBIT 一家独占了近 60% 的资产，第二梯队（FBTC、ARKB）也基本稳住了几十亿，第三梯队则完全打不进渠道。

Hashdex 的问题是典型的**"迟到 + 独特性不足"**：入场晚了几个月、费率不占优、缺乏机构渠道分销能力。这暴露了 ETF 时代的一条铁律——**发行方之间的竞争最终是分销力的竞争**，产品同质化环境下渠道决定一切。往下 6 个月，预计还会有 2-3 家小 BTC ETF 关停，尤其是 ETH ETF 中 AUM 长期低于 $50M 的几家。

**接下来关注：**下一个可能清盘的现货 BTC/ETH ETF 名单、SEC 是否会有 XRP/SOL/DOGE ETF 批复（这批更晚入场者的宿命）、AUM 前三与末三家的费率差扩大速度。

---

### 🔑 6. Circle $701M Q2 营收 + Mastercard 稳定币试点 — **稳定币基础设施进入日常化**

Circle Q2 财报：营收 $701M，USDC 流通量升至 $73.3B（+19%），**链上交易量同比 +151% 至 $14.8T**——年化 $59T 的规模已经追近 Visa 全球全年 $15.7T 交易额。同一天 Mastercard 与 Borderless 启动稳定币跨境支付试点，覆盖 100+ 国家。

这两条合起来给出稳定币赛道进入"日常化阶段"的最清晰佐证：**发行侧（Circle 增长率）+ 网络侧（Arc 机构验证）+ 前端侧（Mastercard/Visa 直接吸收）+ 监管侧（GENIUS Act）** 四个环节全部就位。稳定币不再是"加密内部工具"，正在成为传统金融的支付底座。

风险维度：Circle 营收几乎完全来自 USDC 储备收益（短期美债利差），一旦美联储进入降息周期，Circle 收入端将承压。这也解释了为什么 Circle 需要 Arc 这样的公链业务作为收入结构升级——从"利差公司"进化为"基础设施公司"。

**接下来关注：**Tether 的 8 月流通量数据（USDT 增速能否跟上）、稳定币赛道的估值传导（Circle 上市后的市盈率如何影响一级市场稳定币项目定价）、Fed 9 月议息会议对稳定币收益结构的影响。

---

## 市场脉搏

| 资产 | 价格 | 24h 变化 | 关键关注位 |
|------|------|----------|-----------|
| BTC | ~$64,745 | +0.7% | 支撑 $63,500 / 阻力 $67,000 |
| ETH | ~$2,300 附近 | 关注 ETH/BTC 突破 | 阻力 $3,000（心理关口）|
| ETH/BTC | 突破 9 年趋势线 | — | 若站稳 0.06 → 位置目标 0.08 |
| BTC ETF 3 日净流入 | $626M | — | 关注 8 月能否延续无卖出 |
| USDC 流通量 | $73.3B (+19% QoQ) | — | 关注 Arc 主网上线后增速 |

**情绪与结构信号：**
- **BTC ETF 8 月无卖出**是 6 个月以来最强的机构参与信号
- **ETH/BTC 9 年阻力位突破**如果能确认，将标志加密市场从"BTC 独大"进入"BTC + ETH 双极"叙事
- Hashdex 清盘是**行业理性化**的健康信号，不宜解读为看空 BTC
- 稳定币赛道正在完成基础设施建设，下一波驱动将是**支付端渗透率**而非发行量本身

**未来 7 天需盯的三件事：**Circle Arc 主网发布会（预计 8 月中旬更多细节释放）、Solana 350ms slot 时间在主网上线的信号、8 月 BTC ETF 是否维持零卖出记录。

---

*Sources: [Financefeeds](https://financefeeds.com/crypto-etfs-extend-recovery-on-august-5-as-bitcoin-funds-attract-244-million-and-ethereum-returns-to-inflows/), [The Coin Republic](https://www.thecoinrepublic.com/2026/08/06/ethereum-etf-inflow-triggers-eth-btc-breakout-after-9-years-what-next/), [Crypto Integrated](https://www.cryptointegrat.com/p/crypto-news-august-6-2026), [Investing.com](https://www.investing.com/analysis/us-crypto-regulation-sets-the-stage-for-stablecoins-to-enter-core-finance-in-2026-200672588), [Elliptic](https://www.elliptic.co/insights/how-us-crypto-regulation-is-being-rewritten-in-2026/)*
