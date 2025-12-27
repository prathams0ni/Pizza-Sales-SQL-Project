# 🍕 Pizza Hut Sales Analysis using SQL

## 📌 Project Overview
This project focuses on analyzing Pizza Hut sales data using SQL to answer real-world business questions.  
The goal is to derive meaningful insights related to revenue, customer ordering patterns, pizza popularity, and category-wise performance using structured query language.

A total of **13 business-driven SQL queries** were written and optimized to demonstrate strong command over SQL fundamentals and advanced concepts.

---

## 📊 Dataset Content

The analysis is performed on a relational dataset consisting of four CSV files.  
Each table represents a different aspect of Pizza Hut’s sales operations.

---

### 🍽️ orders.csv
Contains order-level information.

| Column Name | Description |
|------------|-------------|
| order_id | Unique identifier for each order |
| date | Date on which the order was placed |
| time | Time at which the order was placed |

---

### 🧾 order_details.csv
Contains item-level details for each order.

| Column Name | Description |
|------------|-------------|
| order_details_id | Unique identifier for each order line item |
| order_id | References the corresponding order |
| pizza_id | References the pizza ordered |
| quantity | Number of pizzas ordered |

---

### 🍕 pizzas.csv
Contains pricing and size information for pizzas.

| Column Name | Description |
|------------|-------------|
| pizza_id | Unique identifier for each pizza |
| pizza_type_id | References the pizza type |
| size | Pizza size (S, M, L, XL, XXL) |
| price | Price of the pizza |

---

### 📋 pizza_types.csv
Contains descriptive information about pizza types.

| Column Name | Description |
|------------|-------------|
| pizza_type_id | Unique identifier for each pizza type |
| name | Name of the pizza |
| category | Pizza category (Classic, Veggie, Chicken, Supreme) |
| ingredients | Ingredients used in the pizza |

---

### 🔗 Dataset Relationships
- `orders.order_id` → `order_details.order_id`
- `order_details.pizza_id` → `pizzas.pizza_id`
- `pizzas.pizza_type_id` → `pizza_types.pizza_type_id`

These relationships enable comprehensive sales, revenue, and category-level analysis using SQL joins.


## ❓ Business Questions Solved

1. Total number of orders placed  
2. Total revenue generated from pizza sales  
3. Highest priced pizza  
4. Most common pizza size ordered  
5. Top 5 most ordered pizza types by quantity  
6. Total quantity ordered per pizza category  
7. Hourly distribution of orders  
8. Category-wise pizza distribution  
9. Average number of pizzas ordered per day  
10. Top 3 pizza types based on revenue  
11. Percentage contribution of each pizza type to total revenue  
12. Cumulative revenue analysis over time  
13. Top 3 pizzas by revenue within each pizza category  

---

## 🛠 SQL Concepts & Techniques Used
- INNER JOINs
- GROUP BY & Aggregate Functions (SUM, COUNT, AVG)
- Subqueries
- Window Functions (RANK)
- Date & Time Analysis
- Revenue & Performance Metrics


---

## 🎯 Key Learnings
- Translating business questions into SQL logic  
- Writing optimized and readable SQL queries  
- Applying window functions for ranking and cumulative analysis  
- Understanding relational database structures and joins  

---

## ✅ Conclusion
This project demonstrates practical SQL skills required for data analyst roles.  
It highlights the ability to analyze transactional data, extract business insights, and present results in a structured and professional manner.

---
