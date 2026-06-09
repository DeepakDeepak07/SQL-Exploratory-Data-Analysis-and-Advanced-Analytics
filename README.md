# 🚀 SQL Exploratory Data Analysis & Advanced Analytics Project

## 📌 Project Overview

This project demonstrates a complete SQL analytics workflow, starting with database exploration and exploratory data analysis (EDA), then progressing into advanced analytical techniques and business reporting.

Using SQL Server and T-SQL, the project transforms raw sales data into actionable business insights through customer analytics, product analytics, segmentation, trend analysis, and performance reporting.

The project follows a structured analytics lifecycle used by professional data analysts and business intelligence teams.

---

## 🎯 Project Objectives

The primary goals of this project are to:

* Explore and understand a relational database structure
* Perform Exploratory Data Analysis (EDA)
* Analyze customer and product behavior
* Measure business performance over time
* Identify top-performing products and customers
* Build reusable analytical reports
* Demonstrate advanced SQL analytical techniques

---

# 🏗️ Database Architecture

The project uses a Star Schema design consisting of:

### Fact Table

| Table      | Description                        |
| ---------- | ---------------------------------- |
| fact_sales | Stores transactional sales records |

### Dimension Tables

| Table         | Description                           |
| ------------- | ------------------------------------- |
| dim_customers | Customer information and demographics |
| dim_products  | Product attributes and hierarchy      |

### Reporting Views

| View             | Description                                  |
| ---------------- | -------------------------------------------- |
| report_customers | Customer performance and segmentation report |
| report_products  | Product performance and segmentation report  |

---

# 📂 Project Structure

```text
SQL-Exploratory-Data-Analysis-and-Advanced-Analytics
│
├── datasets/
│   └── csv-files/
│
├── scripts/
│   ├── 00_init_database.sql
│   ├── 01_database_exploration.sql
│   ├── 02_dimensions_exploration.sql
│   ├── 03_date_range_exploration.sql
│   ├── 04_measures_exploration.sql
│   ├── 05_magnitude_analysis.sql
│   ├── 06_ranking_analysis.sql
│   ├── 07_change_over_time_analysis.sql
│   ├── 08_cumulative_analysis.sql
│   ├── 09_performance_analysis.sql
│   ├── 10_data_segmentation.sql
│   ├── 11_part_to_whole_analysis.sql
│   ├── 12_report_customers.sql
│   └── 13_report_products.sql
│
├── images/
│
└── README.md
```

---

# 🔍 Exploratory Data Analysis (EDA)

EDA is performed to understand the structure, quality, and characteristics of the dataset before conducting deeper business analysis.

## 1️⃣ Database Exploration

Investigates database objects and structure.

### Analysis Includes

* Tables and schemas
* Fact and dimension relationships
* Dataset structure

---

## 2️⃣ Dimensions Exploration

Examines categorical attributes within the business.

### Analysis Includes

* Customer countries
* Product categories
* Product subcategories
* Product catalog structure

---

## 3️⃣ Date Range Exploration

Analyzes historical coverage of the dataset.

### Analysis Includes

* First order date
* Last order date
* Order history duration
* Customer age distribution

---

## 4️⃣ Measures Exploration

Calculates core business metrics.

### KPIs Generated

* Total Sales
* Total Orders
* Total Customers
* Total Products
* Total Quantity Sold
* Average Selling Price

---

## 5️⃣ Magnitude Analysis

Measures business volume across dimensions.

### Analysis Includes

* Revenue by category
* Revenue by customer
* Customer distribution by country
* Product distribution by category
* Sales volume by country

---

## 6️⃣ Ranking Analysis

Identifies top and bottom performers.

### Analysis Includes

* Top revenue-generating products
* Lowest-performing products
* Highest-value customers
* Customers with the fewest orders

### SQL Concepts

* TOP
* RANK()
* Window Functions

---

# 📈 Advanced SQL Analytics

After EDA, advanced analytics techniques are applied to uncover deeper business insights.

---

## 7️⃣ Change Over Time Analysis

Analyzes business performance across time periods.

### Metrics

* Monthly Sales
* Monthly Customers
* Monthly Quantities Sold

### SQL Concepts

* YEAR()
* MONTH()
* DATETRUNC()
* FORMAT()

---

## 8️⃣ Cumulative Analysis

Calculates running totals and cumulative business performance.

### Examples

* Running Revenue
* Running Orders
* Running Quantity Sold

### SQL Concepts

* Window Aggregates
* SUM() OVER()

---

## 9️⃣ Performance Analysis

Compares current performance against historical benchmarks.

### Analysis Includes

* Year-over-Year Growth
* Previous Year Comparisons
* Product Performance Trends

### SQL Concepts

* LAG()
* AVG() OVER()
* CASE Statements

---

## 🔟 Data Segmentation

Groups customers and products into meaningful business segments.

### Product Segments

* Below 100
* 100–500
* 500–1000
* Above 1000

### Customer Segments

* VIP
* Regular
* New

---

## 1️⃣1️⃣ Part-to-Whole Analysis

Measures contribution percentages across business categories.

### Analysis Includes

* Category contribution to revenue
* Percentage of total sales

### SQL Concepts

* Window Functions
* SUM() OVER()
* Percentage Calculations

---

# 📊 Customer Analytics Report

The Customer Report creates a reusable business view for customer intelligence.

## Metrics Included

* Customer Name
* Customer Age
* Age Group
* Customer Segment
* Total Orders
* Total Sales
* Total Quantity Purchased
* Total Products Purchased
* Customer Lifespan
* Recency
* Average Order Value
* Average Monthly Spend

### Customer Segments

| Segment | Criteria                               |
| ------- | -------------------------------------- |
| VIP     | > €5,000 sales and ≥ 12 months history |
| Regular | ≤ €5,000 sales and ≥ 12 months history |
| New     | Less than 12 months history            |

---

# 📦 Product Analytics Report

The Product Report creates a reusable business view for product intelligence.

## Metrics Included

* Product Name
* Category
* Subcategory
* Cost
* Product Segment
* Total Orders
* Total Revenue
* Total Quantity Sold
* Total Customers
* Product Lifespan
* Recency
* Average Selling Price
* Average Order Revenue
* Average Monthly Revenue

### Product Segments

| Segment        | Criteria                          |
| -------------- | --------------------------------- |
| High-Performer | Revenue > 50,000                  |
| Mid-Range      | Revenue between 10,000 and 50,000 |
| Low-Performer  | Revenue < 10,000                  |

---

# 🛠️ SQL Skills Demonstrated

## Core SQL

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* DISTINCT
* CASE

## Aggregate Functions

* SUM()
* AVG()
* COUNT()
* MIN()
* MAX()

## Date Functions

* YEAR()
* MONTH()
* DATEDIFF()
* DATETRUNC()
* FORMAT()

## Window Functions

* RANK()
* LAG()
* SUM() OVER()
* AVG() OVER()

## Advanced Techniques

* Common Table Expressions (CTEs)
* Customer Segmentation
* Product Segmentation
* Trend Analysis
* Contribution Analysis
* Business Reporting

---

# 🎓 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Business Analytics
* Customer Analytics
* Product Analytics
* SQL Reporting
* KPI Development
* Data Modeling
* Star Schema Concepts
* SQL Server Development
* Analytical Thinking

---
