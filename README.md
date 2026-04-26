# E-Commerce & Marketing Performance Analysis

> *"Turning raw data into decisions — an end-to-end analytics project."*

---

## Project Overview

This project delivers a comprehensive analysis of e-commerce performance and marketing effectiveness using a full modern data analytics stack — from raw data ingestion through to interactive business intelligence dashboards.

The goal is to uncover actionable insights around customer retention, revenue concentration, channel efficiency, and conversion performance, enabling data-driven decision-making across commercial and marketing functions.

---

## Tech Stack

| Stage | Tool / Method |
|---|---|
| Data Source | Kaggle (CSV files) |
| Data Ingestion | CSV import → SQL tables |
| Data Storage | SQL (relational tables) |
| Data Transformation | SQL (cleaning, joins, views) |
| Business Logic | SQL Views + DAX Measures |
| BI Connection | Power BI via DirectQuery |
| Visualization | Microsoft Power BI |

---

## Workflow

```
Kaggle Dataset (CSV files)
      │
      ▼
Import CSVs → SQL Tables
      │
      ▼
Data Cleaning & Transformation (SQL)
      │
      ▼
Structured SQL Views
      │
      ▼
Power BI connected via DirectQuery
      │
      ▼
DAX Measures & Calculated Columns
      │
      ▼
Interactive Dashboard (3 Pages)
```

---

## Dashboard Structure

The report is organized across three analytical pages:

- **Overview** — High-level KPIs, revenue trends by month and year, geographic distribution, and country-level performance breakdown.
- **E-Commerce** — Customer segmentation (RFM), loyalty tier analysis, revenue by category and top brands.
- **Marketing** — Channel performance, experiment group analysis, device-type distribution, event funnel, and campaign-level revenue.

---

## Key Findings

### Business Performance
- Total revenue of **$8.37M** across **64K customers** and **103K transactions**, with steady month-over-month growth of **2.09%**.
- The **US market leads at $3.0M**, nearly double India ($1.7M), followed by UK, Brazil, and Canada at ~$0.8M each.

### Customer Retention Risk
- **53% of RFM revenue is attributed to "Lost" customers** — the single most critical finding in this analysis.
- Immediate action is recommended: targeted win-back campaigns segmented by recency and historical spend.

### Loyalty Tier Gap
- The **Bronze tier generates $4.5M (54% of total revenue)**, meaning the majority of customers remain at the lowest loyalty level.
- This represents a significant opportunity for structured tier upgrade programs and loyalty incentives.

### E-Commerce
- **Electronics dominates at $3.5M**, with a healthy supporting mix from Home ($2.0M), Fashion ($1.3M), and Sports ($1.0M).
- Over-reliance on a single category is a risk to monitor — particularly in the event of supply disruption or market saturation.
- The **top 10 brands are tightly clustered** between $110K–$146K, indicating no single brand drives outsized purchase decisions.

### Marketing & Channels
- **Affiliate is the highest-performing channel at $1.61M**, outperforming Paid Search ($1.53M), Email ($1.36M), Display ($1.21M), and Social ($0.97M).
- Social delivers the lowest return and warrants budget reallocation or strategy review.
- **60% of sessions originate from mobile devices**, making checkout experience optimization a direct and measurable revenue lever.

### Conversion Funnel
- Only **~10% of views convert to purchases**, with bounce events accounting for approximately **190K lost opportunities**.
- Funnel drop-off between add-to-cart (284K) and purchase (103K) suggests significant abandonment at the checkout stage.

### A/B Testing
- Experiment group distribution is skewed **3:1:1 (Control vs. Variant A vs. Variant B)**, which limits the statistical reliability of conclusions drawn from this test.
- Future experiments should target balanced group allocation for valid inference.

---

## Recommendations

1. **Launch win-back campaigns** for Lost customer segments, prioritizing high-recency, high-value churned customers.
2. **Introduce loyalty upgrade incentives** to move Bronze customers toward Silver and Gold tiers.
3. **Optimize mobile checkout** — with 60% of sessions on mobile, even a 5% improvement in mobile conversion could yield significant revenue uplift.
4. **Reallocate Social budget** toward Affiliate and Paid Search where ROI is demonstrably stronger.
5. **Investigate funnel drop-off** between add-to-cart and purchase — exit surveys, abandoned cart emails, or UX testing could identify friction points.
6. **Redesign A/B testing framework** to ensure statistically balanced group sizes before drawing experiment conclusions.

---

## Data Source

Dataset sourced from [Kaggle](https://www.kaggle.com) as CSV files. Data was imported into SQL, cleaned and transformed into structured relational tables and views, then connected to Microsoft Power BI using DirectQuery for live querying and visualization.


