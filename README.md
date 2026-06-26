# E-commerce Business Analytics Project
### Profitability Analysis & Customer Behavior Insights

**Tools:** Python · Pandas · Matplotlib · Seaborn · Power BI  
**Dataset:** Sample Superstore | 9,994 transactions · $2.3M revenue · 2015–2018

---

## Project Overview

This project analyses four years of e-commerce transactional data 
to identify profitability drivers, loss-making areas, and customer 
behavior patterns — translating raw sales data into actionable 
business recommendations.

**Central Business Question:**
> How can an e-commerce business improve profitability and better 
> understand customer behavior using analytics?

---

## 📊 Executive Dashboard

The interactive Power BI dashboard provides an executive-level overview of sales performance, profitability, regional trends, and customer segmentation. It is designed to help business stakeholders quickly identify performance drivers and make data-informed decisions.

### Executive Overview
![Executive Overview](Dashboard/1.%20Executive%20Overview.png)

### Profitability Analysis
![Profitability Analysis](Dashboard/2.%20Profitability%20Analysis.png)

### Regional Performance
![Regional Performance](Dashboard/3.%20Regional%20Performance.png)

### Customer Insights
![Customer Insights](Dashboard/4.%20Customer%20Insights.png)

## Key Business Findings

### 1. Discounting is the Biggest Profitability Threat

| Discount Level | Avg Profit Margin | Orders |
|---------------|-------------------|--------|
| 0% — No Discount | +34.0% | 4,798 |
| 1–10% | +15.6% | 94 |
| 11–20% | +17.5% | 3,709 |
| 21–30% | -11.5% | 227 |
| 30%+ | -91.5% | 1,166 |

1,166 orders (12% of all transactions) were loss-making due to excessive discounting.

### 2. Furniture — High Revenue, Near-Zero Profit

| Category | Revenue | Profit | Margin |
|----------|---------|--------|--------|
| Technology | $836,154 | $145,455 | 17.4% |
| Office Supplies | $719,047 | $122,491 | 17.0% |
| Furniture | $741,999 | $18,451 | 2.5% |

### 3. Regional Performance Gap

| Region | Revenue | Profit | Margin |
|--------|---------|--------|--------|
| West | $725,458 | $108,418 | 14.9% |
| East | $678,781 | $91,523 | 13.5% |
| South | $391,722 | $46,749 | 11.9% |
| Central | $501,240 | $39,706 | 7.9% |

### 4. Customer Segments

| Segment | Revenue | Margin |
|---------|---------|--------|
| Home Office | $429,653 | 14.0% |
| Corporate | $706,146 | 13.0% |
| Consumer | $1,161,401 | 11.5% |

---

## Strategic Recommendations

| Priority | Recommendation | Est. Profit Recovery |
|----------|---------------|---------------------|
| HIGH | Implement 20% discount cap | $50,000–$80,000 |
| HIGH | Exit Tables & Bookcases | $21,197 |
| MEDIUM | Central region intervention | $23,000–$25,000 |
| MEDIUM | Prioritise Home Office segment | $7,000–$11,000 |
| MEDIUM | Double down on Technology | $14,500+ |
| **TOTAL** | **Combined potential** | **$115,000–$152,000** |

---
## Business Impact

The analysis identifies multiple operational improvements that could
potentially recover between **$115,000 and $152,000** in annual profit by:

- Optimizing discount policies
- Reducing losses in Furniture
- Prioritizing profitable customer segments
- Improving regional sales strategy

The project demonstrates how data-driven decision making can translate
analytical findings into measurable business outcomes.

## 📂 Project Structure

```text
ecommerce-analytics/
│
├── Dashboard/
│   ├── 1. Executive Overview.png
│   ├── 2. Profitability Analysis.png
│   ├── 3. Regional Performance.png
│   ├── 4. Customer Insights.png
│
├── 01_data_cleaning.ipynb
├── 02_eda.ipynb
├── 03_insights.ipynb
│
├── 01_sales_profit_trend.png
├── 02_category_performance.png
├── 03_subcategory_profit.png
├── 04_discount_profit.png
├── 05_regional_performance.png
├── 06_segment_analysis.png
│
├── ecommerce_dashboard.pbix
├── insights_report.txt
├── recommendations_report.txt
└── README.md
```

## Methodology

1. **Data Preparation** — Loaded 9,994 records, engineered 7 derived metrics including Profit Margin %, Days to Ship, and Discount Bucket classifications
2. **Exploratory Analysis** — Analysed profitability across 3 categories, 17 sub-categories, 4 regions, and 3 customer segments
3. **Insight Generation** — Translated findings into business language with quantified profit impact
4. **Dashboard** — Built 4-page executive Power BI dashboard for non-technical stakeholders

---

## 🎯 Skills Demonstrated

- Business Analytics
- Exploratory Data Analysis (EDA)
- Data Cleaning & Feature Engineering
- Profitability Analysis
- Customer Segmentation
- Business Intelligence Dashboard Development
- Executive Reporting
- Strategic Recommendation Development
- Python (Pandas, Matplotlib, Seaborn)
- Power BI

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3 | Core analysis language |
| Pandas | Data manipulation |
| Matplotlib & Seaborn | Data visualisation |
| Jupyter Notebook | Analysis environment |
| Power BI | Executive dashboard |

---

*Business analytics portfolio project demonstrating proficiency in 
data analysis, business insight generation, and strategic 
recommendation development.*
