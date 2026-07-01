# CodeAlpha_Credit_Scoring
# 🏦 Credit Scoring Prediction System

A Machine Learning web application that predicts whether a customer is likely to have **Good Credit** or **Bad Credit** using financial information.

This project was developed as part of the **CodeAlpha Machine Learning Internship**.

---

# Project Overview

Financial institutions use credit scoring models to determine whether an applicant is eligible for a loan.

This project predicts customer creditworthiness using Machine Learning classification algorithms.

The project includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Model Training
- Model Evaluation
- Feature Importance Analysis

---

# Dataset

**German Credit Dataset**

Total Records: **1000**

Features: **20**

Target Classes:

- Good Credit
- Bad Credit

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Joblib

---

# Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

# Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 72% |
| Decision Tree | 71% |
| Random Forest | 79% |

Random Forest produced the best overall performance and was selected as the final model.

---

# Features Used

- Status of Checking Account
- Credit Duration
- Credit History
- Purpose
- Credit Amount
- Savings Account
- Employment Duration
- Payment-to-Income Ratio
- Personal Status and Sex
- Secondary Obligor
- Residence Since
- Collateral
- Age
- Other Installment Plans
- Housing
- Number of Existing Credits
- Job
- Number of Guarantors
- Telephone
- Foreign Worker

---

# Project Workflow

1. Load Dataset
2. Data Exploration
3. Data Cleaning
4. Label Encoding
5. Train-Test Split
6. Train Models
7. Evaluate Models
8. Select Best Model
9. Save Model using Joblib


---

# Feature Importance

Random Forest Feature Importance was used to determine the most influential features affecting credit approval.

<img src="images/feature_importance.png" alt="Project Screenshot" width="500">

# Installation

Clone the repository

```bash
git clone https://github.com/Sai-Rohith202/CodeAlpha_Credit_Scoring.git
```

Move into the project folder

```bash
cd CodeAlpha_Credit_Scoring
```

Install dependencies

```bash
pip install -r requirements.txt

```


# Project Structure

```
CodeAlpha_Credit_Scoring
│
├── app.py
├── Credit_Scoring_Model.ipynb
├── credit_scoring_model.pkl
├── label_encoders.pkl
├── requirements.txt
├── README.md
├── dataset/
├── images/
└── model/
```

---

# Future Improvements

- Hyperparameter Optimization
- XGBoost Classifier
- Explainable AI (SHAP)
- User Authentication
- Cloud Deployment
- Responsive Dashboard

---

# Author

**Sai Rohith**

Machine Learning Enthusiast

Python Developer

AI & Data Science Learner

---

# License

This project is developed for educational purposes under the CodeAlpha Internship.
