Customer Shopping Behaviour Analysis

An end-to-end retail analytics project analyzing customer purchasing patterns using **Python, SQL (PostgreSQL), and Power BI**.
This project explores revenue trends, customer segmentation, subscription impact, and operational insights through data cleaning, structured querying, and interactive dashboard visualization.


 📌 The goal of this project was to:
- Clean and prepare raw retail data
- Perform exploratory data analysis (EDA)
- Validate business metrics using SQL queries
- Build an interactive Power BI dashboard for business insights

The workflow mimics a real-world analytics pipeline:
Raw Data → Python Cleaning → SQL Validation → Power BI Visualization


🧰 Tools & Technologies Used
- **Python (Google Colab)**
  - Pandas
  - NumPy
    
- **PostgreSQL (Supabase)**
  - Revenue aggregation
  - Customer segmentation queries
    
- **Power BI**
  - Interactive dashboard creation
  - KPI tracking
  - Data storytelling


📊 The Power BI dashboard provides:
- Total Revenue & Key KPIs
- Revenue by Category
- Revenue by Gender
- Revenue by Location (Map Visualization)
- Impact of Discounts
- Payment Method Analysis
- Customer Age Group Analysis
- Subscription Behaviour Insights
  

📷 Dashboard Preview
<img width="1558" height="730" alt="image" src="https://github.com/user-attachments/assets/0e647e39-102f-4f4f-8478-321d04160d40" />


🧮 SQL was used to validate revenue calculations and customer segmentation logic before building visuals in Power BI.
- ```sql
  select gender, SUM(purchase_amount) AS total_revenue
  FROM retail_customers
  GROUP BY gender
  ORDER BY gender;



Project Files
1. Google Colab Notebook: https://colab.research.google.com/drive/1zSbS4OqgAA0X7AYHZ9_vhQ2O4MNV_DyQ?usp=sharing
2. Power BI Dashboard (.pbix file): Available in /powerbi folder
