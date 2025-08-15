## Mall Customer Segmentation - K-Means Clustering

## 📌 Objective
This project performs unsupervised learning using K-Means clustering to segment mall customers based on Annual Income and Spending Score.

## 📂 Dataset 
Mall_Customers.csv
Columns:
CustomerID – Unique identifier (not used for clustering)
Gender – Categorical feature
Age – Customer age
Annual Income (k$) – Annual income in $1000s
Spending Score (1-100) – Score assigned by the mall based on spending behavior

⚙️ Tools Used
Pandas – Data handling
Matplotlib – Visualization
Scikit-learn – K-Means clustering & evaluation

📊 Steps Performed
Load dataset using Pandas
Select features: Annual Income (k$) and Spending Score (1-100)
Elbow Method – Determine optimal number of clusters
Fit K-Means – Assign cluster labels
Silhouette Score – Evaluate clustering quality
Visualize clusters with centroids
