# 🚴‍♂️ Tableau Dashboard for The Bike Haven Company 

## 📌 Project Overview
**The Bike Haven: Sales Performance Dashboard**  
Transitioning The Bike Haven from static, low-insight reporting to an interactive Tableau analytics ecosystem to drive online sales growth.

---

## 📊 The Problem & Business Context

When Chris joined **The Bike Haven** as Sales Manager, he recognized a clear mismatch: the bikes and components were of exceptional quality, but the sales figures didn't reflect that potential. 

The primary bottleneck was our reporting. The existing sales reports were completely static, making it nearly impossible to spot regional trends, identify underperforming product lines, or track seasonal sales spikes. As the newly hired Tableau Analyst, my objective was to revamp these legacy reports into dynamic, interactive dashboards that give Chris and the leadership team actionable, real-time insights into online sales performance.

---

## 🚀 The Solution: Tableau Dashboards & Stories

Instead of relying on rigid, rows-and-columns data, the new visual framework gives stakeholders an intuitive way to explore performance metrics on the fly.

### 🎯 Key Features Designed for Chris:
*   **Executive Sales Overview:** High-level KPIs tracking total revenue, profit margins, and order volume compared to previous periods.
*   **Product Performance Matrix:** Dynamic filtering to isolate high-performing bike models versus sluggish inventory, helping Chris plan product revamps.
*   **Customer & Regional Insights:** Geographic heat maps pinpointing where online sales are thriving and where branding efforts need a boost.
*   **Interactive "What-If" Analysis:** Parameter controls allowing Chris to simulate changes in discount rates or shipping costs to see the direct impact on bottom-line profit.

---

## 🛠️ Tech Stack & Data Architecture

*   **BI Tool:** Tableau Desktop / Tableau Public
*   **Data Modeling & Logic Checklist:**
    *   Joined `Sales_Fact` with `Product_Dimension` and `Customer_Dim` to create a robust star-schema layout.
    *   Cleaned and handled missing values in shipping dates to ensure accurate time-series analysis.
    *   Created optimized calculated fields for **Profit Margin %**, **Customer Acquisition Cost (CAC)**, and **Year-over-Year (YoY) Growth**.

---

## 📈 Dashboard Previews & Insights

<img width="1108" height="882" alt="The Bike Haven Sales Dashboard Preview" src="https://github.com/user-attachments/assets/e4f2878a-6d55-4be6-ae7a-aae4c4e25d46" />

> 💡 **Key Insight:** Online sales drop sharply in northern territories during Q3, suggesting a critical need for localized seasonal marketing campaigns and targeted inventory shifts.

---

## 🧑‍💻 How to View the Project

*   **Local Desktop:** 
    1. Download the `The_Bike_Haven_Sales_Analysis.twbx` file from this repository.
    2. Open it using Tableau Desktop or the free [Tableau Reader](https://www.tableau.com/products/reader).

---

## 🏁 Impact & Next Steps
With this new visual architecture, Chris and the marketing team can now self-serve their critical data queries in **under 30 seconds**—a process that previously took days of manual Excel tracking. 

**Phase Two Expansion:** Moving forward, the next step of this project will involve integrating predictive forecasting models directly within Tableau to anticipate inventory demand ahead of peak cycling seasons.
