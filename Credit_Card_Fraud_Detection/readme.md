# Credit Card Fraud Detection

## Why This Project Matters
Fraudulent credit card transactions cost banks **millions every year**.  
Detecting fraud is extremely challenging because fraudulent cases are **less than 0.2%** of all transactions.

A single undetected fraud can cause heavy financial loss, while flagging genuine transactions creates customer dissatisfaction.

This project demonstrates how **machine learning** can support banks in identifying suspicious transactions with high accuracy.

---

## Project Summary
I built a machine learning model to identify whether a credit card transaction is **Legit (0)** or **Fraud (1)** using historical transaction patterns.

The dataset was highly imbalanced, so I applied under-sampling and trained a Logistic Regression model to understand patterns behind fraudulent activity.

---

## My Approach

### 1. Problem Understanding
**Business goal:**  
Classify incoming credit card transactions and flag suspicious ones for further review.

### 2. Data Cleaning & Preprocessing
- Checked dataset structure and missing values  
- Separated legit vs fraudulent transactions  
- Performed **under-sampling** to balance classes  
- Validated distributions and summary statistics  
- Split data into training and testing sets  

### 3. Exploratory Data Analysis (EDA)
Key patterns identified in:

- **Transaction Amount**  
- **Class distribution (0 vs 1)**  
- **Statistical difference between legit and fraud transactions**  
- **Mean comparison of features for both classes**

Fraud transactions showed distinct behaviors compared to normal ones.

### 4. Model Building — Logistic Regression
**Why Logistic Regression?**

- Works well for binary classification  
- Fast, interpretable, and efficient  
- Good baseline for fraud detection problems  
- Performs well after class balancing  

**Steps:**
- Balanced the dataset using under-sampling  
- Trained Logistic Regression model  
- Predicted outcomes on train and test sets  
- Compared accuracy scores  

### 5. Model Evaluation
- **Training Accuracy:** ~94%  
- **Testing Accuracy:** ~93%  

Evaluated using:  
- Accuracy score  
- Class distribution balancing  
- Manual comparison of predictions  

---

## Business Evaluation

The model helps financial institutions:

- **Prevent financial losses** by identifying risky transactions  
- **Improve customer trust** with proactive fraud detection  
- **Enhance decision-making** with data-driven risk analysis  
- **Reduce manual workload** for fraud analysts  
- Highlight important indicators of fraud (e.g., unusual transaction amounts or patterns)

This system can be used as an early warning layer before manual investigation.

---

## Tech Stack

### Languages & Libraries
- Python  
- NumPy  
- Pandas  
- Scikit-Learn  
- Matplotlib, Seaborn  

### Tools
- Google Colab  
- GitHub  

---

## Conclusion
This project demonstrates that even with a simple logistic regression model, fraud detection becomes significantly more effective when the class imbalance problem is handled properly.

By balancing the dataset and training on meaningful patterns, the model can quickly classify transactions and support fraud prevention systems—making it highly useful for real-world banking environments.

---
