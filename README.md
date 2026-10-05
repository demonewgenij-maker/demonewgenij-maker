# Hi 👋

**AI Automation & Python Integration Engineer**

My part is the ideas and design, AI's part is the routine code.

I build production automations end-to-end: chat bots, LLM assistants and
agents, workflow automation (n8n), 1C/ERP integrations, e-commerce sites —
and the infrastructure that keeps all of it alive in prod.

### What I do
- 🤖 **Bots & assistants** — Telegram (python-telegram-bot) and custom
  chat-bot platforms; a fleet of production bots for a trading company:
  price-list updaters, restock and order helpers, a contract-drafting bot,
  an accountant's helper, a roofing-materials calculator, an LLM assistant
  that answers questions from 1C data.
- 🧠 **LLM / agents** — RAG, semantic search, multi-provider LLM routing,
  MCP servers (incl. one for 1C), agent workflows — plus what makes them
  shippable: golden-query regression gates, quality scoring, pytest suites.
- 🔗 **Automation & integration** — n8n workflows, REST/API integrations,
  data pipelines (PDF/Excel price-lists → parsing → fuzzy matching →
  loading into 1C), scrapers with anti-bot handling.
- 🛒 **E-commerce / web** — hands-on with a live WordPress + WooCommerce
  store (3.5k products, 12.6k variations): catalog and product pages,
  landing hubs, price/stock sync from 1C, image processing, caching and
  TTFB fixes, Yandex Metrika/Webmaster, SEO hygiene — always via
  reversible steps with backups, never touching the theme.
- ⚙️ **Backend** — Python, FastAPI, SQLite, WebSockets, PWA + web-push.
- 🛠️ **DevOps** — Docker, Traefik/nginx, VPS networking and proxies,
  hot-deploy, watchdogs and scheduled-task supervision, cron/systemd timers.

### Tech
`Python` · `FastAPI` · `python-telegram-bot` · `n8n` ·
`MCP` · `LLM / RAG` · `Docker` · `SQLite` · `WebSocket` · `REST APIs` ·
`WordPress / WooCommerce` · `1C`

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
Running ~15 bots and assistants in production for one trading company
(price-list bots for 8 suppliers, order/restock helpers, contract and
accounting helpers, an LLM assistant over 1C with a regression gate),
an internal team messenger,
a task-manager PWA, and the company's WooCommerce storefront — plus n8n,
monitoring and the infra behind it. The repos here are sanitized,
from-scratch versions of that work.

### Contact
- Telegram: [@JoniBlack05](https://t.me/JoniBlack05)
