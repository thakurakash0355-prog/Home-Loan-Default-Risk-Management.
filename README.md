# Home Loan Default Risk Management

## 📌 Project Overview

This project focuses on predicting the likelihood of a borrower defaulting on a home loan and supporting financial institutions in effective credit risk management.

The objective is to analyze borrower and loan-related information, identify important risk factors, and build a machine learning model that can classify applicants based on their probability of loan default.

## 🎯 Business Objective

The main objectives of this project are:

- Identify customers who are at higher risk of loan default.
- Analyze borrower and financial characteristics affecting credit risk.
- Perform data cleaning and exploratory data analysis.
- Handle missing values and categorical variables effectively.
- Build and compare machine learning classification models.
- Evaluate model performance using appropriate classification metrics.
- Support data-driven loan approval and risk management decisions.

## 📊 Project Workflow

The project follows an end-to-end machine learning workflow:

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Missing Value Treatment
6. Feature Engineering
7. Categorical Variable Encoding
8. Feature Selection
9. Data Preprocessing
10. Model Training
11. Model Comparison
12. Model Evaluation
13. Risk Prediction
14. Business Insights

## 🧠 Machine Learning Approach

This is a supervised machine learning classification problem where the model predicts whether a loan applicant is likely to default.

The project focuses on comparing multiple classification algorithms and selecting an appropriate model based on performance and business requirements.

### Models Considered

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- Other suitable classification algorithms

## 📈 Model Evaluation

The models are evaluated using important classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

For credit risk management, particular attention is given to *Recall and ROC-AUC*, because correctly identifying high-risk borrowers is important for minimizing potential financial losses.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📁 Project Structure

```text
Home-Loan-Default-Risk-Management/
│
├── home_loan_def.ipynb
├── README.md
├── requirements.txt
│
└── Data/
    ├── application_train.csv
    ├── bureau.csv
    ├── bureau_balance.csv
    ├── credit_card_balance.csv
    ├── installments_payments.csv
    ├── POS_CASH_balance.csv
    └── previous_application.csv
