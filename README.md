# Thesis-code.html
# 🎯 Identification and Classification of Bank Customers Based on Credit Risk & Default Prediction

**Published Research:** *"Credit Risk Management for Enhancing Facilities Allocation to Bank Customers"*

This repository presents a machine learning-based framework for **credit risk segmentation** and **default probability prediction** of bank customers. Developed as part of my academic thesis, this project combines **clustering techniques** and **predictive modeling** to support smarter loan allocation and risk management in the banking sector.

> 🔒 **Note on Data Privacy**: Due to confidentiality and privacy constraints related to real banking data, **actual output values, customer identifiers, and sensitive financial figures have been removed or anonymized** in the shared notebooks. The analysis logic, code structure, and methodology remain fully intact and reproducible.
---

## 📁 Files Included
- `thesis-code.html` → Complete implementation of the thesis project, including **K-Means clustering**, **risk-based customer segmentation**, and **default prediction models (XGBoost, Logistic Regression)**.

> 💡 **Tip**: Open `.html` files directly in your browser to view the full notebook — including code, visualizations (with dummy/obfuscated values), and model workflows.

---

## 🎓 Project Overview

The banking system plays a vital role in a country’s economic development. One of the key challenges banks face is **accurately assessing customer credit risk** when granting loans.
This project aims to:
1. **Segment customers** based on their credit risk using clustering algorithms.
2. **Predict the probability of default** for each segment using advanced machine learning models.

The approach combines **unsupervised learning** (for segmentation) and **supervised learning** (for prediction), creating a hybrid framework that supports strategic decision-making in credit risk management.

---

### 🔍 Techniques Used
- **Unsupervised Learning**
  - **K-Means Clustering** (Optimal k selected via Elbow & Silhouette)
  - **Hierarchical Clustering** (for validation)
  - **Genetic Algorithm (GA)**: Optimizes initial centroids for K-Means to avoid local optima.
- **Supervised Learning**
  - **XGBoost Classifier** (High-performance gradient boosting)
  - **Logistic Regression** (Baseline model for interpretability)
- **Data Preprocessing**
  - Handling missing values, outlier detection, normalization
- **Visualization**
  - Matplotlib & Seaborn for cluster profiles and model evaluation

---

### 🧠 Key Findings from Thesis Research

The K-Means clustering results revealed **four distinct customer segments**:

| Cluster | Risk Level       | Characteristics |
|--------|------------------|----------------|
| 1      | ✅ **Low Risk**     | Minimal overdue debt, positive loan status — ideal candidates for new loans. |
| 2      | ⚠️ **Medium Risk**  | Stable but show early warning signs — require monitoring. |
| 3      | ⚠️🔥 **Critical**     | High overdue debt — at risk of becoming high-risk; needs intervention. |
| 4      | ❌ **High Risk**    | Highest delinquency and defaulted loans — must be closely supervised. |

Using **XGBoost and Logistic Regression**, the model predicts the **default probability** for each cluster, enabling banks to:
- Reduce non-performing loans
- Optimize resource allocation
- Enhance decision accuracy in loan approvals

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   https://famo78.github.io/Thesis-code/thesis-code.html
