# Omnichannel Retail Performance & Logistics Intelligence Dashboard

A 3-page interactive Power BI dashboard tracking sales profitability, discount efficiency, and return rates across Website, Mobile App, and Amazon storefronts.

---

## 📌 Executive Summary & Business Problem
* **Business Challenge:** A multi-channel retail brand experienced margin compression despite growing top-line sales, driven by marketplace promotional discounts and an overall return rate of 23.8%.
* **Objective:** Deliver an end-to-end reporting suite enabling leadership to track margin health, evaluate channel profitability, and isolate reverse logistics drivers.

---

## 📊 Dashboard Views

### 1. Executive Overview
Tracks overall financial health, sales contribution across channels (Website, App, Amazon), and Top 5 revenue-generating products.
![Executive Overview](page1_overview.png)

### 2. Category & Channel Deep-Dive
Evaluates promotional discount elasticity and Average Order Value (AOV) across sales channels to optimize pricing strategy.
![Category Deep-Dive](page2_deepdive.png)

### 3. Logistics & Reverse Supply Chain
Isolates unit loss and product returns by category and root cause.
![Logistics and Returns](page3_logistics.png)

---

## 💡 Strategic Business Insights & Takeaways
* **Apparel Sizing Risk:** Sizing/Fit issues drive 70% of all product returns, pushing the Apparel return rate to 47.6%. Improving sizing guides and fit tools will directly reduce return operational overhead.
* **Channel AOV Disparity:** The Website generates the highest AOV (₹6.9K), whereas Amazon yields ₹3.9K due to promotional discounting. Ad spend should prioritize direct-to-consumer channels.
* **Margin Anchors:** Electronics and Home & Living maintain strong profitability (>40% margin) with baseline zero-return rates, providing consistent bottom-line stability.

---

## 🛠️ Technical Implementation
* **Tool:** Microsoft Power BI Desktop
* **Data Modeling:** Star Schema architecture with clean 1-to-many dimensional relationships.
* **DAX Formulas:** Dynamic Outlier Labeling, Margin %, Return Rate % with baseline zero-handling, and Channel AOV calculations.
* **Visuals & Design:** KPI callout cards, dual-axis trend analysis, scatter plots for discount elasticity, and cross-report synchronized slicers.
