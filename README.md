# Retail-Sales-Analysis
Here’s a **README.md** for your SQL Retail Sales Analysis project based on the query file you shared:

---

# SQL Retail Sales Analysis

## 📌 Overview

This project analyzes a retail sales dataset using SQL. It covers the complete process from **database creation** and **data cleaning** to **exploratory data analysis (EDA)** and **business insights generation**.
The queries help in understanding customer behavior, sales trends, and performance across different product categories.

## 📂 Files in the Project

* **retail\_sales.sql** – Contains database creation, data cleaning, and analysis queries.

## 🛠 Technologies Used

* SQL (PostgreSQL syntax)
* Functions: `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `COUNT`, `SUM`, `AVG`, `ROUND`, `RANK`, `JOIN`, `CASE`

## 🚀 Steps Performed in the Project

### 1. **Database Creation & Table Setup**

* Created a database named `sql_project_p2`
* Defined the `retail_sales` table with fields like transaction\_id, sale\_date, sale\_time, customer\_id, gender, age, category, quantity, price\_per\_unit, cogs, and total\_sale

### 2. **Data Cleaning**

* Checked for `NULL` values in important columns (`transaction_id`, `sale_date`, `sale_time`, `gender`, `category`, `quantity`, `cogs`, `total_sale`)
* Deleted rows with missing critical data

### 3. **Exploratory Data Analysis (EDA)**

* Counted total sales and total unique customers
* Listed unique product categories

### 4. **Business Analysis Queries**

* **Q1:** Sales made on a specific date (2022-11-05)
* **Q2:** Clothing category sales with quantity > 4 in November 2022
* **Q3:** Total sales and orders per category
* **Q4:** Average customer age for 'Beauty' category purchases
* **Q5:** Transactions with total sales greater than 1000
* **Q6:** Transaction count by gender and category
* **Q7:** Best-selling month per year based on average sales
* **Q8:** Top 5 customers by total sales amount
* **Q9:** Unique customer count per category
* **Q10:** Sales distribution by time shifts (Morning, Afternoon, Evening)

## 📈 Key Insights (Sample)

* Identified top-performing months each year
* Found best-selling categories and customer demographics
* Discovered purchase patterns based on time of day

## 📜 How to Run the Project

1. Load the SQL script into your PostgreSQL environment.
2. Execute the database and table creation commands.
3. Run the cleaning queries to prepare the dataset.
4. Execute each analysis query to view results and insights.


If you want, I can also **write a short “Summary Insights” section** so it looks more professional for GitHub or resume use.
Do you want me to add that?
