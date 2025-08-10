# 🏭 Manufacturing Cost Prediction using Polynomial Regression

## 📌 Overview
This project demonstrates how **Polynomial Regression** can be used to better model non-linear relationships between production units and manufacturing costs.  
Initially, a **Linear Regression** model was tested, but it did not fit the data well. Switching to a polynomial approach provided a significantly better fit.

## 📊 Dataset
The dataset contains:
- **Number of Units** — production quantity
- **Manufacturing Cost** — associated cost for production

## 🛠️ Steps
1. **Data Exploration** — loaded and examined the dataset.
2. **Visualization** — scatter plot to understand data distribution.
3. **Linear Regression** — tested as a baseline model.
4. **Polynomial Regression** — implemented for better curve fitting.
5. **Evaluation** — compared R² scores and visualized the fitted curve.

## 📈 Results
- **Linear Regression**: Poor fit (underestimates curvature of the data).
- **Polynomial Regression**: High R² score, closely follows the data trend.
