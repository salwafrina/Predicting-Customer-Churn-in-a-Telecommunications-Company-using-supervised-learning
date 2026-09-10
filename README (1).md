# Predicting Customer Churn in a Telecommunications Company using Supervised Learning

A classification project to predict customer churn (customers discontinuing their subscription) at a telecommunications company using the **Naive Bayes** algorithm.

## 📌 Description

Customer churn occurs when customers stop using a company's services. Since retaining existing customers is more cost-effective than acquiring new ones, detecting potential churn early is a strategic priority for telecom companies.

This project builds a classification model to predict whether a customer will churn or not, based on demographic data, service type, and subscription history.

## 🎯 Objectives

- Predict customer churn using the Naive Bayes classification method.
- Identify key factors that influence churn.
- Provide recommendations to help telecom companies improve customer retention strategies.

## 📊 Dataset

- **Source:** Telco Customer Churn Dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`)
- **Size:** 7,043 rows, 21 columns (7,032 rows after data cleaning)
- **Target variable:** `Churn` (Yes/No)
- **Features:** customer demographics (gender, SeniorCitizen, Partner, Dependents), service information (InternetService, OnlineSecurity, TechSupport, etc.), and contract/billing data (Contract, PaymentMethod, MonthlyCharges, TotalCharges)

## 🛠️ Methodology

1. **Data Cleaning** — removing duplicate records and handling missing values.
2. **Encoding** — converting categorical features into numerical values using Label Encoding.
3. **Data Splitting** — 80% training data, 20% testing data.
4. **Modeling** — training a Naive Bayes model to distinguish patterns between churned and retained customers.
5. **Evaluation** — assessing model performance using accuracy, precision, recall, F1-score, and confusion matrix.

## 📈 Results

| Metric | No (Stay) | Yes (Churn) |
|---|---|---|
| Precision | 0.88 | 0.56 |
| Recall | 0.81 | 0.69 |
| F1-score | 0.84 | 0.62 |

**Overall accuracy: ~77.6%**

## ⚙️ Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib

## 🚀 How to Run

```bash
# clone this repository
git clone <this-repo-url>
cd <folder-name>

# install dependencies
pip install pandas numpy scikit-learn matplotlib

# run the notebook
jupyter notebook Predicting_Customer_Churn_in_a_Telecommunications_Company_using_supervised_learning.ipynb
```

> Make sure the dataset file (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) is in the same folder as the notebook, or adjust the file path inside the notebook accordingly.

## 👥 Team

- Devlin Wen Sujatmiko
- George Steve
- Salwa Afrina Fadli

UNIJI, DKI Jakarta, Indonesia

## 📚 References

1. A. K. Agasti, P. K. Sahu, R. Panda, "Predicting customer churn in telecommunication sector using Naive Bayes algorithm," *Indonesian Journal of Electrical Engineering and Computer Science*, vol. 32, no. 1, 2023.
2. A. Ebrah, M. Elnasir, "Churn prediction using machine learning and recommendations plans for telecoms," *Journal of Computer and Communications*, vol. 7, no. 11, 2019.
3. S. Ouf, M. A. Abdel-Hamid, H. A. Hefny, "A proposed hybrid framework to improve the accuracy of customer churn prediction in telecom industry," *Journal of Big Data*, vol. 12, no. 1, 2024.
4. Tridens Technology, "Telecom churn: definition, prediction, and prevention," 2024.
