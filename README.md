# Customer Churn Analysis & Prediction

## Overview

Customer churn is one of the most critical business challenges for subscription-based companies. Acquiring new customers is often more expensive than retaining existing ones, making churn analysis essential for improving profitability and customer satisfaction.

This project analyzes customer behavior using the Telco Customer Churn dataset and develops machine learning models to predict churn risk. The project combines Exploratory Data Analysis (EDA), predictive modeling, feature importance analysis, and business recommendations to identify the key factors influencing customer retention.

---

## Business Problem

Telecommunication companies face significant revenue loss when customers discontinue their services. The objective of this project is to:

* Identify patterns associated with customer churn.
* Understand which customer segments are most likely to leave.
* Build predictive models to estimate churn probability.
* Generate actionable retention strategies based on analytical findings.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

### Features Include:

* Demographics (Gender, Senior Citizen, Partner, Dependents)
* Account Information (Tenure, Contract Type, Payment Method)
* Services Used (Internet Service, Online Security, Tech Support, Streaming Services)
* Billing Information (Monthly Charges, Total Charges)
* Churn Status (Target Variable)

### Dataset Size

* Records: 7,043 customers
* Features: 21 variables

---

## Project Workflow

### 1. Data Cleaning

* Checked dataset structure and missing values
* Converted data types where necessary
* Processed and cleaned TotalCharges field
* Prepared data for analysis and modeling

### 2. Exploratory Data Analysis (EDA)

Performed analysis on:

* Customer churn distribution
* Gender-based churn trends
* Contract type impact
* Monthly charges analysis
* Tenure analysis
* Correlation analysis

### Key EDA Findings

* Customers with month-to-month contracts exhibit significantly higher churn rates.
* Customers with shorter tenure are more likely to leave.
* Higher monthly charges correlate with increased churn probability.
* Long-term contracts improve customer retention.
* Service-related features influence customer loyalty.

---

## Machine Learning Models

### Logistic Regression

Used as a baseline classification model.

#### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

### Random Forest Classifier

Used to capture non-linear relationships and feature interactions.

#### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

### Model Comparison

The project compares both models to identify the most effective approach for churn prediction.

---

## Feature Importance Analysis

Feature importance analysis was performed using the Random Forest model to determine which variables have the strongest influence on churn prediction.

### Major Churn Drivers

* Contract Type
* Tenure
* Monthly Charges
* Total Charges
* Internet Service
* Payment Method
* Online Security
* Tech Support

These insights help businesses prioritize customer retention efforts.

---

## Business Recommendations

### High-Risk Customers

Characteristics:

* Month-to-month contracts
* Low tenure
* High monthly charges

Recommended Actions:

* Offer contract upgrade incentives
* Introduce loyalty discounts
* Improve onboarding experience

### Medium-Risk Customers

Characteristics:

* Moderate tenure
* Limited service usage

Recommended Actions:

* Cross-sell additional services
* Improve customer engagement programs

### Low-Risk Customers

Characteristics:

* Long-term contracts
* Stable billing history

Recommended Actions:

* Reward loyalty
* Maintain service quality
* Upsell premium plans

---

## Technologies Used

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn

### Development Environment

* Jupyter Notebook

---

## Project Structure

```text
Customer-Churn-Analysis/
│
├── notebook_churn.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── All Graphs/
│   ├── churn distribution.png
│   ├── contract.png
│   ├── correlation.png
│   ├── gender.png
│   ├── monthly charges.png
│   └── tenure.png
│
└── README.md
```

## Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* Feature Engineering
* Machine Learning
* Classification Modeling
* Model Evaluation
* Feature Importance Analysis
* Business Intelligence
* Data Storytelling

---

## Future Improvements

* XGBoost implementation
* Hyperparameter tuning
* SHAP explainability
* Interactive Power BI dashboard
* Customer risk segmentation dashboard
* Real-time churn prediction application

---

## Author

**Swapneel**

* LinkedIn: https://www.linkedin.com/in/kumar-swapneel-a9262328b/
* GitHub: https://github.com/SWAPNEEL100GRAY
