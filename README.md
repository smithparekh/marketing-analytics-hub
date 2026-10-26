# 📊 Marketing Analytics Hub

An interactive, self-contained marketing analytics reference dashboard built for Data Analysts working in growth, e-commerce, and D2C marketing roles.

**Live Demo →** [smithparekh.github.io/marketing-analytics-hub](https://smithparekh.github.io/marketing-analytics-hub)

---

## What This Covers

This dashboard is a single-file HTML reference tool covering every major marketing metric a Data Analyst needs to know — with formulas, worked examples in ₹, industry benchmarks, and a full glossary of 45+ terms.

---

## Metric Categories

### 🎯 Acquisition
How efficiently you bring in new users and traffic.

| Metric | Formula | What It Tells You |
|--------|---------|-------------------|
| **CAC** (Customer Acquisition Cost) | Total Spend ÷ New Customers | Cost to acquire one paying customer |
| **CPC** (Cost Per Click) | Ad Spend ÷ Total Clicks | Cost of each visit from paid ads |
| **CPM** (Cost Per Mille) | (Spend ÷ Impressions) × 1000 | Cost of reaching 1,000 people |
| **CTR** (Click-Through Rate) | Clicks ÷ Impressions × 100 | How compelling your ad creative is |
| **CPL** (Cost Per Lead) | Spend ÷ Leads Generated | Cost of each prospect before purchase |
| **TOFU/MOFU/BOFU** | — | Funnel stage classification (Top/Mid/Bottom) |

---

### 💰 Revenue & ROI
How marketing spend translates to money made.

| Metric | Formula | What It Tells You |
|--------|---------|-------------------|
| **ROAS** (Return on Ad Spend) | Revenue ÷ Ad Spend | ₹ earned per ₹ spent on ads |
| **ROI** (Return on Investment) | Net Profit ÷ Cost × 100 | True profitability after all costs |
| **LTV / CLV** (Lifetime Value) | AOV × Frequency × Lifespan | Total value of a customer relationship |
| **MER** (Marketing Efficiency Ratio) | Total Revenue ÷ Total Spend | Blended ROAS across all channels |
| **AOV** (Average Order Value) | Revenue ÷ Orders | Average transaction size |
| **Contribution Margin** | Revenue − Variable Costs | What's left after direct costs |
| **Payback Period** | CAC ÷ Monthly Gross Margin | Months to recover acquisition cost |

---

### 🔄 Conversion
How well you turn visitors into buyers.

| Metric | Formula | What It Tells You |
|--------|---------|-------------------|
| **CVR** (Conversion Rate) | Conversions ÷ Visitors × 100 | % of visitors completing the goal |
| **Bounce Rate** | Single-page Sessions ÷ All × 100 | % who leave without interacting |
| **Cart Abandonment Rate** | 1 − (Purchases ÷ Cart Adds) × 100 | % who add to cart but don't buy |
| **Funnel Drop-off** | (Stage N − Stage N+1) ÷ Stage N | Loss at each funnel step |
| **RPCV** | Revenue ÷ Converting Visitors | Revenue per buyer |
| **Time to Convert** | Avg(Purchase Date − First Visit) | Days from discovery to first purchase |

---

### 🔒 Retention
How well you keep the customers you acquire.

| Metric | Formula | What It Tells You |
|--------|---------|-------------------|
| **Churn Rate** | Lost ÷ Start Customers × 100 | % customers lost in a period |
| **Retention Rate** | (End − New) ÷ Start × 100 | % customers still active |
| **NPS** (Net Promoter Score) | % Promoters − % Detractors | Customer loyalty index (−100 to +100) |
| **CSAT** | Satisfied ÷ Total Responses × 100 | Post-interaction satisfaction |
| **RPR** (Repeat Purchase Rate) | Repeat Buyers ÷ Total Buyers × 100 | Brand loyalty in e-commerce |
| **Win-back Rate** | Reactivated ÷ Lapsed Targeted × 100 | Success of re-engagement campaigns |

---

### 💡 Engagement
How users interact with your product and content.

| Metric | Formula | What It Tells You |
|--------|---------|-------------------|
| **DAU/MAU Stickiness** | DAU ÷ MAU × 100 | Daily habit strength |
| **Session Duration** | Total Time ÷ Total Sessions | Depth of engagement per visit |
| **Pages per Session** | Pageviews ÷ Sessions | Browsing depth |
| **Social ER** | (Likes+Comments+Shares) ÷ Impressions × 100 | Content interaction quality |
| **Email Open Rate** | Opens ÷ Delivered × 100 | Subject line effectiveness |
| **CTOR** (Click-to-Open Rate) | Clicks ÷ Opens × 100 | Email body/CTA effectiveness |

---

### 🔗 Attribution
Giving credit to the right marketing channel.

| Model | How Credit Is Assigned | Best For |
|-------|------------------------|----------|
| **First-touch** | 100% to first interaction | Awareness campaigns |
| **Last-touch** | 100% to final interaction | Bottom-funnel / direct response |
| **Linear** | Equal split across all touchpoints | Balanced multi-channel view |
| **Time-decay** | More credit closer to conversion | Short sales cycles |
| **Data-driven** | ML-based incremental impact | High-volume, mature programs |

---

## Marketing Funnel

```
IMPRESSIONS (10,000)       ← TOFU: Awareness
       ↓  3.5% CTR
AD CLICKS (350)
       ↓  80% to site
WEBSITE VISITS (280)       ← MOFU: Consideration
       ↓  64% view product
PRODUCT VIEWS (180)
       ↓  50% add to cart
ADD TO CART (90)           ← BOFU: Decision
       ↓  61% start checkout
CHECKOUT START (55)
       ↓  58% complete
PURCHASES (32)             → 0.32% end-to-end CVR
```

---

## Key Ratios to Know

| Ratio | Healthy Target | What Happens If Off |
|-------|---------------|---------------------|
| **LTV : CAC** | ≥ 3 : 1 | Below 1 = losing money on every customer |
| **CAC Payback Period** | < 12 months | Longer = cash flow risk |
| **ROAS** | ≥ 3× (e-commerce) | Below 2× = likely unprofitable |
| **Organic : Paid Traffic** | ≥ 60% organic | Over-reliance on paid = fragile growth |
| **DAU / MAU** | ≥ 20% | Lower = weak product habit |

---

## Glossary Highlights (45+ Terms)

`CAC` `ROAS` `ROI` `LTV` `CLV` `MER` `AOV` `CVR` `CTR` `CPM` `CPC` `CPL` `CTOR` `NPS` `CSAT` `RPR` `DAU` `MAU` `ARPU` `MRR` `ARR` `UGC` `UTM` `PMAX` `CRO` `A/B Test` `Cohort Analysis` `Retargeting` `Lookalike Audience` `Share of Voice` `Cart Abandonment` `Bounce Rate` `Churn` `Win-back` `TOFU` `MOFU` `BOFU` `Contribution Margin` `Payback Period` `Engagement Rate` `Open Rate` `Deliverability` `First-touch` `Last-touch` `Data-driven Attribution`

---

## Tech Stack

- **Pure HTML/CSS/JS** — no frameworks, no dependencies, no build step
- **Canvas API** — for channel performance and funnel charts
- **Google Fonts** — Space Grotesk + DM Sans + JetBrains Mono
- **Fully responsive** — works on mobile and desktop
- **Dark mode** — system preference + manual toggle

---

## How to Use

1. Open `index.html` in any browser — no server needed
2. Or visit the live GitHub Pages URL above
3. Navigate sections via sidebar (desktop) or tab bar (mobile)
4. Use Glossary filters to find terms by category

---

## About

Built by **Smith Parekh** — Data Analyst with 4.9 years of experience across growth analytics, publisher intelligence, and e-commerce BI at ParityCube (Cuelinks, DesiDime, Zingoy).

This dashboard is part of a broader analytics portfolio covering SQL query engineering, Metabase dashboards, and marketing data pipelines.

**Connect:** [LinkedIn](https://linkedin.com/in/smithparekh) · smith.parekh@paritycube.com
