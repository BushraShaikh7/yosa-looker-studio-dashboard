# YOSA — Google Ads Performance Dashboard (Looker Studio)

Freelance data analyst project for Youth Orchestras of San Antonio (YOSA), a nonprofit running Google Ad Grant campaigns. Built a live, cloud-hosted Looker Studio dashboard directly on the Google Ads connector, no exports, no manual refresh.

**Live dashboard:** https://datastudio.google.com/s/pYDLNYKIEN0

Looker Studio reports aren't downloadable files, there's nothing to clone or run locally. This repo documents the build: what it shows, what it found, and how it was made.

## What it does

- KPI scorecards (Clicks, Cost, Impressions, CTR, Avg. CPC, Conversions) with period-over-period comparison arrows
- Trend chart comparing current performance against the same period last year
- Campaign, ad group, and keyword-level breakdowns, plus device split analysis
- Two pages: a quick-glance overview, and a deep-dive the client specifically flagged as the most useful section

## Key findings

- Found a campaign with a $500 target cost-per-acquisition actually converting at $0.56, a roughly 300x efficiency gap sitting quietly in the account, not on any chart
- Traced a separate cost spike to rising auction competition, Google's own diagnosis, not a setting on the client's side
- Delivered a written campaign analysis alongside the dashboard, flagging campaigns with zero activity for the client to review

## Tools

Looker Studio · Google Ads · Google Analytics 4 · Data Visualization

## Screenshots

See `/screenshots` for the Overview and Deep Dive pages.
