# US Stock Daily Report

Generate a daily US stock market news report in Chinese, covering indices, notable movers, earnings, macro, and sector shifts.

## Data Sources

- **Bloomberg, Reuters, CNBC, WSJ, Financial Times** — mainstream financial journalism
- **Yahoo Finance, MarketWatch, Seeking Alpha** — market data and analysis
- **SEC EDGAR** — 8-K, 10-Q, 10-K filings and insider transactions
- **Company IR pages and earnings press releases**
- **Federal Reserve / Treasury** — rate decisions, FOMC minutes, policy signals
- **BLS / BEA** — CPI, PCE, jobs, GDP releases

## Categories

Cover stories across these categories (not all every day):
- **指数** — S&P 500, Nasdaq, Dow, Russell 2000, VIX
- **个股** — notable movers, 10%+ gainers/losers, large-cap news
- **财报** — earnings beats/misses, guidance, outlook changes
- **宏观** — Fed, rates, inflation, employment, geopolitics affecting markets
- **板块** — sector rotation, thematic shifts (AI, energy, financials, biotech)
- **并购** — M&A deals, spinoffs, activist campaigns
- **IPO** — new listings, direct listings, lockup expirations
- **分析师** — major upgrades/downgrades, price target changes

## Analysis Steps

1. **Gather 10-12 stories** from the past 24 hours / latest trading session
2. **Cover the breadth**: indices + individual movers + at least one macro item
3. **Extract concrete numbers**: prices, % changes, market cap, EPS, revenue, guidance
4. **Pick 4-6 stories** for "重点点评" — the ones that matter most
5. **Identify today's themes** for the focus line

## Report Format

```markdown
# 美股每日热门新闻 · {YYYY-MM-DD}

> 今日焦点：**{3-5 defining headlines separated by ·}**

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
(10-12 rows. 标题 wrapped in **bold**. 分类 is a single short tag like 指数/个股/财报)

---

## 重点点评

### 🔑 1. {headline} — {angle}

{3-4 paragraphs of analysis:
- Context: what happened, key numbers
- Why it matters: market/sector/company implications
- What to watch: upcoming earnings, Fed meeting, catalyst dates}

---

### 🔑 2. {headline} — {angle}

{same structure}

---

(4-6 total deep commentary entries)

## 市场脉搏

{Brief closing section with a market snapshot:
- Three major index closes and % changes (S&P 500, Nasdaq, Dow)
- VIX level
- 10Y Treasury yield
- Dollar index (DXY)
- Notable commodity moves (oil, gold) if relevant}
```

## Output

Save to: `stock_daily/{YYYY-MM-DD}/report.md`

## Notes

- All text in **Chinese**
- Use bold **bold** around headlines in the speed table
- Include specific prices with $ prefix ($425.30), percentages with sign (+2.3%, -1.8%), and large numbers with units ($42B market cap, $1.2T revenue)
- Category tags should be single words (2-3 Chinese characters max)
- "重点点评" should have an opinionated "角度" (angle) in the heading — not just restate the news
- During earnings season, prioritize major reporters (mega-caps, top banks, Dow components)
- Distinguish regular session moves vs. after-hours / pre-market moves when relevant
- If a market-moving macro event (CPI, FOMC, NFP) is happening, lead with it
