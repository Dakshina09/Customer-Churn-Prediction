# Customer-Churn-Prediction

Project Overview

This project focuses on predicting customer churn using Machine Learning techniques. Customer churn prediction helps businesses identify customers who are likely to stop using a service, allowing companies to improve retention strategies and reduce revenue loss.

The project performs:
Data preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Statistical Analysis
Machine Learning Model Training
Hyperparameter Tuning
Customer Segmentation
Model Explainability
Business Insight Generation
Problem Statement

Customer churn is one of the biggest challenges faced by subscription-based businesses. Predicting churn early helps companies:
Improve customer retention
Reduce customer acquisition costs
Increase profitability
Personalize customer experience
The goal of this project is to build a predictive machine learning system that can classify whether a customer will churn or not.

Dataset
Dataset used:
Customer Churn Dataset

Features include:
Age
Gender
Tenure
Usage Frequency
Support Calls
Payment Delay
Subscription Type
Contract Length
Total Spend
Last Interaction
Churn

Technologies Used
Programming Language
Python

Libraries
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
shap
imbalanced-learn
scipy
joblib
Machine Learning Models Used

The following models were implemented and compared:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier

Project Workflow


1. Data Preprocessing
Missing value handling
Label encoding
Feature scaling
Data splitting
SMOTE balancing

3. Exploratory Data Analysis
Churn distribution analysis
Correlation heatmaps
Subscription analysis
Gender-based churn analysis
Contract length analysis
Tenure analysis
Spending pattern visualization

4. Feature Engineering
New features created:
Average Spend Per Month
Engagement Score

5. Statistical Analysis
Performed:
Chi-Square Test
T-Test
Correlation Analysis

6. Model Evaluation
Evaluation metrics used:
Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix

7. Hyperparameter Tuning
Used: GridSearchCV

8. Customer Segmentation
Used: K-Means Clustering

9. Model Explainability

Used: SHAP Explainability

Key Insights
Customers with higher support calls are more likely to churn.
Long-term contracts reduce churn probability.
High engagement customers are more likely to stay.
Payment delays strongly influence churn behavior.
Subscription type significantly impacts customer retention.
Business Recommendations
Improve customer support response quality.
Introduce loyalty programs for long-term customers.
Offer personalized discounts to high-risk customers.
Create targeted campaigns for low-engagement users.
Improve payment reminder systems.
Results

The Random Forest and XGBoost models achieved the best performance for churn prediction.

Additional techniques like:

SMOTE
Hyperparameter tuning
Feature engineering

helped improve model performance and robustness.

Project Structure
Customer-Churn-Prediction/
│
├── customer_churn_dataset.csv
├── customer_churn_prediction.ipynb
├── customer_churn_model.pkl
├── README.md
│
├── images/
│   ├── churn_distribution.png
│   ├── roc_curve.png
│   ├── feature_importance.png
│   └── segmentation.png
│
└── requirements.txt

Future Improvements

Possible future enhancements:

Deep Learning implementation
Real-time churn prediction API
Streamlit dashboard deployment
Power BI dashboard integration
Cloud deployment
Automated retraining pipeline
