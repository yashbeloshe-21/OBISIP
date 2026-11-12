# 🍷 Wine Quality Prediction Using Machine Learning Classification

## 👨‍💻 Project Information

- **Internship:** Oasis Infobyte Internship Program
- **Domain:** Data Analytics
- **Level:** Level 2
- **Task:** Task 2
- **Project:** Wine Quality Prediction
- **Author:** Yash Beloshe

## 🎯 Objective

Build and compare multiple Machine Learning classification models to predict wine quality based on its physicochemical properties using the Wine Quality Dataset.

The objective is to develop an end-to-end Machine Learning workflow, including data loading, data inspection, exploratory data analysis, feature engineering, data preprocessing, model training, evaluation, and interpretation.

The project implements both binary classification (Good/Bad wine) and three-class classification (Low/Medium/High quality wine) using Random Forest, Stochastic Gradient Descent (SGD), and Support Vector Classifier (SVC).

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## 📁 Project Files

| File | Description |
|---|---|
| `Wine_Quality_Prediction.ipynb` | Jupyter Notebook containing the complete analysis and Machine Learning implementation |
| `README.md` | Project documentation |
| `winequality-white.csv` | White Wine Quality dataset |
| `random_forest_binary.pkl` | Trained Random Forest binary classification model |
| `sgd_binary.pkl` | Trained SGD binary classification model |
| `svc_binary.pkl` | Trained SVC binary classification model |
| `random_forest_multiclass.pkl` | Trained Random Forest multi-class classification model |
| `sgd_multiclass.pkl` | Trained SGD multi-class classification model |
| `svc_multiclass.pkl` | Trained SVC multi-class classification model |
| `standard_scaler.pkl` | Saved feature scaler |
| `binary_scaler.pkl` | Binary classification feature scaler |
| `multiclass_scaler.pkl` | Multi-class classification feature scaler |

## 🔍 Analysis Performed

1. Dataset loading and initial inspection
2. Dataset structure, dimensions, and data type analysis
3. Descriptive statistical analysis
4. Unique wine quality score identification
5. Wine quality class distribution analysis
6. Exploratory Data Analysis (EDA)
7. Distribution plots for all chemical features
8. Alcohol, volatile acidity, residual sugar, and fixed acidity analysis
9. Correlation matrix calculation
10. Correlation heatmap visualization
11. Feature correlation analysis with wine quality
12. Outlier detection using boxplots
13. Outlier identification using the Interquartile Range (IQR) method
14. Class imbalance analysis
15. Binary classification target creation
16. Three-class classification target creation
17. Feature selection and target variable preparation
18. Stratified train/test split (80/20)
19. Feature scaling using StandardScaler
20. Random Forest Classifier implementation
21. Stochastic Gradient Descent (SGD) Classifier implementation
22. Support Vector Classifier (SVC) implementation
23. Model training for binary and multi-class classification
24. Model evaluation using accuracy, precision, recall, and F1-score
25. Confusion matrix visualization for all models
26. Random Forest feature importance analysis
27. Model performance comparison
28. Wine quality prediction using sample and custom input data
29. Saving trained models using Joblib

## 📊 Dataset Information

- **Dataset:** Wine Quality – White Wine
- **Source:** UCI Machine Learning Repository
- **Total Records:** 4,898
- **Total Features:** 11 input features
- **Target Variable:** `quality`
- **Number of Quality Categories:** 7 (scores 3–9)

### Dataset Features

| Feature | Description |
|---|---|
| `fixed acidity` | Amount of fixed acids in wine |
| `volatile acidity` | Amount of volatile acids in wine |
| `citric acid` | Amount of citric acid in wine |
| `residual sugar` | Amount of sugar remaining after fermentation |
| `chlorides` | Amount of salt in wine |
| `free sulfur dioxide` | Free sulfur dioxide concentration |
| `total sulfur dioxide` | Total sulfur dioxide concentration |
| `density` | Density of wine |
| `pH` | Acidity or alkalinity level |
| `sulphates` | Amount of sulphates in wine |
| `alcohol` | Alcohol percentage in wine |
| `quality` | Wine quality score (target variable) |

## ⚙️ Feature Engineering

Two classification approaches were implemented to transform the original wine quality scores.

