# Playbook: Reseller Arbitrage Loop

Buy low, sell high, repeat. This playbook builds a repeatable arbitrage pipeline: scan marketplaces for mispriced listings, verify the spread, and flip.

## What you get

A weekly (or daily) scan that surfaces products listed below their market value — your buy list, ranked by profit margin.

## Step 1 — Pick your actors

From the [catalog](../catalog/README.md):

- **Arbitrage & deal finders** — actors built specifically to spot pricing gaps
- **Marketplace scrapers** — pull live listings from eBay, Amazon, Craigslist, Facebook Marketplace

Run the same product category across two marketplaces. The gap between them is your opportunity.

## Step 2 — Define your hunting ground

Arbitrage works best in categories you understand. Good starting points:

- **Electronics** — high volume, clear pricing, fast sellers
- **Sneakers & collectibles** — pricing inefficiencies are common
- **Tools & equipment** — local mispricing is rampant on Craigslist/FB Marketplace

Pick one category. Learn its prices cold. The actors give you data; your category knowledge tells you what's actually a deal.

## Step 3 — Scan for spreads

Schedule your marketplace scrapers to pull listings in your category. Compare against sold listings (not asking prices — *sold* prices are the truth). Flag anything listed 30%+ below recent sold comps.

Example: a used DeWalt drill set sells consistently for $180 on eBay. Your scan finds one on Craigslist at $100. That's an $80 gross spread.

## Step 4 — Verify before you buy

The scan finds candidates; you verify:

- **Condition** — photos, description, "tested/working" signals
- **Fees** — eBay takes ~13%, factor shipping both ways
- **Velocity** — how fast do these actually sell? A 50% margin means nothing if it sits for 6 months

## Step 5 — Flip and reinvest

List it where it sells best (usually eBay for reach, FB Marketplace for local/no fees). Bank the profit, feed it back into the next buy. The scan runs on schedule — your pipeline never dries up.

## The math

One $60–$80 flip per week is $3,000–$4,000/year from a pipeline that costs a few dollars a month in actor runs. Chris's own flipping operation runs on exactly this kind of loop.

**[→ Start scanning on Apify](https://apify.com?fpr=p2hrc6)**
