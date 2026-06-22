# Hi 👋

**AI Automation & Python Integration Engineer**

I build production automations end-to-end: Telegram/chat bots, workflow
automation (n8n), LLM-powered assistants (RAG, agents), system integrations
and the infrastructure to run them — then ship and keep them alive in prod.

### What I do
- 🤖 **Bots & assistants** — Telegram (python-telegram-bot) and custom chat-bot
  platforms; from one-off helpers to multi-feature production bots with
  inline menus, drill-down flows and watchdog-based reliability.
- 🔗 **Automation & integration** — n8n workflows, REST/API integrations,
  data pipelines (PDF/Excel parsing → matching → loading into business systems).
- 🧠 **LLM / AI** — RAG, semantic search, multi-provider LLM routing,
  agentic workflows.
- ⚙️ **Backend** — Python, FastAPI, SQLite, WebSockets, PWA + web-push.
- 🛠️ **DevOps** — Docker, reverse proxies, hot-deploy, networking,
  scheduled-task / service supervision.

### Tech
`Python` · `FastAPI` · `python-telegram-bot` · `n8n` · `Docker` ·
`SQLite` · `WebSocket` · `LLM / RAG` · `REST APIs`

### Projects
- **[telegram-bot-boilerplate](https://github.com/demonewgenij-maker/telegram-bot-boilerplate)** —
  production-minded python-telegram-bot (v21) starter: clean handler layout,
  drill-down inline menus, env-only config, a heartbeat/`/health` watchdog
  endpoint and a pytest suite. A sanitized distillation of patterns from many
  bots I've shipped.
- **[onec-price-updater](https://github.com/demonewgenij-maker/onec-price-updater)** —
  toolkit for updating **1C / 1Enterprise** nomenclature prices from supplier
  price-lists: CSV parser → Jaccard matcher with ambiguity detection → diff
  report → retrying 1C HTTP client. Dry-run by default, 33 passing tests.
- **[realtime-team-chat](https://github.com/demonewgenij-maker/realtime-team-chat)** —
  compact realtime team chat (mini Slack/Telegram): FastAPI + WebSocket hub +
  SQLite + JWT auth, with a vanilla-JS PWA frontend. Parameterized SQL,
  XSS-safe rendering, 18 tests including real WebSocket delivery.

### Currently
Growing this portfolio with more sanitized, from-scratch projects (an LLM/RAG
assistant, an n8n custom node) that mirror real production work.
