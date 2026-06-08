# Credit Scoring Model using Machine Learning

## 📌 Project Overview

This project aims to predict loan approval status and assess an applicant's creditworthiness using Machine Learning techniques. The model analyzes financial and demographic information to determine whether a loan application is likely to be approved or rejected.

---

## 🎯 Objective

To build a Credit Scoring Model that predicts loan approval status based on applicant details such as income, loan amount, credit history, education, and property area.

---

## 📊 Dataset

**Dataset:** Loan Prediction Dataset

### Features Used

* Gender
* Married
* Dependents
* Education
* Self Employed
* Applicant Income
* Coapplicant Income
* Loan Amount
* Loan Amount Term
* Credit History
* Property Area

### Target Variable

* Loan_Status

  * Y = Loan Approved
  * N = Loan Rejected

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Handling Missing Values
4. Feature Engineering
5. Encoding Categorical Variables
6. Train-Test Split
7. Model Training
8. Hyperparameter Tuning
9. Model Evaluation
10. Visualization and Analysis

---

## ⚙️ Feature Engineering

A new feature named **TotalIncome** was created:

TotalIncome = ApplicantIncome + CoapplicantIncome

This feature helps capture the overall income of the applicant's household and improves predictive performance.

---

## 🤖 Machine Learning Models Used

### 1. Logistic Regression

* Accuracy: 78.86%
* Precision: 75.96%
* Recall: 98.75%
* F1 Score: 85.87%
* ROC-AUC: 70.30%

### 2. Decision Tree

* Accuracy: 69.10%
* Precision: 75.00%
* Recall: 78.75%
* F1 Score: 76.83%
* ROC-AUC: 64.96%

### 3. Random Forest

* Accuracy: 78.05%
* Precision: 75.73%
* Recall: 97.50%
* F1 Score: 85.25%
* ROC-AUC: 69.68%

---

## 📈 Hyperparameter Tuning

Grid Search Cross Validation was applied to optimize the Random Forest model.

### Best Parameters

* n_estimators = 100
* max_depth = 5
* min_samples_split = 2

### Best Cross Validation Score

* 81.25%

---

## 📊 Visualizations

The project includes:

* Loan Status Distribution
* Confusion Matrix
* ROC Curve
* Feature Importance Analysis

---

## 🏆 Results

Among the evaluated models, **Logistic Regression** achieved the best overall performance with:

* Accuracy: 78.86%
* F1 Score: 85.87%
* ROC-AUC: 70.30%

Credit History was identified as the most influential feature affecting loan approval.

---

## 📂 Project Structure

```text
CodeAlpha_CreditScoringModel
│
├── data
│   └── train_u6lujuX_CVtuZ9i.csv
│
├── images
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
│
├── Credit_Scoring_Model.ipynb
├── requirements.txt
└── README.md
```

---

## 🎓 Internship Task

This project was completed as part of the **CodeAlpha Machine Learning Internship** under the task:

**Task 1: Credit Scoring Model**

---

## 👨‍💻 Author

Byreddy Uday Pujith Reddy
B.Tech Artificial Intelligence Engineering
Amrita Vishwa Vidyapeetham, Nagercoil
