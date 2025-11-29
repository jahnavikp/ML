# SMS Spam Classifier

A Machine Learning project that classifies SMS messages as **Spam** or **Ham** using Natural Language Processing (NLP) and multiple ML algorithms.

---

## Project Overview
This project builds a text classification model using the **spam.csv** dataset. It includes data cleaning, text preprocessing, visualization, vectorization, model training, and evaluation.

---

## Dataset
The dataset contains two important columns:

- **v1 → target** (ham/spam)  
- **v2 → message** (SMS text)

Unused columns were removed, and the dataset was cleaned and preprocessed.

---

## Data Preprocessing
Steps performed:
- Dropped unnecessary columns  
- Renamed columns (`target`, `message`)  
- Label encoding (ham → 0, spam → 1)  
- Removed duplicates  
- Added new features:
  - `num_characters`
  - `num_words`
  - `num_sentences`

---

## Exploratory Data Analysis (EDA)
Visualizations include:
- Pie chart of ham vs spam  
- Histograms of text features  
- Pairplots  
- Heatmap of correlations  

---

## NLP Pipeline
Text preprocessing includes:
- Lowercasing  
- Tokenization  
- Removing stopwords  
- Removing punctuation/special characters  
- Stemming using PorterStemmer  

Also generated:
- WordCloud for spam  
- WordCloud for ham  

---

## Feature Extraction
Used:
- **TF-IDF Vectorizer** (max_features=3000)

This converts text into numerical vectors for ML models.

---

## Machine Learning Models
Tested multiple classifiers:
- Gaussian Naive Bayes  
- Multinomial Naive Bayes  
- Bernoulli Naive Bayes  
- Logistic Regression  
- SVM  
- KNN  
- Decision Tree  
- Random Forest  
- AdaBoost  
- Bagging  
- Extra Trees  
- Gradient Boosting  
- XGBoost

Also used:
- **Voting Classifier**
- **Stacking Classifier**

Evaluated using **accuracy** and **precision**.

---

## Best Performing Models
- **Multinomial Naive Bayes (MNB)**  
- **SVM (sigmoid kernel)**  
- Ensemble models (Voting & Stacking)

---

## Tech Stack
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- NLTK  
- Scikit-learn  
- WordCloud  
- XGBoost  
