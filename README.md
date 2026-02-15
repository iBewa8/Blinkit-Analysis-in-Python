🛒 Blinkit Sales Data Analysis (Python Project)

📌 Project Overview

This project analyzes Blinkit retail sales data using Python to extract business insights and evaluate key performance indicators (KPIs).

The analysis includes data cleaning, KPI calculations, and visual exploration of sales performance across product categories and fat content types.

🎯 Business Requirements

The project answers the following business questions:
 • What is the Total Sales?
 • What is the Average Sales per transaction?
 • How many Items were sold?
 • What is the Average Rating?
 • How do sales vary by:
 • Item Fat Content
 • Item Type

🧹 Data Cleaning

Before analysis, the dataset was cleaned to ensure consistency:
 • Standardized categorical values in Item Fat Content
 • Fixed inconsistent entries such as:
 • LF → Low Fat
 • low fat → Low Fat
 • reg → Regular
 • Removed formatting inconsistencies using string normalization techniques

📊 KPIs Calculated
 • Total Sales
 • Average Sales
 • Number of Items Sold
 • Average Rating

All KPIs were calculated using Pandas aggregation functions (sum(), mean(), count()).

📈 Data Visualization

1️⃣ Sales by Fat Content
 • Pie chart showing contribution of Low Fat vs Regular products
 • Helps understand customer preference patterns

2️⃣ Sales by Item Type
 • Bar chart (sorted descending)
 • Highlights top-performing product categories
 • Displays formatted sales values for clarity

🛠️ Tools & Libraries Used
 • Python
 • Pandas
 • NumPy
 • Matplotlib
 • Seaborn
 • Jupyter Notebook

💡 Key Insights
 • Certain item categories dominate total sales.
 • Low Fat products represent a significant portion of overall revenue.
 • Sales distribution reveals strong demand in daily-consumption categories.

🚀 How to Run the Project
 1. Clone the repository
 2. Place the dataset file in the project directory
 3. Open the notebook in Jupyter
 4. Run all cells sequentially
