# GitHub Trending Daily Report

Generate a daily GitHub trending repositories analysis in Chinese.

## Data Source

- **Primary**: [github.com/trending](https://github.com/trending) — daily trending repos
- **Alternative scraper**: `https://api.ossinsight.io/v1/trends/repos/` (if available)
- Fetch the top 10-15 trending repos of the day with: repo name, description, language, total stars, stars gained today, forks

## Analysis Steps

1. **Fetch today's trending list** (top 13-15 repos)
2. **Enrich each repo**: if description is missing or unclear, briefly read the README or repo page to understand what it does
3. **Identify themes**: look for patterns — is today dominated by AI agents, new frameworks, a specific ecosystem (Claude, Rust, etc.)?
4. **Pick 3-5 focus repos** worth deeper commentary (biggest gainers, strategically significant, or theme-defining)
5. **Write commentary** on each focus repo: what it does, why it's trending, what it signals about the ecosystem

## Report Format

```markdown
# GitHub 热门仓库日报 · {YYYY-MM-DD}

## 今日焦点

> **{theme keywords separated by ·, 3-5 items}**
>
> - `{repo}` {brief one-line takeaway with star count}
> - `{repo}` {...}
> - (3-5 bullet points total)

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
(13-15 rows, with repo as markdown link)

---

## 重点项目点评

### 🥇 [{repo}](https://github.com/{repo}) — 今日榜首，+{N}⭐

**{subheading that frames why this matters}**

{2-3 paragraphs analysis. What does it do, why is it trending, what does it signal}

---

### 🥈 [{repo}](https://github.com/{repo}) — +{N}⭐

{same structure, 2-3 paragraphs}

---

### 🥉 [{repo}](https://github.com/{repo}) — +{N}⭐

{same structure}

---

(Include 3-5 total "重点项目点评" entries)

## 生态观察

{One short section summarizing the day's themes — what's heating up, what's cooling, what's new}
```

## Output

Save to: `github_daily/{YYYY-MM-DD}/trending.md`

## Notes

- All text in **Chinese**
- Star counts should use `+N,NNN⭐` format with comma separators
- Repo names as markdown links: `[owner/repo](https://github.com/owner/repo)`
- Focus on **why it's trending**, not just **what it is** — link to broader ecosystem shifts
- 3-5 deep commentaries is ideal; don't force more if the day is quiet
