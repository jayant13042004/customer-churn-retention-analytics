# Customer Churn & Retention Analytics

Churn analytics workflow with a Power BI dashboard and a baseline churn classifier, built on a **synthetic dataset**.

## Important note on the data
The dataset is synthetic. A 26-record source was expanded to 7,000+ records while keeping the data consistent. The results demonstrate the workflow and tooling, not real customer behavior.

## What it does
- Builds the churn analytics workflow on the synthetic data (Python, Pandas, SQL)
- **Power BI dashboard** with **5 KPIs and 6 visualizations** to track churn
- Baseline churn classifier with Scikit-learn to demonstrate the prediction workflow

## KPIs
List your 5 KPIs here (for example churn rate, retention rate, ...) with one line on how each is calculated.

(Dashboard screenshot: `![dashboard](images/dashboard.png)`)

## Tech stack
Python, Pandas, SQL, Scikit-learn, Power BI

## How to reproduce
1. Run `notebooks/[data_generation].ipynb` to create the dataset
2. Run `notebooks/[churn_analysis].ipynb`
3. Open `dashboard/[file].pbix` in Power BI Desktop

## Author
Jayant Jagtap · [LinkedIn](https://www.linkedin.com/in/jayantjagtap/)
