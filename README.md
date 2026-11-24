# Customer Churn Analysis and Retention Strategy

## Project Overview

This project focuses on analysing customer churn for a subscription-based telecommunications business using data analytics tools and techniques.

The objective is to identify customer segments with higher churn rates, understand the factors associated with customer attrition, and develop data-driven recommendations to improve customer retention.

The project uses the IBM Telco Customer Churn dataset, which contains information about 7,043 customers, including their demographics, subscription details, services, billing information and churn status.

## Business Problem

Customer churn directly affects recurring revenue, customer lifetime value and long-term business sustainability.

The key business questions explored in this project are:

- What percentage of customers discontinue their subscriptions?
- Which customer segments have the highest churn rates?
- How do contract type and customer tenure relate to churn?
- Are monthly charges, payment methods and internet services associated with customer attrition?
- Which customer groups should the business prioritise for retention initiatives?

## Project Objectives

1. Analyse customer demographics, subscription patterns and billing behaviour.
2. Identify customer segments with elevated churn rates.
3. Perform exploratory data analysis to uncover patterns and trends.
4. Develop interactive dashboards to communicate key findings.
5. Recommend targeted customer retention strategies based on analytical insights.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Google Sheets | Data cleaning, calculations and pivot table analysis |
| SQLite | Data querying and analytical SQL |
| Python | Data analysis and exploratory data analysis |
| Pandas and NumPy | Data manipulation and numerical analysis |
| Matplotlib and Seaborn | Data visualisation |
| Power BI | Interactive dashboards and business reporting |

## Dataset Information

- Dataset: IBM Telco Customer Churn
- Total customer records: 7,043
- Original dataset fields: 21
- Analytical fields after preparation: 23
- Target variable: Churn
- Churn categories: Yes and No

The dataset includes customer tenure, contract type, monthly charges, total charges, internet service, payment method and other customer attributes.

## Key Findings

The exploratory data analysis identified the following patterns:

| Customer Segment | Churn Rate |
|---|---:|
| Overall customer base | 26.54% |
| Month-to-month contracts | 42.71% |
| Customers with 0–12 months tenure | 47.44% |
| Customers paying $60–$89.99 monthly | 33.74% |
| Electronic check users | 45.29% |
| Fiber optic customers | 41.89% |

The highest-risk combination identified was month-to-month customers with 0–12 months of tenure, with a churn rate of 51.35%.

These findings represent observed associations and do not establish causation.

## Project Structure

```text
Customer-Churn-Analysis/
│
├── data/
│   └── Cleaned dataset (local, not tracked by Git)
│
├── notebooks/
│   └── 01_data_loading_and_inspection.ipynb
│
├── visualisation/
│   └── Exported Python charts
│
├── reports/
│   └── Project findings and documentation
│
├── README.md
├── .gitignore
└── .vscode/
```

## Methodology

The project follows a structured analytical workflow:

1. Data collection and understanding
2. Data cleaning and preparation
3. Exploratory data analysis
4. SQL-based data analysis
5. Python-based analysis and visualisation
6. Power BI dashboard development
7. Business insights and retention recommendations

## Current Project Status

- [x] Dataset preparation and cleaning
- [x] Google Sheets analysis
- [x] SQL analysis
- [x] Python data loading and inspection
- [x] Python exploratory data analysis
- [x] Power BI dashboard development
- [x] Final business recommendations and project report

## Expected Business Outcomes

The analysis aims to help the business:

- Identify customers who are more likely to discontinue their subscriptions.
- Improve onboarding and engagement during the early customer lifecycle.
- Investigate pricing and service-related dissatisfaction.
- Evaluate payment experience and subscription preferences.
- Develop targeted retention initiatives to reduce customer attrition.

---

**Project:** Customer Churn Analysis and Retention Strategy  
**Domain:** Telecommunications / Subscription Business  
**Focus:** Data Analytics, Business Intelligence and Customer Retention