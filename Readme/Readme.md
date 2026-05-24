# E-Commerce Sales Analysis – Exploring Revenue, Customer Behavior & Marketplace Performance

*.Analyzing e-commerce sales data to uncover business insights related to revenue growth, customer retention, seller performance, and operational efficiency using SQL and Python.*

---

# E-Commerce Sales Data Analysis Project

## Live Dashboard

Live Dashboard:   https://zainbaloach.github.io/Sales-Data-Analysis/
Live Report: https://zainbaloach.github.io/Sales-Data-Analysis/


## Project Files

* Dashboard: Dashboard.html
* Report: Sales Data Analysis Report.html

---

## Table of Contents

## 📑 Table of Contents

* [Overview](#overview)
* [Business Problem](#business-problem)
* [Dataset](#dataset)
* [Tools & Technologies](#tools--technologies)
* [Project Structure](#project-structure)
* [Data Cleaning & Preparation](#data-cleaning--preparation)
* [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
* [SQL Analysis & Business Questions](#sql-analysis--business-questions)
* [Key Findings](#key-findings)
* [Dashboard](#dashboard)
* [How to Run This Project](#how-to-run-this-project)
* [Final Recommendations](#final-recommendations)
* [Author & Contact](#author--contact)

---

## Overview - E-Commerce Sales Analysis

This project analyzes a large e-commerce marketplace dataset to understand customer purchasing behavior, sales trends, payment patterns, seller performance, and operational efficiency.

The analysis was primarily performed using SQL queries executed through Python in Jupyter Notebook by connecting a SQL database with Python. The project combines business analysis with data visualization to generate actionable insights from real-world sales data.

---

## Business Problem

E-commerce businesses generate large amounts of transactional data, but extracting meaningful insights from that data is essential for improving decision-making and growth.

This project focuses on:

* Understanding sales performance over time
* Identifying high-performing product categories and sellers
* Exploring customer purchasing and retention behavior
* Analyzing payment and installment trends
* Evaluating delivery performance and operational efficiency
* Generating business insights using SQL-based analysis

---

## Dataset

The project uses a multi-table e-commerce dataset containing:

* Customers
* Orders
* Order Items
* Payments
* Products
* Sellers
* Product Category Translation

The dataset includes information related to:

* Orders and purchases
* Customer locations
* Product categories
* Seller information
* Revenue and payments
* Delivery timelines

---

## Tools & Technologies

* SQL (MySQL)
* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* GitHub

---

## Project Structure

```bash
ecommerce-sales-analysis/
│
├── README.md
│
├── Data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   ├── payments.csv
│   ├── products.csv
│   ├── sellers.csv
│   
│
├── Dashboard/
│   └── Dashboard.html
│
├── Project Report/
│   └── Sales Data Analysis Report.html
│
├── Notebooks/
│   └── customer(SQL)-Data-Analysis.ipynb
│
├── Images/
│   └── Dashboard.png
```

---

## Data Cleaning & Preparation

* Connected SQL database with Python using Jupyter Notebook
* Imported and organized multiple CSV files into relational tables
* Checked for missing values and inconsistencies
* Performed joins across multiple tables for analysis
* Converted and handled date/time columns for time-series analysis
* Prepared datasets for SQL querying and visualization

---

## Exploratory Data Analysis (EDA)

The project explores:

* Monthly and yearly sales trends
* Revenue contribution by product categories
* Customer distribution by city and state
* Seller performance and rankings
* Payment methods and installment usage
* Delivery and operational performance
* Customer retention behavior

Visualizations and SQL analysis were used together to better understand marketplace performance and customer activity.

---

## SQL Analysis & Business Questions

The following business problems were solved using SQL queries:

* Listed unique cities where customers are located
* Counted the number of orders placed in 2017
* Calculated total sales per product category
* Calculated the percentage of orders paid in installments
* Counted customers from each state
* Calculated monthly order trends in 2018
* Found average number of products per order grouped by customer city
* Calculated revenue contribution by product category
* Identified correlation between product price and purchase frequency
* Ranked sellers by total revenue generated
* Calculated moving average of customer order values
* Calculated cumulative monthly sales for each year
* Calculated year-over-year sales growth
* Measured customer retention rate within six months
* Identified top three highest-spending customers each year

Advanced SQL concepts used:

* Joins
* CTEs
* Aggregate Functions
* Window Functions
* Ranking Functions
* Date Functions
* Group By & Having Clauses

---

## Key Findings

* Revenue showed strong month-over-month growth throughout the analysis period
* São Paulo contributed the highest share of total revenue
* Credit cards were the dominant payment method
* Most customers made only one purchase, highlighting low retention
* Delivery success and on-time fulfillment rates were strong
* A small group of sellers generated a significant portion of total revenue
* Certain product categories consistently contributed the highest sales

---

## Dashboard

An interactive dashboard and executive-style report were created to visualize:

* Revenue trends
* Order growth
* Product category performance
* Delivery insights
* Seller rankings
* Customer retention patterns
* Payment behavior

AI tools were used to help improve the dashboard design, layout, and report presentation.
## Live Dashboard & Report Link:

https://zainbaloach.github.io/Sales-Data-Analysis/

---

## How to Run This Project

Clone the repository:

```bash
git clone https://github.com/zainbaloach/Sales-Data-Analysis.git
```

Open the notebook:

```bash
notebooks/customer(SQL)-Data-Analysis.ipynb
```

Install required libraries:

```bash
pip install pandas numpy matplotlib mysql-connector-python
```

---

## Final Recommendations

* Improve customer retention through loyalty and re-engagement strategies
* Expand seller presence across more geographic regions
* Optimize delayed delivery routes and logistics operations
* Use category-level sales insights for targeted marketing
* Encourage repeat purchases through personalized offers
* Continue monitoring YoY growth and seller concentration trends

---

## Author & Contact

**Zain**
Aspiring Data Analyst

📧 Email: [zainbaloach007@gmail.com](mailto:zainbaloach007@gmail.com)
🔗 LinkedIn: https://www.linkedin.com/in/zainb1/
🔗 GitHub: [https://github.com/zainbaloach](https://github.com/zainbaloach)
