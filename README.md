# AI FinOps Control Tower

Interactive dashboard for enterprise AI token consumption, USD cost, and user demand across 6 cost centers.

**Live dashboard:** [https://raw.githack.com/mm-bovespa/ai-finops-control-tower/main/index.html](https://raw.githack.com/mm-bovespa/ai-finops-control-tower/main/index.html)

Alternative preview: [jsDelivr](https://cdn.jsdelivr.net/gh/mm-bovespa/ai-finops-control-tower@main/index.html)

## Period
- Actuals: May 2026 – September 2026
- Forecast: October 2026 – February 2027
- Last updated: 11 Sep 2026

## Stack
Single-file HTML. Tailwind CDN + Chart.js. Vanilla JS. Mock data lives in the `DATA` object at the top of the script so it can be swapped for an API later.

## GitHub Pages
If Actions is allowed on this account, the workflow in `.github/workflows/pages.yml` publishes the same `index.html` to GitHub Pages.
