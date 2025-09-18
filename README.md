# Predicting-salaries-based-on-position

## 📋 Project Overview
This project demonstrates the implementation of both **Simple Linear Regression** and **Polynomial Linear Regression** using a dataset containing position levels and corresponding salaries. The goal is to compare the performance of both models in predicting salaries based on position levels.

## 📊 Dataset
The dataset used is `Position_Salaries.csv`, which includes three columns:
- `Position`: Job position levels (encoded numerically from 1 to 10)
- `Position name`: Job position names(e.g. CEO, manager ...)
- `Salary`: Corresponding salary values

## 🛠️ Tools & Libraries
- **Python**
- **NumPy**: For numerical operations
- **Pandas**: For data manipulation
- **Matplotlib**: For data visualization
- **Scikit-learn**: For machine learning models

## 🔧 Models Implemented
### 1. Simple Linear Regression
- A basic linear regression model trained on the entire dataset.
- Uses `LinearRegression` from `sklearn.linear_model`.

### 2. Polynomial Linear Regression
- Transforms the original features into polynomial features using `PolynomialFeatures` from `sklearn.preprocessing`.
- Trains a linear regression model on the transformed features.
- Degree of polynomial used: **2**

## 📈 Visualizations
- **Simple Linear Regression**: Plots the best-fit straight line.
- **Polynomial Linear Regression**: Plots the best-fit curved line (polynomial regression curve).

## 📁 Files
- `Jozveh_Polynominal_linear_regression.ipynb`: Jupyter notebook containing all code, visualizations, and explanations.
- `Position_Salaries.csv` : dataset

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```
3. Place the `Position_Salaries.csv` file in the same directory.
4. Open and run the Jupyter notebook.

