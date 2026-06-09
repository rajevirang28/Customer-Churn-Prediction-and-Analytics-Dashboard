# Customer Churn Prediction and Analytics Dashboard

---

## Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Understanding why customers leave and identifying high-risk customers can help organizations improve retention and maximize revenue.

This project performs an end-to-end analysis of customer churn using Python, Machine Learning, and Power BI. It includes data cleaning, exploratory data analysis (EDA), predictive modeling, and interactive dashboard visualization to generate actionable business insights.

---

## Project Objectives

* Analyze customer behavior and churn patterns.
* Identify factors contributing to customer attrition.
* Build machine learning models to predict customer churn.
* Visualize key metrics through an interactive Power BI dashboard.
* Provide data-driven recommendations to improve customer retention.

---

## Technologies Used

### Programming & Analytics

* Python
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* Power BI

### Machine Learning

* Scikit-Learn
* Logistic Regression
* Random Forest Classifier

### Development Tools

* Jupyter Notebook
* Git
* GitHub

---

## Dataset

### Dataset Source

IBM Telco Customer Churn Dataset

### Dataset Features

The dataset contains customer demographic information, account details, subscription information, billing data, and churn status.

customerID – Unique customer identifier.
gender – Gender of the customer.
SeniorCitizen – Indicates whether the customer is a senior citizen.
Partner – Specifies whether the customer has a partner.
Dependents – Indicates whether the customer has dependents.
tenure – Number of months the customer has stayed with the company.
PhoneService – Indicates whether the customer subscribes to phone services.
InternetService – Type of internet service subscribed to by the customer.
Contract – Customer's contract type (Month-to-Month, One Year, Two Year).
PaymentMethod – Method used by the customer for payments.
MonthlyCharges – Monthly amount charged to the customer.
TotalCharges – Total amount charged to the customer over their tenure.
Churn – Target variable indicating whether the customer left the company (Yes/No).

---

## Project Workflow

### 1. Data Collection

* Load telecom customer churn dataset.

### 2. Data Cleaning

* Handle missing values.
* Convert data types.
* Remove inconsistencies.

### 3. Exploratory Data Analysis (EDA)

* Churn distribution analysis.
* Contract type analysis.
* Tenure analysis.
* Monthly charges analysis.
* Payment method analysis.

### 4. Feature Engineering

* Create tenure groups.
* Encode categorical variables.
* Prepare features for machine learning.

### 5. Machine Learning

* Logistic Regression
* Random Forest Classifier

### 6. Model Evaluation

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

### 7. Dashboard Development

* Interactive Power BI Dashboard
* KPI Monitoring
* Customer Segmentation
* Churn Risk Analysis

---

## Machine Learning Models

### Logistic Regression

Used as a baseline classification model to predict customer churn.

### Random Forest Classifier

Used for improved predictive performance and feature importance analysis.

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

## Dashboard Features

### KPI Cards

* Total Customers
* Churn Rate
* Average Monthly Charges
* Average Customer Tenure

### Visualizations

* Churn Distribution
* Churn by Contract Type
* Churn by Payment Method
* Customer Tenure Analysis
* Monthly Charges Analysis
* Feature Importance Ranking

### Interactive Filters

* Gender
* Contract Type
* Internet Service
* Payment Method
* Senior Citizen Status

---

## Dashboard Preview

Add screenshots of your Power BI dashboard here.

```markdown
![Dashboard Preview](images/dashboard_preview.png)
```

---

## Key Insights

* Customers with month-to-month contracts exhibit significantly higher churn rates.
* Short-tenure customers are more likely to leave the service.
* Customers with higher monthly charges tend to churn more frequently.
* Electronic check payment users demonstrate higher churn behavior.
* Long-term contracts improve customer retention.

---

## Business Recommendations

1. Offer discounts for annual and multi-year contracts.
2. Implement retention campaigns targeting new customers.
3. Provide personalized offers to high-risk customers.
4. Improve onboarding experiences during the first year.
5. Monitor customers with high monthly charges for potential dissatisfaction.



## Future Enhancements

* XGBoost-based churn prediction.
* Customer Lifetime Value (CLV) analysis.
* Real-time churn prediction API.
* Automated Power BI refresh pipeline.
* Deployment using Streamlit or Flask.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction-and-Analytics-Dashboard.git
```

Navigate to the project directory:

```bash
cd Customer-Churn-Prediction-and-Analytics-Dashboard
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Results

| Metric    | Score           |
| --------- | --------------- |
| Accuracy  | ~80–85%         |
| Precision | Varies by model |
| Recall    | Varies by model |
| F1 Score  | Varies by model |

---

## Project Highlights

End-to-End Data Analytics Project

Machine Learning-Based Churn Prediction

Interactive Power BI Dashboard

Business Intelligence & Reporting

Real-World Telecom Customer Dataset
