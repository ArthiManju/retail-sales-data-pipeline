# Retail Sales Data Pipeline

This project demonstrates a simple ETL pipeline built using Python and PostgreSQL, with insights visualized using Seaborn and Matplotlib.

## 📌 Project Overview

- Load and clean sales data from CSV
- Insert cleaned data into PostgreSQL using SQLAlchemy
- Perform aggregation queries to extract business insights
- Visualize top-performing product categories
  
## 🛠️ Technologies Used

- Python (pandas, sqlalchemy)
- PostgreSQL
- Jupyter Notebook
- Seaborn, Matplotlib
  
## 📈 Visualization Included

The notebook includes a **bar chart** showing the **Top Products by Sales**, grouped by sub-category:

![Bar Chart of Top Products](assets/top_products_chart.png) 
https://github.com/ArthiManju/retail-sales-data-pipeline/blob/main/Top%20products%20by%20Sales.PNG

## 🚀 How to Run

1. Clone this repository
2. Set up a PostgreSQL database and update credentials in the notebook
3. Run `Retail_Sales.ipynb`
4. View the output chart and SQL results

## 📂 Files

- `Retail_Sales.ipynb`: Main notebook with all logic and charts
- `sales_data.csv`: Sample dataset
