# HR Employee Attrition Analysis

End-to-end data science project predicting employee attrition using the IBM HR Analytics dataset. Includes EDA, visualizations, data preprocessing, and multiple supervised ML classifiers to identify key factors driving turnover.

## Dataset
IBM HR Analytics Employee Attrition dataset (Kaggle)

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Key Findings
- About 16% of employees left the company (around 237 out of 1,470).
- Overtime is a major factor: 30.5% attrition for employees working overtime vs 10.5% for those who do not.
- Young and new employees leave the most: 36% attrition in the 18-25 age group and about 30% in employees with 0-2 years at the company.
- Low income employees have about 29% attrition, compared to about 10% for high income employees.
- Sales Representatives have the highest attrition by job role (about 40%), and employees who travel frequently show about 25% attrition.
- Poor work-life balance (level 1) and low job satisfaction (level 1) are linked with higher attrition (about 31% and 23%).
- Random Forest had the highest accuracy (84.35%), but Logistic Regression had the best recall (63.83%), so it catches more employees who are likely to leave.

## How to Run
Open the notebook in Google Colab, upload the dataset, and run all cells.
