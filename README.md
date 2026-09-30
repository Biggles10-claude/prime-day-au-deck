# Amazon AU Prime Big Deal Days 2026 — deal board

Claude Artifacts–style interactive board (not a swipe / `100dvh` deck).

**Live:** https://biggles10-claude.github.io/prime-day-au-deck/

## Snapshot
- Event window: 29 Sep–5 Oct 2026
- Buybox postcode: Melbourne **3000**
- Snapshot AWST: **2026-09-30T12:55:51+08:00**
- Candidates 1368 · buybox OK 1351 · **include 454** · exclude 914 · OOS 37 · fail 14
- Include verdicts: ATL 61 · near-ATL 23 · real-discount 361 · insufficient-history 9

## Features
- Filters: status (Include default / Exclude / OOS / All), category, max price, text search, verdict
- Responsive card grid of matching ASINs from the day2 full-scan JSON
- Data embedded in `assets/data.js` (slim fields from `final_deals.json`)

## Source data
Canonical scan: local `prime-full-scan/2026-09-30-am/final_deals.json` + NOTES. This page does not re-scrape Amazon.
