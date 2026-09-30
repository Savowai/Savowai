## Adam Sebhat

Data Science graduate (University of Washington, 2025) building AI-powered web products —
mostly Next.js and TypeScript, with Claude doing the parts that used to need a person.

Currently doing applied AI and automation work through my own practice, plus freelance
engagements. Open to engineering roles. Los Angeles, CA.

### Selected work

**[flock-demographics-analysis](https://github.com/Savowai/flock-demographics-analysis)** —
([live](https://flock-demographics-analysis.vercel.app)) an end-to-end geospatial study of whether
3,025 Flock license plate readers across LA County and King County track neighbourhood
demographics. Python scripts collect Census ACS, TIGER/Line, OpenStreetMap and LAPD / Seattle PD
crime data; GeoPandas handles the spatial joins in state-plane projections; statsmodels fits
negative binomial models with a road-mile offset, checked with Moran's I, a spatial lag model and
block-group robustness runs.

A RAG pipeline covers the policy record: 42 statutes, agency policies and audits chunked into
1,125 passages, embedded with sentence-transformers (all-MiniLM-L6-v2) and indexed in ChromaDB,
answering only from retrieved passages with the source cited. The Next.js site runs entirely in
the browser (DuckDB-WASM for the data, Transformers.js over int8-quantised vectors for search), so
it needs no server or API key.

**[savowai-app](https://github.com/Savowai/savowai-app)** — an approval-gated AI operations
platform. Four role-based agents coordinate lead discovery, business research, outreach prep, and
site builds across a 10-stage workflow, with a human reviewing every stage before anything
executes. Next.js 16, React 19, Claude API, Airtable, NextAuth, Vercel cron.

The hard part wasn't calling an LLM — it was deciding what happens when one fails. Incomplete
generations are rejected rather than saved, because a half-built page sent to a real business is
worse than no page at all.

**[claude-automation-portfolio](https://github.com/Savowai/claude-automation-portfolio)** — the
agents, scheduled tasks, custom skills and MCP connectors I run on my own work with Claude Code,
the Claude API and Cowork: a daily job-search pipeline, an Airtable base that serves as memory for
every session, a morning brief and more. Each case study covers how the system is wired, what
failed, and the rule added so it doesn't fail the same way twice.

**[xr-football](https://github.com/Savowai/xr-football)** —
([live](https://xrphilosophy.vercel.app)) Premier League analytics. A Python pipeline pulls 380
fixtures from the ESPN API, computes exponentially weighted form and matchup-aware xG, and outputs
Poisson scorelines, W/D/L probabilities, and expected points. Automated data refresh via GitHub
Actions.

**[medlink-transport](https://github.com/Savowai/medlink-transport)** — booking and information
site for a non-emergency medical transportation service in King & Snohomish County, WA. Built
around wheelchair accessibility and patients who schedule by phone.

**[savowai-website](https://github.com/Savowai/savowai-website)** — studio marketing site.
Next.js 16, Framer Motion, Airtable intake.

### Client work

Two engagements for Somuleco AI via Upwork: a security audit of an Angular application with
prioritized remediation guidance, and a Firebase Authentication integration with restructured
navigation for a SwiftUI app.

### Education

**University of Washington** — BS, Data Science (2023–2025)
**South Seattle College** — AA, Business (2020–2022)

### Tools

Python · TypeScript · JavaScript · SQL · Next.js · React · Node · Tailwind · Claude API ·
Airtable · Firebase · Vercel · GitHub Actions · scikit-learn

### Certifications

- [Claude with the Anthropic API](claude-with-the-anthropic-api-anthropic.pdf) — Anthropic (Aug 2026)
- [Teaching the AI Fluency Framework](teaching-the-ai-fluency-framework-anthropic.pdf) — Anthropic (Sep 2026)
- [AI Fluency for Small Businesses](ai-fluency-for-small-businesses-anthropic-paypal.pdf) — Anthropic & PayPal (Aug 2026)

**Portfolio:** [adamsebhatportfolio.vercel.app](https://adamsebhatportfolio.vercel.app) ·
**Email:** asebjunior@gmail.com
