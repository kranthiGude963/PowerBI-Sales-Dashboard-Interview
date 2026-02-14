# PowerBI-Sales-Dashboard-Interview
Executive Sales Performance Dashboard built in Power BI with DAX, interactive slicers, KPI metrics, and actionable business insights.

![Dashboard Preview](images/dashboard_preview.png)


**Sales Performance Dashboard – Power BI**
🔹 **Project Objective**

This dashboard was built as part of an interview assessment to deliver an executive-level summary answering three core business objectives:

Performance

Trend

Efficiency

The design ensures decision-makers can understand performance within one minute.

🔹** Business Questions Answered**

Which regions and products drive the highest sales?

How is performance trending monthly?

Are high sales translating into strong profitability?

Where should management take action?

🔹** Key KPIs**

Total Sales

Total Profit

Profit Margin %

All KPIs were built using DAX measures:

Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales])

🔹 **Dashboard Features**

Interactive slicers (Product, Region, Month)

Monthly trend analysis

Top 3 ranking visuals

Margin comparison by Product and Region

Insight callouts with business recommendations

🔹 **Key Insights**

North region leads in sales and profit.

Product B drives high revenue but lower margin in East region.

Pricing review recommended for Product B in East.

🔹 **Technical Implementation**

Data modelling with Month Number sorting

Chronological month hierarchy

Clean numeric formatting

Optimized DAX using SUM and DIVIDE

Single-page executive layout

🔹 **Tools Used**

Power BI

DAX

Excel

