# Superstore Customer Cohort Analysis

## Project Overview

This project analyzes customer retention patterns using retail order data. Customers are grouped into cohorts based on their first purchase month, and their purchasing activity is tracked over subsequent months.

The project uses SQL and Python to calculate cohort retention rates, construct a retention matrix, and visualize customer retention patterns over time.

## Tools & Technologies

- SQL (DuckDB)
- Python
- Pandas
- Matplotlib

## Analysis

- Defined customer cohorts based on customers' first purchase month.
- Used SQL CTEs, JOINs, and date functions to calculate monthly active customers.
- Calculated initial cohort sizes and monthly retention rates.
- Processed the results using Python and Pandas.
- Built a cohort retention matrix and visualized retention patterns.

## Repository Contents

| File | Description |
|---|---|
| `Superstore Customer Cohort Analysis.ipynb` | Complete analysis notebook, including SQL queries, Python code, and visualizations. |

## Dataset

The analysis uses the Superstore dataset.

Dataset source: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset is connected through Kaggle Notebook's Input environment.

## Kaggle Notebook

https://www.kaggle.com/code/yinghelai/superstore-customer-cohort-analysis-sql-python

## How to Run

The notebook was developed and executed in the Kaggle environment.

To reproduce the analysis:

1. Open the Kaggle Notebook using the link above.
2. Add the required Superstore dataset to the notebook's Input.
3. Run all notebook cells.

Note: The file path used in the notebook refers to Kaggle's input directory and may need to be adjusted when running in another environment.
