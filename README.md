# Bank Customer Churn Analysis

## Project Overview
This project uses Python and Pandas to clean bank customer data, perform exploratory data analysis (EDA), and prepare a structured dataset for further analysis and machine learning.

## Business Objective
The goal is to understand customer churn patterns and identify customer characteristics that may be associated with a higher likelihood of leaving the bank.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Project Workflow
1. Import and inspect customer and account datasets.
2. Merge datasets using `CustomerId`.
3. Identify and remove duplicate records.
4. Clean inconsistent values and handle missing data.
5. Perform exploratory data analysis.
6. Analyze churn patterns across customer segments.
7. Create visualizations to explore numerical and categorical variables.
8. Perform feature engineering and prepare a model-ready dataset.

## Key Findings
- **Total customer records analyzed:** 10,000
- **Customers who exited:** 2,037
- **Customers who stayed:** 7,963
- **Overall churn rate:** 20.37%
- **Duplicate records removed:** 4

### Customer Churn Analysis
![Customer Churn Analysis](<Bank Customer Churn.png>)
### Churn Rate by Country
![Churn Rate by Country](<Churn Rate by Country.png>)

### Churn Rate by Gender
![Churn Rate by Gender](<Churn Rate by Gender.png>)

## Repository Contents
- `bank_customer_churn_analysis.ipynb` — Python analysis notebook.
- `bank_customer_cleaned.csv` — cleaned dataset, if redistribution is permitted.
- `bank_customer_model_ready.csv` — feature-engineered dataset, if redistribution is permitted.

## How to Run
1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook and obtain the source dataset from its authorised source.
4. Run the notebook cells in order.

## Disclaimer
This project is for educational and portfolio purposes. The analysis identifies patterns and associations; it does not establish causation or guarantee predictive performance.
