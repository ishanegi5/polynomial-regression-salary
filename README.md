# Polynomial Regression on Salary Prediction  

This is a small machine learning project where we use **Polynomial Regression** to predict salary based on years of experience.  
The dataset is handmade and shows a **non-linear relationship** between experience and salary.  

## 📊 Dataset
The dataset is manually created:

| Experience | Salary  |
|------------|---------|
| 1          | 4000    |
| 2          | 4500    |
| 3          | 6000    |
| 4          | 8000    |
| 5          | 11000   |
| 6          | 15000   |
| 7          | 20000   |
| 8          | 27000   |
| 9          | 36000   |
| 10         | 50000   |

## ⚙️ Models Used
1. **Linear Regression** – baseline model (performs poorly on non-linear data).  
2. **Polynomial Regression** – better fit with degree=2 or 3.  

## 📈 Results
- **R² Score (Polynomial Regression):** ~0.99  
- **MSE:** ~2.1M  
- **MAE:** ~1116  
- **RMSE:** ~1453  

Polynomial Regression gives an excellent fit compared to Linear Regression.  

## 🔑 Steps
1. Import libraries and dataset  
2. Apply PolynomialFeatures transformation  
3. Train-test split  
4. Fit Linear and Polynomial Regression models  
5. Evaluate with R², MSE, MAE, RMSE  
6. Visualize results  

## 🚀 How to Run
```bash
git clone https://github.com/ishanegi5/polynomial-regression-salary.git
cd polynomial-regression-salary
python polynomial_regression.py
📌 Visualization
The project includes a plot showing how Linear Regression fails but Polynomial Regression fits the curve properly.

📜 License
This project is open-source and available under the MIT License.
