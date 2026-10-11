# Superstore Sales Analysis

## Project Overview
This capstone project explores a Superstore sales dataset using Python, Pandas, Matplotlib, Seaborn, and PostgreSQL. It demonstrates data cleaning, exploratory data analysis (EDA), visualisation, and SQL-based business analysis.

## Objectives
- Load and inspect a retail sales dataset.
- Clean missing values, check duplicates, and prepare date columns.
- Explore sales by product category, region, and customer segment.
- Visualise sales patterns and investigate the sales distribution and outliers.
- Use SQL queries to summarise overall sales and compare business performance.
- Translate findings into practical business recommendations.

## Dataset
The notebook was developed with a Superstore dataset containing approximately 9,800 records and 18 columns, including order and shipping dates, customer segment, region, product category, sub-category, product name, and sales.

**Dataset note:** `train.csv` is not included in this repository by default. If you are permitted to share the dataset, place `train.csv` in the repository root next to the notebook. Otherwise, download it from the original authorised source and keep it locally. Do not commit private, licensed, or restricted data.

## Tools
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- PostgreSQL and pgAdmin 4 (for the optional SQL analysis)

## How to Run
1. Download or clone this repository.
2. Put `train.csv` in the project root (the same folder as the notebook).
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open `Superstore_Sales_Analysis.ipynb`.
6. Choose **Kernel → Restart & Run All** and save the notebook after the cells finish.

## SQL Analysis
The `sql/` folder contains example PostgreSQL queries for:
- Total sales
- Sales by category
- Sales by region
- Sales by customer segment

The notebook and SQL script are separate deliverables; configure and import the CSV into PostgreSQL before running the SQL queries.

## Repository Structure
```text
superstore-sales-analysis/
├── Superstore_Sales_Analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── sql/
    └── superstore_analysis.sql
```

## Current Key Findings
Based on the dataset analysis prepared for this project:
- Technology has the highest total sales among the three product categories.
- The West region has the highest total sales, while the South has the lowest.
- The Consumer segment contributes the largest share of sales.
- The mean sales value is higher than the median, suggesting a right-skewed distribution with some high-value records.

These are descriptive findings. They do not establish why the differences occur; further analysis would be needed to determine causes.

## Author
Add your name and any preferred professional contact or portfolio links here.
