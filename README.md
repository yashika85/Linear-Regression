# Linear-Regression

# 📊 Linear Regression with Advertising Dataset

This project demonstrates how to implement both **Simple** and **Multiple Linear Regression** using Python and Scikit-learn.  
The dataset contains advertising spends (TV, Radio, Newspaper) and their impact on product Sales.

---

## 🎯 Objective

- Understand and visualize how ad budgets affect sales.
- Learn to build, train, and evaluate linear regression models.
- Compare simple regression (one feature) with multiple regression (all features).

---

## 🧰 Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📁 Dataset

- File: `advertising_sales.csv`
- Columns:
  - `TV`: Advertising budget for TV (in thousands)
  - `Radio`: Advertising budget for Radio
  - `Newspaper`: Advertising budget for Newspaper
  - `Sales`: Resulting product sales

---

## 🔍 What I Did (Step-by-step)

1. **Imported the dataset** and explored the structure
2. **Split the data** into training and testing sets
3. **Built a Simple Linear Regression** model (TV → Sales)
4. **Visualized the regression line** and understood coefficients
5. **Built a Multiple Linear Regression** model (TV, Radio, Newspaper → Sales)
6. **Evaluated both models** using MAE, MSE, RMSE, and R² scores
7. **Compared the results** of simple vs. multiple regression

---

## 📈 Key Outputs

| Model                  | R² Score | RMSE     |
|------------------------|----------|----------|
| Simple Linear (TV)     | ~0.85    | Moderate |
| Multiple Linear (All)  | ~0.99    | Very Low |

- TV spend alone explains ~85% of the variation in sales.
- Combining all three ad channels explains almost 99%!

---

## ▶️ How to Run

1. Clone the repository or copy the `.ipynb` notebook.
2. Place `advertising_sales.csv` in the same folder.
3. Run all cells in the notebook.

```bash
pip install pandas numpy scikit-learn matplotlib
jupyter notebook Linear_Regression_Advertising.ipynb
