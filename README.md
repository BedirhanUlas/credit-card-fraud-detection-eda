# Credit Card Fraud Detection – EDA & Baseline Model (Module 20)

## 📌 Project Overview
This repository contains the initial phase of the credit card fraud detection project, developed as part of the UC Berkeley Machine Learning Capstone (Module 20). The goal of this stage is to explore the dataset, address class imbalance, and build a baseline model using logistic regression.

---

## 📊 Dataset
- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Total Transactions**: 284,807
- **Fraudulent Cases**: 492 (approx. 0.17%)
- **Features**:
  - `Time`, `Amount`
  - V1–V28: Anonymized PCA components
  - `Class`: Target variable (0 = Non-Fraud, 1 = Fraud)

📦 **Note**: The dataset is too large to be stored directly in this GitHub repository.  
Please download it from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and place `creditcard.csv` inside a folder named `dataset/`.

---

## 🔍 Tasks Completed in This Module
### ✅ Exploratory Data Analysis (EDA)
- Visualized transaction distributions by time and amount
- Compared fraud and non-fraud patterns
- Identified class imbalance and feature correlations

### ✅ Data Preprocessing
- Scaled `Time` and `Amount` using `StandardScaler`
- Applied **SMOTE** to oversample the minority class (fraud)

### ✅ Baseline Modeling
- Trained a **Logistic Regression** model on the balanced dataset
- Evaluated using confusion matrix and classification report

---

## 🧪 Key Insights
- The dataset is highly imbalanced and requires oversampling techniques
- Most fraudulent transactions are low in amount
- Logistic Regression provides a solid baseline but may miss some fraud cases

---

## 🗂️ Repository Structure
```
credit-card-fraud-detection-eda/
├── Capstone Project Module 20.ipynb    # EDA and baseline model notebook
├── dataset/
│   └── creditcard.csv                  # Place the dataset here manually
└── README.md                           # This file
```

---

## 🧠 What's Next?
In Module 24, this project will be expanded with:
- Advanced ensemble models (Random Forest, XGBoost)
- Model comparison visuals
- Final technical and non-technical reporting

---

## 📎 Notes
- This notebook focuses on building a clean, functional foundation for fraud detection
- Final model training and comparison will be published separately in the final project repository

---

**Author:** Bedirhan Ulas  
**Course:** UC Berkeley Machine Learning Capstone – Module 20
