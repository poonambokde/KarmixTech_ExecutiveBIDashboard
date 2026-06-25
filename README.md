Executive Business Intelligence Dashboard

📌 Overview

This project is an end-to-end Executive Business Intelligence Dashboard built as part of the Data Analyst Internship at Karmix Tech. It analyzes company-wide sales and profitability performance across regions, product categories, and customer segments — designed to help leadership quickly understand business health and take data-driven decisions.

🎯 Business Problem

Senior management needed a single view to answer:


What happened? — How is overall revenue, profit, and growth trending?
Why did it happen? — Which categories, regions, or segments are driving or dragging performance?
What action should be taken? — Where should the business focus investment or cut losses?


📊 Dataset


Source: Custom-generated retail sales dataset simulating real Indian business transactions
Size: 6,000 records | 3-year span (2022–2024)
Key fields: Order Date, Region, State, City, Category, Sub-Category, Customer Segment, Quantity, Discount, Sales, Profit


🛠️ Tools & Technologies


Python (Pandas) — Data exploration & KPI validation
Power BI — Dashboard development, DAX measures, data modeling
DAX — Profit Margin % measure, Year calculation
GitHub — Version control & project documentation


🔄 Project Workflow


Data loading & quality check (null values, data types)
Exploratory Data Analysis in Python — validated Sales, Profit, Category, Region, and Year-wise trends
Data import into Power BI, data type corrections, DAX measure creation
Dashboard design following a professional executive layout
Insight extraction & storytelling


📈 KPIs Tracked

KPIBusiness MeaningTotal SalesRevenue generatedTotal ProfitNet profitabilityProfit Margin %Operational efficiencyTotal QuantitySales volume

🖥️ Dashboard Structure


Top Section: KPI Cards — Total Sales, Total Profit, Profit Margin %, Total Quantity
Middle Section: Sales & Profit Trend (Line), Profit by Category (Bar), Sales & Profit by Region (Column), Sales by Customer Segment (Donut)
Bottom Section: Detailed table — Category, Sub-Category, Region-wise Sales, Profit, and Margin %
Side Section: Slicers for Region, Category, Customer Segment, and Year
Insights Box: Key business takeaways for stakeholders


💡 Key Insights


Overall profit margin stands at just 4.69%, significantly impacted by consistent losses in the Furniture category.
Electronics is the strongest performer, contributing the highest revenue and profit — a strong candidate for further investment.
Sales dipped in 2023 but recovered in 2024, indicating a need to review seasonal and demand-driven factors.
All four regions (North, South, East, West) perform at a similar scale, with West marginally leading in both sales and profit.
Consumer segment drives over half of total sales (56%), followed by Corporate (30%) and Small Business (14%).


📁 Repository Structure

KarmixTech_ExecutiveBIDashboard/
│
├── Executive_BI_Dashboard.pbix      # Power BI dashboard file
├── Executive_BI_Sales_Dataset.csv   # Dataset used
├── README.md                        # Project documentation
└── screenshots/                     # Dashboard preview images

🚀 How to View


Clone/download this repository
Open Executive_BI_Dashboard.pbix in Power BI Desktop
Explore the dashboard using the slicers (Region, Category, Customer Segment, Year)


🙋‍♀️ Author

Poonam Bokade
Data Analytics Intern @ Karmix Tech
📌 #KarmixTech #DataAnalytics #PowerBI


This project was completed as part of the Karmix Tech Data Analyst Internship program.
