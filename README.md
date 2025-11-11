# 🚀 Machine Learning Projects (ONNX + GitHub Pages)

This repository includes two simple machine learning projects trained in Python and deployed using **ONNX Runtime Web** so you can run predictions directly in your browser.

---

## 🧠 1. Auto Price Prediction

**Goal:** Predict the price of a car based on its features.

**Steps:**
1. Data preprocessing (handling missing values, encoding, scaling)
2. Train models (Neural Network + Random Forest)
3. Evaluate using R² score
4. Export the best model to `model.onnx`
5. Use `index_auto.html` to test predictions on the web

**Results:**
- Accuracy (R²): ~0.90  
- Best Model: Random Forest  

---

## 💼 2. Adult Income Classification

**Goal:** Predict if a person earns more than \$50K/year.

**Steps:**
1. Clean and encode the data
2. Apply SMOTE for class balancing
3. Train an XGBoost classifier
4. Evaluate using Accuracy, F1, and ROC-AUC
5. Export model to `xgb_model.onnx`
6. Use `index_income.html` for web demo

**Results:**
- Accuracy: ~90%  
- F1 Score: ~0.89  

---

## ⚙️ Requirements

Install the required libraries before running:

```bash
pip install pandas numpy scikit-learn torch xgboost imbalanced-learn onnx onnxruntime matplotlib seaborn
