# Linear Regression with Advertising Dataset

## 📌 Project Overview

This project demonstrates the implementation of Simple and Multiple Linear Regression using Python and Scikit-learn.

The project uses an Advertising Dataset to analyze how advertising budgets across TV, Radio, and Newspaper channels relate to product Sales.

The objective is to build regression models, make predictions, evaluate model performance, and understand the relationship between advertising expenditure and sales.

## 🎯 Project Objectives

- Understand the fundamentals of Linear Regression.
- Explore the relationship between advertising budgets and sales.
- Implement Simple Linear Regression using TV advertising.
- Implement Multiple Linear Regression using all advertising channels.
- Evaluate regression models using performance metrics.
- Compare the performance of simple and multiple regression models.

## 📂 Dataset Information

**Dataset:** `advertising_sales.csv`

The dataset contains 200 records and 4 columns.

| Column | Description |
|---|---|
| TV | TV advertising budget |
| Radio | Radio advertising budget |
| Newspaper | Newspaper advertising budget |
| Sales | Product sales |

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Explored the dataset using `head()` and `info()`.
- Checked data types and missing values.

### 2. Simple Linear Regression
- Selected TV advertising as the independent variable.
- Selected Sales as the dependent variable.
- Split the dataset into training and testing sets.
- Trained a Linear Regression model.
- Generated predictions.

### 3. Multiple Linear Regression
- Used TV, Radio, and Newspaper as independent variables.
- Used Sales as the target variable.
- Trained a multiple regression model.
- Generated sales predictions.

### 4. Model Evaluation

The models are evaluated using:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

## 📈 Simple Linear Regression Results

| Metric | Result |
|---|---:|
| MAE | 64.96 |
| MSE | 6432.56 |
| RMSE | 80.20 |
| R² Score | 0.8343 |

The Simple Linear Regression model uses TV advertising expenditure to predict product sales.

## 📁 Project Structure

```text
Linear-Regression/
│
├── Linear Regression-checkpoint.ipynb
├── advertising_sales.csv
└── README.md
```

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/yashika85/Linear-Regression.git
```

**2. Navigate to the project folder**

```bash
cd Linear-Regression
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

**4. Open Jupyter Notebook**

```bash
jupyter notebook
```

**5.** Open the Linear Regression notebook and run all cells.

*Note: Keep the CSV dataset in the project folder and update the file path in the notebook if required.*

## 📚 Key Learnings

- Understanding Simple and Multiple Linear Regression.
- Training and testing machine learning models.
- Understanding independent and dependent variables.
- Making predictions using Scikit-learn.
- Evaluating regression models using statistical metrics.
- Interpreting regression coefficients and model performance.

## 🔮 Future Improvements

- Add actual vs. predicted value visualizations.
- Analyze residuals to understand prediction errors.
- Compare regression models using a results table.
- Experiment with additional regression algorithms.

## 👩‍💻 Author

**Yashika Khan**

- GitHub: https://github.com/yashika85
- LinkedIn: https://www.linkedin.com/in/yashika-khan-43609832b/

---

⭐ If you find this project useful, feel free to explore the repository.
