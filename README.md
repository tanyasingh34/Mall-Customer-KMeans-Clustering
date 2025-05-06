# Mall Customers Clustering with K-Means

# Objective
To segment mall customers using K-Means clustering and visualize the clusters for business insights.

# Dataset
- **File**: `Mall_Customers.csv`
- Contains customer data with features like Age, Annual Income, and Spending Score.

# Tools & Libraries
- Python, Pandas, Matplotlib, Seaborn
- Scikit-learn (KMeans, PCA, Silhouette Score)

# Steps Performed
1. Loaded and cleaned the dataset
2. Standardized numerical features
3. Applied Elbow Method to find the optimal number of clusters
4. Performed K-Means clustering
5. Visualized clusters using PCA
6. Evaluated clusters using Silhouette Score

# Results
- **Optimal Clusters (K)**: 5
- **Silhouette Score**: 0.55 (example)

# Visualizations
- Elbow Method plot
- Cluster scatter plot (PCA projection)

# Learnings
- K-Means is sensitive to initialization and scales better with standardized data.
- Visualizing clusters helps interpret customer segments.
