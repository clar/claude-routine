# Polymarket Daily Analysis

Generate a daily Polymarket prediction market analysis report in Chinese.

## Data Source

Use the Polymarket Gamma API (public, no auth required):

- **Hot events (by 24h volume)**: `https://gamma-api.polymarket.com/events?limit=20&active=true&closed=false&order=volume24hr&ascending=false`
- **High liquidity events**: `https://gamma-api.polymarket.com/events?limit=20&active=true&closed=false&order=liquidity&ascending=false`
- **Recently created**: `https://gamma-api.polymarket.com/events?limit=10&active=true&closed=false&order=startDate&ascending=false`

### Key fields per event

- `title` — event name
- `volume24hr` — 24h trading volume (USD)
- `liquidity` — total liquidity (USD)
- `markets[]` — individual outcomes
  - `question` — outcome question
  - `outcomePrices` — `[YES_price, NO_price]` (0-1, represents probability)
  - `bestBid`, `bestAsk` — order book spread
  - `volume24hr` — outcome-level 24h volume

## Analysis Steps

1. **Fetch data** from all three endpoints above using WebFetch or curl
2. **Identify top 10 hot markets** by 24h volume, extract YES probability and volume
3. **Detect pair cost arbitrage**: find markets where YES + NO price < $0.98 (potential free money)
4. **Detect high-spread markets**: where bestAsk - bestBid > 0.05 (illiquid, risky)
5. **Categorize markets** into: Politics, Geopolitics, Crypto, Sports, Economy, Tech, Other
6. **Identify notable probability shifts**: compare current prices to see extreme probabilities (>90% or <10%)

## Report Format

Generate a markdown file with this structure:

```markdown
# Polymarket 每日预测市场分析 · {YYYY-MM-DD}

## 今日焦点

> **{3-5 个今日最值得关注的市场主题，用 · 分隔}**
>
> - **{市场}** {一行要点，附 YES 概率 / 24h 交易量}
> - **{市场}** {...}
> - (3-5 bullet points total)

---

## 热门市场速览

| # | 市场 | 分类 | YES 概率 | 24h 交易量 | 流动性 |
|---|------|------|----------|-----------|--------|
(top 10 by volume24hr)

---

## 重点点评

Pick 3-5 most interesting/impactful markets and provide analysis:
- What is being predicted and why it matters
- Current probability and what it implies
- Key drivers that could shift the odds

---

## 套利与异常信号

### 配对成本异常 (YES+NO < $0.98)
List any markets where pair cost is below $0.98, if none say "今日未发现明显套利机会"

### 高价差市场 (Spread > 5%)
List markets with wide spreads as liquidity warnings

---

## 新上线市场

List 3-5 recently created markets worth watching

---

## 分类概览

Brief summary of prediction market sentiment by category (Politics, Crypto, Geopolitics, etc.)

> 免责声明：本报告仅供信息参考，不构成任何投资或交易建议。Polymarket 在部分司法管辖区可能受到限制。
```

## Output

Save the report to: `polymarket_daily/{YYYY-MM-DD}/report.md`

Use today's date. Create the directory if it doesn't exist.

After generating the report, stage and commit with message format:
`feat: add Polymarket daily report {YYYY-MM-DD}`

## Notes

- All analysis text should be in **Chinese**
- Volume and liquidity numbers should be formatted with $ and appropriate units ($1.2M, $45K, etc.)
- Probabilities should be shown as percentages (e.g., 85.3%)
- If an API call fails, note it in the report and continue with available data
- Focus on quality of analysis over quantity — 3 insightful observations beat 10 shallow ones
