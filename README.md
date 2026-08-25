# E-Commerce Data Analytics

## 📌 Project Overview

This project analyzes e-commerce sales data to identify sales trends, customer behavior, product performance, regional performance, and profitability.

The project follows an end-to-end data analytics workflow using Python, SQL, and Power BI.

---

## 🎯 Business Objectives

The main objectives of this project are:

- Analyze overall sales and revenue performance
- Identify top-performing products
- Analyze sales across different regions
- Identify the best-performing product categories
- Analyze monthly sales trends
- Understand customer purchasing behavior
- Analyze payment methods
- Identify repeat customers
- Analyze profitability
- Build an interactive Power BI dashboard

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
- **SQL**
  - MySQL
  - MySQL Workbench
  - MySQL Command Line
- **Power BI**
  - Data visualization
  - Dashboard development
- **Git & GitHub**
  - Version control
  - Project hosting

---

## 📂 Dataset

The project uses an e-commerce transaction dataset containing approximately 1,000 records.

The dataset contains information such as:

- Order ID
- Order Date
- Customer ID
- Customer Name
- Region
- City
- Category
- Sub-Category
- Product Name
- Quantity
- Price
- Discount
- Payment Mode
- Shipping Cost
- Profit
- Revenue
- Month

---

## 🐍 Python Data Analysis

Python was used for:

- Data loading
- Data cleaning
- Missing-value analysis
- Duplicate removal
- Data type conversion
- Feature creation
- Exploratory Data Analysis (EDA)
- Business insight generation
- Data visualization

### Visualizations

The analysis includes:

- Monthly Sales Trend
- Top 10 Products by Revenue
- Revenue by Region
- Revenue by Category
- Orders by Payment Mode
- Profit by Category

---

## 🗄️ SQL Analysis

MySQL was used to analyze the cleaned dataset.

Key SQL analysis includes:

- Database and table creation
- Total revenue calculation
- Top product analysis
- Region-wise sales analysis
- Category analysis
- Repeat customer analysis
- Aggregation using `GROUP BY`
- Filtering using `HAVING`
- Sorting using `ORDER BY`

The SQL queries are available in:

`sql/ecommerce_analytics.sql`

---

## 📊 Power BI Dashboard

Power BI was used to create an interactive dashboard for business analysis.

The dashboard focuses on:

- Total Revenue
- Total Profit
- Total Orders
- Average Order Value
- Monthly Sales
- Regional Performance
- Category Performance
- Product Performance
- Customer Analysis

Power BI file:

`powerbi/ecommerce_dashboard.pbix`
The Power BI dashboard provides an interactive view of e-commerce sales,
profitability, product performance, regional performance, and customer behavior.

### Dashboard Preview

![Power BI Dashboard](powerbi/dashboard_overview.jpg)

---
## 💡 Key Business Insights

The analysis identified the following key business findings:

- **Best Performing Region:** West
- **Best Performing Category:** Electronics
- **Top Product:** Laptop
- **Best Sales Month:** April
- **Most Used Payment Mode:** UPI
- **Repeat Customer Percentage:** 55.75%
- **Most Profitable Payment Mode:** UPI

These findings can help the business identify high-performing regions, products, categories, customer behavior, and payment preferences.

---

## 📁 Project Structure

```text
ecommerce_project/
│
├── data/
│   ├── raw/
│   │   └── ecommerce.csv
│   │
│   └── cleaned/
│       └── ecommerce_cleaned.csv
│
├── notebook/
│   └── ecommerce_analysis.ipynb
│
├── sql/
│   └── ecommerce_analytics.sql
│
├── powerbi/
│   └── ecommerce_dashboard.pbix
│
├── .gitignore
└── README.md