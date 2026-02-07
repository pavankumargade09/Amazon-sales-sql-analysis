# 📦 Amazon Sales Analysis Using Advanced SQL (Data Analytics Project)

## 📌 Project Overview
This project focuses on analyzing the **Amazon Sales Dataset** using SQL to extract meaningful business insights related to orders, revenue, fulfilment methods, customer segments, and sales trends.

The project demonstrates the use of **advanced SQL techniques** such as **CTEs, subqueries, window functions, and aggregations** to solve real-world business problems.

---

## 🧠 Problem Statement
Amazon aims to understand its sales performance by analyzing order data across cities, states, product categories, fulfilment methods, and customer types (B2B vs Non-B2B).  
The objective is to identify revenue drivers, customer behavior patterns, and operational insights.

---

## 📂 Dataset
- **Dataset Name**: Amazon Sales Dataset  
- **Key Columns**:
  - Order ID  
  - Date  
  - Status  
  - Fulfilment  
  - Category  
  - Amount  
  - Ship City  
  - Ship State  
  - B2B  

---

## 📋 Tasks & SQL Analysis

### ✅ Task 1: Total Number of Orders
- Calculated the total number of orders in the dataset.

### ✅ Task 2: Distinct Order Statuses
- Retrieved all unique order statuses.

### ✅ Task 3: Orders by Fulfilment Type
- Identified the number of orders fulfilled by:
  - Amazon  
  - Merchant  

### ✅ Task 4: Cancelled Orders Analysis
- Found the total number of cancelled orders.

### ✅ Task 5: Orders per Ship City
- Calculated total orders per ship city and sorted them by highest order count.

### ✅ Task 6: Revenue by Ship State
- Computed total revenue generated from each ship state.
- Considered only **Shipped** orders for accurate revenue calculations.

### ✅ Task 7: Total Sales by Category
- Analyzed total sales amount for each product category.

### ✅ Task 8: Top 5 Revenue-Generating Cities
- Identified the top 5 ship cities contributing the highest revenue.

### ✅ Task 9: Average Order Value by Category
- Calculated the average order amount for each product category.

### ✅ Task 10: B2B vs Non-B2B Orders
- Compared the total number of orders placed by:
  - B2B customers  
  - Non-B2B customers  

### ✅ Task 11: High-Value Orders
- Identified orders with an amount greater than the overall average order value using a subquery.

### ✅ Task 12: Repeat Orders by Ship City
- Used a **CTE** to identify ship cities with more than one order.
- Assumed repeat customers based on the same ship city.

### ✅ Task 13: Fulfilment-Wise Revenue Contribution
- Calculated total revenue by fulfilment type.
- Determined the percentage contribution of each fulfilment method to overall revenue using **CTEs**.

### ✅ Task 14: Order Ranking by Amount
- Ranked orders based on order value from highest to lowest using a **window function**.

### ✅ Task 15: Running Total of Revenue
- Calculated cumulative revenue over time using a window function ordered by date.

---

## 🧰 SQL Concepts Used
- Aggregate Functions (SUM, COUNT, AVG)
- GROUP BY, ORDER BY, LIMIT
- WHERE filtering
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions (RANK, SUM OVER)
- Time-Series Analysis

---

## 📊 Key Insights
- Certain cities and states contribute significantly higher revenue.
- Amazon-fulfilled orders contribute a major share of total revenue.
- B2B orders represent a smaller but important customer segment.
- High-value orders can be identified using average-based benchmarks.
- Revenue trends can be tracked effectively over time.
