# SQL-DATA-ANALYTICS-PROJECT
Developed an end-to-end SQL Data Analytics project using SQL Server and T-SQL to explore business data, analyze sales and customer performance, identify trends, segment data, and generate actionable insights using CTEs, joins, subqueries, and window functions.

## 📂 Script Structure

### 00 — Database Initialization

**`00_init_database.sql`**

Sets up the database environment required for the project and prepares the tables and data for analysis.

---

### 01 — Database Exploration

**`01_database_exploration.sql`**

Provides an initial understanding of the database structure, tables, columns, and available data before performing detailed analysis.

---

### 02 — Dimensions Exploration

**`02_dimensions_exploration.sql`**

Explores the project's dimension data, particularly **customers and products**, to understand their attributes and relationships with transactional sales data.

---

### 03 — Date Range Exploration

**`03_date_range_exploration.sql`**

Examines the available date ranges in the dataset to understand the period covered by the sales data and establish the timeline for analysis.

---

### 04 — Measures Exploration

**`04_measures_exploration.sql`**

Analyzes important numerical measures such as **sales, quantities, prices, and other business metrics** to understand the scale and characteristics of the data.

---

### 05 — Magnitude Analysis

**`05_magnitude_analysis.sql`**

Performs aggregated analysis to understand the magnitude of business performance across different customers, products, and categories.

---

### 06 — Ranking Analysis

**`06_ranking_analysis.sql`**

Ranks customers and products based on business performance, helping identify **top-performing customers, products, and other key contributors**.

---

### 07 — Change Over Time Analysis

**`07_change_over_time_analysis.sql`**

Analyzes how sales and other business metrics change over time to identify **growth patterns, trends, fluctuations, and seasonal behavior**.

---

### 08 — Cumulative Analysis

**`08_cumulative_analysis.sql`**

Performs cumulative calculations such as **running totals and accumulated performance**, providing a broader view of business growth over time.

---

### 09 — Performance Analysis

**`09_performance_analysis.sql`**

Evaluates the performance of customers and products by comparing their contribution against relevant business metrics and identifying high- and low-performing areas.

---

### 10 — Data Segmentation

**`10_data_segmentation.sql`**

Segments customers and products into meaningful groups based on their characteristics and performance, enabling more targeted business analysis.

---

### 11 — Part-to-Whole Analysis

**`11_part_to_whole_analysis.sql`**

Measures how individual customers, products, or categories contribute to the **overall business performance**, helping identify the most significant contributors.

---

### 12 — Customer Report

**`12_report_customers.sql`**

Creates a consolidated customer analysis covering important metrics and behavioral insights to support **customer-level business decisions**.

---

### 13 — Product Report

**`13_report_products.sql`**

Creates a consolidated product analysis to evaluate **product performance, sales contribution, and overall business impact**.

---

## 🧠 SQL Concepts Demonstrated

The scripts demonstrate practical SQL Server techniques including:

* **Database & Data Exploration**
* **SELECT, WHERE, GROUP BY & HAVING**
* **JOINs**
* **Aggregate Functions**
* **CASE Statements**
* **Subqueries**
* **Common Table Expressions (CTEs)**
* **Date & Time Functions**
* **Window Functions**
* **Ranking Functions**
* **Running & Cumulative Calculations**
* **Trend Analysis**
* **Customer & Product Segmentation**
* **Performance Analysis**
* **Business Reporting**

---

## 🎯 Project Objective

The objective of these scripts is to demonstrate how a Data Analyst can move from **raw business data → structured SQL analysis → meaningful insights → analytical reports**.

Rather than using SQL only for retrieving data, the project applies SQL to answer practical business questions around:

**Sales Performance • Customer Behavior • Product Performance • Trends • Rankings • Segmentation • Business Contribution**

---

## 🛠️ Technology

**Database:** SQL Server
**Language:** T-SQL
**Analysis:** SQL Data Analytics
**Data Sources:** Customer, Product & Sales datasets

---

## 📁 Related Project Folders

* **`DATASETS/`** — External datasets used for analysis
* **`SCRIPTS/`** — SQL analysis scripts
* **`DOCS/`** — Supporting project documentation
* **`README.md`** — Overall project documentation

