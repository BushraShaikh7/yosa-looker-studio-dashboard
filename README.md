# YOSA — Google Ads Performance Dashboard (Looker Studio)

Freelance data analyst project for Youth Orchestras of San Antonio (YOSA), a nonprofit running Google Ad Grant campaigns. Built a live, cloud-hosted Looker Studio dashboard directly on the Google Ads connector, no exports, no manual refresh.

**Live dashboard:** https://datastudio.google.com/s/pYDLNYKIEN0

Looker Studio reports aren't downloadable files, there's nothing to clone or run locally. This repo documents the build: what it shows, what it found, and how it was made.

## What it does

- KPI scorecards (Clicks, Cost, Impressions, CTR, Avg. CPC, Conversions) with period-over-period comparison arrows
- Trend chart comparing current performance against the same period last year
- Campaign, ad group, and keyword-level breakdowns, plus device split analysis
- Three pages: a quick-glance overview, a deep-dive the client specifically flagged as the most useful section, and a written conclusion summarising the period's real findings

## Key findings

- Found a campaign with a $500 target cost-per-acquisition actually converting at $0.56, a roughly 300x efficiency gap sitting quietly in the account, not on any chart
- Traced a separate cost spike to rising auction competition, Google's own diagnosis, not a setting on the client's side
- Delivered a written campaign analysis alongside the dashboard, flagging campaigns with zero activity for the client to review

## Tools

Looker Studio · Google Ads · Google Analytics 4 · Data Visualization

## Pages

**[View all 3 pages (PDF)](./YOSA-Dashboard-Pages.pdf)** — Overview, Deep Dive, and Conclusion. GitHub renders this inline, no download needed.
