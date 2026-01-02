# 🛒 E-commerce Performance Dashboard (Option A) — Google Sheets

**Author:** Ana C. Carrasco  
**Tools:** Google Sheets, Pivot Tables, Array Formulas, KPI Design, Data Visualization  
**Data Source:** Open e-commerce transactional dataset (Kaggle)

---

## 📊 Dashboard Overview

This dashboard provides a comprehensive overview of e-commerce performance using transactional-level data. It consolidates revenue, order volume, customer activity, and product performance into a single interactive view designed to support fast, data-driven decisions.

The goal is to transform raw transaction data into clear operational insights without relying on paid BI tools.

---

## 🧠 Business Purpose

This dashboard is designed to:

- Monitor overall e-commerce health through core KPIs.
- Identify revenue and order volume trends over time.
- Highlight top-performing products and international markets.
- Support operational and commercial decision-making with minimal manual reporting.

---

## 🔍 Key Metrics & Visuals

### KPIs
- Total Revenue  
- Total Orders  
- Total Customers  
- Total Items Sold  
- Average Order Value (AOV)

### Visualizations
- **Monthly Revenue Trend (2010–2011):** Identifies seasonality and revenue volatility.
- **Monthly Order Volume:** Shows demand patterns independent of revenue.
- **Top 5 Revenue by Country (Excluding UK):** Highlights international markets without home-market dominance.
- **Top 10 Products by Revenue:** Reveals products driving the majority of sales.

---

## 🛠️ Tools & Techniques Used

- Google Sheets
- Pivot Tables for aggregation and ranking
- ARRAYFORMULA for scalable calculations
- Calculated fields (Line Revenue, Year, Month, Year-Month, AOV)
- Scorecard charts for KPI visualization
- Bar and line charts for trends and comparisons
- Sheet protection to prevent accidental edits while preserving interactivity

---

## ⚙️ Workflow / How It Was Built

1. **Data Preparation**
   - Cleaned raw transactional data.
   - Removed invalid records (zero quantity, missing customer IDs).
   - Created derived fields for time analysis and revenue calculation.

2. **Modeling**
   - Aggregated revenue, orders, customers, and items sold using pivot tables.
   - Calculated AOV using total revenue divided by total orders.

3. **Visualization**
   - Used line charts for time-series analysis.
   - Used bar charts for rankings and comparisons.
   - Applied consistent currency and numeric formatting.

4. **Interactivity**
   - Designed the dashboard layout to support filters and slicers.
   - Ensured KPI cards and charts update correctly with filtered data.

5. **Design Choices**
   - Neutral color palette for clarity and readability.
   - Clear labeling and spacing to reduce cognitive load.
   - KPI cards positioned for immediate visibility.

---

## 🚀 Impact / What This Dashboard Improves

- Reduces manual reporting by consolidating metrics into a single view.
- Improves visibility into revenue versus order behavior.
- Enables faster identification of top products and international opportunities.
- Demonstrates how scalable dashboards can be built using free tools.

---

## 📂 Files & Assets

- `banner_ecommerce_option_a.png` — Dashboard screenshot  
- Google Sheets file containing raw data, cleaned data, pivots, KPIs, and dashboard tabs ([HERE](https://docs.google.com/spreadsheets/d/1ScdSzhTDQwOzP0Fr6qzHfTYq-l2iaOXGhKklkO41Kwo/edit?usp=sharing))

---

## 🔮 Future Enhancements

- Add customer repeat rate and cohort analysis.
- Introduce funnel metrics (e.g., sessions → orders).
- Compare performance with a second e-commerce dataset (Option B).
- Automate data refresh using scripts or external connectors.

---

## 📌 Portfolio Context

This dashboard represents **E-commerce Performance — Option A**, focused on transactional-level analysis.  
A complementary **Option B** dashboard will extend this work with behavioral and retention metrics, allowing both dashboards to be connected into a broader analytical narrative.
