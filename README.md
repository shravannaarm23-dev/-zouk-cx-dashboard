# Zouk — Customer Intelligence Dashboard

**[View the live dashboard →](https://shravannaarm23-dev.github.io/-zouk-cx-dashboard/)**

An analyst-style teardown of 98 Google Play reviews for [Zouk](https://zouk.co.in), an Indian D2C vegan-leather bags brand, built to surface where the business is actually losing customers versus where it isn't.

## Headline finding

Reviews split almost exactly 50/50 positive–negative — but the split moved fast, from ~39% negative (Dec 2025–Mar 2026) to ~63% negative (Apr–Jun 2026). The product isn't the problem: quality and craftsmanship are the most-praised, most-upvoted themes in the data. What's breaking is everything after checkout — and support responsiveness, not delivery delay itself, is the single most common factor behind negative reviews.

## What's inside

- **Overview** — sentiment trend by month, headline stats, strategic context
- **Issue Breakdown** — every complaint category ranked by frequency, positive themes vs. negative
- **Voice of Customer** — all 98 reviews, paraphrased, tagged, filterable, sorted by helpfulness
- **Recommendations** — five fixes ranked by evidence weight, each tied back to specific reviews

## Method

All 98 reviews are real, sourced from Zouk's public Google Play listing (Dec 2025–Jun 2026) — nothing here is synthetic. Each was read and tagged by sentiment and issue category, then aggregated into the breakdowns and trend lines the dashboard computes live from that dataset.

Built as a single self-contained HTML file — no build step, no external dependencies beyond two Google Fonts.
