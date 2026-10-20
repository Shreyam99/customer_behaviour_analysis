# Customer Shopping Trends Analysis

An end-to-end data analytics project exploring customer shopping behaviour using SQL, Python, and Power BI. The project focuses on understanding purchasing patterns, customer preferences, sales performance, and subscription behaviour through data analysis and interactive visualisation.

## Project Overview

Retail businesses need to understand how customers shop, which product categories perform well, and what factors influence purchasing decisions. This project analyses customer shopping data to extract useful insights and presents key findings through a Power BI dashboard.

## Objectives

- Analyse customer purchasing behaviour and product preferences.
- Explore sales and revenue across product categories.
- Understand customer demographics and shopping patterns.
- Examine subscription status, shipping preferences, and customer ratings.
- Build an interactive dashboard to communicate analytical findings.

## Tools and Technologies

- **SQL:** Data querying, aggregation, and analysis.
- **Python:** Data analysis using Jupyter Notebook and relevant libraries.
- **Power BI:** Data visualisation, DAX measures, and dashboard development.
- **Dataset:** CSV file containing customer shopping information.

## Project Workflow

1. **Data Preparation:** Load the customer shopping dataset and inspect its structure, columns, and data quality.
2. **SQL Analysis:** Use SQL queries to investigate purchasing patterns, category-level performance, and customer behaviour.
3. **Python Analysis:** Explore the dataset and perform analysis using a Jupyter Notebook.
4. **Power BI Dashboard:** Develop visualisations and measures to summarise key business metrics.
5. **Insights:** Interpret the results to identify patterns that may support retail business decisions.

## Dashboard Highlights

The Customer Behavior Dashboard includes:

- **Number of Customers:** Overview of customer records.
- **Average Purchase Amount:** Average spending per record, based on the dashboard's calculation.
- **Average Review Rating:** Summary of customer ratings.
- **Subscription Analysis:** Distribution of customers by subscription status.
- **Revenue by Category:** Comparison of revenue across product categories.
- **Sales by Category:** Comparison of purchase activity across categories.
- **Age Group Analysis:** Comparison of sales and revenue across customer age groups.
- **Interactive Filters:** Explore results by subscription status, gender, category, and shipping type.

## Repository Structure

```text
customer-shopping-analysis/
├── README.md
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
└── customer_behavior_dashboard.pbix
```

*Note: The filenames above should match the actual files in your repository.*

## How to Run the Project

### Python

1. Install Python and Jupyter Notebook.
2. Install the libraries required by the notebook.
3. Download or clone this repository.
4. Open `Customer_Shopping_Behavior_Analysis.ipynb`.
5. Update the dataset path if necessary and execute the notebook cells.

### SQL

1. Open the SQL script in a compatible SQL environment.
2. Import the dataset into the appropriate database table.
3. Update table or column names if your database schema differs.
4. Execute the queries to reproduce the analysis.

### Power BI

1. Install Power BI Desktop.
2. Open `customer_behavior_dashboard.pbix`.
3. If prompted, update the dataset source path.
4. Refresh the data and explore the dashboard using its interactive filters.

## Key Learnings

- Working with structured retail customer data.
- Querying and aggregating data using SQL.
- Analysing data with Python.
- Creating DAX measures and interactive Power BI visualisations.
- Translating data into business-oriented insights.

## Source and Acknowledgement

This project is based on an existing public educational project. The original repository is available here:

[Customer Trends Data Analysis — SQL, Python and Power BI](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI)

Please refer to the original repository's licence and retain appropriate attribution when reusing its materials.

## Future Improvements

- Add customer segmentation and cohort analysis.
- Explore purchasing trends over time.
- Introduce additional KPIs and advanced DAX measures.
- Improve dashboard usability and visual design.
- Develop further recommendations based on analytical findings.

---

**Technologies:** SQL | Python | Jupyter Notebook | Power BI | DAX | Data Analytics
