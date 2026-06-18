# eKhaya - Real Estate Deal Finder

> *Stop searching for deals. Start receiving them.*

eKhaya is a real estate deal finder for property investors. It aggregates listing data across three deal types - undervalued properties, high cash-flow rentals, and fix-and-flip opportunities - and scores each property using a proprietary AI model.

## Live demo

👉 **[View live site]([https://Lorrancia.github.io/ekhaya])**

## What's in this repo

```
ekhaya/
├── index.html          # Full interactive concept site
└── README.md           # This file
```

## Features demonstrated

- **AI-ranked deal feed** - scored property cards with 5-second gut-check design
- **Strategy filtering** - High cash-flow / Fix & flip / Undervalued tabs
- **Interactive scoring model** - shift weights by strategy mode
- **Tiered pricing** - Explorer / Investor / Portfolio
- **Real-time alert bar** - score threshold notifications

## The AI scoring model

eKhaya's proprietary model outputs a 0–100 deal score using 5 signals with **shifting weights by strategy**:

| Signal | Cash-flow | Fix & flip | Undervalued |
|---|---|---|---|
| Projected rental yield | 30 pts | 5 pts | 12 pts |
| Neighborhood trajectory | 25 pts | 20 pts | 25 pts |
| Price vs. market value | 20 pts | 28 pts | 35 pts |
| Price reduction history | 15 pts | 12 pts | 20 pts |
| Rehab cost vs. ARV | 10 pts | 35 pts | 8 pts |

## Launch markets

Arizona & California - Phoenix, Tucson, LA, OC, Inland Empire, Bay Area, Sacramento

## Business model

| Tier | Price | Target |
|---|---|---|
| Explorer | $29/mo | Casual investors |
| Investor | $79/mo | Serious investors · 1–5 deals/yr |
| Portfolio | $199/mo | Small funds · 10+ deals/yr |

## Built with

- Vanilla HTML, CSS, JavaScript - no frameworks, no dependencies
- Inter + JetBrains Mono typefaces
- Tabler Icons

## About

Built as a product concept and portfolio piece as part of the AI Fluency Course, using the 4D Framework: **D**escription · **D**iscernment · **D**elegation · **D**iligence.

The name *eKhaya* comes from the Zulu/Xhosa word for "home."

---

*© 2026 eKhaya — Concept*
