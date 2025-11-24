# Credit Card Fraud Detection

Financial institutions lose millions every year due to **fraudulent transactions**.  
The challenge? Fraud cases represent **less than 0.2%** of the total transactions — making it extremely hard for traditional systems to catch them.

This project demonstrates how machine learning can be used to **identify fraudulent credit card transactions** with high precision, even in the presence of a highly imbalanced dataset.

---

## Business Problem

Banks face three major issues:

1. **High Imbalance**  
   Fraud cases are extremely rare, making it hard to train traditional models.

2. **High Financial Loss**  
   Every undetected fraud directly impacts revenue, insurance payouts, and customer trust.

3. **Need for Real-Time Detection**  
   Decisions must be made instantly to block suspicious transactions before damage occurs.

**Goal:**  
Build a model that can **differentiate fraud from legitimate transactions** and support fraud analysts in reducing financial risk.

---

## Key Business Insights

### 1️⃣ Data Imbalance is Extreme  
- Legit transactions: **284,315+**  
- Fraud transactions: **492**  
This shows why rule-based systems fail — they rarely see fraud patterns.

### 2️⃣ Fraud Transactions Show Distinct Patterns  
- Different spending behavior  
- Sharp deviations in certain numeric features  
- Unusual transaction values compared to legit users  

These patterns allow machine learning models to create meaningful decision boundaries.

### 3️⃣ Under-Sampling Provided Cleaner Learning  
To ensure fair learning, the majority class (legit) was under-sampled to match fraud counts.  
This helped the model avoid “always predicting legit” and instead learn true fraud signals.

---

## Machine Learning Approach

- **Model Used:** Logistic Regression  
- **Strategy:** Under-Sampling to balance 0/1 classes  
- **Train/Test Split:** 80/20  

### Performance:
- **Training Accuracy:** ~94%  
- **Testing Accuracy:** ~93%  

These results show that even simple ML models can perform extremely well when class imbalance is handled correctly.

---

## Final Outcome

This model can help financial institutions:

✔ **Reduce loss** by automatically flagging high-risk transactions  
✔ Improve **customer safety** by catching fraud earlier  
✔ Support **fraud analysts** with prioritized alerts  
✔ Automate **risk monitoring**  
✔ Provide **real-time classification** for millions of transactions

Even with a simple logistic regression model, the results demonstrate strong predictive capability when combined with proper data handling.

---

## Conclusion

This project proves that:

- Handling data imbalance is **more important** than choosing complex models  
- Fraud patterns can be detected through statistical differences in transaction behavior  
- Logistic Regression remains a powerful baseline model for classification problems  
- A balanced dataset enables accurate learning without bias  

**Overall, this ML system offers a practical, scalable, and cost-effective solution for fraud detection — making it highly relevant for real-world financial applications.**

---

