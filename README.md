# Credit Card Users Churn Prediction

## Overview
This repository hosts the **Credit Card Users Churn Prediction** project, completed as part of the Data Science and Machine Learning course by Great Learning in collaboration with UT Austin. The primary goal is to develop a predictive model to help Thera Bank identify customers likely to stop using their credit card services.

## Business Context
Thera Bank has experienced a significant decline in credit card usage, impacting its revenue derived from various fees such as annual fees, balance transfers, cash advances, late payments, and foreign transactions. To prevent customer attrition, Thera Bank seeks to identify potential churners proactively and improve services based on the findings.

## Objective
The main objectives of this project include:
- Developing a classification model to accurately predict customers who might churn.
- Identifying key factors that influence customer attrition.
- Suggesting actionable insights for the bank to enhance customer retention.

## Data Description
The dataset comprises customer account details with the following attributes:

| Attribute                  | Description                                                     |
|----------------------------|-----------------------------------------------------------------|
| `CLIENTNUM`                | Unique identifier for each customer                             |
| `Attrition_Flag`           | Status of the customer (Attrited or Existing)                   |
| `Customer_Age`             | Age of the customer                                             |
| `Gender`                   | Gender of the account holder                                    |
| `Dependent_count`          | Number of dependents                                            |
| `Education_Level`          | Education level of customer                                     |
| `Marital_Status`           | Marital status of the customer                                  |
| `Income_Category`          | Customer's annual income category                               |
| `Card_Category`            | Type of credit card held by the customer                        |
| `Months_on_book`           | Duration of the customer’s relationship with the bank (months)  |
| `Total_Relationship_Count` | Number of products held by the customer                         |
| `Months_Inactive_12_mon`   | Months of inactivity in the past year                           |
| `Contacts_Count_12_mon`    | Number of contacts initiated by the customer in the past year   |
| `Credit_Limit`             | Credit limit on the card                                        |
| `Total_Revolving_Bal`      | Total revolving balance on the credit card                      |
| `Avg_Open_To_Buy`          | Average available credit over the past 12 months                |
| `Total_Amt_Chng_Q4_Q1`     | Change in transaction amount from Q4 to Q1                      |
| `Total_Trans_Amt`          | Total transaction amount over the past year                     |
| `Total_Trans_Ct`           | Total transaction count over the past year                      |
| `Total_Ct_Chng_Q4_Q1`      | Change in transaction count from Q4 to Q1                       |
| `Avg_Utilization_Ratio`    | Average credit utilization ratio                                |

**Key relationships:**
- **Revolving Balance:** Unpaid credit balance carried forward each month.
- **Average Open To Buy:** Average available credit limit over the past year.
- **Utilization Ratio Relationship:**
  \[(Avg_Open_To_Buy / Credit_Limit) + Avg_Utilization_Ratio = 1\]

## Analysis & Modeling Steps
- Data exploration and preprocessing
- Feature engineering and selection
- Building predictive models (Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, etc.)
- Model evaluation and optimization
- Interpretation and recommendations

## Tools and Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## How to Use
1. Clone this repository:
```bash
git clone [repository_url]
```

2. Open and execute the provided Jupyter notebook (`.ipynb` file) to follow and replicate the analysis and modeling process.

---

**Author:** Alex Brockman 
**Course:** Data Science and Machine Learning, Great Learning @ UT Austin  
**Date:** May 2024

