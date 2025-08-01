# 💳 Credit Card Fraud Detection using Machine Learning – Dealing with Imbalanced Datasets

This project aims to detect fraudulent credit card transactions using supervised machine learning models. By leveraging a real-world anonymized dataset, the models help identify potentially fraudulent activity with high accuracy.

---

## 📁 Dataset

- Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
  
- Total transactions: 284,807
- Fraudulent transactions: 492 (0.172%)
- Features are PCA-transformed (V1–V28) + Time, Amount

---

## ⚙️ Tools & Technologies Used

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Algorithms:** Logistic Regression, Random Forest, Decision Tree, XGBoost  
- **Techniques:** SMOTE (oversampling), Cross-validation, Confusion Matrix, ROC-AUC

---

## 🚀 Project Workflow

1. Data Preprocessing
   - Null value check
   - Feature scaling
2. Exploratory Data Analysis (EDA)
   - Class imbalance analysis
   - Correlation matrix
   - Fraud vs non-fraud behavior
3. Data Balancing
   - Applied SMOTE for oversampling
4. Model Training & Evaluation
   - Trained 4 models
   - Evaluated using Accuracy, Precision, Recall, F1 Score, ROC Curve

---

## 📊 Results (on balanced dataset)

| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression | 96.4%   | 93.1%     | 92.7%  | 92.9%    |
| Random Forest       | 99.2%   | 98.8%     | 99.0%  | 98.9%    |
| Decision Tree       | 98.5%   | 97.2%     | 97.5%  | 97.3%    |
| XGBoost             | 99.3%   | 99.0%     | 99.1%  | 99.0%    |

> ✅ XGBoost outperformed other models with high recall, which is crucial in fraud detection.

---

## 📌 Key Learnings

- Dealt with severe class imbalance using SMOTE.
- Understood how different models handle imbalanced data.
- Learned the importance of Recall in fraud detection.
- Practiced EDA, feature engineering, and model evaluation.

---

## 📷 Screenshots

<sub>(Insert model comparison graph, confusion matrix heatmaps, etc. here)</sub>

---

## 📂 How to Run

```bash
git clone https://github.com/Sunita10Sonar/CreditCard-FraudDetection.git
cd CreditCard-FraudDetection
open the notebook in Jupyter or VSCode
