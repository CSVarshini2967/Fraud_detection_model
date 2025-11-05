# Fraud Detection using Machine Learning (Random Forest)

##  Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning.  
Due to the highly imbalanced nature of real-world fraud data, the project applies **SMOTE** to improve recall on fraud cases and uses a **Random Forest Classifier** to ensure robust prediction performance.

This project was built as part of a hackathon challenge.

---

## Key Features
- ✅ Handles highly imbalanced dataset using **SMOTE**
- ✅ Data preprocessing with scaling and feature engineering
- ✅ Random Forest for fraud classification
- ✅ Performance evaluation with multiple metrics
- ✅ Visualizations for model interpretability
- ✅ Export of fraud prediction results

---

## Dataset
- Public fraud dataset (Credit Card/Transaction based)
- Contains legitimate and fraudulent transactions
- Imbalanced classes → Fraud ≈ minority



---

##  Tech Stack
| Category | Tools |
|---------|------|
| Language | Python |
| ML | Random Forest (sklearn) |
| Data Manipulation | Pandas, NumPy |
| Balancing Technique | SMOTE (imblearn) |
| Visualization | Matplotlib, Seaborn |
| Model Evaluation | Confusion Matrix, ROC-AUC, Precision-Recall, F1 |

---

##  Model Performance (Test Set)

| Metric | Score |
|--------|------|
| Accuracy | **0.8027** |
| Precision | **0.70** |
| Recall | **0.6725** |
| F1-Score | **0.69** |
| AUC-ROC | **0.7835** |

###  Classification Report

| Class | Precision | Recall | F1-score |
|-------|----------|--------|----------|
| Legitimate | 0.85 | 0.86 | 0.86 |
| Fraud | 0.70 | 0.67 | 0.69 |

✅ The model balances fraud detection performance without excessive false alarms.


