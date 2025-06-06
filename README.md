

This project is part of a Data Analyst Internship where I worked with SQL to explore and analyze eCommerce-style transaction data.



📁 Dataset Overview

Three CSV files were used and imported into SQL:

- `Orders.csv` – Contains customer order information
- `Restaurants.csv` – Contains restaurant details
- `Payment.csv` – Contains payment method data

---

## 🧠 Objectives

- Use **SQL queries** to perform real-world data analysis tasks
- Apply concepts like filtering, aggregation, joins, subqueries, views, and ranking
- Gain hands-on experience using structured datasets

---

## 🛠 Tools Used

- SQL (MySQL syntax)
- Data imported from CSV files
- Query execution via MySQL Workbench / SQLite / Online SQL Editor

---

## ✅ SQL Tasks Performed

### 1️⃣ **Aggregation with Filtering**
```sql
SELECT Item, COUNT(Item) AS Total_Items 
FROM Orders 
WHERE YEAR(Date) = 2020 
GROUP BY Item 
HAVING COUNT(Item) > 5 
ORDER BY Item;

├── Orders.csv
├── Restaurants.csv
├── Payment.csv
├── task3_queries.sql          # All SQL queries used
├── screenshots/               # Optional: output screenshots
└── README.md                  # This file

