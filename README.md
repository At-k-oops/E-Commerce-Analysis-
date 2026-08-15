🛒 E-Commerce Data Analysis & Interactive Power BI Dashboard

An end-to-end E-Commerce Data Analytics project combining Python, Pandas, NumPy and Power BI to clean, transform, analyze and visualize 250,000+ order records, along with customer and product information.

The project focuses on understanding customer behavior, product performance, sales trends, order quality, customer-sales relationships and product-sales performance through interactive business dashboards.

📌 Project Overview

This project analyzes a large-scale e-commerce dataset containing:

250K+ Orders
40K Customers
2,000 Products
Multiple product categories and brands
Customer demographics
Order status and payment information
Sales and discount information
Shipping costs
Product inventory
Customer tiers
Order validity/corruption information

The analysis was performed in Python for data preparation and exploration and then brought into Power BI for interactive business intelligence and storytelling.

Overall Workflow

Raw E-Commerce Data
        --->
Python Data Processing
        --->
Data Cleaning & Transformation
        --->
Exploratory Data Analysis
        --->
Derived / Analysis-Ready Datasets
        --->
Power BI Data Model
        --->
DAX Measures & Calculations
        --->
Interactive 5-Page Dashboard
        --->
Business Insights

🛠️ Tools & Technologies

Tool	Purpose

🐍 Python	Data processing, cleaning and analysis

🐼 Pandas	Data manipulation and transformation

🔢 NumPy	Numerical operations

📊 Power BI	Interactive dashboard and visualization

📐 DAX	Measures and analytical calculations

📁 Excel/CSV	Data storage and intermediate datasets

🔗 GitHub	Project version control and documentation

🐍 Python Analysis

Python was used as the first stage of the analytical workflow rather than directly building the dashboard from raw data.

Python workflow included:

Loading raw datasets
Inspecting dataset structure
Understanding columns and data types
Data quality checks
Identifying invalid/corrupted records
Handling missing/inconsistent data
Data transformation
Creating analysis-ready datasets
Generating derived fields required for analysis
Preparing datasets for Power BI
Exploratory analysis of customers, products and orders

The processed datasets were subsequently used as inputs for the Power BI dashboard.

Python Libraries

Pandas and Numpy

📊 Power BI Dashboard

The final Power BI report contains 5 analytical pages.

1️⃣ Customer Analysis

This page focuses on understanding the customer base and its demographic distribution.

Key KPIs-->
Total Customers,
Top Customer City,
Top Customer State,
Largest Customer Age Group,

Analysis -->
Customer distribution by state,
Customer information by city,
Monthly customer registrations,
Customer registration by year,
Gender distribution,
Customer age-group distribution,
Customer tier vs order status,

Key Question

Who are the customers and where are they coming from?

2️⃣ Product Analysis

This page analyzes the company's overall product portfolio and inventory.

Key KPIs-->
Total Products,
Top Brand,
Top Category

Analysis-->
Products by brand,
Product inventory by brand,
Product distribution by category and brand,
Brand review performance,
Average product ratings,
Category-level product distribution,

Key Question

What does the company's product portfolio look like and how are products distributed across brands and categories?

3️⃣ Sales Analysis

This page provides an overall view of sales and order performance.

Key KPIs-->
Total Sales,
Valid Sales,
Corrupted Sales,
Total Orders,
Valid Orders,
Corrupted Orders,

Analysis -->
Sales comparison by state,
Orders by order status,
Monthly sales trends,
Shipping costs by state,
Order delivery days,
Payment method distribution,
Yearly sales performance,

Key Question

How is the business performing in terms of sales, orders and operational efficiency?

4️⃣ Customer-Sales Analysis

This page connects customer characteristics with actual sales performance.

Key Analysis -->
Top customer identification,
Top customer name,
Top customer state,
Customer tier,
Customer tier vs order status,
State and city valid-order analysis,
Yearly sales comparison,
Age-wise sales,
City × Month sales matrix,
Total, valid and corrupted sales,
Total spending.

Key Question

Which customers and customer segments contribute to the business's sales performance?

The City × Month matrix provides a more granular view of sales performance across time and geography.

5️⃣ Product-Sales Analysis

The final page connects product-level information with order and sales performance.

Key KPIs -->
Product with Most Valid Orders,
Product with Maximum Sales,
Product with Most Corrupted Orders.

Analysis-->
Brand discount details,
Category-wise sales,
Category order quantity,
Valid vs corrupted orders,
Stock quantity vs order quantity,
Category total orders,
Average product rating,
Product-level sales performance,

Key Questions

Which products generate the most business value?

Which products have order-quality issues?

How does inventory relate to customer demand?

📈 Key Business Metrics

The dashboard provides visibility into metrics such as:

Sales
Total Sales: ₹5.93B

Valid Sales: ₹5.33B

Corrupted Sales: ₹602.55M

Orders

Total Orders: 250K

Valid Orders: 225K

Corrupted Orders: 25K

Customers

Total Customers: 40K

Products

Total Products: 2,000

These metrics allow the dashboard to distinguish between overall business activity and valid/usable business activity.

