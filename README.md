# Credit Card Anomaly Recognition

A machine learning project to detect fraudulent credit card transactions using real-world anonymized data. The project handles class imbalance with SMOTE and builds a **stacked ensemble model** using **Neural Networks (Keras)** and **XGBoost**, optimized for high recall and precision on fraud detection.

---

## 📊 Dataset

- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions
- 492 fraud cases (~0.17%)
- Features are numerical (PCA-anonymized), with `Time`, `Amount`, and binary `Class` (0 = legitimate, 1 = fraud)

---

## 🚀 Project Highlights

- Performed exploratory data analysis (EDA) to identify trends and outliers
- Addressed severe class imbalance using **SMOTE oversampling**
- Built a **stacked ensemble model** combining:
  - **Neural Network** (Keras, TensorFlow)
  - **XGBoost Classifier**
- Used stratified splits and proper model validation techniques
- Evaluated using precision, recall, F1-score, and ROC-AUC - focused on **fraud detection (Class 1)**

---

## 🔍 Results

> 📌 **Metrics below are specific to Class 1 (fraud cases):**

- **Recall:** 0.85  
- **Precision:** 0.76  
- **F1-score:** 0.80  
- **ROC-AUC:** 0.95  

Model captures the majority of fraudulent transactions while minimizing false positives.

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:**  
  - Pandas, NumPy, Matplotlib  
  - Scikit-learn, Imbalanced-learn  
  - **XGBoost**, **Keras (TensorFlow)**

---

## 📁 Files Included

- `fraud_detection.ipynb` - Complete notebook with EDA, modeling, evaluation  
- `README.md` - Project documentation  

---

## 📌 Author

**NerdFighter16**

---

## 🧾 License

This project is licensed under the MIT License.