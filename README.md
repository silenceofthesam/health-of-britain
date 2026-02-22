# ⬡ Health of Britain — Economic & Social Intelligence Dashboard

A self-contained, interactive dashboard tracking the economic, social, and political condition of the United Kingdom. Built as a single HTML file with Bloomberg terminal aesthetics, it provides at-a-glance readings across 47+ indicators with expandable trend analysis.

**[View Live Dashboard →](https://silenceofthesam.github.io/health-of-britain/)**

---

## What It Covers

The dashboard is organised across seven tabs:

- **Overview** — headline snapshot: CPI, unemployment, GDP, gilt yields, net migration, public debt
- **Economic** — inflation metrics, interest rates, mortgage rates, lending composition
- **Consumer Health** — GfK confidence, insolvencies, arrears, household debt, credit borrowing
- **Fiscal & Trade** — public borrowing, tax receipts, trade balance, current account deficit
- **Social** — NEET rates, youth unemployment, economic inactivity, mental health waiting lists
- **Politics** — polling averages, approval ratings, regional breakdown, top public concerns
- **Demographics** — population, birth rate, pension dependency, worker-to-pensioner ratio

---

## Features

- **Interactive indicator cards** — click any card to expand a full trend panel with 2Y, 5Y, and 10Y historical views
- **Live data** — CPI, unemployment, and GDP pull directly from the ONS API on page load
- **Static fallbacks** — all other indicators use manually curated figures, updated monthly
- **Fully self-contained** — one HTML file, no backend, no dependencies beyond a CDN-loaded Chart.js

---

## Updating

This dashboard is refreshed monthly with the latest official figures. Each update is committed here and the live URL reflects the new data automatically.

**Data sources include:** ONS, Bank of England, Insolvency Service, GfK, Electoral Calculus, YouGov MRP

---

## Monthly Update Process

1. Review latest releases from ONS, BoE, and other sources
2. Generate updated `index.html` with revised figures
3. Upload and commit to this repository — the live URL updates within minutes

---

## Technical Notes

- Built with vanilla HTML, CSS, and JavaScript
- Charts rendered via [Chart.js](https://www.chartjs.org/)
- Fonts: IBM Plex Mono & IBM Plex Sans (Google Fonts)
- No build process, no framework, no server required

---

*For questions or corrections, open an issue on this repository.*
