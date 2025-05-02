# Elevate-Labs-Data-Analytics-Internship-Task-06
TASK 6: Sales Trend Analysis Using Aggregations


# 📊 Sales Trend Analysis Using Aggregations

## 🧾 Objective
Analyze **monthly revenue** and **order volume** using SQL-style data grouping and aggregation in Python via SQLAlchemy.

---

## 🛠 Tools & Technologies
- **Python**
- **SQLAlchemy**
- **SQLite** (can be adapted for MySQL/PostgreSQL)
- **Jupyter Notebook**

---

## 🗃️ Dataset
**Table**: `orders`

**Columns**:
- `order_id`: Unique identifier for each order
- `order_date`: Date of the order
- `amount`: Revenue from the order
- `product_id`: ID of the product sold

---

## 📈 Analysis Goals
- Extract **month and year** from `order_date`
- Group data by **year and month**
- Use `SUM(amount)` to calculate **monthly revenue**
- Use `COUNT(DISTINCT order_id)` to calculate **monthly order volume**
- Sort the results by **year and month**

---

## 📜 Implementation Steps
1. **Connect** to SQLite database using SQLAlchemy.
2. **Define ORM model** for the `orders` table.
3. **Query data** to:
   - Extract year/month using `strftime()` (for SQLite)
   - Aggregate total revenue and order volume
4. **Sort results** chronologically.
5. **Display** the analysis as a table.

---

## 🧪 Sample Output

