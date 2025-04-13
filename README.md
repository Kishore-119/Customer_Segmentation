# 🧠 Customer Segmentation using K-Means Clustering

This project segments customers into distinct groups based on their purchasing behavior using K-Means clustering. It enables businesses to identify valuable customer groups and tailor marketing strategies.

## 🔧 Tools & Libraries Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📊 Dataset

Used the **Mall Customers** dataset containing:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## 📈 Approach

1. **Data Cleaning & Selection**: Selected relevant features for clustering (Annual Income & Spending Score).
2. **Feature Scaling**: Applied `StandardScaler` to normalize the data.
3. **Optimal Clusters**: Used the **Elbow Method** to determine the ideal number of clusters.
4. **Clustering**: Applied **K-Means Clustering**.
5. **Visualization**: Visualized customer clusters in a 2D scatter plot.


