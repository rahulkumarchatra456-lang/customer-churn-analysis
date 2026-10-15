# Customer Churn Analysis Using Python & SQL

## Project Overview

This project explores customer churn patterns using customer, subscription, and customer support data. The analysis focuses on understanding churn and retention metrics, comparing subscription plans, and exploring potential relationships between churn and customer support indicators.

**Project type:** Exploratory Data Analysis (EDA)

## Objectives

- Calculate customer churn and retention rates.
- Compare churn rates across subscription plans.
- Clean and integrate customer, subscription, and support datasets.
- Explore customer tenure, cancellation patterns, satisfaction, and support escalations.
- Communicate findings through visualizations and summary metrics.

## Tools & Technologies

- Python
- SQL and SQLite
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methodology

1. Extracted data from SQLite tables.
2. Cleaned column names, missing values, categorical fields, and date columns.
3. Integrated customer, subscription, and support records.
4. Engineered churn flags, tenure, and churn-risk categories.
5. Calculated churn, retention, average monthly charges, and other exploratory metrics.
6. Created visualizations and pivot tables to examine customer churn patterns.

## Key Findings

- Overall churn rate: 28.57%.
- Retention rate: 71.43%.
- Basic plan churn rate: 60.00%.
- Standard plan churn rate: 22.22%.
- Premium plan churn rate: 14.29%.
- Average monthly charges: 18.85 (currency unspecified in the source).

The sample shows a higher churn rate among Basic-plan customers than among Standard- and Premium-plan customers. This is a direction for further investigation, not a universal conclusion.

## Visualizations

The notebook includes plan-wise, state-wise, contract-wise, cancellation-reason, and customer-satisfaction analyses, along with correlation and categorical comparisons.

## Limitations

- The analysis contains only 21 customer/subscription records and 9 original support records.
- The results are exploratory and may not generalize to a larger customer population.
- Support-data handling and categorical encoding require validation before interpreting all correlations.
- Currency units are not specified in the source.
- Customer data must be anonymized before public sharing.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `customer_churn_analysis.ipynb` in Jupyter Notebook.
4. Ensure the approved sample database or data files are available at the paths expected by the notebook.
5. Run the notebook cells in order.

## Author

Your Name
Rahul Kumar

