 🛍️ Mall Customer Segmentation using K-Means Clustering

📌 Task Objective

To apply unsupervised learning using K-Means Clustering to segment mall customers based on their annual income and spending score.

 🗂 Dataset Used

- Source: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- File: Mall_Customers.csv
- Total Records: 200
- Features Used: 
  - Annual Income (k$)
  - Spending Score (1-100)

 🛠 Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

 ✅ Steps Performed

 1. Data Preprocessing
- Removed CustomerID
- Selected only relevant features: Annual Income and Spending Score

 2. Elbow Method
- Tried values of K from 1 to 10
- Optimal K = 5 found using the Elbow method

 3. Clustering
- Applied KMeans clustering with n_clusters = 5
- Used k-means++ initialization for better convergence

 4. Visualization
- Created a scatter plot showing all 5 clusters
- Highlighted cluster centroids with yellow stars

 5. Evaluation
- Calculated Silhouette Score to assess cluster quality
Silhouette Score: 0.5539

✅ Score above 0.5 confirms good clustering



 📊 Results Summary

| Step                | Result             |
|---------------------|--------------------|
| Optimal Clusters (K)| 5                  |
| Clustering Done     | ✅ (KMeans)        |
| Silhouette Score    | 0.55 (Good)        |


 📁 Files Included

- Mall_Customers.csv — Dataset  
- kmeans_clustering.ipynb — Code file  
- README.md — This file  
