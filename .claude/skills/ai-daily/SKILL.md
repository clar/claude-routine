# AI Daily News Report

Generate a daily AI industry news report in Chinese, covering models, products, research, policy, and business developments.

## Data Sources

Aggregate from multiple sources to get the fullest picture:

- **Anthropic / OpenAI / Google / Meta official blogs and press**
- **The Information, Bloomberg, Reuters, CNBC** — business/funding news
- **TechCrunch, The Verge, Ars Technica** — product launches
- **Nature, arXiv, Stanford HAI** — research / academic
- **Government/regulatory sources** — EU AI Act, China AI rules, White House policy
- **X/Twitter** for real-time signals from founders and researchers (if accessible)

## Scope

**What to include:**
- New model releases (versions, benchmarks, context length, pricing)
- Major funding rounds, revenue milestones, business deals
- Research breakthroughs (benchmarks broken, new capabilities)
- Regulatory and policy developments (US, EU, China, etc.)
- Notable controversies, safety incidents, or ethics debates
- Enterprise adoption stories and market shifts

**What to skip:**
- Minor product updates (tool tips, UI tweaks)
- Rumors without credible sourcing
- Repetitive content from yesterday

## Analysis Steps

1. **Gather 10-15 stories** from the past 24 hours
2. **Rate importance**: 5 stars (industry-defining), 4 (major development), 3 (notable)
3. **Rank by importance** then by timeliness
4. **Pick 3-5 stories** for deep commentary — the ones that reshape the landscape
5. **Identify the day's themes** for the focus line

## Report Format

```markdown
# AI 每日热点日报 · {YYYY-MM-DD}

## 今日焦点

> **{3-5 defining themes separated by ·}**
>
> - **{headline}** {one-line takeaway with key number or angle}
> - **{headline}** {...}
> - (3-5 bullet points total)

---

## 热点速览

| # | 新闻标题 | 来源 | 重要度 |
|---|---------|------|--------|
(10-15 rows, 重要度 uses ⭐ 1-5)

---

## 深度点评

### 🏆 No.1 · {headline}

**[{source name with link}]({url})**

{3-4 paragraphs analysis:
- What happened, key numbers and facts
- Why it matters for the industry
- What to watch for next}

**点评：** {1-2 sentences sharp take}

---

### 🚀 No.2 · {headline}

{same structure}

---

(3-5 deep commentary entries)

## 行业观察

{Brief closing section on themes of the day — competitive shifts, trend accelerations, regulatory direction}
```

## Output

Save to: `ai_daily/{YYYY-MM-DD}/report.md`

## Notes

- All text in **Chinese**
- Always include source links in the deep commentary
- Use specific numbers (ARR figures, benchmark scores, funding amounts) — concrete beats vague
- The "点评" line should be punchy, opinionated, and forward-looking
- Importance stars: 5 = reshapes the industry, 4 = major player moves, 3 = notable but incremental
