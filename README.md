# Superstore Sales Analysis | Excel, Power BI, DAX, Power Query

**Business Problem**

* Superstore lacks a clear understanding of sales dynamics across products, customer segments, and regions. W
  ith data from 2019–2020, the business seeks to uncover hidden inefficiencies, unprofitable areas, and growth
  opportunities using data analysis and visualization.

**Objective**

* To design an interactive Power BI dashboard using cleaned sales data to:
* Track key performance metrics (Sales, Profit, Quantity, Returns).
* Visualize performance by time, product category, region, and customer segment.
* Uncover trends and patterns to support strategic decision-making.

**Tools & Techniques**

* **Excel:** 	Data cleaning, pre-processing
* **Power Query	ETL process :** importing, transforming data
* **Power BI :**	Visualization and dashboard creation
* **DAX :**	Custom measures and KPIs (e.g., Profit Margin %, YoY Growth)

 **Key Metrics & DAX Measures**
 ``` dax
DAX

Total Sales = SUM(SuparStore[Sales])
Total Profit = SUM(SuperStore[Profit])
Month_Order = FORMAT(SuperStore[Order Date],"MMMM")
Average_delivery = DATEDIFF(SuperStore[Order Date].[Date],SuperStore[Ship Date].[Date],DAY)
Order_year = YEAR(SuperStore[Order Date].[Date])
```

**Dashboard Features**

Your Power BI dashboard can include:

* KPIs: Total Sales, Total Profit, Quantity, Average Delivery
* Filters/Slicers: Year, Month, Region

* **Visuals:**
  
* Sales and Profit by Category/Sub-Category (Bar chart)
* Profit by Region and State (Map)
* Monthly Sales and Profit (Area Chart)
* Segment and Payment ( Donut Chart)

**Insight**

* products had the highest sales but the lowest profit margin. This suggests the need to review pricing or supplier costs to improve overall profitability."


