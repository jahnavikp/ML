# Wine Quality Prediction

A Machine Learning project that predicts whether wine is **Good Quality** or **Bad Quality** using chemical properties of wine.

---

## Project Overview
This project uses the **Wine Quality dataset** to:
- Explore data through visualization  
- Build a Random Forest Classifier  
- Predict wine quality based on 11 input features  

Quality is binarized as:
- **1 = Good Quality (quality >= 7)**
- **0 = Bad Quality (quality < 7)**

---

## Dataset
Each wine sample contains 11 chemical properties:
- fixed acidity  
- volatile acidity  
- citric acid  
- residual sugar  
- chlorides  
- free sulfur dioxide  
- total sulfur dioxide  
- density  
- pH  
- sulphates  
- alcohol  

Target column:
- **quality** (0–10 score)

---

## Data Preprocessing
Steps performed:
- Checked missing values  
- Descriptive statistics  
- Visualized relations with quality  
- Generated heatmap of correlations  
- Separated features (X) and label (Y)  
- Label binarization for quality  

---

## Exploratory Data Analysis (EDA)
Visualizations include:
- Count plot of wine quality  
- Bar plots comparing chemical features vs quality  
- Correlation heatmap  

---

## Model Used
A **Random Forest Classifier** was trained on:
- 80% training data  
- 20% testing data  

Metric used:
- **Accuracy Score**

---

## Prediction System
The model takes **11 input values** from the user and predicts:
- **Good Quality Wine**
- **Bad Quality Wine**

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---
