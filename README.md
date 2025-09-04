# Data-Analyst-Task-2

# Task 2: Descriptive and Predictive Analysis with Interactive Dashboard
Take any sales dataset of your choice and perform both descriptive and predictive analysis.
Create an interactive dashboard using Python visualization libraries such as Plotly or Dash.
Ensure that the graphs are interactive and can cross-filter each other. Include at least three
different types of visualizations.

#  Descriptive and Predictive Analysis with Interactive Dashboard

This project demonstrates **Descriptive and Predictive Analysis** on a sales dataset using **Python, Pandas, Plotly, and Dash**.  
It provides an **interactive dashboard** where users can explore sales data, analyze trends, and predict future sales.

## Features

###  Descriptive Analysis
- Summary statistics (mean, max, min, std) of **Sales** and **Profit**
- Aggregations:
  - Sales by **Category**
  - Profit by **Region**
  - Monthly Sales trends
- Helps answer:  
  - *Which products are selling most?*  
  - *Which region is most profitable?*  
  - *How do sales vary month-to-month?*

###  Predictive Analysis
- Built a **Linear Regression model** to predict **Sales based on Profit**
- Equation form:
  \[
  Sales = m \times Profit + c
  \]
- Example use case:  
  - If Profit = ₹1000 → Predict corresponding Sales
- Helps with **forecasting sales** and **business planning**

###  Interactive Dashboard
- Developed using **Dash + Plotly**
- Includes **3 interactive charts**:
  1.  **Bar Chart** – Sales by Product Category  
  2.  **Scatter Plot** – Sales vs Profit (with regression line)  
  3.  **Line Chart** – Monthly Sales Trend
