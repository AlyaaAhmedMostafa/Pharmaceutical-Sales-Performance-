#  Pharmaceutical Sales Performance Dashboard
### Power BI Analytics Report · Jan 2022 – Dec 2024

> **Dataset:** 5,500 Records · 46 Territories · 8 Regions · 10 Products · 6 Therapeutic Categories

---

##  Table of Contents

1. [Executive Summary](#-executive-summary)
2. [Dashboard Overview](#-dashboard-overview)
3. [Sales Performance](#-sales-performance)
4. [Market Context](#-market-context)
5. [HCP Engagement](#-hcp-engagement)
6. [Territory Performance Index](#-territory-performance-index)
7. [Rep Leaderboard](#-rep-leaderboard)
8. [Operations](#-operations)
9. [Strategic Recommendations](#-strategic-recommendations)
10. [Data Model & Methodology](#-data-model--methodology)

---

##  Executive Summary

This report presents a full-spectrum analysis of pharmaceutical sales operations across **46 territories** spanning **January 2022 through December 2024**. The organization generated **$209.84M in total revenue**, reflecting an **8.3% increase versus 2023**, against a backdrop of flat market share and a revenue attainment rate of **0.96** — sitting 4.4 percentage points below plan.

While top-line growth is encouraging, the analysis surfaces several critical operational and strategic challenges:

- **Revenue attainment remains below target** across a meaningful share of territories, with 8 territories flagged as needing coaching-level intervention.
- **Oncology dominates the product mix** at nearly 57% of revenue, creating significant concentration risk.
- **Revenue leakage of $17.87M** tied to product returns and distribution gaps demands immediate operational attention.
- **25 of 46 reps** are flagged as priority coaching cases, signaling a field force effectiveness gap that could compress future growth.

Despite these headwinds, pockets of excellence exist — elite territories like IL-Chicago and IA-Main are operating at TPI scores above 2.0, and the West and Midwest regions are sustaining year-over-year growth above 7%.

---

##  Dashboard Overview

The Power BI dashboard is organized across **7 analytical pages**, each examining a distinct performance dimension:

| Page | Focus Area |
|------|-----------|
| **Main Dashboard** | Executive KPI summary, attainment distribution, revenue trends |
| **Sales Performance** | Volume, revenue, growth, product mix |
| **Market Context** | Market share trends, competitive positioning, regional share |
| **HCP Engagement** | Physician call rates, prescription rates, rep effectiveness |
| **Territory Performance Index** | Context-adjusted rep benchmarking, difficulty analysis |
| **Rep Leaderboard** | Composite scores, tier rankings, coaching flags |
| **Operations** | Distribution coverage, return rates, supply chain health |

### Top-Line KPIs

| Metric | Value | Trend |
|--------|-------|-------|
| Total Revenue | **$209.84M** | ↑ 8.3% vs 2023 |
| Revenue Attainment | **0.96** | ↓ 4.4pp below plan |
| Market Share | **35.47** | → Flat (0.0pp YoY) |
| Avg Rx Rate | **2.73** | ↓ 0.02 YoY |
| TPI Avg Score | **1.20** | ↓ 0.02 — On Track |

---

##  Sales Performance

### Volume & Profitability

| Metric | Value | Change |
|--------|-------|--------|
| Total Units Sold | **360,000** | ↑ 5.7% vs Last Year |
| Gross Profit | **$165.74M** | Margin: 79.0% |
| 3-Year CAGR | **-0.01** | Near-flat long-term growth |
| Revenue Per Rep | **$4.56M** | ↑ 3.3% vs Last Year |

The 79% gross margin is a strong indicator of pricing power and cost discipline. However, the near-zero 3-year CAGR signals that recent growth may be driven by pricing or market conditions rather than durable volume expansion.

### Product Revenue Performance

| Product | Category | Revenue | Target | Units | Margin | Trend |
|---------|----------|---------|--------|-------|--------|-------|
| OncoPrime 100mg | Oncology | $226,949,927 | $235,239,562 | 108,007 | 0.84 | ▼▼ |
| OncoPrime 50mg | Oncology | $129,831,630 | $135,978,758 | 103,966 | 0.82 | ▲▲ |
| ImmunoCor | Immunology | $94,855,467 | $100,302,274 | 107,151 | 0.79 | ▲▲ |
| NeuroShield 10mg | Neurology | $48,544,588 | $50,798,615 | 101,968 | 0.76 | ▲ |
| NeuroShield 5mg | Neurology | $32,828,069 | $34,531,713 | 102,822 | 0.74 | ▼▼ |
| DiabeCare XR | Endocrinology | $27,370,826 | $28,432,787 | 105,259 | 0.67 | ▲ |
| CardioMax 20mg | Cardiovascular | $20,674,248 | $21,769,755 | 98,274 | 0.71 | ▲ |
| DiabeCare Plus | Endocrinology | $17,893,587 | $19,111,346 | 97,019 | 0.65 | ▼▼ |
| CardioMax 10mg | Cardiovascular | $16,235,208 | $17,059,273 | 112,192 | 0.68 | ▲▲ |
| PulmoRelief | Respiratory | $11,089,692 | $11,658,971 | 116,788 | 0.58 | ▲ |

>  **Every product is below its revenue target.** OncoPrime 100mg has the largest absolute gap (~$8.3M), though OncoPrime 50mg and ImmunoCor show positive momentum trends.

### Revenue by Therapeutic Category

```
Oncology        ████████████████████████████░░░░░░░░░░░  56.97%
Immunology      ████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  15.15%
Neurology       ███████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  12.99%
Endocrinology   ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   7.23%
Cardiovascular  (remainder)
Respiratory     (remainder)
```

**Oncology contributes nearly 57% of all revenue.** While this reflects product strength, it creates portfolio concentration risk — any regulatory, competitive, or formulary change in oncology would have outsized revenue impact.

### YoY Revenue Growth by Region

| Region | YoY Growth |
|--------|-----------|
| West | **+7.7%** |
| Midwest | **+7.5%** |
| Mid-Atlantic | **+7.0%** |
| Northeast | **+6.9%** |
| Southwest | **+6.3%** |
| Great Plains | **+4.7%** |
| Southeast | **+4.0%** |

Growth is broadly positive across all regions, though the **Southeast and Great Plains lag** significantly. The Southeast's combination of below-average growth and declining market share (see Market Context) marks it as a strategic priority for intervention.

---

##  Market Context

### Market Share by Region

| Region | Market Share | YoY Δ | Position |
|--------|-------------|-------|----------|
| Midwest | 27,397.27 | ↑ +0.3pp | STRONG |
| Mid-Atlantic | 27,244.31 | ↓ -0.9pp | STRONG |
| West | 26,157.32 | ↑ +0.9pp | STRONG |
| Northeast | 25,737.17 | ↓ -0.4pp | STRONG |
| Southwest | 23,601.28 | ↑ +2.1pp | STRONG |
| Southeast | 22,928.94 | ↓ -3.1pp | COMPETITIVE |
| Great Plains | 22,844.37 | ↑ +1.4pp | COMPETITIVE |
| Northwest | 20,515.17 | ↓ -2.5pp | DEVELOPING |

### Key Market Insights

- **Southwest shows the most momentum** with a +2.1pp market share gain, suggesting successful competitive displacement.
- **Southeast is under the most competitive pressure** (-3.1pp), the largest single-region decline in the portfolio. This warrants an urgent review of competitive positioning and rep deployment.
- **Northwest is classified as DEVELOPING** with the lowest absolute market share and a -2.5pp decline — this region may require a market-building strategy before expecting attainment.
- **Overall market share is flat at 35.47**, meaning revenue growth is primarily coming from market expansion rather than share gains. Sustainable long-term growth will require improving the competitive win rate.

### Market Share Bands (Territory Distribution)

| Band | Territory Count |
|------|----------------|
| Competitive (30–35%) | 14 |
| Developing (<30%) | 8 |
| Market Leader (≥35%) | 8 |
| Strong Performer | 16 |

With only **8 territories** classified as Market Leader and **8 as Developing**, there is significant room to push a greater number of territories up the competitive ladder through targeted investment and rep coaching.

---

##  HCP Engagement

Physician engagement is a critical upstream driver of prescribing behavior. The data shows a well-structured tiering system but meaningful gaps between tier performance levels.

### Engagement KPIs

| Metric | Value |
|--------|-------|
| Avg Rx Rate | **2.73** |
| Avg Call Rate / Day | **5.80** |
| High Influencer Physicians (Rx ≥ 3.5/visit) | **41** |
| Revenue per Call | **$19,630** |

### Call Rate by Physician Tier

```
Top Tier    ████████████████████████  7.2 calls/day
Mid Tier    ███████████████████       5.5 calls/day
Low Tier    ██████████████            4.1 calls/day
```

### Prescription Rate by Physician Tier

```
Top Tier    ████████████████████████  3.8 Rx/visit
Mid Tier    ████████████████          2.5 Rx/visit
Low Tier    ██████████                1.6 Rx/visit
```

The call-to-Rx relationship follows a logical pattern — higher-tier physicians receive more calls and generate more prescriptions. However, the **gap between Top and Low tier Rx rates (3.8 vs 1.6)** suggests that rep time allocation should be more aggressively tiered. Reps may still be over-investing in low-influencer physicians relative to the return.

### Prescription Rate by Product — All Products Classified as EFFECTIVE

All listed products achieve an "EFFECTIVE" performance classification. Notable standout metrics:

- **ImmunoCor** generates the highest Revenue per Rx at **$62,475.61**, making each prescription exceptionally valuable.
- **DiabeCare XR** follows at **$19,308.68 Rev/Rx**, reflecting its specialty positioning.
- **CardioMax 10mg** has the highest unit volume among non-oncology products (112,192 units), suggesting strong market penetration in cardiovascular.

---

##  Territory Performance Index

The TPI is a **context-adjusted benchmarking score** that accounts for market difficulty when evaluating rep performance, making it a fairer measure than raw attainment alone.

### TPI Score Distribution

| Band | Count |
|------|-------|
| On Track (0.8–1.1) | **23** |
| Elite (≥ 2.0) | **14** |
| Strong (1.2–1.9) | **1** |
| Needs Coaching (< 0.5) | **8** |

>  The bimodal distribution — a large "On Track" cluster and a sizeable "Elite" cluster — with very few in the "Strong" middle band, suggests a talent bifurcation. The middle cohort may present the highest coaching ROI opportunity.

### Top 5 Territories — ELITE

| Rank | Territory | TPI Score | Difficulty | Band |
|------|-----------|-----------|------------|------|
| 1 | IL-Chicago | 2.20 | 0.94 | ELITE |
| 2 | IA-Main | 2.14 | 1.00 | ELITE |
| 3 | NV-South | 2.13 | 1.00 | ELITE |
| 4 | OR-Main | 2.12 | 0.98 | ELITE |
| 5 | PA-West | 2.12 | 0.99 | ELITE |

### Bottom 5 Territories — COACHING REQUIRED

| Territory | TPI Score | Difficulty | Band |
|-----------|-----------|------------|------|
| AK-Main | 0.34 | 1.01 | COACHING |
| MO-Main | 0.33 | 0.99 | COACHING |
| NC-West | 0.33 | 1.02 | COACHING |
| NY-South | 0.34 | 1.02 | COACHING |
| WY-Main | 0.33 | 1.02 | COACHING |

> ⚠️ **Critically, all 5 bottom territories show market difficulty scores near 1.0**, meaning their poor TPI is not explained by operating in a hard market — it is a rep performance issue requiring structured coaching intervention.

### Full TPI Scorecard — Top 10

| Rank | Territory | Region | Rep Tier | TPI | Difficulty | Attainment | Rx Rate | Coverage | Status |
|------|-----------|--------|----------|-----|------------|------------|---------|----------|--------|
| 1 | IL-Chicago | Midwest | Top | 2.20 | 0.94 | 95.8% | 3.84 | 80.33 | ELITE |
| 2 | IA-Main | Great Plains | Top | 2.14 | 1.00 | 98.4% | 3.90 | 81.17 | ELITE |
| 3 | NV-South | Southwest | Top | 2.13 | 1.00 | 97.7% | 3.81 | 80.39 | ELITE |
| 4 | OR-Main | West | Top | 2.12 | 0.98 | 98.4% | 3.78 | 80.30 | ELITE |
| 5 | PA-West | Mid-Atlantic | Top | 2.12 | 0.99 | 91.9% | 3.79 | 79.90 | ELITE |
| 6 | RI-Main | Northeast | Top | 2.12 | 0.95 | 96.3% | 3.59 | 79.72 | ELITE |
| 7 | NH-Main | Northeast | Top | 2.10 | 0.98 | 98.7% | 3.74 | 79.92 | ELITE |
| 8 | TX-North | Southwest | Top | 2.09 | 1.03 | 92.3% | 3.82 | 81.57 | ELITE |
| 9 | VA-Main | Southeast | Top | 2.08 | 1.00 | 99.3% | 3.73 | 80.39 | ELITE |
| 10 | MA-West | Northeast | Top | 2.08 | 0.94 | 92.1% | 3.74 | 80.55 | ELITE |

---

##  Rep Leaderboard

### Workforce Summary

| Metric | Value |
|--------|-------|
| Total Active Reps | **46** |
| Top Tier Reps | **13** (28% of workforce) |
| Avg Overall Score | **67.51 / 100** |
| Priority Coaching Cases | **25** (54% of workforce) |

>  Over **half the salesforce** is classified as Priority Coaching. This is the most critical finding in the entire dashboard. At current levels, the coaching burden likely exceeds the capacity of front-line managers to deliver meaningful intervention without structural support.

### Score Distribution

```
41–50   ███████              ~7 reps
51–60   ██                   ~2 reps
61–70   ████████████████████ ~21 reps  ← Largest cluster
71–80   ██                   ~3 reps
81–100  █████████████        ~13 reps
```

### Top 8 Reps by Composite Score

| Rank | Rep | Territory | Tier | Score | Revenue | Attainment | Rx Rate | TPI | Coaching Priority |
|------|-----|-----------|------|-------|---------|------------|---------|-----|------------------|
| 1 | Michael Johnson | IA-Main | Top | 85.04 | $16,138,054 | 98.4% | 3.90 | 2.14 | LOW |
| 2 | Lisa Wilson | OR-Main | Top | 84.46 | $25,833,342 | 98.4% | 3.78 | 2.12 | LOW |
| 3 | Sarah Thomas | VA-Main | Top | 84.42 | $15,211,456 | 99.3% | 3.73 | 2.08 | LOW |
| 4 | Chris Thomas | IL-Chicago | Top | 84.35 | $16,137,228 | 95.8% | 3.84 | 2.20 | LOW |
| 5 | Robert Johnson | NV-South | Top | 84.22 | $16,872,979 | 97.7% | 3.81 | 2.13 | LOW |
| 6 | Chris Thomas | NH-Main | Top | 84.04 | $14,265,824 | 98.7% | 3.74 | 2.10 | LOW |
| 7 | Emily Davis | TX-North | Top | 84.02 | $11,644,633 | 92.3% | 3.82 | 2.09 | LOW |
| 8 | Sarah Brown | NC-East | Top | 83.63 | $17,729,741 | 94.2% | 3.80 | 2.08 | LOW |

>  **Lisa Wilson (OR-Main)** stands out with the highest revenue among the top 8 at **$25.8M**, despite a slightly lower composite score — suggesting her territory has significant scale advantages or market size benefits not fully reflected in the TPI.

---

##  Operations

### Operational KPIs

| Metric | Value | Trend |
|--------|-------|-------|
| Avg Distribution Coverage | **69.58%** | ↑ +0.1pp YoY |
| Avg Product Return Rate | **3.43%** | — |
| Revenue Leakage | **$17.87M** | — |
| Critical Gap Territories (<60% coverage) | **8** |  |

### Distribution Coverage Heatmap — Region × Quarter

| Region | Q1 | Q2 | Q3 | Q4 |
|--------|----|----|----|----|
| Great Plains | 69.7% | 67.0% | 66.6% | **69.8%** |
| Mid-Atlantic | 74.0% | 73.1% | 72.1% | **74.7%** |
| Midwest | 71.8% | 70.5% | 73.3% | 70.7% |
| Northeast | 70.3% | 71.6% | 72.3% | 72.5% |
| Northwest | 60.7% | 61.1% | **59.4%**  | 60.1% |
| Southeast | 65.2% | 66.4% | 65.4% | **67.0%** |
| Southwest | 72.9% | 71.8% | 73.0% | 72.2% |
| West | 72.7% | 73.6% | 72.3% | 72.3% |

>  **Northwest hit a critical low of 59.4% in Q3**, falling below the 60% threshold. Combined with its DEVELOPING market position and negative market share trend, the Northwest requires an integrated supply chain and sales strategy review.

### Product Return Rates

| Product | Avg Return Rate % |
|---------|-------------------|
| OncoPrime 50mg | **3.8%** ← Highest |
| OncoPrime 100mg | 3.6% |
| NeuroShield 10mg | 3.6% |
| CardioMax 20mg | 3.5% |
| DiabeCare Plus | 3.5% |
| PulmoRelief | 3.4% |
| ImmunoCor | 3.3% |
| NeuroShield 5mg | **3.3%** ← Lowest |

OncoPrime products — the highest-revenue items in the portfolio — also carry the **highest return rates**. Given OncoPrime's revenue dominance, even marginal improvements in return rate could recover millions in leakage.

### Revenue Leakage by Territory (Sample)

| Territory | Return Rate | Units Returned | Revenue Leakage | Risk |
|-----------|-------------|----------------|-----------------|------|
| AK-Main | 5.50% | 1,017 | $672,899 | **Critical** |
| FL-North | 5.11% | 557 | $301,409 | **Critical** |
| CA-South | 3.84% | 1,032 | $578,259 | **Critical** |
| AZ-Main | 2.39% | 494 | $311,582 | Excellent |
| CA-North | 2.55% | 596 | $300,806 | Excellent |
| DE-Main | 1.60% | 483 | $288,304 | Excellent |
| FL-South | 3.02% | 566 | $366,736 | Excellent |
| CT-Main | 2.77% | 552 | $250,501 | Excellent |

**AK-Main, FL-North, and CA-South** are the three Critical-risk territories for revenue leakage — collectively responsible for over **$1.55M** in returns from just these three territories alone.

---

##  Strategic Recommendations

### 1. Immediate — Field Force Coaching Overhaul
With **25 of 46 reps (54%)** flagged as Priority Coaching, the current coaching capacity is almost certainly insufficient.
- Deploy a structured **coaching program tiered by TPI band** — prioritizing the 8 Needs Coaching territories, where TPI scores of ~0.33 indicate systemic underperformance.
- Leverage top performers (Michael Johnson, Lisa Wilson, Chris Thomas) as peer coaches or regional exemplars.
- Establish a **90-day performance improvement plan** for all 5 bottom territories; consider territory reassignment for persistent underperformers.

### 2. Immediate — Revenue Leakage Reduction
At **$17.87M**, revenue leakage represents approximately **8.5% of total revenue** — a significant recoverable value.
- Conduct a root cause analysis on **AK-Main, FL-North, and CA-South** (Critical risk territories).
- Review OncoPrime return processes; a 1pp reduction in OncoPrime 50mg returns alone could recover ~$1.3M.
- Set a KPI target: reduce system-wide return rate from 3.43% to below 2.5% within 12 months.

### 3. Near-Term — Portfolio Diversification
Oncology represents **56.97% of revenue** from just 2 products (OncoPrime 100mg & 50mg). This concentration creates existential risk.
- Accelerate growth investment in **ImmunoCor** (strong margin of 0.79, positive trend) and **NeuroShield 10mg**.
- Develop territory-specific product mix targets to reduce oncology dependency below 50% over 24 months.

### 4. Near-Term — Southeast & Northwest Region Intervention
- **Southeast**: -3.1pp market share decline + lowest YoY growth (4.0%) + COMPETITIVE classification. Conduct a competitive landscape audit and review rep deployment.
- **Northwest**: -2.5pp market share + DEVELOPING classification + sub-60% Q3 distribution coverage. Prioritize supply chain reliability before pushing revenue targets.

### 5. Medium-Term — HCP Tiering Optimization
The 2.4× Rx rate difference between Top and Low tier physicians (3.8 vs 1.6) suggests reps are not optimally allocating their time.
- Implement a **call plan optimization** model to reallocate ~20% of low-tier physician time toward top-tier accounts.
- Set a target to grow the **41 High Influencer physicians** (Rx ≥ 3.5/visit) by 25% within 18 months.

### 6. Medium-Term — Market Share Growth Strategy
Overall market share is flat at 35.47 despite 8.3% revenue growth, meaning growth is market-driven rather than share-driven.
- Identify the **14 Competitive (30–35% share) territories** as the primary share-gain opportunity.
- Model the revenue impact of moving these territories to the Strong Performer band.
- Target Southwest's +2.1pp momentum as a replicable playbook for other regions.

---

## Data Model & Methodology

### Dataset Specifications

| Attribute | Detail |
|-----------|--------|
| Records | 5,500 |
| Time Period | January 2022 – December 2024 (36 months) |
| Territories | 46 |
| Regions | 8 |
| Products | 10 |
| Therapeutic Categories | 6 (Oncology, Immunology, Neurology, Endocrinology, Cardiovascular, Respiratory) |
| Rep Tiers | 3 (Top, Mid, Low) |


### Tools & Technologies
- **Visualization:** Microsoft Power BI Desktop
- **Data Modeling:** DAX measures and calculated columns
- **Interactivity:** Slicers for Year, Region, Tier, and Product across all 7 pages
- **Statistical Methods:** YoY comparisons, CAGR, attainment banding, scatter quadrant analysis
