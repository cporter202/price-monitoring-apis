<div align="center">

<img src="./assets/hero.png" alt="Price Monitoring APIs — 262 actors to track prices, find deals, and flip smarter" width="100%" />

<br />

# 💰 Price Monitoring APIs

**Never overpay. Flip smarter. Track any product's price across the web — powered by production-ready Apify actors.**

[![GitHub stars](https://img.shields.io/github/stars/cporter202/price-monitoring-apis?style=for-the-badge)](https://github.com/cporter202/price-monitoring-apis/stargazers)
[![Actors](https://img.shields.io/badge/actors-262-22c55e?style=for-the-badge)](catalog/README.md)
[![License](https://img.shields.io/github/license/cporter202/price-monitoring-apis?style=for-the-badge)](LICENSE)

<p>
  <a href="catalog/README.md"><strong>🔍 Browse the Actor Catalog</strong></a> ·
  <a href="#-start-with-a-job-to-be-done"><strong>🚀 Start Building</strong></a> ·
  <a href="https://apify.com?fpr=p2hrc6"><strong>⚡ Try Apify Free</strong></a>
</p>

</div>

## 📖 What this repo is

A focused directory of **262 price-monitoring APIs**: track prices over time, watch competitors, catch price drops the hour they happen, find arbitrage gaps between marketplaces, and build deal alerts that print money. Every actor is a ready-to-run [Apify](https://apify.com?fpr=p2hrc6) worker — no scrapers to build, no blocks to fight.

```mermaid
flowchart LR
    A[🔎 Pick an actor] --> B[⏱️ Schedule it]
    B --> C[📉 Price history builds]
    C --> D[🔔 Alert on drops & gaps]
    style A fill:#22c55e,stroke:#16a34a,color:#fff
    style D fill:#f59e0b,stroke:#d97706,color:#fff
```

The main content of this repository:

- [🔍 Browse the actor catalog](catalog/README.md) — 262 actors across price trackers, competitor intel, arbitrage finders, and marketplace scrapers.

| Coverage snapshot | This directory |
|---|---:|
| 💰 Verified price actors | **262** |
| 🔄 Arbitrage & deal finders | **24** |
| 🛒 Marketplace scrapers | **46** |
| 📊 Competitor price intel | **46** |
| 💸 Price trackers & monitors | **146** |
| Starting cost | **Free tier + pay-per-result** |

## 🎯 Start with a job to be done

| If you need to… | Start here |
|---|---|
| 📉 Track a product's price over time and get drop alerts | [Deal-drop alert playbook](playbooks/deal-drop-alerts.md) |
| 🔄 Find underpriced items to resell for profit | [Reseller arbitrage playbook](playbooks/reseller-arbitrage.md) |
| 📊 Watch what competitors charge and stay priced to win | [Actor catalog](catalog/README.md) → competitor intel |
| 🛒 Pull live prices from Amazon, eBay, Walmart & more | [Actor catalog](catalog/README.md) → marketplace scrapers |

## 🛠️ Common build paths

- **🔔 Deal-drop alerts** — watch products you buy, get pinged the hour the price drops. The [playbook](playbooks/deal-drop-alerts.md) sets it up in under an hour.
- **🔄 Reseller arbitrage** — scan marketplaces for mispriced listings, buy low, sell high. The [arbitrage playbook](playbooks/reseller-arbitrage.md) walks the full loop.
- **📊 Competitor price monitoring** — track rival pricing daily, auto-adjust yours, never lose a sale on price again.
- **💸 Price history dashboards** — build "was $X, now $Y" datasets for content, tools, or internal buying decisions.

## 🌟 Featured actors

| Actor | Why it stands out |
|---|---|
| [Competitor Price Monitor](https://apify.com/nexgendata/competitor-price-monitor?fpr=p2hrc6) | Purpose-built e-commerce price tracking across competitors |
| [Google Shopping Scraper](https://apify.com/nexgendata/google-shopping-scraper?fpr=p2hrc6) | Prices + sellers across Google Shopping in one run |
| [Amazon FBA Product Research](https://apify.com/intelscrape/amazon-fba-product-research?fpr=p2hrc6) | BSR + arbitrage scanning for Amazon sellers |
| [Allegro EAN Price Tracker](https://apify.com/klevio/allegro-ean-price-tracker?fpr=p2hrc6) | Track every seller's price by EAN barcode |

[See all 262 in the catalog →](catalog/README.md)

## ❓ Why price monitoring beats manual checking

Prices move daily. Nobody checks 500 SKUs by hand — and by the time you notice a drop, the deal is gone. Scheduled actors check prices while you sleep, build history you can chart, and fire alerts the moment something moves. At fractions of a cent per check, the ROI is absurd.

<p align="center">
  <a href="https://apify.com?fpr=p2hrc6"><strong>⚡ Get started on Apify (free tier) →</strong></a>
</p>

## 🤝 Contributing

Found a price-monitoring actor that belongs here? Open a PR adding it to `catalog/README.md` with a verified `apify.com` URL and a one-line description. Only actors confirmed live on the Apify Store, please.

## 📢 Disclosure

Links to Apify in this repo include my affiliate code (`fpr=p2hrc6`). You pay exactly the same price — it supports keeping this directory updated and verified.

## 📄 License

MIT — see [LICENSE](LICENSE).
