# 🏠 House Price Prediction Using Linear Regression

## 👨‍💻 Project Information

- **Internship:** Oasis Infobyte Internship Program
- **Domain:** Data Science
- **Level:** Level 2
- **Task:** Task 1
- **Project:** Predicting House Prices with Linear Regression
- **Author:** Yash Beloshe

## 🎯 Objective

Build and evaluate a Linear Regression model to predict house prices based on various property features using the Ames Housing Dataset.

The objective is to develop an end-to-end Machine Learning workflow, including data cleaning, exploratory data analysis, feature selection, data preprocessing, model training, evaluation, and interpretation.

The project also compares Linear Regression with Ridge and Lasso Regression to understand the impact of regularization on predictive performance.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📁 Project Files

| File | Description |
|---|---|
| `House_Price_Prediction.ipynb` | Jupyter Notebook containing the complete analysis and Machine Learning implementation |
| `README.md` | Project documentation |
| `data/train.csv` | Ames Housing training dataset |

## 🔍 Analysis Performed

1. Dataset loading and initial inspection
2. Dataset structure and descriptive statistical analysis
3. Exploratory Data Analysis (EDA)
4. Missing value identification and analysis
5. Target variable analysis (SalePrice)
6. House price distribution visualization
7. Outlier detection using boxplots
8. Feature selection and discussion
9. Handling missing numerical and categorical values
10. Categorical feature encoding using One-Hot Encoding
11. Correlation analysis and heatmap visualization
12. Train/test split (80/20)
13. Linear Regression model training using Scikit-learn
14. House price prediction using the trained model
15. Model evaluation using MSE, RMSE, MAE, and R² Score
16. Actual vs. predicted price visualization
17. Residual plot analysis
18. Regression coefficient analysis
19. Ridge Regression model implementation
20. Lasso Regression model implementation
21. Performance comparison of all three regression models

## 📊 Selected Features

The following features were selected to predict house prices:

| Feature | Description |
|---|---|
| `OverallQual` | Overall material and finish quality |
| `GrLivArea` | Above-ground living area |
| `TotalBsmtSF` | Total basement area |
| `GarageCars` | Garage capacity in number of cars |
| `YearBuilt` | Original construction year |
| `FullBath` | Number of full bathrooms |
| `BedroomAbvGr` | Number of bedrooms above ground |
| `LotArea` | Total lot size |
| `Neighborhood` | Physical location of the property |

**Target Variable:** `SalePrice`

## 📈 Model Evaluation

The regression models are evaluated using the following performance metrics:

- **Mean Squared Error (MSE):** Measures the average squared difference between actual and predicted house prices.
- **Root Mean Squared Error (RMSE):** Measures prediction error in the original price unit.
- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted prices.
- **R² Score:** Measures how much variation in house prices is explained by the regression model.

## 🤖 Machine Learning Models

Three regression algorithms are implemented and compared:

- **Linear Regression:** Establishes a baseline model for predicting house prices.
- **Ridge Regression:** Applies L2 regularization to reduce large coefficient values.
- **Lasso Regression:** Applies L1 regularization and can reduce less useful feature coefficients to zero.

## 💡 Key Findings

The project explores:

- Relationships between property features and house prices.
- The influence of living area and overall quality on property value.
- Correlations between numerical features and the target variable.
- Prediction accuracy and errors made by the Linear Regression model.
- Positive and negative relationships identified through regression coefficients.
- Differences in predictive performance between Linear, Ridge, and Lasso Regression.

## 📊 Project Visualizations

### House Price Distribution

Displays the distribution of house prices and helps identify the overall price range and skewness.

### Correlation Heatmap

Illustrates relationships between numerical features and helps identify features correlated with house prices.

### Actual vs. Predicted House Prices

Compares actual house prices with model predictions. Points closer to the diagonal reference line indicate better predictions.

### Residual Plot

Visualizes prediction errors to identify possible patterns and evaluate regression assumptions.

### Model Comparison

Compares Linear Regression, Ridge Regression, and Lasso Regression using their evaluation metrics.

## ▶️ How to Run the Project

1. Clone or download this repository.

2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter notebook
```

3. Obtain the Ames Housing Dataset from the Kaggle competition:

[House Prices: Advanced Regression Techniques – Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

4. Download and extract the dataset.

5. Place the `train.csv` file inside the `data` folder.

6. Open Jupyter Notebook.

7. Open `notebooks/House_Price_Prediction.ipynb`.

8. Run all notebook cells sequentially.

## 📌 Conclusion

This project demonstrates the application of supervised Machine Learning techniques for predicting house prices using Linear Regression.

Through exploratory data analysis, feature selection, data preprocessing, and model training, the project develops an end-to-end house price prediction workflow.

The implementation of Ridge and Lasso Regression also provides an opportunity to compare regularized regression techniques and understand their impact on model performance.

Overall, this project strengthens practical knowledge of Python, data analysis, Machine Learning, regression algorithms, model evaluation, and data visualization.

---

**Developed by Yash Beloshe**

*Oasis Infobyte Internship Program – Data Analytics*
