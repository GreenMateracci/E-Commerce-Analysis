# E-commerce Data Analysis (SQL + Python)
prepared by Stanisław Kamiński
## Overview
This Project includes building a synthetic e-commerce database used to identify business insights such as revenue trends,
customer behavior and most popular products. 

Dataset was generated in Python, simulating real life scenarios such as
different customer purchasing patterns or products popularity.

## Tech Stack
- Python (Pandas, Numpy, Faker, Matplotlib)
- SQL (SQLite)
- Data Aggregation and Analysis
- Relational Database Design

## Database Structure
The project uses a relational database with four tables:
- customers (customers information)
- products (products catalog)
- orders (orders data)
- order_items (items included in each order)

## Key Questions
The analysis answers the following:
- What is the total revenue?
- How does the revenue change over time?
- What are the top customers?
- What is the average value of an order?
- What are the most popular categories of products?
- Which products contribute the most to the total revenue?!

## Key Insights
- Small number of customers generate large portion of the revenue (Pareto principle)
- Revenue varies over time indicating possible seasonality
- Top products correspond to significant portion of the revenue

## Visualizations
Visualizations are provided in /images folder

## How to run:
- Clone the repository data
- Run the Python script or Jupyter Notebook file to generate data
  (SQL queries are included in the Python file. Alternatively there are premade database files that can be used to execute queries)