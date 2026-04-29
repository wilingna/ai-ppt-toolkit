<div align="center">

# ⚡ AI-PPT-Web

### One web page replaces NotebookLM + Gemini. Paste notes → get Gamma-ready markdown.
### 一个网页替掉 NotebookLM 和 Gemini，粘资料 → 直接拿到 Gamma 能用的 Markdown

**No login chains. No tab-switching. Same proven 3-tool methodology — minus 2 tools.**
**不用三个账号轮流登录，不用三个标签页来回切。同一套已验证的方法论，少两个工具。**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Live App](https://img.shields.io/badge/app-live-brightgreen)](https://wilingna.github.io/ai-ppt-web/)
[![Based on](https://img.shields.io/badge/methodology-300k%2B%20views-red)](https://github.com/wilingna/ai-ppt-toolkit)
[![No Build](https://img.shields.io/badge/build-zero%20config-blue)](https://github.com/wilingna/ai-ppt-web)
[![Stars](https://img.shields.io/github/stars/wilingna/ai-ppt-web?style=social)](https://github.com/wilingna/ai-ppt-web)

[**🔗 Open the App**](https://wilingna.github.io/ai-ppt-web/) · [English](#english) · [中文](#中文) · [Quick Start](#-quick-start) · [The Story](#-the-story--方法论演进)

</div>

---

## 🎯 TL;DR

**EN** — `ai-ppt-web` is the web-based upgrade of [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) (300k+ views, 51⭐) — a methodology validated by tens of thousands of Chinese knowledge workers. Claude replaces the NotebookLM + Gemini steps in one page. You paste messy multi-source notes, you get polished Gamma-ready markdown. Then one paste into Gamma → done.

**中文** — 本工具是 [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit)（30 万+ 播放、51 颗星）这套方法论的**网页版升级**。Claude 在一个网页里替掉了 NotebookLM 和 Gemini 两步——粘乱资料进去，拿出 Gamma 能直接用的 Markdown，再粘一次到 Gamma 就完成了。

```
Before · 之前:  Notes → NotebookLM → Gemini → Gamma   (3 tools, 3 logins)
After  · 现在:  Notes → ai-ppt-web → Gamma            (1 page + Gamma)
```

---

<a name="english"></a>
## 🌍 English

### "Why not just use Gamma directly?"

Because Gamma is excellent at *visuals* and bad at *thinking*. Drop a messy pile of meeting notes into Gamma and you get pretty slides with fluffy AI-flavored text. The hard part of slide-making isn't the layout — it's:

1. Figuring out what your audience actually cares about
2. Picking the spine of the story
3. Writing in a voice that sounds like a *human at your company*, not GPT

`ai-ppt-web` does that **before** Gamma sees a single word. Gamma stays in its lane (visuals); Claude handles the thinking.

### What you get

- **Step 1 output**: A spine — what to say, what to cut, what your audience is really listening for
- **Step 2 output**: Gamma-ready markdown — punchy headlines (no more "现状分析" / "Current Situation"), human voice, anti-AI-cliché filtering
- **Tool count**: 1 web page + Gamma
- **Cost**: ~$0.05–$0.10 per full run via OpenRouter
- **Privacy**: API key stays in your browser. No PPTFlux server in the request chain.

---

<a name="中文"></a>
## 🇨🇳 中文

### "为什么不直接用 Gamma？"

因为 Gamma 强在**视觉**，弱在**思考**。一堆乱资料丢进 Gamma，你会拿到一份"看着挺好看，但内容很 AI"的 PPT。做 PPT 真正难的不是排版，是：

1. 想清楚你的听众真正关心什么
2. 找到故事的主线
3. 用"企业里的人说话"的口气写，不是 GPT 腔

ai-ppt-web 在 Gamma 看到内容**之前**就把这些事做完了。Gamma 继续干它擅长的视觉，Claude 干思考的活。

### 你能拿到什么

- **Step 1 产出**：故事主线——讲什么、舍什么、听众真正在意什么
- **Step 2 产出**：Gamma 直接能用的 Markdown——金句化标题（告别"现状分析""存在问题"）、有人味的表达、反 AI 套话过滤
- **工具数量**：1 个网页 + Gamma
- **费用**：完整一次约 $0.05-0.10（通过 OpenRouter）
- **隐私**：API Key 只存本地浏览器，请求链路里没有任何中间服务器

---

## ⚖️ ai-ppt-web vs Gamma-only vs ai-ppt-toolkit

| | **Gamma 直接用** | **ai-ppt-toolkit**（三件套） | **ai-ppt-web**（本仓库） |
|---|---|---|---|
| 工具数 · Tools | 1 | 3 (NLM + Gemini + Gamma) | 1 web + Gamma |
| 账号 · Accounts | 1 | 3 | OpenRouter only |
| 思考质量 · Thinking | ⭐⭐ AI 套话多 | ⭐⭐⭐⭐⭐ 最深 | ⭐⭐⭐⭐ 接近三件套 |
| 速度 · Speed | ⚡⚡⚡⚡⚡ | ⚡⚡ | ⚡⚡⚡⚡ |
| 适合 · Best for | 临时凑个 deck | 想理解底层逻辑 | 日常快速产出高质量 |

> **Picking guide · 选哪个**: First time? Read [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) to understand the methodology. Then come back here for daily use.
> **选择建议**: 第一次接触？先去 [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) 学方法论。理解了之后回来用本工具日常提效。

---

## 🚀 Quick Start

### Option A — Use it online · 直接在线用（推荐）

👉 **[wilingna.github.io/ai-ppt-web](https://wilingna.github.io/ai-ppt-web/)**

### Option B — Run locally · 本地运行

```bash
git clone https://github.com/wilingna/ai-ppt-web
cd ai-ppt-web
open index.html   # macOS, or just double-click
```

Single-file HTML. Vanilla JS. Zero build, zero dependencies.
单文件 HTML，原生 JS，零构建零依赖。

### Six steps to a deck · 六步成 deck

#### 1️⃣ Get an OpenRouter API key · 准备 OpenRouter API Key

- Sign up at [openrouter.ai](https://openrouter.ai/) (supports WeChat / Alipay) · 注册 [openrouter.ai](https://openrouter.ai/)（支持微信 / 支付宝充值）
- Top up $5 — covers 50–100 runs · 充 $5 够用 50–100 次
- Keys page → Create Key → copy · Keys 页面 → Create Key → 复制

#### 2️⃣ Open the app, paste your key · 打开工具填 Key

API key runs locally in your browser only. No third-party server.
API Key 仅在本地浏览器使用，不经过任何第三方服务器。

#### 3️⃣ Fill in topic, duration, audience · 填主题、时长、汇报对象

#### 4️⃣ Upload or paste your raw notes · 上传或粘贴资料

Supported formats · 支持格式:

| Format | Note |
|---|---|
| 📄 PDF | ✅ |
| 📝 Word `.docx` | ✅ |
| 📊 Excel `.xlsx` / CSV | ✅ |
| 🖼 Images PNG/JPG | ✅ |
| 📃 TXT / Markdown | ✅ |
| Just paste text | The messier, the better — Claude will sort it · 越乱越多越好 |

#### 5️⃣ Step 1 — Generate the spine · 生成大纲

Claude figures out:
- What leadership actually cares about · 管理层真正关心什么
- The narrative arc · 故事线怎么走
- What to keep vs. cut · 哪些放、哪些舍

#### 6️⃣ Step 2 — Generate the script · 生成演讲内容

Claude produces:
- Punchy headlines (no more "现状分析" / "Existing Issues") · 金句化标题
- Scenario-grounded body copy · 场景化扩写
- AI-smell stripped · 去 AI 味
- **Gamma-formatted markdown** · 输出 Gamma 专用 Markdown

#### 7️⃣ Paste into Gamma · 导入 Gamma

1. Copy the markdown · 复制 Markdown
2. [gamma.app](https://gamma.app) → paste · 打开 Gamma → 粘贴
3. ⚠️ **Choose "Keep text as-is" (保持此文本原样)** — this is critical, otherwise Gamma rewrites and re-injects AI smell · 务必选「保持此文本原样」，否则 Gamma 会重写让 AI 味回来
4. Generate, fine-tune visuals · 生成，微调视觉

---

## ❓ FAQ

<details>
<summary><b>Q: Is my API key safe? · API Key 安全吗？</b></summary>

Stored in your browser's localStorage only. Code is fully open-source — audit it yourself. Nothing in the request chain except OpenRouter.
只存在你本地浏览器的 localStorage，代码完全开源可审计。请求链路里除了 OpenRouter 没有任何第三方。

</details>

<details>
<summary><b>Q: How much per run? · 一次多少钱？</b></summary>

Step 1 + Step 2 combined ≈ **$0.05–$0.10**. A $5 OpenRouter top-up lasts 50–100 runs.
Step 1 + Step 2 加起来约 **$0.05-0.10**，OpenRouter 充 $5 够用 50-100 次。

</details>

<details>
<summary><b>Q: Do I need a VPN? · 需要翻墙吗？</b></summary>

OpenRouter is accessible from mainland China without a VPN.
OpenRouter 国内可直连，无需翻墙。

</details>

<details>
<summary><b>Q: Will the original toolkit be deprecated? · 三件套还能用吗？</b></summary>

No. Both repos stay alive — they serve different purposes. Toolkit teaches the *why*, this teaches the *fast*.
不会下架。两个仓库定位不同：toolkit 教"为什么"，本工具帮"更快"。

</details>

<details>
<summary><b>Q: Why not auto-export to Gamma? · 为什么不自动导入 Gamma？</b></summary>

Gamma has no public API. Manual paste is the only option for now — but it's literally one paste.
Gamma 没有公开 API，只能手动粘贴——但也就一次粘贴的事。

</details>

---

## 📖 The Story · 方法论演进

This repo is the middle child in a 3-stage evolution. If you're building "AI for slides" tools yourself, the path might resonate:
本仓库是一段三阶段演进的中间站。如果你也在做"AI 做 PPT"，这条路径或许能给你启发：

### 🥇 [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) — The Methodology · 方法论

Three tools, three jobs. NotebookLM + Gemini + Gamma. **51 ⭐, 300k+ views on Xiaohongshu** — the most validated AI-slides workflow in the Chinese productivity community.
三个工具各司其职。**51 颗星、小红书 30 万+ 播放**——华语生产力圈最被验证的 AI 做 PPT 工作流。

### 🥈 **ai-ppt-web** (this repo) · 第一次合并

Claude replaces the first two tools. Three tools collapsed into one web page + Gamma. Manual relay collapsed into auto-handoff. **You're here.**
Claude 吃掉前两步。三个工具压成一个网页 + Gamma，手动接力变自动衔接。**你在这里。**

### 🥉 [PPTFlux](https://github.com/wilingna/PPTFlux) — The Loop Closes · 闭环

4 agents replace even Gamma. Outputs are interactive HTML decks with 6 design languages × 18 layouts, two layers of editability.
4 Agent 连 Gamma 都吃掉了。产出是交互式 HTML 幻灯片，6 套设计 × 18 种排版，两层编辑权。

> **toolkit teaches *why*. ai-ppt-web makes it *faster*. PPTFlux makes it *one-shot*.**
> **toolkit 教你"为什么"，ai-ppt-web 让你"更快"，PPTFlux 让你"一气呵成"。**

---

## 🛠 Tech Stack

- Single-file HTML + Vanilla JS — no build, no framework
- OpenRouter API gateway — one key, all major models
- Claude (recommended) for Step 1 + Step 2
- Hosted on GitHub Pages — the entire app is one `index.html`

---

## 🤝 Contributing

Issues and PRs welcome — especially:
- New file format support · 新文件格式支持
- Better prompt templates for non-business scenarios · 非商业场景的 prompt 模板
- UI/UX polish · 界面体验改进

---

## 📜 License

MIT — use it, fork it, ship it.

---

## 👋 About

Built by **wilingna** ([@wilingna](https://github.com/wilingna))
Big-tech HR turned AI Systems Architect. Building AI workflows and Chinese-aesthetic digital culture for global audiences.
大厂 HR 出身的 AI Systems Architect，做 AI 工作流 / 中国传统美学数字文化出海。

### My Other Projects · 其他项目

| Repo | What it does |
|---|---|
| [ai-ppt-toolkit](https://github.com/wilingna/ai-ppt-toolkit) | The original 3-tool methodology · 三件套原版（51⭐）|
| [PPTFlux](https://github.com/wilingna/PPTFlux) | 4-agent pipeline → interactive HTML decks · 4 Agent 闭环 |
| [ai-decision-5steps](https://github.com/wilingna/ai-decision-5steps) | High-quality decisions in 5 AI-powered steps · 5 步 AI 决策 |
| [ai-content-pipeline](https://github.com/wilingna/ai-content-pipeline) | 7-agent content production pipeline · 7 Agent 内容生产线 |

---

<div align="center">

### ⭐ If this saved you a triple-tab afternoon, drop a star.
### ⭐ 如果帮你省了一下午三标签页接力，点个 star 吧。

**Or even better — tell me what your workflow looks like in [Issues](https://github.com/wilingna/ai-ppt-web/issues).**
**或者更好——在 [Issues](https://github.com/wilingna/ai-ppt-web/issues) 里告诉我你的工作流长什么样。**

</div>
