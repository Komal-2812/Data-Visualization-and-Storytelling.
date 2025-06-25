📊 Task 2: Data Visualization and Storytelling
Tool Used: Power BI  
Dataset: Sample - Superstore.csv

🎯 Objective
Create a business-ready Power BI dashboard to analyze and present insights from Superstore sales data using visual storytelling techniques. 
This includes key KPIs, profit analysis, customer trends, and regional performance using interactive elements like slicers and page navigation buttons.

📁 Dataset Overview
The dataset contains historical sales transactions for a fictional retail Superstore. It includes details such as:
- Customer demographics
- Product categories and sub-categories
- Sales and profit metrics
- Geographical distribution (Region, State)
- Shipping modes and order dates

📊 Dashboard Features:

✅ Page 1: Executive Overview
- KPIs: Total Sales, Total Profit, Total Orders, Profit Margin
- Line Chart: Monthly Sales Trend
- Map: Profit by State
- Bar Charts: Sales & Profit by Category
- Pie Chart: Orders by Ship Mode
- Navigation Button: Go to Details Page

✅ Page 2: Customer & Segment Insights
- Table with Conditional Formatting: Profit margin by customer
- Scatter Plot: Sales vs Profit
- Segment vs Region Analysis 
- Discount vs Profit Trend 
- Back to Overview Button

🧠 DAX Measures Used
DAX
Profit Margin = DIVIDE(SUM('Orders'[Profit]), SUM('Orders'[Sales]), 0)
Order Count = DISTINCTCOUNT('Orders'[Order ID])

📌 Key Insights
- Technology category leads in sales but has varying profit margins.
- West region performs best overall; Central has loss-making states.
- Corporate segment generates the highest sales.
- Top 10 customers contribute significantly to total revenue.
- Standard Class is the most used shipping method.
- Sales spike in Q4, suggesting a seasonal pattern.
  

