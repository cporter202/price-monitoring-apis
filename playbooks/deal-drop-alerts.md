# Playbook: Deal-Drop Alerts

Stop overpaying. This playbook sets up automated price tracking on the products you buy — and pings you the hour the price drops.

## What you get

Scheduled price checks on any product URL, with a history you can chart and instant alerts when the price falls below your target.

## Step 1 — Pick your actor

From the [catalog](../catalog/README.md):

- **Price trackers & monitors** — purpose-built for watching a product URL over time
- **Marketplace scrapers** — for Amazon, eBay, Walmart, and other store listings

Choose one that supports the site you buy from most.

## Step 2 — Set your watch list

In the Apify Console, paste the product URLs you want to watch into the actor input. Start with 5–10 products while you test. Set a target price for each if the actor supports it.

## Step 3 — Schedule it

Use the actor's **Schedules** feature: daily checks are the sweet spot for most products (hourly for hot deals during sales events). Each run appends the current price to the dataset, building your price history.

## Step 4 — Alert on drops

Point an Apify webhook at a small script, Make.com scenario, or Zapier flow:

- **Price dropped below target** → immediate notification (email, SMS, Slack)
- **Biggest drop this week** → weekly digest so you see trends
- **Back in stock** → for items that sell out

## The math

Say you buy a $300 tool for your business. A 20% drop you catch via alert saves $60 — from a setup that costs pennies per check. Scale that across everything you buy and the alerts pay for themselves hundreds of times over.

**[→ Start tracking on Apify](https://apify.com?fpr=p2hrc6)**
