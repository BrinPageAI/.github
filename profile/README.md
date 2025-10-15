# BrinPage

**BrinPage** builds developer-first AI tooling. Our first product is **CPM (Context Prompt Modules)** — a local-first SDK + dashboard to edit modular prompts, preview results in real time, and control model/temperature/cost using your own provider key (BYOK).

---

## What we do

We focus on practical, production-oriented AI tools:
- **CPM (Context Prompt Modules)** · Local dashboard and SDK for modular, governed prompt context.
- **BirdMind (roadmap)** · Domain-specific model aimed at high-precision tasks (starting with code).

> Note: Our previous project **CGM** has been paused as we focus the company on CPM.

---

## CPM — Context Prompt Modules

**Why CPM**
- **Modular context**: Base Prompt (always-on) + on-demand modules (Style/Tone, Facts, Playbooks, Citations).
- **Live preview**: See the final assembled context before sending.
- **Full control**: Switch model, temperature and options without touching app code.
- **Cost awareness**: Requests and estimated spend visible while you iterate.
- **Local-first (BYOK)**: Your OpenAI key, your environment. Light/Dark UI.

**How it fits**
- Works alongside your existing app/services.
- Keep prompts versionable and consistent across features and teams.
- Reduce token waste by attaching modules only when needed.

---

## Install & Run (under a minute)

```bash
# 1) Add the SDK
npm install @brinpage/cpm
```
```bash
# 2) Link your provider (.env)
OPENAI_API_KEY=sk-...
```
```bash
# 3) Launch the local dashboard
npx brinpage cpm
# then open http://localhost:3027
```

---

## Links

Website: https://brinpage.com

Docs: https://docs.brinpage.com

X / instagram : @brinpageai
