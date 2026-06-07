# Customer Churn Prediction Using Machine Learning

## Project Overview

This project aims to predict customer churn for a subscription-based service using Machine Learning techniques. The model analyzes customer demographics and account information to identify customers who are likely to leave the service.

## Dataset Description

The dataset contains the following features:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card Status
* Active Membership Status
* Estimated Salary

### Target Variable

**Exited**

* 0 → Customer Retained
* 1 → Customer Churned

## Data Preprocessing

* Removed unnecessary columns (RowNumber, CustomerId, Surname)
* Handled categorical variables using One-Hot Encoding
* Feature scaling using StandardScaler
* Train-test split performed

## Exploratory Data Analysis (EDA)

### Churn Distribution

Analyzed the distribution of churned and retained customers.

### Correlation Analysis

Generated a correlation heatmap to identify relationships between features.

### Customer Demographics Analysis

* Age Distribution
* Gender Distribution
* Geography-wise Churn Analysis

## Machine Learning Models

### Logistic Regression

Accuracy: **81.10%**

### Random Forest Classifier

Accuracy: **87.05%**

### Gradient Boosting Classifier

Accuracy: **86.75%**

## Model Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 81.10%   |
| Random Forest       | 87.05%   |
| Gradient Boosting   | 86.75%   |

## Best Performing Model

**Random Forest Classifier** achieved the highest accuracy of **87.05%**.

## Key Insights

* Age is one of the most influential factors affecting customer churn.
* Active customers are less likely to leave the service.
* Customers with fewer products tend to churn more frequently.
* Geography and account balance contribute to churn prediction.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Future Improvements

* Hyperparameter Tuning
* XGBoost Implementation
* Model Deployment using Streamlit
* Real-Time Prediction Dashboard

## Conclusion

This project demonstrates how Machine Learning can be used to predict customer churn and help businesses improve customer retention through data-driven decision making.
