# Car Price Prediction 

Predicting the selling price of a used car is a valuable use case in the automobile industry.  
Accurate predictions help dealerships, platforms, and customers make informed pricing decisions.

---

## Project Summary
This project compares three regression models to estimate the selling price of a car:

- **Linear Regression**
- **Lasso Regression**
- **K-Nearest Neighbors (KNN Regressor)**

The model predicts prices based on features like fuel type, seller type, transmission, age, and kilometers driven.

---

## Approach

### **1️⃣Problem Understanding**
Goal: Predict the selling price of a car using its key attributes.

---

### **2️⃣ Data Preprocessing**
- Loaded and inspected dataset  
- Checked for missing values  
- Encoded categorical columns:
  - Fuel Type → Petrol/Diesel/CNG
  - Seller Type → Dealer/Individual
  - Transmission → Manual/Automatic
- Dropped irrelevant columns (`Car_Name`)
- Split the dataset into **train** and **test** sets

---

### **3️⃣ Exploratory Data Analysis**
Analyzed:
- Fuel type distribution  
- Seller type distribution  
- Transmission type influence  
- Age and KM driven  
- Selling price patterns  

---

### **4️⃣ Model Building**
Trained and evaluated:

#### 🔹 **Linear Regression**
- Baseline model for regression
- Fast and interpretable

#### 🔹 **Lasso Regression**
- L1 regularization  
- Reduces overfitting  
- Useful for feature selection  

#### 🔹 **KNN Regressor**
- Non-linear model  
- Predicts using nearest neighbors  
- Captures complex patterns  

---

## Model Evaluation
Evaluated using:

- **R² Score**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

Visualized:
- **Actual vs Predicted Prices** (Train & Test)

---

## Business Impact
This model can help:

- Dealerships determine fair selling prices  
- Buyers avoid overpriced listings  
- Platforms (Cars24, OLX, CarDekho) improve pricing algorithms  
- Analysts understand impact of features on valuation  

---

## Tech Stack
**Python · Pandas · NumPy · Scikit-Learn · Matplotlib · Seaborn**  
**Google Colab · GitHub**

---

## Conclusion
This project demonstrates how machine learning can accurately predict car prices.  
By comparing multiple models, it identifies strong baseline approaches suitable for real-world pricing systems.

