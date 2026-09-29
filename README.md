## Adam Sebhat

Data Science graduate (University of Washington, 2025) building AI-powered web products —
mostly Next.js and TypeScript, with Claude doing the parts that used to need a person.

Currently doing applied AI and automation work through my own practice, plus freelance
engagements. Open to engineering roles. Los Angeles, CA.

### Selected work

**[flock-demographics-analysis](https://github.com/Savowai/flock-demographics-analysis)** —
([live](https://flock-demographics-analysis.vercel.app)) does surveillance camera placement track
neighbourhood demographics? 3,025 Flock license plate readers mapped against census tracts in LA
County and King County, controlling for arterial road density, population, income and reported
crime. Negative binomial models with a road-mile offset, Moran's I and a spatial lag model for the
clustering, block-group robustness checks. Python, GeoPandas, DuckDB, statsmodels; the site is
Next.js with DuckDB-WASM and a 42-document retrieval layer running entirely in the browser.

The two counties produced opposite signs, so the result that replicated is the retailer one: Home
Depot and Lowe's carry roughly five times the odds of a nearby camera they don't operate, versus
matched big-box retailers. Several explanations fit it and the data doesn't separate them, which
the report says plainly. The camera data is crowdsourced and incomplete, and that constraint leads
the write-up rather than sitting in a footnote.

**[savowai-app](https://github.com/Savowai/savowai-app)** — an approval-gated AI operations
platform. Four role-based agents coordinate lead discovery, business research, outreach prep, and
site builds across a 10-stage workflow, with a human reviewing every stage before anything
executes. Next.js 16, React 19, Claude API, Airtable, NextAuth, Vercel cron.

The hard part wasn't calling an LLM — it was deciding what happens when one fails. Incomplete
generations are rejected rather than saved, because a half-built page sent to a real business is
worse than no page at all.

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

### Also

Completed [*AI Fluency for Small Businesses*](ai-fluency-for-small-businesses-anthropic-paypal.pdf)
(Anthropic & PayPal).

Reach me at **asebjunior@gmail.com**.
