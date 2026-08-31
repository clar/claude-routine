# GitHub Trending 每日热榜 · 2026-09-01

## 今日焦点

> **Agent Skill 生态爆发 · 多智能体教育应用 · 从零训练小型 LLM · 反审查工具 · SEO 开源替代**
>
> - `THU-MAIC/OpenMAIC` +2,819⭐ — 清华推出多智能体教室，教育交互领域第一次跑出破圈项目
> - `tt-a1i/archify` +3,993⭐ — Agent Skill 生态今日榜首，生成"可验证"的架构与流程图
> - `K-Dense-AI/scientific-agent-skills` +1,968⭐ — 面向科学家的 Agent Skill 库，累计 19 万科研用户
> - `zhaoxuya520/reverse-skill` +1,439⭐ — 逆向工程 & 授权渗透 Skill 路由包，AI 安全研究工具化
> - `p-e-w/heretic` +536⭐ — 大模型审查全自动移除工具，引发合规性讨论

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 生成可验证的架构与流程图（HTML+动效） | JavaScript | 38,495 | +3,993 | 2,464 |
| 2 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | 多智能体沉浸式互动课堂 | TypeScript | 26,865 | +2,819 | 4,740 |
| 3 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 把 AI Agent 变成 AI 科学家 | Python | 40,676 | +1,968 | 3,766 |
| 4 | [zhaoxuya520/reverse-skill](https://github.com/zhaoxuya520/reverse-skill) | 逆向 & 授权渗透 Skill 路由包 | PowerShell | 33,072 | +1,439 | 4,488 |
| 5 | [every-app/open-seo](https://github.com/every-app/open-seo) | Semrush/Ahrefs 的开源替代 | TypeScript | 15,717 | +608 | 1,894 |
| 6 | [handsomestWei/patent-disclosure-skill](https://github.com/handsomestWei/patent-disclosure-skill) | 中文专利撰写与政策解读 Skill | Python | 6,191 | +571 | 728 |
| 7 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | Agent harness 性能优化系统 | JavaScript | 245,209 | +548 | 37,046 |
| 8 | [p-e-w/heretic](https://github.com/p-e-w/heretic) | 大模型审查全自动移除 | Python | 29,622 | +536 | 3,247 |
| 9 | [k1tbyte/Wand-Enhancer](https://github.com/k1tbyte/Wand-Enhancer) | WeMod 增强扩展 | C# | 23,339 | +511 | 59,517 |
| 10 | [jingyaogong/minimind](https://github.com/jingyaogong/minimind) | 2 小时从零训练 64M LLM | Python | 56,055 | +472 | 7,313 |
| 11 | [majd/ipatool](https://github.com/majd/ipatool) | 命令行下载 iOS/iPadOS/tvOS 应用包 | Go | 10,512 | +376 | 895 |
| 12 | [checkstyle/checkstyle](https://github.com/checkstyle/checkstyle) | Java 编码规范检查工具 | Java | 9,400 | +199 | 4,206 |
| 13 | [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) | Rust PDF 分类与文本提取库 | Rust | 17,333 | +199 | 1,198 |
| 14 | [kaifcodec/user-scanner](https://github.com/kaifcodec/user-scanner) | 邮箱/用户名 OSINT 深度挖掘套件 | Python | 4,194 | +184 | 444 |
| 15 | [Osmantic/ODS](https://github.com/Osmantic/ODS) | 一键把 PC/Mac 变 AI 服务器 | Python | 5,452 | +163 | 772 |

---

## 重点项目点评

### 🥇 [tt-a1i/archify](https://github.com/tt-a1i/archify) — 今日榜首，+3,993⭐

**Agent Skill 生态在今日榜单上占据前三席，archify 是"可视化诊断"这一细分场景的代表**

archify 是一个 Agent Skill，专门为架构图、工作流、时序图、数据流和生命周期图生成"可验证"的自包含 HTML 输出（含动效与高清导出）。它抓住的痛点是：**LLM 生成的图 90% 靠不住**——布局漂移、连线错误、语义不闭合。archify 把生成流程约束在一套预设的 schema 与验证器里，让模型输出必须过关才导出。

它 3,993 的日增说明两件事：一是 Agent Skill 已经从"玩具"走到"工作流集成"阶段，用户开始为特定输出质量付费/装配；二是**"可验证输出"（verifiable outputs）**在成为新的产品差异化——不是"能不能生成"，而是"生成的一定对"。

对比一年前 Mermaid、PlantUML 这类静态方案，archify 走的是"AI 生成 + 硬约束校验 + 富交互 HTML"的路径，代表了 Skill 层未来一年的主流范式。

---

### 🥈 [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) — +2,819⭐

**清华 MAIC 出手，多智能体教育首次拿到主流开源关注**

OpenMAIC（Open Multi-Agent Interactive Classroom）是清华 MAIC 团队的开源版沉浸式多智能体课堂。项目背景是学界近年一直在推的 "Agents as Peers/TA/Teacher" 教学模式：多个具备不同角色（讲师、助教、爱提问的同学、爱抬杠的同学）的 LLM Agent 组成一节课堂，学习者通过与他们互动完成学习目标。

它的爆红并非偶然：一方面对应中国教育信息化政策今年在多智能体教学工具上的重点扶持；另一方面它是**第一个把多智能体教学从论文级 demo 打包成可"一键部署"的开源项目**，前端体验直接对标商用教育产品。TypeScript + 完整前后端一体，说明团队并非只做学术复现，而是奔着可落地的产品方向。

日增 2,819⭐ 会持续吸引更多本地化版本 fork（K-12、职业教育、企业培训场景），未来一到两周会看到大量中文教程与集成到国内 LLM 的分叉。

---

### 🥉 [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) — +1,968⭐

**"把任意 Agent 变成 AI 科学家"——Skill 库已成为科研人的标配**

scientific-agent-skills 是面向科学家的 Agent Skill 集合，官方 README 声称已被 19 万科学家使用。它覆盖了文献综述、实验设计、数据分析、论文写作、代码复现等全链条 Skill，可直接挂载到 Claude / GPT / 开源 Agent runtime 上。

它的意义不在"新颖"——类似方向的项目已经出现过多次——而在"规模化"：一个 Skill 库能被主流实验室与研究者广泛引用，说明 **Skill 已经取代"Prompt 工程"成为科研 AI 工具的组织形态**。研究者不再需要自己写复杂 system prompt，而是像装 npm 包一样装 Skill。

配合今日榜首 archify 和第四位 reverse-skill，一天里同时有三个 Skill 项目冲进 Top 5，说明 Skill 生态已经具备"每日高流量新增"的自然增长曲线——这在半年前还完全不成立。

---

### 🏅 [p-e-w/heretic](https://github.com/p-e-w/heretic) — +536⭐

**大模型"审查移除"自动化，触及了开源社区最敏感的红线**

heretic 是一个针对开源 LLM 的"审查移除"（uncensoring）工具，声称能全自动检测并解除模型的拒答/自我审查行为。它并不训练新模型，而是通过技术手段修改权重或激活模式，让模型对被审查话题给出更"直接"的回答。

它爆红的原因是双向的：一方面开源社区长期讨论"对齐即审查"的模糊边界，heretic 提供了一个纯技术化、可复现的解决方案；另一方面从内容安全和法律合规角度，这个项目位于灰区——它不违反任何具体许可，但可能被用于绕过厂商风控。

值得关注的是，heretic 的存在会加速厂商在**权重级别**（而非仅 prompt 级别）内置更难移除的安全约束，也可能推动开源侧 fine-tuning 时把安全层做成不可分离结构。围绕它的争论，会在未来数月成为开源模型开发者与安全研究者的重要战场。

---

### 🎖️ [jingyaogong/minimind](https://github.com/jingyaogong/minimind) — +472⭐

**"2 小时训 64M 模型"——教育化项目继续维持长期热度**

minimind 已经不是新项目，但今日仍能日增 472⭐，说明它作为"入门 LLM 训练"教材的地位已确立。项目提供从数据、tokenizer、模型结构、训练脚本、微调、评测的完整闭环，硬件门槛低（一台带 GPU 的家用机足够），2 小时可训完 64M 参数模型。

它在今日榜单出现的意义，是与前面 Skill 生态相对照——**Agent 侧在"高层组装"，模型侧仍在"底层教育"**，两个方向同时活跃说明开源社区没有偏科。特别是伴随 Apple Mac Mini/Studio 对 AI 硬件的可及性提升，"在自己电脑上从零训模型"的人群还会继续扩大。

---

## 生态观察

**今日榜单最强信号：Agent Skill 生态正式脱离"实验"进入"日常爆款"阶段。**

Top 15 里有 5 个直接是 Skill 项目（archify、scientific-agent-skills、reverse-skill、patent-disclosure-skill、ECC），另有 1 个 Agent 教育应用（OpenMAIC）。这已经不是"某个赛道热"，而是"生态基础设施成形"——就像 2015 年 npm 生态从少数明星包扩展到"每天有新包成为热门"的阶段。

**中文项目占比继续走高**：OpenMAIC（清华）、minimind、reverse-skill、patent-disclosure-skill 都是中文团队，且 README 与文档大量中文优先。这与国内 LLM 生态活跃度、政策鼓励开源发布密切相关。

**冷启动项目在减少**：今日 Top 5 大多是既有仓库的爆发式二次爆红，纯新建仓库直接冲榜的现象在减弱。这符合 GitHub Trending 从"发现新项目"到"发现旧项目新用法"的趋势演变。

**明日观察点**：archify 会不会催生一批模仿性 "verifiable output" 类 Skill；OpenMAIC 有没有中英文双语 fork；heretic 会不会被 GitHub 或某厂商推动下架，成为开源社区首个"审查移除"合规争议案例。
