# 📊 Customer Segmentation Analysis Using K-Means Clustering

## 👨‍💻 Project Information

- **Internship:** Oasis Infobyte Internship Program
- **Domain:** Data Analytics
- **Level:** 1
- **Task:** Task 2
- **Project:** Customer Segmentation Analysis
- **Author:** Yash Beloshe

## 🎯 Objective

Perform Customer Segmentation Analysis on an online retail transaction dataset using the K-Means clustering algorithm to identify distinct customer groups based on their purchasing behaviour through RFM (Recency, Frequency, and Monetary) analysis.

The objective is to understand customer purchasing patterns, identify valuable customer segments, and develop targeted marketing strategies to improve customer retention and business growth.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📁 Project Files

| File                              | Description                                                                     |
| --------------------------------- | ------------------------------------------------------------------------------- |
| `Customer_Segmentation.ipynb`     | Jupyter Notebook containing the complete analysis and clustering implementation |
| `README.md`                       | Project documentation                                                           |
| `images/elbow_method.png`         | Elbow Method visualization for selecting optimal clusters                       |
| `images/cluster_distribution.png` | Customer distribution across clusters                                           |
| `images/customer_clusters.png`    | Customer segmentation scatter plot                                              |

## 🔍 Analysis Performed

1. Dataset loading and initial inspection
2. Data cleaning and preprocessing
3. Missing value and duplicate record handling
4. Descriptive statistical analysis
5. Exploratory Data Analysis
6. Calculation of total purchase amount
7. RFM analysis (Recency, Frequency, and Monetary)
8. Average purchase value and historical customer lifetime value calculation
9. Feature selection and outlier analysis
10. Logarithmic feature transformation
11. Feature standardization using StandardScaler
12. Optimal cluster selection using the Elbow Method
13. Customer segmentation using K-Means clustering
14. Silhouette Score evaluation
15. Customer cluster visualization using scatter plots
16. Customer segment profiling and distribution analysis

## 📈 Key Business Insights

The analysis explores:

- Customer purchasing frequency and spending behaviour.
- Differences in customer engagement and recency.
- Identification of high-value and potentially inactive customers.
- Distribution of customers across different clusters.
- Purchasing patterns and characteristics of each customer segment.

## 💡 Business Recommendations

- **Customer Retention:** Develop loyalty programs and exclusive rewards for high-value customers.
- **Targeted Marketing:** Create personalized campaigns based on customer purchasing behaviour.
- **Customer Reactivation:** Offer special discounts and promotional campaigns to inactive customers.
- **Revenue Optimization:** Focus on high-value customer segments to improve business profitability.
- **Customer Engagement:** Encourage repeat purchases through personalized product recommendations and offers.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl jupyter
```

3. Obtain the Online Retail dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail).
4. Place the dataset CSV file in the same folder as the notebook and name it `data.csv`.
5. Open Jupyter Notebook.
6. Open `Customer_Segmentation.ipynb`.
7. Run all notebook cells sequentially.

## 📌 Conclusion

This project demonstrates the application of RFM analysis and unsupervised machine learning techniques to segment e-commerce customers based on their purchasing behaviour.

By implementing K-Means clustering, the analysis identifies distinct customer groups that can help businesses understand customer value, improve retention strategies, personalize marketing campaigns, and make data-driven business decisions.

---

**Developed by Yash Beloshe**

*Oasis Infobyte Internship Program – Data Analytics*
