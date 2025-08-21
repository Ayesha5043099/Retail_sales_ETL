
# Retail Sales Project

## Project Overview  
This project shows how to take raw retail sales data, clean it, store it in a database, analyze it with SQL, and finally make a dashboard for visualization.  

---

## Steps to Do the Project

### 1. Get the Data  
- Download the **Superstore dataset** from Kaggle.  
- Save it as `superstore.csv`.  

### 2. Clean the Data (Python + Pandas)  
- Fix column names  
- Remove or fill missing values  
- Add a new column →  
  ```
  total_price = Quantity × unit_price
  ```  
- Save the cleaned file as `superstore_clean.csv`  

### 3. Load Data into PostgreSQL  
- Create a database called `superstore`  
- Make a table called `retail_data`  
- Use Python + SQLAlchemy to load the CSV into PostgreSQL  

### 4. Run SQL Queries  
- **Top 5 Selling Products**  
- **Total Revenue by Region**  
- **Monthly Sales Trend**  

### 5. Make Dashboard (Power BI )  
- Bar chart → Top products  
- Line graph → Monthly sales trend  
- Pie chart → Revenue by category  

---

## Tools Used  
- Python (Pandas)  
- PostgreSQL  
- SQL  
- Power BI 

---

## 🎯 Result  
- Clean data stored in database  
- SQL queries give insights  
- Dashboard shows sales performance in simple visuals  
