# 🧠 Social Media Advertising - SVM Case Study

This is a beginner-friendly, full case study applying **Support Vector Machines (SVM)** to a real-world dataset to predict user behavior based on social media advertising data.

---

## 📌 Objective

Predict whether a user will purchase a product based on their **Age** and **Estimated Salary**, using an SVM classification model.

---

## 📊 Dataset Overview

- **Dataset**: Social Network Ads
- **Features**:
  - `Age`
  - `EstimatedSalary`
- **Target**:
  - `Purchased` (0 = No, 1 = Yes)

---

## 🔍 Workflow Summary

1. Data Import and Exploration
2. Data Visualization (Seaborn & Matplotlib)
3. Preprocessing & Feature Selection
4. Train/Test Split
5. Model Training with SVM (Linear and RBF kernels)
6. Performance Evaluation (Accuracy, Confusion Matrix)

---

## 📈 Model Used

- **Support Vector Classifier (SVC)** from `scikit-learn`
- Kernels: `linear` and `rbf`
- Performance evaluated using:
  - Accuracy score
  - Confusion matrix
  - Visualization of decision boundaries

---

## 📦 Required Libraries

```python
pandas
numpy
seaborn
matplotlib
scikit-learn
