# 项目说明

本仓库用于存放每日自动生成的资讯报告（AI、加密、美股、GitHub trending、Polymarket）。

## 日期规则（强制）

生成或引用"今日报告"的路径时，**必须**严格遵守以下流程：

1. **以中国时间（UTC+8 / Asia/Shanghai）为准**，不使用 UTC 或本地时区。
2. 在决定日期之前，**必须先执行一次 shell 命令**获取权威日期，不得凭 context、记忆或仓库已有目录推断：
   ```
   TZ='Asia/Shanghai' date +%Y-%m-%d
   ```
3. 该命令输出即为"今日"日期（格式 `YYYY-MM-DD`），用于所有报告目录：
   - `ai_daily/{YYYY-MM-DD}/report.md`
   - `crypto_daily/{YYYY-MM-DD}/report.md`
   - `stock_daily/{YYYY-MM-DD}/report.md`
   - `polymarket_daily/{YYYY-MM-DD}/report.md`
   - `github_daily/{YYYY-MM-DD}/trending.md`
4. 当任务委派给子 agent 时，父 agent **必须先自己执行上述命令**拿到具体日期字符串，再把该字符串显式写入子 agent 的 prompt；不得让子 agent 自行推断日期。
5. 仓库中已存在某个日期的目录**不意味着**那就是今天，可能是历史报告——永远以命令输出为准。

## 分支与提交

- 默认在 `main` 分支直接开发
- 开工前先 `git pull origin main`
- 提交前检查 `git status`，避免遗漏文件
- 完成后 `git push -u origin main`

## Skill 目录

各报告对应的 skill 定义在 `.claude/skills/` 下，报告格式以各 SKILL.md 为准。
