# Predicting-salaries-based-on-position

## 📋 Project Overview
This project demonstrates the implementation of **Simple Linear Regression**,**Polynomial Linear Regression** and **Support vector machine** using a dataset containing position levels and corresponding salaries.

## 📊 Dataset
The dataset used is `Position_Salaries.csv`, which includes three columns:
- `Position name`: Job position names(e.g. CEO, manager ...)
- `Position level`: Job position levels (encoded numerically from 1 to 10)
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

### 3. Support vector machine
- Used feature scalling with `sklearn.preprocessing.Standardscaler` for better performance
- Train the model on the scaled version of the dataset.

### Note
- The first two models are in `Jozveh_Polynominal_linear_regression.ipynb`
- You can find the third model in: `jozveh_Support_Vector_Regression.ipynb`

## 📈 Visualizations
- **Simple Linear Regression**: Plots the best-fit straight line.
- **Polynomial Linear Regression**: Plots the best-fit curved line (polynomial regression curve).
- **Support vercot machine**: Plots the SVR results.

## 📁 Files
- `Jozveh_Polynominal_linear_regression.ipynb`: Jupyter notebook containing all code, visualizations, and explanations for the solution with **Simple Linear Regression** and **Polynomial Linear Regression**
- `jozveh_Support_Vector_Regression.ipynb`: Jupyter notebook containing all code for **Support vector machine** solution
- `Position_Salaries.csv` : dataset

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```
3. Place the `Position_Salaries.csv` file in the same directory.
4. Open and run the Jupyter notebook.

