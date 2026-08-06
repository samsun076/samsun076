# Hey, I'm Dave 👋

I build automation systems for businesses that run on paperwork, plus a handful of products of my own. Most of it ships private — the contribution graph is real, the source just isn't public.

🌐 **Portfolio:** [dmarcinowski.com](https://dmarcinowski.com) &nbsp;·&nbsp; ⚙️ **Shop:** [automagic.ly](https://automagic.ly)

<img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,astro,python,sqlite,supabase,cloudflare,docker" alt="TypeScript, React, Next.js, Tailwind, Astro, Python, SQLite, Supabase, Cloudflare, Docker" height="36" />

## 🚢 In production

### 🧾 Invoice automation platform · client work · in production since Feb 2026

Runs a telecom-heavy client's monthly invoicing end to end. 33 carrier accounts, 25 of them retrieved unattended — some by driving the carrier's portal, some by reimplementing its login in plain HTTP, some pulled straight out of an inbox, because no two carriers deliver the same way. 22 extractor formats normalize the bills, split charges across cost centers, and generate the branded cover sheet every invoice needs — roughly 30 a month that used to be assembled by hand at 5–10 minutes apiece. Finished packets submit themselves back into the customer's AP intake system. `Python · FastAPI · SQLite · Playwright · React · Fly.io`

### ⏱️ ChiroTracker · client work · in production since Feb 2026

QR-badge time clock that replaced paper timesheets at a small clinic — kiosk clock-in, employee management, hours dashboard. Built offline-tolerant as a PWA so a dropped connection never costs someone their punch.

### 🤖 [ai-portfolio-dm](https://dmarcinowski.com) · live

Paste a job description, get an honest fit verdict — including "probably not." A portfolio that lets employers interrogate the candidate instead of skimming a PDF. `Next.js · Supabase · Claude API`

## 🔨 Building now

### 🏃 Debrief · solo build · in daily use since Jul 2026

Training-analysis app for runners — the watch records, this is where you sit down and think about it. **Local-first on purpose: no accounts, no servers, no subscription.** Your training history is a SQLite file on your own machine, synced outbound-only under your own API credentials — the inverse of every major platform in the category, each of which holds your data and rents you access to it. Two-way MCP integration then lets Claude or GPT read that history and write back tailored workouts and load warnings, instead of giving advice against no data. Approved on the **Suunto API partner program**. `Electron · SQLite · MCP` — [debrief.run](https://debrief.run)

### 🎯 Seedmark · [FILL: status]

Shows a high-school distance runner where their times actually stand against college recruiting benchmarks, tracked over a multi-year horizon. The benchmark math is deterministic and tested, and grades against an expected age curve — so normal development never reads as failure. Runs on 📚 **RunDB**, a data engine with per-record provenance: every source passes policy review before a single fetch, and the audit trail is committed alongside the code.

### ⚙️ Automagic.ly

The shop. Practical AI-assisted process automation for businesses that run on paperwork. Next site ships with a proof-ledger content model — every marketing claim carries its source, method, and caveat before it goes live.

## 🧪 Also exploring

**local-AI** — an M4 Pro running Qwen3-Coder on MLX behind an outbound relay, giving a community a 24/7 agent at zero marginal cost per token. &nbsp;·&nbsp; **theDBSample** — provenance-tracked research database for collegiate track & XC results; ships the pipeline, never the data. &nbsp;·&nbsp; **Memex** — an LLM-maintained knowledge base holding only what a model can't look up.

## 📊 Stats

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=samsun076&theme=github-dark-blue&hide_border=true">
  <img src="https://streak-stats.demolab.com?user=samsun076&hide_border=true" alt="Contribution streak" height="165">
</picture>

---

<sub>Active work is private for now — ask me about it.</sub>
