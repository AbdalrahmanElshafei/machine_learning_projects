# 🚢 Titanic - Machine Learning from Disaster

This project is my submission for the Titanic - Machine Learning from Disaster competition on [Kaggle](https://www.kaggle.com/competitions/titanic).

The objective is to predict which passengers survived the Titanic shipwreck using basic data like age, sex, ticket class, etc.

---

## 📊 Project Highlights

- ✅ Performed detailed **Exploratory Data Analysis (EDA)**
- ✅ Handled **missing values** (Age, Cabin, Embarked)
- ✅ Engineered new features:
  - Extracted `Title` from Name
  - Created `FamilySize` and `IsAlone`
  - Simplified and mapped `Cabin` to numerical categories
- ✅ Converted categorical variables to numeric using **Label Encoding** and **One-Hot Encoding**
- ✅ Scaled numerical features for better model performance

---

## 🧠 Model Selection

I tested multiple classification algorithms using **K-Fold Cross-Validation**:

- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- **Support Vector Machine (SVM)** ✅

After comparing their performance, I selected **SVM** as the final model due to its accuracy and generalization.

---

## 📁 Project Structure

```plaintext
├── titanic.ipynb          # Main notebook with EDA, preprocessing, modeling
├── submission.csv         # Final predictions for Kaggle
├── train.csv              # Training data from Kaggle
├── test.csv               # Test data from Kaggle
├── requirements.txt       # (Optional) Python dependencies
└── README.md              # Project documentation
