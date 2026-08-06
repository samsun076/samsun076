# Hey, I'm Dave 👋

I build automation systems for businesses that run on paperwork, plus a handful of products of my own — usually the ones I got tired of waiting for someone else to build. I'm opinionated about the software I use, and most of what's below started as something that bugged me.

Most of it ships private — the contribution graph is real, the source just isn't public.

> **How I build:** deterministic core first — tested extraction, tested math, repeatable output — then non-deterministic workflows layered on top, only where judgment actually helps. The model goes at the edges, never in the critical path.

🌐 **Portfolio:** [dmarcinowski.com](https://dmarcinowski.com) &nbsp;·&nbsp; ⚙️ **Shop:** [automagic.ly](https://automagic.ly)

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,astro,python,sqlite,supabase,cloudflare,docker" alt="TypeScript, React, Next.js, Tailwind, Astro, Python, SQLite, Supabase, Cloudflare, Docker" height="36" />

## 🚢 In production

### 🧾 Invoice automation platform
**Client work · live since Feb 2026**

Monthly telecom invoicing for a telecom-heavy client, end to end.

- **33 carrier accounts, 22 retrieved unattended** — portal automation, reimplemented HTTP logins, or straight out of an inbox, because no two carriers deliver the same way
- **22 extractor formats** normalize the bills and split charges across cost centers
- Cover sheets, monthly reporting, and submission back into the customer's AP intake system — **all of it automatic**
- Retries know the difference between **a failed download and a carrier that just hasn't posted the bill yet** — different problems, different escalation
- Downloading, coding, cover sheets, review: **the old way took about 20 hours a month**

`Python · FastAPI · SQLite · Playwright · React · Fly.io`

### ⏱️ ChiroTracker
**Client work · live since Feb 2026**

QR-badge time clock that replaced paper timesheets at a small clinic — kiosk clock-in, employee management, hours dashboard. Offline-tolerant PWA, so a dropped connection never costs someone their punch.

### 🤖 ai-portfolio-dm
**Live**

Paste a job description, get an honest fit verdict — including "probably not." Lets employers interrogate the candidate instead of skimming a PDF.

`Next.js · Supabase · Claude API` — [dmarcinowski.com](https://dmarcinowski.com)

## 🔨 Building now

### 🏃 Debrief
**Solo build · private beta · in daily use since Jul 2026**

Training analysis for runners — the dashboard that talks back. The watch records; this is where you sit down and think about it. No kudos, no feed, no post-run dopamine.

- **A coach that already knows you** — two-way MCP puts your whole training history in the room at the start of every conversation. No screenshots, nothing re-explained, no starting over. Its decisions land straight back on the dashboard
- **Local-first on purpose** — no accounts, no servers, no subscription. Your training history is a SQLite file on your own machine, synced outbound-only under your own credentials
- **Runs on the AI you already pay for**, not a second subscription
- Approved on the **Suunto API partner program**

`Electron · SQLite · MCP` — [debrief.run](https://debrief.run)

### 🍽️ MyMacros
**Open source · in development**

Photograph a meal, get the macros. Most trackers make you log a workout to earn calories back — this one already knows what you ran.

- **Model at the edge, math at the core** — Sonnet 5 vision estimates macros from a photo; the daily budget is deterministic, computed against real training load
- Run data arrives through **Debrief's** Suunto pipeline, weight from a Garmin Index scale — the two are built to meet
- **The one public repo here** — everything else on this profile is closed

`React · Hono · Cloudflare Workers · D1 · R2 · TypeScript` — [github.com/samsun076/MyMacros](https://github.com/samsun076/MyMacros)

### 🎯 Seedmark
**In development**

Shows a high-school distance runner where their times actually stand against college recruiting benchmarks, tracked over a multi-year horizon.

- Benchmark math is deterministic and tested, graded against an **expected age curve** — so normal development never reads as failure
- Runs on 📚 **RunDB**, a data engine with per-record provenance: every source passes policy review before a single fetch, and the audit trail is committed alongside the code

### ⚙️ Automagic.ly
**Landing page live · v2 in progress**

The shop — practical AI-assisted process automation for businesses that run on paperwork. The v2 site ships with a proof-ledger content model: every marketing claim carries its source, method, and caveat before it goes live.

## 🧪 Also exploring

- 🖥️ **local-AI** — an M4 Pro running Qwen3-Coder on MLX behind an outbound relay, giving a community a 24/7 agent at **zero marginal cost per token**
- 🗃️ **theDBSample** — provenance-tracked research database for collegiate track & XC results; ships the pipeline, never the data
- 🧠 **Memex** — an LLM-maintained knowledge base holding only what a model can't look up: decisions with their reasoning, project context, hard-won gotchas

## 📊 Stats

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=samsun076&theme=github-dark-blue&hide_border=true">
  <img src="https://streak-stats.demolab.com?user=samsun076&hide_border=true" alt="Contribution streak" height="165">
</picture>

---

<sub>Active work is private for now — ask me about it.</sub>
