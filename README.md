# Bank Loan Default Analysis

## Project Overview
This project aims to analyze and predict credit card loan defaults using historical data. The goal is to understand key factors that influence default behavior and to build machine learning models to predict future defaults.

---

## Dataset
- **Source:** Credit card default dataset (CSV file)
- **Location:** `Data/raw/credit_card_default.csv`
- **Description:** The dataset contains customer demographics, credit limits, payment history, and default status for the next month.

**Key Features:**
- `LIMIT_BAL` – Credit limit
- `SEX` – Gender
- `AGE` – Age
- `PAY_X` – Payment history
- `BILL_AMT_X` – Billing amounts
- `PAY_AMT_X` – Payment amounts
- Other derived features for payment consistency, utilization ratio, etc.

---

## Project Structure

bank-loan-default-analysis/
│
├── dashboard/ # Visualization dashboards (to be developed)
├── Data/
│ ├── raw/ # Raw CSV dataset
│ └── processed/ # Processed/cleaned data (empty for now)
├── notebooks/
│ ├── 01_data_exploration.ipynb
│ ├── 02_feature_engineering.ipynb
│ └── 03_modeling_evaluation.ipynb
├── report/ # Project reports and outputs (empty)
├── .gitignore
└── README.md
---

## Methodology
1. **Data Exploration**
   - Identify missing values, outliers, and distributions
   - Visualize default patterns across demographics and payments

2. **Feature Engineering**
   - Create new features like payment consistency scores, utilization ratios
   - Encode categorical variables

3. **Modeling & Evaluation**
   - Train machine learning models:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Evaluate using accuracy, precision, recall, F1-score, ROC-AUC

---

## Results
- Key factors influencing defaults identified
- Predictive models built and evaluated
- Insights can inform risk management strategies

---

## Next Steps
- Develop dashboards for interactive visualization
- Automate preprocessing and feature engineering
- Deploy predictive model as a web application or API

---

## Author
**Alaa Touihri** – Data Analyst | Python | SQL | Machine Learning  
[GitHub Profile](https://github.com/AlaaTouihri)
