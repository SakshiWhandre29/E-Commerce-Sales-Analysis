.

🌟 E-Commerce Sales & Customer Insights Analysis
End-to-End Portfolio Project (Python • Power BI • Data Modeling)

📌 Project Summary

This project demonstrates my complete data analytics workflow — from raw data to a fully interactive business dashboard.
I performed:

✔ Data cleaning

✔ Exploratory Data Analysis (EDA)

✔ Customer segmentation

✔ Feature engineering

✔ DAX modeling

✔ Power BI dashboard creation

✔ Business insights + recommendations


This showcases the skills I would apply in a real company to analyze e-commerce performance and customer behavior.

🎯 Objective

To help an e-commerce business understand:

What drives their revenue

Who their best customers are

Which categories/products perform best

When customers purchase the most

How repeat customers contribute to growth

🧰 Skills Demonstrated

🔹 Python

Data Cleaning

Feature Engineering

EDA (Trends, Patterns, Outliers)

Aggregations

Customer Segmentation

🔹 Power BI

Data Modeling

DAX Measures

KPI Cards

Treemap, Line Chart, Bar Chart, Donut Chart

Sorting, filtering, relationship setup

Dashboard design best practices

🔹 Analytics Skills

Business understanding

Data storytelling

Insight generation

RFM-style customer grouping

🗂️ Portfolio Project Workflow


📍 Phase 1 — Data Understanding & Cleaning

Removed duplicates

Standardized category names

Converted dates

Engineered:

Month

Weekday

Quarter

Year

Identified missing values

Basic sanity checks

Files:
ecommerce_raw.csv → cleaned → ecommerce_cleaned.csv


📍 Phase 2 — Exploratory Data Analysis (Python)

Key analysis performed:

Sales trend by month

Orders per weekday

Revenue by category

Top selling products

Average order value

New vs repeat customers

Customer frequency patterns

Notebook:
EDA_ecommerce.ipynb

📍 Phase 3 — Customer Segmentation

Created repeat customer indicator:

df['CustomerType'] = df['CustomerID'].map(
    lambda c: 'Repeat Customer' if customer_counts[c] > 1 else 'New Customer'
)


Exported final dataset:
ecommerce_day4_segmented.csv

📍 Phase 4 — Power BI Dashboard Development

⚡ KPIs Built

Total Sales

Total Profit

Total Orders

Average Order Value (AOV)

Repeat Customer Count

📊 Dashboard Visuals

Sales by Month (Line Chart)

Sales by Weekday (Column Chart)

Top Products (Bar Chart)

Sales by Category (Treemap)

Customer Segmentation (Donut Chart)

Profit vs Sales Scatterplot

Filters Panel

🧮 Important DAX

Total Sales = SUM('Data'[Amount])

Total Orders = DISTINCTCOUNT('Data'[OrderID])

AOV = DIVIDE([Total Sales], [Total Orders])

Repeat Customers = CALCULATE(DISTINCTCOUNT(Data[CustomerID]), Data[CustomerType] = "Repeat Customer")


🖼️ Final Dashboard Snapshot


(E-Commerce-Sales-Analysis/Screenshot.png)


![Dashboard Preview](E-Commerce-Sales-Analysis
/Dashboard/
)

💡 Key Business Insights

📌 1. Strong Repeat Customer Contribution

Repeat customers contributed a significant portion of sales — highlighting strong retention.

📌 2. Category A dominates revenue

Category A accounts for the largest share of total sales.

📌 3. Weekends show peak sales

Saturday and Sunday show the highest number of orders.

📌 4. Top products generate ~40% revenue

A small group of products drive most sales → classic 80/20 rule.

📌 5. Monthly sales show seasonal spikes

Certain months (e.g., Aug–Oct) show strong performance.

📁 Project Folder Structure

📦 E-Commerce-Sales-Portfolio
│
├── data/
│   ├── ecommerce_raw.csv
│   ├── ecommerce_cleaned.csv
│   └── ecommerce_day4_segmented.csv
│
├── notebook/
│   └── EDA_ecommerce.ipynb
│
├── dashboard/
│   └── ecommerce_dashboard.pbix
│
└── README.md

🚀 How to Use / Run This Project

Clone the repository

Open the notebook/EDA_ecommerce.ipynb file

Explore → clean → model the data

Load ecommerce_day4_segmented.csv into Power BI

Add DAX measures

View dashboard

🙋‍♀️ About Me

Sakshi Whandre
Aspiring Data Analyst
🔍 Passion for Analytics • Power BI • SQL • Python
📧 Email: sakshiwhandre2905@gmail.com

🔗 LinkedIn: linkedin.com/in/sakshi-whandre-8a685a227
