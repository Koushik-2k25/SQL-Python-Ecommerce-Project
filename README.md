# 📊 SQL-Python E-commerce Analytics Project

This project provides data-driven insights into customer behavior, sales performance, and business trends using SQL for querying and Python for analysis and visualization. It connects to a MySQL e-commerce database to extract meaningful metrics and visualize patterns.

## 🚀 Features

- Extracted and analyzed customer locations, order counts, and purchase behavior.
- Calculated category-wise sales and revenue distributions.
- Derived monthly and yearly sales trends.
- Computed customer retention, seller performance, and growth rates.
- Visualized results using `matplotlib` and `seaborn`.

## 📂 Technologies Used

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **SQL**: MySQL queries including `JOIN`, `CTE`, `window functions`
- **Database**: MySQL
- **Tools**: Jupyter Notebook

## 📁 Dataset

- Kaggle E-commerce Dataset:  
  🔗 [Target Dataset on Kaggle](https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv)

## 🧪 Project Notebook

You can explore the full working notebook with all SQL queries, Python code, and visualizations on GitHub:

🔗 [View The Whole Project](https://github.com/Koushik-2k25/SQL-Python-Ecommerce-Project/blob/main/python%2Bsql_ecommerce.ipynb)


## 🧩 Questions Explored in Project

1. List all unique cities where customers are located.
2. Count the number of orders placed in 2017.
3. Find the total sales per product category.
4. Calculate the percentage of orders paid in installments.
5. Count the number of customers from each state.
6. Calculate the number of orders per month in 2018.
7. Find the average number of products per order by customer city.
8. Calculate the percentage of total revenue by product category.
9. Identify the correlation between product price and purchase count.
10. Rank sellers by total revenue generated.
11. Compute the moving average of order values per customer.
12. Calculate cumulative monthly sales for each year.
13. Determine year-over-year (YoY) growth rate in total sales.
14. Calculate customer retention rate within 6 months.
15. Identify top 3 highest-spending customers in each year.

## 📈 Key Analyses & Queries

### ✅ Customer Insights
- Unique cities from customer data
- Customers per state
- Customer retention rate (repeat purchases)

### ✅ Order & Sales Analysis
- Orders in 2017 and 2018
- Monthly orders for 2018
- Moving average of order value per customer
- Monthly & cumulative revenue trends
- Year-over-year sales growth

### ✅ Category Analysis
- Total sales by product category
- Category revenue percentage
- Product price vs purchase frequency correlation

### ✅ Seller & Customer Rankings
- Top-performing sellers by revenue
- Top 3 customers per year by spend  

## 📊 Visualizations

Includes:
- Bar plots of state-wise customers and monthly orders
- Seller revenue bar chart
- Line chart for cumulative monthly sales
- Multi-year top customer rankings

## ✅ Key Outcomes
- **90,202 orders** in 2017  
- Top sales categories: **Perfumery**, **Bed/Table/Bath**, **Furniture**  
- **99.99%** of orders paid via installments  
- Highest customer counts in **São Paulo** & **Rio de Janeiro**  
- Highest avg. products/order: **Padre Carvalho (28)**  
- **Bed/Table/Bath** contributes **42.79%** of revenue  
- Price vs. purchase correlation ≈ **–0.106** (negligible)     
- **0%** customer retention within 6 months  


## 📌 Conclusion

This project demonstrates how SQL and Python can be combined to perform robust e-commerce data analysis. It provided end-to-end insights from querying raw data to delivering visual business intelligence, making it valuable for business strategists and data analysts.
