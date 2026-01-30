# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
Customer segmentation is an important marketing strategy that helps businesses better understand their customers and design targeted actions for different customer groups.

In this project, I apply **unsupervised machine learning** techniques to segment customers of a shopping mall based on their demographic and spending behavior. The goal is to identify meaningful customer segments and translate them into **actionable business insights**.

---

## 🎯 Business Objective
The main objectives of this project are:
- Identify distinct customer segments
- Analyze differences in customer behavior
- Support data-driven marketing and customer strategy decisions

---

## 📂 Dataset
The dataset contains customer information from a shopping mall, including:
- Gender
- Age
- Annual Income
- Spending Score (customer purchasing behavior)

This dataset is well-suited for exploratory analysis and clustering tasks.

---

## 🧠 Methodology
The project follows a structured data science workflow:

1. **Exploratory Data Analysis (EDA)**
   - Analyze distributions of customer features
   - Explore relationships between income, age, and spending behavior

2. **Feature Selection & Scaling**
   - Select relevant variables for clustering
   - Apply feature scaling to ensure proper distance calculations

3. **Clustering**
   - Apply K-Means clustering
   - Use the Elbow Method to determine the optimal number of clusters

4. **Cluster Analysis**
   - Interpret each customer segment
   - Compare clusters based on income, spending, and age

5. **Business Recommendations**
   - Translate customer segments into actionable strategies

---

## 📊 Key Insights
- Customers can be grouped into clearly distinct segments based on income and spending behavior.
- High-income customers do not always have high spending scores, indicating potential upselling opportunities.
- A small group of high-value customers represents a key target for loyalty programs.

---

## 💡 Business Recommendations
- **High income & high spending**: focus on loyalty programs and personalized offers  
- **High income & low spending**: target with premium promotions  
- **Low income & high spending**: offer discounts and bundles  
- **Low income & low spending**: lower marketing priority  

---

## 🛠️ Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📁 Project Structure

mall-customer-segmentation/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ ├── 01_eda.ipynb
│ ├── 02_feature_preparation.ipynb
│ ├── 03_clustering.ipynb
│ ├── 04_cluster_analysis.ipynb
│ └── 05_business_recommendations.ipynb
│
├── src/
├── requirements.txt
└── README.md


---

## 🚀 Future Improvements
- Include additional features such as age in clustering
- Compare K-Means with hierarchical clustering
- Apply PCA for dimensionality reduction and visualization
- Test the approach on a larger dataset

---

## 📌 Conclusion
This project demonstrates how unsupervised learning techniques can be used to gain insights into customer behavior and support business decision-making. It highlights the importance of combining **data analysis**, **machine learning**, and **business understanding** in real-world data science projects.
