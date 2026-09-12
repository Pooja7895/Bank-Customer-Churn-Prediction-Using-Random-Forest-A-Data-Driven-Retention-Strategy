# Bank-Customer-Churn-Prediction-Using-Random-Forest-A-Data-Driven-Retention-Strategy
**A Data-Driven Customer Retention Strategy**
 
📌  **Project Overview** 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Customer churn is a major challenge for **banking and financial institutions**. When customers close their bank accounts or stop using banking services, it can lead to a loss of revenue and increased customer acquisition costs.

This project focuses on predicting whether a bank customer is likely to leave the bank using **Machine Learning Classification Models, with Random Forest** as the primary model.

By analyzing customer demographic, financial, and banking-related information, this project helps identify customers at risk of churn and supports proactive customer retention strategies.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🎯 **Problem Statement**

Banks may lose valuable customers when they close their accounts or stop using banking services.

Many banks identify customer churn only after the customer has already left. At that point, it becomes difficult to take corrective action.

The goal of this project is to:

* Predict whether a customer is likely to leave the bank.

* Identify key factors influencing customer churn.

* Analyze customer demographic, financial, and account-related information.

* Compare different machine learning classification models.

* Improve Random Forest performance through hyperparameter tuning.

* Support banks in developing targeted customer retention strategies.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 **Dataset Description**

The dataset used for this project is the Bank Customer Churn Modelling Dataset.

It contains customer information from a bank and is used to predict whether a customer will leave the bank.

**Dataset Overview**

* Each row represents one bank customer.

* Each column represents demographic, financial, or banking-related information.

* The dataset contains both numerical and categorical features.

* The target variable is Exited.

* This is a binary classification problem.

**Dataset Details**

* Dataset Name	Bank Customer Churn Modelling Dataset

* File Name	Churn_Modelling.csv

* Number of Records	10,000

* Number of Columns	14

* Target Variable	Exited

* Problem Type	Binary Classification

* Business Domain	Banking and Customer Retention


**Target Variable**

* Exited = 1 → Customer has exited the bank.

* Exited = 0 → Customer has remained with the bank.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ **Technologies & Tools Used**

* Programming Language: Python
  
 * Libraries:

  ◦ pandas, numpy – data processing
 
 ◦  matplotlib, seaborn, plotly – data visualization

 ◦  scikit-learn – model building and evaluation


 ◦  joblib – model and scaler serialization

* Development Environment: Jupyter Notebook

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔄 **Project Workflow**

**1.** Data Loading and Exploration

**2.** Import the dataset.

**3.** Understand dataset shape and data types.

**4.** Check for missing values.

**5.** Inspect numerical and categorical columns.

**6.** Exploratory Data Analysis

  ◦ Numerical feature distribution.

  ◦  Categorical feature analysis.

  ◦  Correlation analysis.

  ◦  Customer churn distribution.

 ◦  Churn analysis by geography.

 ◦  Churn analysis by age.

 ◦  Churn analysis by credit score.

**7.** Data Preprocessing

**8** Remove unnecessary identifier columns.

**9.** Separate independent and dependent variables.

**10** Encode categorical features.

**11** Check missing values after encoding.

**12** Train-Test Split

**13** Split the dataset into training and testing data.

**14** Use stratified sampling to maintain class distribution.

**15** Feature Scaling

**16** Model Building

 ◦  Logistic Regression.

 ◦  Model Evaluation

 ◦  Accuracy.

 ◦  Precision.

 ◦  Recall.

 ◦  F1-Score.

 ◦  Classification Report.

 ◦  Confusion Matrix.


**17** Hyperparameter Tuning

**18** Use GridSearchCV to improve Random Forest performance.

**19** Model Saving and Prediction

**20** Save the trained model and scaler using Joblib.

**21** Predict churn probability for a new customer.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🤖  Why Random Forest? 

* Random Forest was selected as the primary model because it:

* Handles non-linear relationships effectively.

* Works well with different numerical and categorical features after preprocessing.

* Combines multiple decision trees to improve prediction performance.

* Reduces overfitting through ensemble learning.

* Provides feature importance insights.

* Performs well for classification problems involving customer behaviour.
