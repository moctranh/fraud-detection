# 💳 Fraud Detection using Machine Learning

This project aims to detect fraudulent credit card transactions using various machine learning models, with a focus on **XGBoost** and **StackingClassifier**. The dataset used is a real-world anonymized credit card transaction dataset from Kaggle.

---

## 📁 Project Structure

- `notebook.ipynb`: Main notebook containing all code steps, including preprocessing, model training, evaluation, and visualization.
- `dataset/creditcard.csv`: Dataset used for model training (can be downloaded from Kaggle).
- `README.md`: Project documentation.

---

## 📊 Dataset

- **Source**: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Records**: 284,807 transactions
- **Fraud cases**: 492 (0.172%)
- **Challenge**: Highly imbalanced dataset

---

## ⚙️ Models & Techniques

- ✅ Data preprocessing (imbalanced handling, feature scaling)
- ✅ Train/Test split and validation
- ✅ Hyperparameter tuning with `RandomizedSearchCV`
- ✅ Models used:
  - `XGBoost`
  - `LightGBM`
  - `RandomForest`
  - `LogisticRegression`
  - `StackingClassifier`
- ✅ Threshold tuning for optimal F1-score
- ✅ Evaluation metrics: Precision, Recall, F1-score, ROC-AUC
- ✅ Visualization of performance metrics over thresholds

---

## 📈 Results

- **Best F1-score**: ~0.87 on fraud detection
- **Precision (Fraud)**: ~0.95
- **Recall (Fraud)**: ~0.80
- **ROC-AUC**: ~0.99

---

## 🚀 How to Run

1. Clone the repo:

```bash
git clone https://github.com/moctranh/fraud-detection.git
cd fraud-detection
