# 🍕 Domino's SQL Project

This project performs a comprehensive SQL-based analysis of a Domino’s pizza sales dataset. The goal is to uncover business insights by writing structured SQL queries using **joins**, **aggregations**, **window functions**, and **views**.

---

## 📌 Objectives

This project addresses the following business questions:

### 🔹 B – Basic Sales & Performance
- **B1**: Total number of orders placed
- **B2**: Total revenue generated from pizza sales
- **B3**: Highest-priced pizza
- **B4**: Most common pizza size ordered
- **B5**: Top 5 most ordered pizza types by quantity

### 🔹 I – Insights & Aggregations
- **I1**: Total quantity sold by pizza category
- **I2**: Order distribution by hour of the day
- **I3**: Pizza category distribution
- **I4**: Average number of pizzas ordered per day
- **I5**: Top 3 most ordered pizza types by revenue

### 🔹 A – Advanced Revenue Insights
- **A1**: Percentage revenue contribution by category
- **A2**: Cumulative revenue over time
- **A3**: Top 3 revenue-generating pizzas per category

---

## 🗂️ Database Structure

The project involves **multiple tables** joined using foreign keys to generate meaningful insights.

### 👇 ER Diagram
![Dominos ER Diagram](https://github.com/user-attachments/assets/1a35c5db-f2d2-473c-86bf-270c81927c2c)


---

## 🧠 SQL Concepts Used

- `CREATE VIEW`
- `JOIN` (INNER JOINs)
- `SUM()`, `COUNT()`, `AVG()`, `ROUND()`
- `RANK() OVER (PARTITION BY ...)`
- `LAG()`, `CUMULATIVE SUM` using `OVER(ORDER BY...)`
- Date/time extraction with `EXTRACT(HOUR FROM ...)`

---

## 🛠 How to Run

1. Load the Domino’s dataset (tables like `orders`, `order_details`, `pizzas`, and `pizza_types`) into the SQL database (e.g., PostgreSQL).
2. Execute each `CREATE VIEW` query provided in the project.
3. Use:
   ```sql
   SELECT * FROM B1;  -- Replace B1 with any view name to check result

---

**🔗 GitHub Repository Link**

https://github.com/Analyst-Rajat333/Dominos-SQL-Project

---

## 👨‍💻 Author

**Rajat Saxena**  
📧 **Email**: [rajatsaxena950@gmail.com](mailto:rajatsaxena950@gmail.com)  
🔗 **GitHub**: [Analyst-Rajat333](https://github.com/Analyst-Rajat333)
