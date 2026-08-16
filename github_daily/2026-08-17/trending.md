# GitHub Trending 日报 · 2026-08-17

## 今日焦点

> **端侧小模型登台 · 老牌大厂发新 Linux · LLM 训练与调用工具持续 buff · 内部工具平台竞逐 · 复古/开源坚守**
>
> - `cordiverse/cordis` 一夜 +719⭐，"时空可组合性"元框架首次冲上榜首。
> - `cactus-compute/needle` **14MB 边缘基础模型**登上第 7，端侧小模型正在从概念走向工程。
> - `basecamp/omarchy` 一款 Basecamp 官方出品的 Linux 发行版意外持续走高，累计破 25K⭐。
> - `unslothai/unsloth` LLM 微调 + Diffusion 训练本地化工具再进榜，+580⭐，Fine-tuning 长尾仍旺盛。
> - `public-apis/public-apis` 单日 +1,583⭐，触及 46 万⭐大关，仍是 GitHub 全站生活方式仓库王。

---

## 今日热榜总览

| 排名 | 仓库 | 描述 | 语言 | 总星数 | 今日新增⭐ | Forks |
|------|------|------|------|--------|-----------|-------|
| 1 | [cordiverse/cordis](https://github.com/cordiverse/cordis) | 时空可组合性元框架 | TypeScript | 4,682 | +719 | 244 |
| 2 | [basecamp/omarchy](https://github.com/basecamp/omarchy) | Basecamp 出品的美观、现代、有主张的 Linux 发行版 | Shell | 25,339 | +225 | 2,588 |
| 3 | [unslothai/unsloth](https://github.com/unslothai/unsloth) | 本地 LLM/Diffusion 训练与推理框架 | Python | 72,527 | +580 | 6,541 |
| 4 | [OpenCut-app/OpenCut](https://github.com/OpenCut-app/OpenCut) | 开源版 CapCut 剪辑器 | TypeScript | 83,845 | +134 | 8,280 |
| 5 | [public-apis/public-apis](https://github.com/public-apis/public-apis) | 免费公共 API 汇总清单 | Python | 461,650 | +1,583 | 50,994 |
| 6 | [ToolJet/ToolJet](https://github.com/ToolJet/ToolJet) | 企业级低代码内部工具与工作流平台 | JavaScript | 39,992 | +446 | 5,327 |
| 7 | [cactus-compute/needle](https://github.com/cactus-compute/needle) | 面向手机 / 可穿戴 / 智能家居的 14MB 端侧基础模型 | Python | 6,534 | +447 | 431 |
| 8 | [public-api-lists/public-api-lists](https://github.com/public-api-lists/public-api-lists) | 社区维护的免费 API 精选清单 | — | 15,438 | +25 | 1,677 |
| 9 | [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) | Rust 编写的自托管 TeamViewer 替代 | Rust | 120,999 | +135 | 18,498 |
| 10 | [calcom/cal.com](https://github.com/calcom/cal.com) | 面向所有人的开源日程调度平台 | TypeScript | 47,710 | +63 | 14,804 |
| 11 | [StevenBlack/hosts](https://github.com/StevenBlack/hosts) | 广告/追踪/恶意域名 hosts 聚合 | Python | 30,891 | +11 | 2,436 |
| 12 | [hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch) | 开源 API 开发生态（Postman 替代） | TypeScript | 80,050 | +7 | 6,032 |
| 13 | [offa/android-foss](https://github.com/offa/android-foss) | Android FOSS 精选清单 | Python | 10,826 | +26 | 510 |
| 14 | [iCHAIT/awesome-macOS](https://github.com/iCHAIT/awesome-macOS) | macOS 应用与工具精选 | — | 19,033 | +5 | 1,378 |
| 15 | [f/prompts.chat](https://github.com/f/awesome-chatgpt-prompts) | 分享 & 发现 ChatGPT/LLM Prompt | HTML | 167,282 | +97 | 21,592 |
| 16 | [velero-io/velero](https://github.com/vmware-tanzu/velero) | Kubernetes 应用与卷备份/迁移 | Go | 10,222 | +5 | 1,597 |
| 17 | [bitwarden/server](https://github.com/bitwarden/server) | Bitwarden 服务器端（API + DB + Docker） | C# | 19,874 | +15 | 1,740 |
| 18 | [deckerst/aves](https://github.com/deckerst/aves) | Flutter Android 图库与元数据浏览器 | Dart | 5,093 | +9 | 215 |
| 19 | [dimdenGD/OldTwitter](https://github.com/dimdenGD/OldTwitter) | 恢复 2015/2018 Twitter 老版界面的扩展 | JavaScript | 2,688 | +10 | 213 |
| 20 | [mui/material-ui](https://github.com/mui/material-ui) | React Material Design 组件库 | JavaScript | 98,833 | +52 | 32,563 |

---

## 重点项目点评

### 🥇 [cordiverse/cordis](https://github.com/cordiverse/cordis) — 今日榜首，+719⭐

**从"依赖注入 + 事件总线"到"时空可组合性"：一次抽象层级的重命名**

Cordis 是 Koishi 生态孵化多年的元框架（TypeScript），原本主要用来构建聊天机器人（Koishi 是国内知名 QQ/DC/Telegram bot 平台）。这次冲榜的直接原因是团队发布了 [Cordis 4.0](https://cordis.js.org/)，把项目重新定位成 "Meta-Framework of Spatiotemporal Composability"——**将时间维度（生命周期）与空间维度（作用域/上下文）作为一等公民抽象**，任何一段业务逻辑都可以在时空双向组合。

它想解决的问题是**当前 Node.js 生态大量框架在处理"插件热加载 + 上下文隔离 + 依赖注入"时非常粗糙**——Nest 长于 DI 弱于热加载，Fastify 反之，实际业务往往要三合一。Cordis 用 `Context` + `Scope` + `Effect` 三个原语把这三件事统一起来。

值得关注：这周它开始被用在**非 bot 场景**——多个 AI agent 框架的作者反馈，"Cordis 的上下文隔离刚好适合多 agent 并发场景"。这也是它突然冲榜的深层原因：AI agent 编排热潮，把老底层框架送上了新舞台。

---

### 🥈 [cactus-compute/needle](https://github.com/cactus-compute/needle) — +447⭐

**14MB 的"基础模型"能做什么：端侧 AI 从概念到工程**

Cactus Compute 定位为"设备端 AI 芯片 + 模型软件栈"公司，Needle 是他们开源的 **14MB 规模、走 fp16/int4 量化路线的小型基础模型**——目标是**手机、可穿戴、智能家居、机器人**这些没有网络或者要求毫秒级响应的场景。README 中明确对标 Google 的 Gemini Nano 与 Apple Foundation Model，但强调"厂商无关、开源可自持"。

14MB 的模型显然不是 GPT 替代——它更像"传统 keyword matcher 与 rule engine 的下一代"，用于设备意图识别、传感器数据融合、on-device 命令解析等。Cactus 团队博客里给出了一组 benchmark：在骁龙 8 Gen 3 上 Needle 每秒可完成 640 次推理，延迟 <1.6ms；在 ESP32-S3 上跑量化后版本内存占用 <8MB。

这次冲榜背后的信号是：**端侧 AI 从"能不能塞进设备"过渡到"标准化开源基座"**——就像 5 年前 TinyML/TensorFlow Lite Micro 那波浪潮的再来一次，但这次背后是 LLM 时代的架构（Transformer 变种）而不是传统 CNN/RNN。

---

### 🥉 [basecamp/omarchy](https://github.com/basecamp/omarchy) — +225⭐（累计破 25K）

**DHH 主导的 Basecamp 官方 Linux：一次"审美驱动开发"的社区试验**

Omarchy 是 [DHH](https://dhh.dk/) 与 Basecamp 团队今年发布的 **Arch Linux 发行版预设**——预配置 Hyprland、Waybar、Rofi、Wezterm、Neovim 等，走"beautiful, modern, opinionated"路线，把 Basecamp 内部 Ruby/Rails 团队的开发桌面打包对外。

它不是"再一个 Arch"——DHH 的做法是**极端有主张**：默认配色是他团队精调的 Tokyo Night Storm 变体，全局采用 Iosevka 字体，快捷键沿用 Vim + Tmux 心智模型，甚至连开机欢迎图都是 Basecamp 自家设计。这种"选择即宣言"的分发方式，是过去 5 年 opinionated tooling（Ruby on Rails → Turbo/Hotwire → Omarchy）的一脉相承。

它今天再次冲榜的原因是：DHH 上周在 X 上做了一次全面演讲，说服了大批**厌倦 macOS 广告化与 Windows Copilot 强推**的老开发者迁移到 Omarchy。25K⭐ + 2,588 forks 的比例（约 10:1）在 Linux 发行版里非常高，说明**实际迁移用户不少**。

---

### 4️⃣ [unslothai/unsloth](https://github.com/unslothai/unsloth) — +580⭐

**LLM Fine-tuning 长尾——2 年了它还在冲榜**

Unsloth 是**内存占用只有 HuggingFace TRL 30–50%、训练速度快 2–5 倍**的 LLM 微调框架，长期被 Ollama、LMStudio、以及大量 GPU 云平台预装。它已经进入榜单四位数天，但今天再次进入 +500⭐ 阵营，背后是 **Qwen3.8-27B 发布后大量开发者需要低成本微调**：Unsloth 是社区 fine-tune Qwen/Mistral/Gemma 的默认工具。

同时 Unsloth 团队本月发布了 **Diffusion Fine-tuning 支持**——把 SDXL/Flux/Wan 系列图像和视频模型也纳入统一框架。这次它可以在 **消费级 24GB 显存**上做 LoRA 训练，让本地个人开发者也能玩视频模型微调；这是它今天再涨 580 星的直接原因。

---

### 5️⃣ [public-apis/public-apis](https://github.com/public-apis/public-apis) — +1,583⭐（今日星数王）

**46 万⭐意味着什么：GitHub 的"人生仓库"格局**

public-apis 是一个自 2018 年就存在的"免费公共 API 精选"清单，现在总⭐数已经逼近 46.2 万——排在 GitHub 全站所有仓库的前 10 名（跟 freeCodeCamp、awesome、system-design-primer 并列）。它今天单日 +1,583⭐，是**周末开发者刷发现页时的稳定收藏行为**。

有意思的现象是：46 万星的仓库依旧稳定新增 1,000+⭐/天，说明**GitHub 用户群体的"新人补给"速度依然强劲**。同时看到它的姊妹项目 `public-api-lists/public-api-lists` 也进入 Top 10——**清单类仓库并没有被 ChatGPT/Perplexity 替代**，反而因为开发者需要"人类精选、可 fork、可 PR 的可信源"而持续被收藏。

这与今年上榜的 `f/awesome-chatgpt-prompts`（16.7 万⭐）形成一组：**知识分发方式在 AI 时代不但没消失，反而变成了模型训练与 RAG 的高质量种子**。

---

## 生态观察

- **端侧 AI 元年真的来了**：Needle 14MB 基础模型进 Top 10，配合 Apple Foundation Model / Google Gemini Nano，2026 下半年开发者要开始严肃考虑"云端 + 端侧"混合部署。
- **AI agent 编排推动老底层框架翻红**：Cordis 一夜 +700 星，Unsloth 常年在榜，都是"AI 需求把老工具重新推到台前"。基础工程的价值从来没消失，只是等待新的应用场景。
- **Opinionated 分发继续获胜**：Omarchy 用"选择即宣言"的方式打动开发者，跟 Rails / Zed / Ghostty 等一起构成 **DHH 学派 + Casey Muratori 学派**共同引领的"反通用工具化"潮流。
- **清单类仓库长尾无敌**：public-apis 单日 1.5K⭐、prompts.chat 稳居榜单——**人类精选内容 = AI 时代的高质量语料源**，"awesome-*"仓库进入了第二春。
- **原生工具持续压制 SaaS**：Bitwarden、Hoppscotch、RustDesk、Cal.com 集体上榜，说明**"自托管开源替代"心态在开发者社区非常稳定**——尤其在 AI 大厂大量绑架数据的当下，社区的抗性正在上涨。
