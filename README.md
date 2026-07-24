# 🛒 SmartCart Customer Segmentation System

## 📌 Project Overview

SmartCart Customer Segmentation System is an **Unsupervised Machine Learning project** that analyzes customer data to identify meaningful customer groups based on purchasing behavior, income, engagement, and demographic attributes.

The project applies clustering algorithms to discover hidden patterns in customer behavior and helps businesses make data-driven decisions for personalized marketing, customer retention, and improved customer experience.

---

## 🎯 Project Objectives

- Analyze customer behavior using exploratory data analysis
- Clean and preprocess customer data
- Perform feature scaling for clustering algorithms
- Identify optimal customer segments
- Apply multiple clustering techniques
- Visualize customer groups
- Extract business insights from customer segments

---

# 🛠️ Technologies Used

## Programming Language
- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

# 🤖 Machine Learning Techniques

## 1. K-Means Clustering

K-Means clustering was applied to group customers based on similarities in their characteristics.

Optimal number of clusters was evaluated using:

- Elbow Method
- Silhouette Score

---

## 2. Hierarchical Clustering

Agglomerative Hierarchical Clustering was used to understand customer relationships and cluster formation.

Techniques used:

- Ward Linkage
- Dendrogram Visualization

---

## 4. Principal Component Analysis (PCA)

PCA was used for dimensionality reduction and visualization of customer clusters in 2D and 3D space.

---

# 📊 Exploratory Data Analysis

Performed analysis using:

- Distribution plots
- Correlation analysis
- Heatmaps
- Feature relationship analysis
- Customer behavior visualization

---

# ⚙️ Data Preprocessing

The following preprocessing steps were performed:

✔ Removed duplicate records  
✔ Handled missing values  
✔ Converted categorical features  
✔ Selected important features  
✔ Applied StandardScaler for normalization  

---

# 📈 Cluster Evaluation

The clustering models were evaluated using:

### Elbow Method
Used to determine the optimal number of clusters by analyzing Within Cluster Sum of Squares (WCSS).

### Silhouette Score
Measures how well-separated and compact the clusters are.

### Dendrogram
Used to visualize hierarchical cluster formation and estimate possible cluster numbers.

---

# 📌 Results

The clustering algorithms successfully identified different customer segments based on their purchasing patterns and characteristics.

The identified segments represent different customer behaviors such as:

- 🔵 Budget Family Shoppers
- 🟡 Premium Loyal Customers
- 🟢 Low-Value Solo Shoppers
- 🔴 High-Value Responsive Customers

These insights can help businesses create targeted strategies and improve customer relationships.

---

# 📂 Project Structure

```
SmartCart-Clustering-System/

│
├── Dataset/
│   └── smartcart_customers.csv
│
├── Notebook/
│   └── SmartCart_ClusteringSystem.ipynb
│
├── Output/
│   ├── images.png
|
│
└── README.md
```

---

# 💡 Business Applications

This customer segmentation system can help businesses:

- Create personalized marketing campaigns
- Identify premium customers
- Improve customer retention
- Optimize product recommendations
- Understand purchasing behavior

---

# 🔮 Future Improvements

- Deploy the clustering model using Flask/Django
- Create an interactive dashboard using Tableau/Power BI
- Integrate recommendation systems
- Automate customer segmentation pipeline
- Deploy as a cloud-based application

---

# 👩‍💻 Author

**Heer Shah**

AI/ML Enthusiast | Python | Machine Learning | Data Science

---

⭐ If you found this project useful, consider giving it a star!
