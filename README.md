# 🛒 Online Retail Sales Performance Analysis | Power BI

## 📌 Overview
An analysis of U.S. online retail business performance from 2019 to 2022, covering multiple dimensions including product, category, customer segment, geographic region, and time. The project leverages Power BI to build an interactive dashboard that supports data-driven decision-making.

---

## 📂 Dataset
- **Source:** [SuperStore Dataset 2019–2022 – Kaggle]
- **Period:** 2019 – 2022
- **Scope:** 4 regions, 49 states, United States
- **Key fields:**
  - Transactions: `order_id`, `order_date`, `ship_date`
  - Products: `product_name`, `category`, `subcategory`, `manufactory`
  - Customers: `segment`
  - Geography: `region`, `state`, `city`
  - Business metrics: `revenue`, `quantity`, `discount`, `profit`, `profit_margin`

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data cleaning, standardization, and transformation
- **DAX** – Measure calculations and KPI 

---

## 📊 Dashboard

### Page 1 – Overview of Revenue
<img width="623" height="865" alt="Dashboard1" src="https://github.com/user-attachments/assets/5f09cff3-b0a2-41ec-8110-85d815c97fb6" />

A high-level view of overall business performance:
- Core KPIs: Total revenue ~$2M, profit $286.4K, profit margin 12%, total quantity 38K units
- Revenue and profit trends by year (2019–2022)
- Quarterly revenue trend with early 2023 forecast
- Revenue and quantity breakdown by category and subcategory
- Top 5 highest-revenue products
- Performance by customer segment (Consumer, Corporate, Home Office)
- Impact of discounts on revenue and profit across years

### Page 2 – Regional Revenue Analysis
<img width="1188" height="663" alt="Dashboard2" src="https://github.com/user-attachments/assets/06c8148f-9397-4954-bcff-340b806a2ac5" />

Geographic performance breakdown across the U.S.:
- Revenue distribution across 4 regions (West, East, South, Central)
- Top 5 states by revenue
- Profit and profit margin by region
- Profit breakdown by region and product category
- State-level revenue map

---

## 💡 Key Insights

**Overall Growth**
- Revenue grew steadily from $0.48M (2019) to $0.73M (2022). Profit margin peaked at 13.4% in 2021 before slightly declining to 12.7% in 2022 as the business scaled up.

**Product Categories**
- Technology leads in revenue ($836K) with a consistently strong profit margin above 12% and low reliance on discounts.
- Office Supplies accounts for the largest share of volume (~60%), driven by high-frequency repeat purchases rather than deep discounting.
- Furniture shows low and volatile profit margins, dropping to just ~1% in 2022, making it the highest-risk category in the portfolio.

**Geographic Performance**
- The West region is the most efficient market — highest revenue ($725K) and highest profit margin (15%).
- The Central region has the lowest profit margin (8%) and records negative profit from the Furniture category.
- All Top 5 revenue-generating states are concentrated on the East and West Coasts (California, New York, Texas, Washington, Pennsylvania).

**Seasonal Trends**
- Revenue consistently bottoms out in Q1 and peaks in Q4, with the highest recorded quarter reaching $89K in Q4 2022, reflecting a strong annual sales cycle.

**Discount & Volume Dynamics**
- Technology grew sales volume while maintaining the lowest average discount (~13%), indicating strong pricing power.
- Furniture relies on the highest discount levels (~17–18%) to drive demand, yet still fails to achieve meaningful profit margin improvement.
