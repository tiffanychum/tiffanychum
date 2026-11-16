# Hi, I'm Tiffany 👋

I build AI platforms by day and AI side quests by night.

My rule: the best way to understand something is to build it. So when I wanted journaling to feel effortless and visual, I built an app. When I wanted a second opinion on stocks, I built a committee of AI analysts. When I wanted learning algorithms to feel like play, I built a game for it.

---

## 🚀 Side quests

### 💼 [Financial Analysis Agent](https://github.com/tiffanychum/financial-analysis-agent)
*A committee of AI analysts that lives in my WhatsApp.*

I message my agent `analyze AAPL`, and about 10 minutes later a full research report arrives.

- 🧮 **Formulas do the math, the LLM only interprets it.** Valuation models, quality scores and technical signals are deterministic and unit-tested.
- 🪑 **Seven analyst seats** (fundamental, valuation, technical, sentiment, a Buffett lens, a Burry lens, macro) vote, and a citation check flags any number that isn't in the data.
- 😈 **The trader has to argue against the majority first**, then three risk managers (aggressive, conservative, neutral) push back on its plan. An optional bull/bear debate can be switched on per run.
- ⚖️ **Two judges plus an "ablation judge"** that decides without the fair-value estimate. If they disagree, confidence is capped.
- 📉 It **scores its own past calls** against real prices and against plain monthly investing. My own backtest found the macro tilt *doesn't* predict returns, so the report says so.

`Python` · `OpenClaw` · `SEC / FRED / Yahoo data` · `350+ unit tests`
*Research only, not financial advice.*

### 🎬 [Scène](https://tiffanychum.github.io/scene-legal/)
*Turn your day into a movie, one line at a time.*

Write one line about your day and get back a cinematic scene, a quote and a song that echo it. Over time your scenes collect into a film roll of your life. 🎞️

- Built and shipped solo on iOS
- Firebase + App Check on the backend
- An agentic pipeline creates the weekly social posts and ads, so marketing is automated too 🤖

`Swift` · `Firebase` · `Generative AI`

### 🤖 [SDLC Agent](https://github.com/tiffanychum/sdlc-agent)
*What if a whole dev team were agents?*

Nine agents (PM, Planner, Coder, Reviewer, QA, DevOps, Researcher, Data Analyst, and a Prompt Optimizer that tunes the others' prompts) work together behind an LLM router.

- Orchestration modes: router-decides, sequential, parallel, supervisor and auto
- Human-in-the-loop checkpoints, a RAG pipeline and a visual workflow builder
- DeepEval regression tests on golden datasets, plus prompt-drift detection
- Full OpenTelemetry tracing with a live trace inspector 🔍

`LangGraph` · `MCP` · `FastAPI` · `Next.js`

### 🎯 [DSA Deliberate Play](https://github.com/tiffanychum/DSA_Deliberate_Play)
*Practising data structures and algorithms, but make it a game.*

- Algorithm visualiser with real-time animations synced to the Python code
- Challenges across sorting, graphs, trees, DP, greedy and bitwise
- XP, achievements and progress tracking (and dark mode, obviously 🌙)

`Next.js` · `TypeScript`

---

## 🌱 Open source

I like fixing the tools I actually use.

- **[OpenClaw](https://github.com/openclaw/openclaw)**: merged a fix for Discord messages being silently dropped during gateway reconnects ([#100896](https://github.com/openclaw/openclaw/pull/100896)), plus Slack, memory and UI fixes. My financial agent runs on it, so I'm also a user.
- **[DeepEval](https://github.com/confident-ai/deepeval)**: fixed missing token counts and costs for GPT-5.x in LLM tracing spans, with unit tests ([#2601](https://github.com/confident-ai/deepeval/pull/2601)). I use DeepEval for agent evaluation at work, which is how I found the bug 🐛

---

## 🏢 By day

I'm an AI platform engineer working on enterprise GenAI infrastructure:

- **AI Gateway**: one API to 80+ LLM, embedding and multimodal models, with routing, caching, rate limiting and guardrails
- **Agent Hub**: a low-code platform for building multi-agent teams, with built-in evaluation
- **Agent sandbox**: isolated, ~100ms-to-start environments where agents can run untrusted code safely

---

## 🧰 Tools I reach for

**AI:** LangGraph · LangChain · MCP · DeepEval · RAG · PyTorch fine-tuning
**Languages:** Python · TypeScript · Go · Swift · SQL · Lua
**Build:** React · Next.js · FastAPI · PostgreSQL · Redis · Firebase
**Infra:** Kubernetes · Docker · Terraform · AWS · GCP · Azure

---

## 💬 Ask me about

AI gateways · multi-agent design · LLM evaluation · why my AI stock committee argues with itself

📫 [LinkedIn](https://www.linkedin.com/in/tiffanychum/)

<!-- profile readme -->