### Binary Classification

Wine quality scores were grouped into two categories:

- **0 – Bad Quality:** Quality score below 6
- **1 – Good Quality:** Quality score 6 or above

### Three-Class Classification

Wine quality scores were grouped into three categories:

- **0 – Low Quality:** Quality score 4 or below
- **1 – Medium Quality:** Quality score 5–6
- **2 – High Quality:** Quality score 7 or above

This approach helps evaluate the models on both simplified and more detailed classification tasks.

## 🤖 Machine Learning Models

Three classification algorithms were implemented and compared:

### 1. Random Forest Classifier
An ensemble learning algorithm that combines multiple decision trees to improve classification performance.

### 2. Stochastic Gradient Descent (SGD) Classifier
A linear classification algorithm that uses stochastic gradient descent for model optimization.

### 3. Support Vector Classifier (SVC)
A Support Vector Machine-based classification algorithm that identifies decision boundaries to separate different classes.

All three algorithms were trained and evaluated for both binary and three-class classification.

## 📈 Model Evaluation

The classification models are evaluated using the following performance metrics:

- **Accuracy:** Measures the proportion of correctly classified observations.
- **Precision:** Measures how many predicted positive classifications are actually correct.
- **Recall:** Measures how many actual positive observations are correctly identified.
- **F1-score:** Represents the harmonic mean of precision and recall.
- **Confusion Matrix:** Displays the relationship between actual and predicted classifications.

A model comparison table and visualization are also used to compare the performance of all six classification experiments.

## 📊 Project Visualizations

### Wine Quality Distribution
Displays the frequency of different wine quality scores and helps identify class imbalance.

### Chemical Feature Distributions
Histograms visualize the distribution of physicochemical properties such as alcohol, acidity, density, and residual sugar.

### Correlation Heatmap
Illustrates relationships between chemical properties and identifies features correlated with wine quality.

### Outlier Detection
Boxplots and the IQR method help identify potential outliers in the chemical features.

### Binary and Three-Class Distribution
Visualizes the distribution of Good/Bad and Low/Medium/High wine quality categories.

### Confusion Matrices
Displays the classification performance of Random Forest, SGD, and SVC models.

### Feature Importance
Highlights the most influential chemical properties used by the Random Forest classifier.

### Model Comparison
Compares the accuracy and weighted F1-scores of all six classification experiments.

## 💡 Key Findings

The project explores:

- Distribution of different wine quality scores.
- Imbalance between wine quality categories.
- Relationships between physicochemical properties and wine quality.
- The influence of alcohol, acidity, and other chemical features on quality predictions.
- Differences in model performance between binary and multi-class classification.
- The effectiveness of Random Forest, SGD, and SVC classifiers.
- Important chemical features identified through Random Forest feature importance.
- The impact of class imbalance on classification performance.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyterlab
```

3. Obtain the Wine Quality Dataset from the UCI Machine Learning Repository:

[Wine Quality Dataset – UCI Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)

4. Download the white wine dataset (`winequality-white.csv`).
5. Place the CSV file in the project folder alongside the Jupyter Notebook.
6. Open Jupyter Notebook or JupyterLab.
7. Open `Wine_Quality_Prediction.ipynb`.
8. Run all notebook cells sequentially.

## 💾 Saved Models

The trained classification models are saved using Joblib in `.pkl` format.

These saved models can be loaded later for making predictions without training the algorithms again.

## 📌 Conclusion

This project demonstrates the application of supervised Machine Learning classification techniques for predicting wine quality using physicochemical properties.

Through exploratory data analysis, feature engineering, class distribution analysis, and model training, the project develops an end-to-end wine quality prediction workflow.

The implementation of Random Forest, Stochastic Gradient Descent, and Support Vector Classifier provides an opportunity to compare different classification algorithms across binary and multi-class prediction tasks.

The project also highlights the importance of class imbalance analysis, stratified sampling, feature scaling, model evaluation, and feature importance in building effective Machine Learning models.

Overall, this project strengthens practical knowledge of Python, data analysis, data visualization, Machine Learning classification algorithms, and model evaluation.

---

**Developed by Yash Beloshe**

*Oasis Infobyte Internship Program – Level 2 | Task 2*
