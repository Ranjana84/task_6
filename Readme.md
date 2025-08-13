# Task 6 – Sales Trend Analysis

This project contains SQL queries to analyze monthly sales trends using the `sales_data_sample` dataset.  
The objective is to calculate **monthly revenue** and **order volume**, apply sorting, and filter by specific time periods.

## 📌 Objective
- Analyze monthly revenue
- Calculate monthly order volume
- Sort results by revenue
- Filter data for specific time periods

## 🛠 Tools Used
- SQLite (via [SQLiteOnline](https://sqliteonline.com/) for execution)
- `sales_data_sample.csv` dataset

## 📂 Dataset Details
The dataset includes:
- **ORDERDATE** – Date of the order
- **SALES** – Total sales amount
- **ORDERNUMBER** – Unique order ID
- **MONTH_ID** & **YEAR_ID** – Month and year of the order
- Additional columns with product and customer details

## 📜 Queries (a–f)
1. **Extract Month** – Using `MONTH_ID`
2. **Group by Year and Month**
3. **Calculate Monthly Revenue**
4. **Calculate Order Volume (Unique Orders)**
5. **Sort by Highest Revenue**
6. **Filter by Specific Year (e.g., 2003)**

## ▶ How to Run
1. Open [SQLiteOnline.com](https://sqliteonline.com/).
2. Import `sales_data_sample.csv` as table `sales_data_sample` (enable **First row is header**).
3. Copy and paste the queries from `task_6.sql`.
4. View and export results.

## 📸 Example Output
| year | month | revenue  | order_volume |
|------|-------|----------|--------------|
| 2003 | 4     | 201609.55| 7            |
| 2003 | 5     | 192673.11| 6            |
| ...  | ...   | ...      | ...          |

## 📬 Author
**Ranjana Chaursiya**  
_Data Analyst Internship – Task 6_
