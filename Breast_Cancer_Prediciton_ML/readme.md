# Breast Cancer Prediction

A Machine Learning project that predicts whether a breast cancer tumor is **Benign** or **Malignant** using the Breast Cancer dataset from `sklearn.datasets`.

## Project Overview
This project helps understand how **Logistic Regression** can be used for classification problems in healthcare.

## What I worked on:

1. Loaded the Breast Cancer dataset from `sklearn`.
2. Converted the dataset into a **pandas DataFrame**.
3. Explored the data: checked shape, info, missing values, and statistical summary.
4. Analyzed the distribution of the target variable (`label`):
   - `1` → Benign
   - `0` → Malignant
5. Separated features (`X`) and target (`Y`).
6. Split the dataset into **training (80%)** and **testing (20%)** sets.
7. Trained a **Logistic Regression** model on the training data.
8. Evaluated the model using **accuracy score** on both training and testing data.
9. Built a **predictive system** to predict the class for new input data.
10. Tested the system with sample inputs to predict if the tumor is Benign or Malignant.

## Technologies Used
- Python
- NumPy
- Pandas
- scikit-learn

## Sample Output

- Input: `(13.54,14.36,87.46,566.3,...,0.07259)`  
  Output: `The Breast Cancer is Benign`

- Input: `(16.13,20.68,108.1,798.8,...,0.1142)`  
  Output: `The Breast Cancer is Malignant`
