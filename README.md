# Bank-Customer-Churn-Prediction-Using-Random-Forest-A-Data-Driven-Retention-Strategy
A Data-Driven Retention Strategy
📌 Project Overview
Customer churn is a critical challenge for banking institutions, as losing customers can negatively impact revenue and long-term customer relationships. This project focuses on predicting whether a bank customer is likely to churn using a Random Forest Classifier, enabling organizations to take proactive customer retention actions.
By analyzing customer demographics, financial information, and banking-related attributes, this model helps identify customers at risk of leaving and supports data-driven decision-making.

🎯 Problem Statement
Banks may lose valuable customers when they close their accounts or stop using banking services.
The goal of this project is to:
Predict customer churn (Exited: Yes/No) accurately
Identify key factors influencing customer churn
Compare different machine learning classification models
Improve model performance through hyperparameter tuning
Assist banks in reducing customer churn through targeted retention strategies

📊 Dataset Description
The dataset contains customer-level information related to banking, including demographic, financial, and account-related attributes.
Key Features Include:
Customer demographics (age, gender, geography)
Financial information (credit score, balance, estimated salary)
Account information (tenure, number of products)
Banking services (credit card ownership, active membership)

Target Variable:
Exited → 1 = Customer churned, 0 = Customer remained

🛠️ Technologies & Tools Used
Programming Language: Python
Libraries:
pandas, numpy – data processing
matplotlib, seaborn – data visualization
scikit-learn – model building and evaluation
joblib – saving the trained machine learning model
Environment: Jupyter Notebook

🔄 Project Workflow
Data Loading & Exploration
Data Cleaning & Preprocessing
Checking dataset structure
Removing unnecessary identifier columns
Encoding categorical features
Exploratory Data Analysis
Analyzing customer churn distribution
Visualizing relationships between features and churn
Correlation analysis
Train-Test Split
Model Building
Logistic Regression
Random Forest Classifier
Model Evaluation
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
Feature Importance Analysis
Hyperparameter Tuning
GridSearchCV
Cross-validation
Model Comparison
Saving the Trained Model
Prediction for a New Customer

🤖 Why Random Forest?
Random Forest was chosen as the primary model because it:
Handles non-linear relationships effectively
Works well with structured tabular data
Captures complex interactions between customer features
Reduces overfitting using ensemble learning
Provides feature importance insights
Performs well for classification problems
