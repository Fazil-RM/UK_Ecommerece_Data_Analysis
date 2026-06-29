# UK E-Commerce Customer Analytics & Retention Engine

## 📊 Executive Project Overview
This end-to-end data analytics project provides an enterprise-grade evaluation of a UK-based e-commerce dataset containing over 540,000 raw transactional records spanning December 2010 to December 2011. 

By combining the data-wrangling power of **Python** with the advanced interactive storytelling of **Power BI**, this project goes beyond descriptive statistics to deliver an **RFM (Recency, Frequency, Monetary) Segmentation** and a **Time-Based Cohort Retention Matrix**. The final deliverables pinpoint exactly where customer churn occurs, classify users into actionable value tiers, and prescribe distinct strategies to increase sales and lifetime value (LTV).

---

## 🛠️ Repository Architecture & Deliverables
* 📁 **`UK_Ecommerece_Data_Analysis.ipynb`**: The master Jupyter Notebook detailing the data cleaning pipeline, anomalous transaction handling (returns/cancellations), RFM modeling, and cohort matrix computation.
* 📁 **`UK_Ecommerece_Dashboard.pbix`**: The standalone Power BI file containing a fully interactive, production-ready 4-page dashboard designed with deep attention to typography, data hierarchy, and UI consistency.
* 📁 **`README.md`**: Project documentation and high-level brief (this file).

---

## 🧪 Data Pipeline & Processing (Python)
The raw dataset was notoriously complex and mirrored real-world transactional discrepancies. The pipeline executed in the notebook resolved:
1. **Missing Data & Duplicates:** Isolated and handled 135,080 missing `CustomerID` records and cleared 5,268 explicit duplicates.
2. **Anomalous Records:** Handled negative unit prices (adjustments/debt write-offs) and structural transactional returns.
3. **RFM Modeling:** Engineered raw data into custom customer-level metrics mapping Recency (days since last purchase), Frequency (total unique orders), and Monetary (lifetime spend).
4. **Cohort Matrix Generation:** Processed transactional dates into dynamic month-by-month tracking indexes to compute a classic time-based retention breakdown.

---

## 📈 Power BI Interactive Dashboard Breakdowns

### Page 1 | Executive Financial Performance
* **Objective:** Establish the baseline macro health metrics of the e-commerce store.
* **Key Visuals:** High-contrast KPI metric cards (Total Revenue: $8.89M, Total Orders: 19K, Average Order Value (AOV): $479.46, Active Customers: 4,339). A clean Monthly Revenue Trend line chart capturing a Q4 holiday sales explosion peaking at over $1.15M in November. Geographic bubble map outlining international distribution alongside a Top 10 product revenue chart.

![Page 1 - Executive Financial Performance](https://ik.imagekit.io/fazil/Page-1.png?updatedAt=1782743752967)

---

### Page 2 | Customer Segmentation & RFM Analytics
* **Objective:** Break down the active customer base into actionable behavioral buckets.
* **Key Visuals:** Nested donut charts splitting customer volume vs. actual revenue contribution across segments (*Champions, Loyal, About to Sleep, Hibernating, At Risk VIPs*). Includes an interactive Customer Drill-Down data grid and clear text blocks highlighting that Champions and Loyal segments drive nearly 50% of top-line revenue.

![Page 2 - Customer Segmentation & RFM Analytics](https://ik.imagekit.io/fazil/Page-2.png?updatedAt=1782743752173)

---

### Page 3 | Customer Retention & Cohort Matrix
* **Objective:** Map the physical lifecycle and decay of customer cohorts over a 12-month window.
* **Key Visuals:** A conditional-formatted Cohort Retention Heatmap matrix displaying month-by-month user drop-offs. Accompanied by a decay trend curve tracking the drop from Month 0 to Month 12, showcasing a baseline Repeat Customer Rate of 66% and an overall Average Customer Lifespan of 3.08 years.

![Page 3 - Customer Retention & Cohort Matrix](https://ik.imagekit.io/fazil/Page-3.png?updatedAt=1782743752474)

---

### Page 4 | Executive Insights & Recommended Actions
* **Objective:** Translate data discoveries directly into core corporate strategy.
* **Key Visuals:** A highly scannable, side-by-side matrix summarizing critical cohort observations against prescriptive business interventions. It breaks down onboarding email cadences, targeted re-engagement campaigns for the 2K inactive users, and custom product recommendations to lift Month 1 retention.

![Page 4 - Executive Insights & Recommended Actions](https://ik.imagekit.io/fazil/Page-4.png?updatedAt=1782743753197)

---

## 🎯 Overall Strategic Findings & Core Takeaways

1. **The First-Month Attrition Crisis:** The cohort heatmap exposes that **76.6% of acquired customers fail to make a secondary purchase in their first month**. This marks the single biggest opportunity for commercial improvement. The first 30 days must be targeted with immediate automated post-purchase workflows.
2. **High Concentration of Value:** Nearly half of all revenue is sustained by a thin tier of *Champions* and *Loyal Customers*. Protecting this baseline from churn via proactive VIP retention perks is vital for stabilizing recurring cash flows.
3. **Severe At-Risk Pools:** Over 2,000 customers currently sit in *Hibernating* or *Inactive* states, representing massive dormant value. Targeted win-back campaigns with strategic, short-window promotional discounts are recommended to reactivate high lifetime-value historical buyers.
4. **Extreme Seasonality:** Business performance is intensely seasonal, scaling up sharply from September through November. Inventory buffers, infrastructure scaling, and ad-spend allocation must be heavily prioritized for early Q3 to capture this predictable velocity.

---
*Developed by [Fazil RM](https://github.com/Fazil-RM) - Final Year Student specializing in Mathematics & Applied Data Science.*