🔍 Key Analytical Areas

The project investigates five major business dimensions:

👥 Customer
Who are the customers?

Which states/cities have the largest customer base?

Which age groups dominate?

How are customers distributed across tiers?

How does customer tier relate to order status?

📦 Product

Which brands have the largest product presence?

Which categories dominate the catalog?

How is inventory distributed?

How do product ratings vary?

💰 Sales

Which states generate the most sales?

How does sales performance change over time?

Which months perform best?

How much sales value is affected by corrupted orders?

🚚 Operations

What are the major order statuses?

How do shipping costs vary geographically?

What are the delivery-day patterns?

Which payment methods are most commonly used?

🎯 Customer & Product Performance

Who is the top customer?

Which products generate maximum sales?

Which products receive the most valid orders?

Which products have the most corrupted orders?

How does inventory relate to order quantity?

🧮 Power BI & DAX

The dashboard uses DAX measures and calculations to derive analytical KPIs and dynamically respond to filters.

Examples of analytical calculations include:

Total Sales,
Valid Sales,
Corrupted Sales,
Total Orders,
Valid Orders,
Corrupted Orders,
Customer counts,
Top customer identification,
Top customer attributes,
Age-group analysis,
Sales aggregation,
Order analysis,
Product performance metrics.

Interactive slicers allow users to analyze the dashboard based on dimensions such as:

Customer Age Group,
State,
Category,
Brand.

📊 Dashboard Design

The report was designed around a consistent visual structure:

                    KPI CARDS
        ─────────────────────────────
             FILTERS / SLICERS
        ─────────────────────────────
        MAIN BUSINESS VISUALIZATIONS
        ─────────────────────────────
       DETAILED ANALYSIS / BREAKDOWN

A consistent navigation panel allows users to move between the five analytical sections.

🎯 Project Objectives

The primary objectives were to:

Analyze a large e-commerce dataset using Python.
Perform data cleaning and transformation.
Identify data-quality issues.
Create analysis-ready datasets.
Build meaningful business KPIs.
Analyze customer behavior.
Analyze product and inventory performance.
Evaluate sales and order performance.
Connect customers/products with sales.
Build an interactive Power BI report.
Present findings through business-oriented data storytelling.

💡 Business Insights

The dashboard enables several business-level observations, including:

A significant portion of overall order value comes from valid transactions.
Sales performance differs substantially between states.
Customer concentration varies geographically.
Different customer tiers show different order-status patterns.
Product categories contribute differently to sales and order volume.
Inventory levels can be compared directly with order quantities.
Certain products stand out in terms of valid orders, sales and corrupted orders.
Monthly and yearly trends reveal changes in business performance.
Shipping costs vary significantly across states.

🚀 What This Project Demonstrates

This project demonstrates practical experience with:

Data Cleaning
Data Transformation
Exploratory Data Analysis
Python / Pandas
NumPy
Data Quality Analysis
Business Intelligence
Power BI
DAX
Data Visualization
Dashboard Design
Interactive Filtering
KPI Development
Business Storytelling
Customer Analytics
Product Analytics
Sales Analytics
Operational Analytics

📌 Project Highlights

🔹 Data Scale

250K+ orders | 40K customers | 2K products

🔹 Analytical Layers

Python → Data Preparation → Power BI → DAX → Business Storytelling

🔹 Dashboard Pages

5 interactive analytical pages

Customer Analysis
<img width="1290" height="717" alt="Screenshot 2026-08-15 172341" src="https://github.com/user-attachments/assets/c67c203d-ac1e-480e-bd70-21709ee998e3" />

Product Analysis
<img width="1286" height="722" alt="Screenshot 2026-08-15 172418" src="https://github.com/user-attachments/assets/5384f700-9859-4a86-b18f-8c511b1c2b2c" />

Sales Analysis
<img width="1280" height="719" alt="Screenshot 2026-08-15 172456" src="https://github.com/user-attachments/assets/0354a2ef-1250-4e10-a3b7-9da2b5934bbe" />

Customer-Sales Analysis
<img width="1288" height="712" alt="Screenshot 2026-08-15 172527" src="https://github.com/user-attachments/assets/baba9a1e-7762-4fc1-a81e-dae59eb2c136" />

Product-Sales Analysis
<img width="1285" height="724" alt="Screenshot 2026-08-15 172557" src="https://github.com/user-attachments/assets/1d700ed8-15ad-4094-aff9-87e6e72febf9" />


🧠 Conclusion

This project goes beyond simply creating Power BI charts.

It demonstrates an end-to-end analytical workflow where raw e-commerce data is processed using Python, transformed into analysis-ready datasets, analyzed through DAX and Power BI, and presented through an interactive five-page business intelligence dashboard.

The final report provides a unified view of customers, products, sales, orders, operations and performance, allowing users to move from high-level KPIs to detailed customer, product, geographical and time-based analysis.

👨‍💻 Author

Atharva Khare

Data Analyst | Python | SQL | Power BI | Data Analytics

📧 Email: atharvakhare80@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/atharva-khare-b1bb933a3
