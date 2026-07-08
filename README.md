# Credit Card Fraud Detection

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. Since fraud cases are extremely rare compared to genuine transactions, the dataset is highly imbalanced. Different techniques such as Logistic Regression, Class Weighting, SMOTE, and Random Forest were implemented and compared to identify the most effective model.

---

## Dataset

- Source: Kaggle Credit Card Fraud Detection Dataset
- Total Transactions: 284,807
- Features: 30
- Target:
  - 0 = Genuine Transaction
  - 1 = Fraudulent Transaction

---

## Project Workflow

- Data Loading
- Data Exploration
- Missing Value Check
- Class Distribution Analysis
- Feature Scaling
- Train-Test Split with Stratification
- Logistic Regression
- Logistic Regression with Class Weight
- SMOTE
- Random Forest
- Hyperparameter Tuning using RandomizedSearchCV
- ROC Curve
- Feature Importance
- Model Saving

---

## Models Compared

| Model | Precision | Recall | F1 Score |
|--------|----------:|--------:|----------:|
| Logistic Regression | 0.83 | 0.64 | 0.72 |
| Balanced Logistic Regression | 0.06 | 0.92 | 0.11 |
| SMOTE + Logistic Regression | 0.06 | 0.92 | 0.11 |
| Random Forest | **0.94** | **0.82** | **0.87** |

---

## Final Model Performance

- Accuracy: **99.96%**
- Precision: **94.12%**
- Recall: **81.63%**
- F1 Score: **87.43%**
- ROC-AUC Score: **96.30%**

---

## Visualizations

- Class Distribution
- Correlation Heatmap
- Confusion Matrix
- ROC Curve
- Feature Importance

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

---

## Key Learning

- Handling Imbalanced Data
- Precision vs Recall
- SMOTE
- Class Weighting
- ROC-AUC
- Random Forest
- Hyperparameter Tuning
- Fraud Detection Pipeline

---

## Project Structure

```
Credit-Card-Fraud-Detection
│
├── data
├── notebooks
├── models
├── images
├── README.md
├── requirements.txt
└── interview_questions.txt
```

---

## Author

Dipak Chaudhari