# Crypto Daily News Report

Generate a daily cryptocurrency and blockchain industry news report in Chinese, covering markets, institutions, regulation, security, and technology.

## Data Sources

- **CoinDesk, The Block, CoinTelegraph, Decrypt** — mainstream crypto journalism
- **Bloomberg Crypto, Reuters, CNBC Crypto** — institutional and macro
- **Official project blogs** — Ethereum Foundation, major L1/L2 teams, exchanges
- **Regulatory sources** — SEC, CFTC, US Treasury, EU MiCA, policy think tanks
- **On-chain / market data** — CoinGecko, CoinMarketCap for prices; Farside/SoSoValue for ETF flows
- **Polymarket / prediction markets** for regulatory probability signals

## Categories

Cover stories across these categories (not all every day):
- **行情** — price action, market structure, derivatives
- **机构** — ETFs, corporate treasuries, banks, asset managers
- **监管** — legislation, SEC/CFTC actions, international policy
- **安全** — hacks, exploits, security incidents
- **技术** — protocol upgrades, L2 developments, research
- **采用** — real-world usage, payment integrations
- **生态** — DeFi, stablecoins, specific ecosystems
- **行业** — conferences, company news, market share shifts

## Analysis Steps

1. **Gather 10-12 stories** from the past 24 hours
2. **Cover the breadth**: don't over-concentrate on one category
3. **Extract concrete numbers**: prices, volumes, TVL, ETF flows, hack amounts
4. **Pick 4-6 stories** for "重点点评" — the ones that matter most
5. **Identify today's themes** for the focus line

## Report Format

```markdown
# Crypto 每日热门新闻 · {YYYY-MM-DD}

> 今日焦点：**{3-5 defining headlines separated by ·}**

---

## 热门新闻速览

| # | 标题 | 分类 | 要点 |
|---|------|------|------|
(10-12 rows. 标题 wrapped in **bold**. 分类 is a single short tag like 行情/监管/机构)

---

## 重点点评

### 🔑 1. {headline} — {angle}

{3-4 paragraphs of analysis:
- Context: what happened, key numbers
- Why it matters: market/regulatory/technical implications  
- What to watch: next steps, potential cascades}

---

### 🔑 2. {headline} — {angle}

{same structure}

---

(4-6 total deep commentary entries)

## 市场脉搏

{Brief closing section with a market snapshot:
- Major asset prices and 24h changes
- Key technical levels to watch
- Macro/sentiment indicator (Fear & Greed Index, funding rates, etc.)}
```

## Output

Save to: `crypto_daily/{YYYY-MM-DD}/report.md`

## Notes

- All text in **Chinese**
- Use bold **bold** around headlines in the speed table
- Include specific prices with $ prefix ($74,390), percentages with %, and large numbers with appropriate units ($1.2B, $540M)
- Category tags should be single words (2-3 Chinese characters max)
- "重点点评" should have an opinionated "角度" (angle) in the heading — not just restate the news
- If a market-moving event is happening (hack, major regulatory action), lead with it
