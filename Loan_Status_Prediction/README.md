# Loan Status Prediction 

## Why This Project Matters
Loan approval is one of the most critical decisions for financial institutions.
A single incorrect approval can cause **losses**, and denying a genuine applicant
can reduce **business growth**.

This project demonstrates how **data-driven decisions** can improve loan approval
accuracy using Machine Learning.

## Project Summary
I built a machine learning model to predict whether a loan application will be
**approved or rejected** based on applicant demographic and financial details.

## My Approach

### 1. Problem Understanding
Business goal:
Predict **Loan_Status (Y/N)** using customer data.

### 2. Data Cleaning & Preprocessing
- Missing value imputation
- Encoding categorical variables
- Outlier handling
- Smart logical imputation
- Train–test split

### 3. Exploratory Data Analysis (EDA)
Key patterns found in:
- Credit history
- Applicant income
- Co-applicant income
- Property area
- Employment type

### 4. Model Building — Support Vector Machine (SVM)
**Why SVM?**
- Works well on medium-sized datasets
- Handles linear & non-linear patterns
- Good classification margins

**Steps:**
- Selected SVM classifier
- Kernel selection
- Hyperparameter tuning (C)
- Training and testing

### 5. Model Evaluation
- **Training Accuracy:** 79.62%
- **Test Accuracy:** 81.25%

Evaluated using:
- Accuracy
- Confusion matrix
- Classification report
- ROC-AUC

## Business Evaluation
Model helps:
- Reduce risky approvals
- Capture genuine applicants
- Improve decision-making
- Highlight factors like credit history, income, dependents

## Tech Stack
**Languages & Libraries**
- Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn

**Tools**
- Google Colab
- GitHub
