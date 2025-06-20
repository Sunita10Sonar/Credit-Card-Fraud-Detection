# 💳 Credit Card Fraud Detection – Dealing with Imbalanced Datasets

## ✅ What
This project aims to detect **fraudulent credit card transactions** using machine learning, tackling the **class imbalance problem** where frauds represent only 0.17% of all transactions.

---

## ⚙️ How
- **Data Preprocessing**:
  - PCA-transformed features used (`V1` to `V28`), with `Amount` and `Time` scaled.
- **Imbalance Handling**:
  - Techniques like **SMOTE (oversampling)** and **NearMiss (undersampling)** used.
- **Algorithms Used**:
  - Logistic Regression, Decision Tree, Random Forest, KNN, and **XGBoost**.
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-Score, ROC-AUC.

---

## 📊 Results
- **Before Balancing**: Models had high accuracy but failed to detect frauds (low recall).
- **After Balancing**: XGBoost and Random Forest gave the best results:
  - **Precision**: ~0.95  
  - **Recall**: ~0.91  
  - **F1-Score**: ~0.93  
- ROC-AUC curve confirms strong model performance.

---

## 🚀 Future Impact
- Helps financial institutions **detect frauds in real time**, reducing losses.
- The approach can be scaled using real-time data pipelines or deep learning.
- Improves security while maintaining customer trust.

---
