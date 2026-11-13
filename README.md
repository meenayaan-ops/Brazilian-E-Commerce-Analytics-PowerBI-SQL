📊 Brazilian E-Commerce Analytics Dashboard

Brazilian E-Commerce Dashboard
🛒 Olist Analytics: Brazilian E-Commerce Sales, Delivery & Customer Insights Dashboard

An interactive Power BI report built to explore Brazilian e-commerce data across revenue trends, delivery performance, seller quality and customer behaviour, with filters for state, payment type and year.

The Brazilian E-Commerce Dashboard is a two-page Power BI report that helps users understand how an online marketplace performs between September 2016 and October 2018. The Executive Dashboard tracks revenue, orders, average order value, customer ratings and late deliveries. The Customer Analytics page segments customers using RFM (Recency, Frequency, Spend) across 27 states and 4,000+ cities

Tech Stack
Power BI – report design, visuals, slicers, bookmarks
DAX – KPIs and measures (revenue, AOV, late delivery %, repeat customer %, RFM segment counts)
MySQL – analytical views for monthly revenue, category sales, state sales, seller performance and RFM scoring
Power Query – data loading and cleaning
Dataset – Olist Brazilian E-Commerce Dataset (Kaggle)

Dashboard Pages

1. Executive Dashboard

KPI cards: total revenue, orders, customers, AOV, average rating, late delivery %
Monthly revenue and order trend
Payment type split
Review score distribution
Revenue and orders against delivery days and late delivery %
Slicers for state, payment type and purchase date, with a Reset Filters button

2. Customer Analytics

RFM customer segmentation (5 segments)
Customers by state on a map
Average recency, frequency and spend by segment
Top cities by revenue
Repeat customer % and average orders per customer
Key Insights
Revenue should be driven by focusing on high-value customer regions.
Logistics needs optimisation for high-freight product categories.
Quality needs improvement for top-selling sellers.
New customers form the largest segment, while Champions and Loyal customers are a smaller group worth nurturing.


How to Use
Download the dataset from Kaggle: Olist Brazilian E-Commerce Dataset.
Load the data into a MySQL database named olist and create the analytical views (SQL scripts in the sql folder).
Open Brazilian_ECommerce_Dashboard.pbix in Power BI Desktop.
Update the data source paths to your local setup and click Refresh.
