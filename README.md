# **Credit Risk Classification Project**

Created by Matthew Guy, 2025

A machine learning project focused on predicting borrower creditworthiness using **Python**, **Pandas**, **Scikit-learn**, and **Logistic Regression**. This project trains a binary classification model to identify high-risk loans from historical lending data.

---

## **Table of Contents**
- [Credit Risk Analysis](#credit-risk-analysis)
- [Features](#features)
- [Installation](#installation)
- [Usage Instructions](#usage-instructions)
- [Dataset Details](#dataset-details)
- [Model Functionality](#model-functionality)
- [Deployment](#deployment)
- [Future Enhancements](#future-enhancements)
- [About](#about)
- [Resources](#resources)

---

## **Credit Risk Analysis**

The purpose of this analysis is to evaluate the creditworthiness of borrowers using a logistic regression model. This model was trained on a dataset of historical lending activity from a peer-to-peer lending services company. The goal is to accurately classify borrowers as either **low risk (0)** or **high risk (1)** based on financial data, helping the company make informed lending decisions.

The dataset used in this analysis included the following key financial features:

- **loan_size**: The amount of the loan.
- **interest_rate**: The interest rate of the loan.
- **borrower_income**: The annual income of the borrower.
- **debt_to_income**: The ratio of the borrower’s debt to their income.
- **num_of_accounts**: The number of financial accounts the borrower has.
- **derogatory_marks**: The number of negative marks on the borrower’s credit history.
- **total_debt**: The total amount of debt the borrower holds.

The analysis involved the following stages:

- Data preprocessing (splitting data into features and labels)
- Splitting the data into training and testing sets (80/20 split)
- Training a logistic regression model using the training set
- Evaluating the model’s performance on the testing set

### **Results**

- **Accuracy**: 99%  
- **Precision for Healthy Loans (0)**: 100%  
- **Recall for Healthy Loans (0)**: 99%  
- **Precision for High-Risk Loans (1)**: 86%  
- **Recall for High-Risk Loans (1)**: 94%  

### **Summary**

The logistic regression model performed exceptionally well on this dataset, achieving an overall accuracy of 99%. It demonstrated perfect precision (100%) for predicting healthy loans (0) and high recall (94%) for identifying high-risk loans (1). This indicates the model is highly effective at correctly classifying healthy loans while also being strong at identifying high-risk cases.

However, the precision for high-risk loans (1) is slightly lower at 86%, meaning that a small percentage of loans classified as high-risk may actually be healthy. Despite this minor limitation, the model’s overall performance is strong, making it a suitable choice for this credit risk classification task.

Given the high accuracy, precision, and recall scores, I would recommend using this logistic regression model for credit risk classification, as it effectively balances sensitivity (recall) and specificity (precision), providing reliable predictions for both healthy and high-risk loans.

---

## **Features**

- Binary classification of loans into **low risk (0)** and **high risk (1)**.  
- Precision, recall, and accuracy metrics for model evaluation.  
- Simple logistic regression for straightforward interpretability.  
- Easy integration with real-time decision-making systems.

---

## **Installation**

### **Requirements**
- GitHub Account  
- Python 3.9+  
- Pandas, NumPy, Scikit-learn, and Matplotlib libraries

### **Quick Start Setup**

1. Clone or download the repository.  
2. Open the project in VS Code or your preferred editor.  
3. Ensure files are in the correct structure:

&nbsp;&nbsp;&nbsp;&nbsp;📁 credit-risk-classification  
&nbsp;&nbsp;&nbsp;&nbsp;├── Credit_Risk/  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── lending_data.csv  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;├── credit_risk_classification.ipynb  
&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;└── README.md  

4. Run `credit_risk_classification.ipynb` in Jupyter Notebook.  
5. Review the outputs and results.

---

## **Usage Instructions**

- Open the **credit_risk_classification.ipynb** notebook.  
- Run all cells to train the model and generate evaluation metrics.  
- Review the model’s accuracy, precision, and recall scores.

---

## **Future Enhancements**

- Integrate a more complex model for improved precision on high-risk loans.  
- Add real-time scoring capabilities for live credit risk assessments.  
- Implement a dashboard for interactive model analysis.

---

## **About**

This project was built as part of the Module 20 Challenge. It focuses on developing a binary classification model for financial risk prediction using historical lending data.

---

## **Resources**

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)  
- [Pandas Documentation](https://pandas.pydata.org/)  
- [NumPy Documentation](https://numpy.org/)  
- [Matplotlib Documentation](https://matplotlib.org/)  
- **DU Bootcamp Module 20**: Used for logistic regression, model evaluation, and data preprocessing.
