# Credit Risk Exploratory Data Analysis

This project performs an end-to-end exploratory data analysis (EDA) on a credit risk dataset sourced from Kaggle. The goal is to identify trends and risk drivers that influence borrower delinquency using a combination of **Python for data cleaning** and **SQL for analysis**.
---

## Project Goals

- Clean and wrangle raw credit data using `pandas`
- Create engineered features (e.g., income brackets, debt buckets, delinquency indicators)
- Export the cleaned data to a SQLite database
- Use SQL queries to explore patterns and draw risk-related insights
- Visualize key findings using `seaborn` and `matplotlib`

---

## Directory Structure
'''
credit-risk-eda/
├── data/
│   ├── Credit Risk Benchmark Dataset.csv # Origincal data set
│   └── clean_credit_risk.csv # Cleaned and processed data
├── database/
│   └── credit_risk.db # SQLite database with final table
├── notebooks/
│   ├── data_cleaning.ipynb # Python-based cleaning & preprocessing
│   └── sql_analysis.ipynb # SQL-based EDA with query results
├── README.md # Project overview and documentation
'''

## SQL Questions 

## Key Insights

## Technologies Used 
 - Python (pandas, numpy, seaborn, matplotlib)
 - SQLite (via sqlite3)
 - Jupyter Notebooks
 - SQL (for query-based EDA)

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/reneshravi/credit-risk-eda.git
cd credit-risk-eda
```
2. Open the notebooks in VS Code or Jupyter:
    - notebooks/data_cleaning.ipynb to inspect preprocessing
    - notebooks/sql_analysis.ipynb to explore SQL-driven insights

Optional: Use DB Browser for SQLite or TablePlus to view the database directly.

## Future Improvements
- Add predictive modeling (e.g., logistic regression)
- Deploy interactive dashboard using Streamlit or Flask
- Integrate with cloud-based SQL (PostgreSQL, BigQuery)

## Dataset
[Kaggle: Credit Risk Benchmark Dataset](https://www.kaggle.com/datasets/adilshamim8/credit-risk-benchmark-dataset)

## Author

Created by [Renesh Ravi](https://linkedin.com/in/reneshravi).