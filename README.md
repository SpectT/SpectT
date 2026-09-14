# Dmytro

**Systems & AI Automation Engineer** specializing in agentic workflows, Model Context Protocol (MCP) integrations, and production full-stack automation.

I design and deploy resilient multi-agent software pipelines, backend data synchronizations, and internal tooling. My focus is on deterministic execution: combining autonomous LLM agents with automated verification gates, strict test suites, and robust cloud infrastructure.

---

## Technical Expertise

* **Agentic AI & Orchestration:** Multi-agent pipeline design (Orchestrator / Architect / Worker / Critic), custom lifecycle hooks, Model Context Protocol (MCP) servers (Database, Browser, File System, CMS), agent state machines, persistent memory stores, code graph indexing (Graphify).
* **Engineering & Quality Assurance:** Automated pre-commit/pre-merge verification gates, deterministic testing, anti-hallucination guardrails, headless rendering validation, pixel-delta and perceptual hash verification.
* **Full-Stack & Cloud:** TypeScript, Python, Node.js, PowerShell, Bash, SQL. Next.js, Webflow, Vercel, Railway, Supabase (PostgreSQL), SQLite, Git (isolated worktrees).
* **Integrations & Data Ingestion:** Telegram Bot API, Google Workspace / Sheets APIs, RESTful webhooks, idempotency control, distributed job queues.
* **Media & Specialized Pipelines:** High-precision automated PDF pre-flight (DeviceRGB, 100% K vector separation for digital print embellishments), neural image upscaling (OpenCV EDSR), automated media transcoding (FFmpeg).

---

## Selected Systems & Case Studies

### 1. Multi-Agent Development Pipeline & Quality Gate Harness
* **Challenge:** LLM-driven coding pipelines frequently degrade codebases by declaring tasks complete without running tests, introducing regressions, or getting trapped in circular critic loops.
* **Solution:** Engineered an orchestrator-first multi-agent development template with dedicated role definitions (Orchestrator, Architect, Worker, Critic). Implemented native runtime hooks (`Stop` / `SubagentStop`) that intercept execution and programmatically block task completion unless machine-readable test artifacts and review verdicts are present. Built circuit breakers to enforce materiality thresholds on critic feedback.
* **Stack:** Node.js, Shell / PowerShell, Git Worktrees, Codex CLI, Custom Execution Hooks.

### 2. Field Service Platform & Idempotent Lead Intake Pipeline
* **Challenge:** High bounce rates on complex forms, duplicate lead submissions, and data loss during CRM/messaging outages for a multi-page local services platform.
* **Solution:** Designed and deployed an accessible, low-friction static frontend paired with a fault-tolerant intake pipeline. Implemented idempotent lead hashing to suppress duplicate submissions, integrated automatic failover and state recovery for blob storage errors, and synchronized real-time routing across Google Sheets and Telegram operator channels. Audited live SEO headers, canonical routing, and sitemap indexing via Google Search Console.
* **Stack:** TypeScript, Node.js, Vercel, Google Sheets API, Telegram Bot API, Technical SEO.

### 3. High-Throughput Vehicle Catalog & Headless CMS Synchronization
* **Challenge:** Managing real-time transit status updates across a multi-thousand vehicle inventory, mitigating third-party API rate limits (HTTP 403/429), and eliminating high-latency embeds on customer-facing pages.
* **Solution:** Built a headless data synchronization pipeline using custom MCP connectors to automate CMS collection updates. Standardized database schema migrations via Prisma on Railway, added defensive API retry workers with exponential backoff, and re-architected frontend media delivery to defer video embeds, reducing initial page payload and eliminating render-blocking network requests.
* **Stack:** Python, TypeScript, Prisma, PostgreSQL, Railway, Webflow MCP, REST APIs.

### 4. Multi-Channel Social Operations & Triage Console
* **Challenge:** Handling inbound customer inquiries across 6+ accounts (Meta & Telegram) across multiple organizations without risking unauthorized or hallucinated automated replies.
* **Solution:** Architected a self-hosted unified inbox system for multi-tenant customer communication. Automated inbound message ingestion, intent classification, sentiment analysis, and queue prioritization, while enforcing a mandatory Human-in-the-Loop approval gate for all outbound communications and publication actions.
* **Stack:** Node.js, Python, PostgreSQL, Meta Graph API, Telegram Bot API, Docker.

### 5. Algorithmic Futures Paper-Trading & Risk Engine
* **Challenge:** Automating paper trading execution with strict risk management, dynamic position sizing, and low-latency market data processing.
* **Solution:** Developed an algorithmic trading bot for USDT perpetual futures. Implemented market data ingestion, WebSocket connection watchdogs, position state machines, trailing stop algorithms, and simulated execution accounting for slippage and exchange fees.
* **Stack:** Python, WebSockets, REST APIs, Pandas, Asynchronous Event Loop.

### 6. Automated Pre-Press & Media Processing Pipelines
* **Challenge:** Preparing enterprise-grade visual assets and print collateral requiring micro-tolerances (0.25 mm) for digital spot varnish and foil embellishment presses without manual rework.
* **Solution:** Authored automated validation scripts to split source layouts into two-page DeviceRGB print PDFs and separate 100% K vector spot masks. Automated pre-flight checks for page geometry, color spaces, and bleed clearances. Built batch image enhancement pipelines using neural super-resolution (OpenCV EDSR) with pixel-delta validation to ensure zero unintended generative artifacts.
* **Stack:** Python (pypdf, ReportLab, OpenCV), PowerShell (System.Drawing), FFmpeg.

---

## Contact & Profiles

* **GitHub:** [github.com/SpectT](https://github.com/SpectT)
* **LinkedIn:** [linkedin.com/in/dmytro-prykhodko-279057173](https://www.linkedin.com/in/dmytro-prykhodko-279057173/)
* **Telegram:** [@fred2331](https://t.me/fred2331)
* **Email:** [spectt23@gmail.com](mailto:spectt23@gmail.com)
