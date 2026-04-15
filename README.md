# Denver RE:Intel

**Real estate intelligence for Denver's bifurcating market.**

A single-file, no-backend HTML tool for analyzing Denver real estate across five dimensions: view zone scoring, market tier analysis, AI wealth demand signals, developer feasibility, and a 2030–2045 future disruption forecast.

---

## What It Does

The Denver market has permanently split into three tiers moving in opposite directions simultaneously. This tool helps buyers, sellers, investors, and developers understand which side of that divide they're operating on — and what's coming next.

### Five Panels

**01 — Zone Finder**
Six Denver-area zones scored across mountain views, city proximity, walkability, school quality, investment upside, and AI demand signal. Priority sliders rerank zones in real time. Budget filter and expandable zone cards with Redfin search links.

**02 — Market Tiers**
The structural three-tier analysis: Tier 1 (luxury/$1.5M+, cash buyer, AI wealth driven), Tier 2 (middle market/$500K–$1.5M, the danger zone), Tier 3 (under $500K, institutional capture). Full neighborhood table with momentum scores, AI demand rating, and risk assessment for 10 Denver neighborhoods.

**03 — AI Wealth Map**
How AI is simultaneously creating overnight millionaires and eliminating the entry-level jobs that sustain middle-market buying power. Demand concentration by neighborhood, displacement paradox analysis, and the new buyer archetypes reshaping pricing.

**04 — Build or Buy**
Developer feasibility calculator. Input zone, project type, square footage, finish level, and land cost — get full construction cost breakdown, resale ceiling, margin analysis, and a go/caution/no verdict with buyer tier assessment.

**05 — Future Layer**
2030–2045 demand forecast across five disruption forces:
- 🚗 Autonomous vehicles and commute-distance decoupling
- 🚁 eVTOL vertiport infrastructure
- 👥 The $84 trillion Great Wealth Transfer
- 🌡 Climate migration and Denver's altitude premium
- 🏫 AI disruption of school district pricing premiums

Filterable timeline, hidden gem zone cards, and a full scenario matrix.

**Vista AI Assistant**
Rule-based market intelligence assistant with deep context on all five panels. No API key required. Answers questions about neighborhoods, market dynamics, feasibility, and future disruption forces.

---

## Technical Details

- **Single HTML file** — no build step, no dependencies, no backend
- **No API keys required** — fully self-contained
- **~108KB** — loads instantly
- Works in any modern browser (Chrome, Safari, Firefox, Edge)
- Mobile responsive
- Map links open Redfin search pages in a new tab

---

## Data Sources

Market data, pricing, and trend analysis sourced from:
- Denver MLS / REColorado
- Redfin market reports
- Zillow Research
- Atlanta Fed Housing Affordability Monitor (HOAM)
- Sotheby's International Realty Luxury Outlook 2025
- Stanford AI Displacement Research 2025
- Redfin Economics wealth concentration report
- Denver Community Planning and Development

**Data current as of April 2026.** Future layer projections are analytical forecasts, not financial advice.

---

## Adding Live AI (Optional — Future Upgrade)

The tool is architected for a single-function upgrade to live Claude AI via the Anthropic API. When ready:

1. Get an API key at [console.anthropic.com](https://console.anthropic.com)
2. In `index.html`, locate the `getVistaResponse()` function
3. Replace the rule-based response logic with an Anthropic API call using `claude-sonnet-4-6`
4. Vista will then have live web search, current listing data, and real-time market intelligence

---

## Zones Covered

| Zone | Highlights |
|---|---|
| Cherry Creek North | Primary AI wealth target, walk score 95+, cash buyer dominant |
| LoHi / Highland | Urban lifestyle, Highland Bridge, ceiling forming at $2M+ |
| Sunnyside | 5–10yr play, G-Line RTD, Highlands-adjacent value |
| Foothills Corridor | Best mountain views, AV corridor thesis, eVTOL potential |
| Washington Park | Deepest family buyer pool, top schools, stable appreciation |
| RiNo / Five Points | Fastest price growth, tech-culture buyer, creative identity |

---

## Disclaimer

This tool is for informational and analytical purposes only. It does not constitute financial, investment, or real estate advice. Always work with a licensed Colorado real estate professional. Market data and projections are estimates based on publicly available information and may not reflect current conditions.

---

*Built with the belief that understanding structural market forces — not just comps — is what separates good real estate decisions from lucky ones.*
