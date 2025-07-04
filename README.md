# SCT_ML_2
**Mall Customer Segmentation – K-Means Clustering**
This project applies K-Means Clustering to segment mall customers based on their Annual Income and Spending Score. The goal is to uncover distinct customer groups to help businesses better target their marketing strategies.

**Problem Statement:**
Retailers often lack clarity about their customer segments. Using unsupervised machine learning, we group customers into meaningful clusters based on purchasing behavior.

Dataset Source:  https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
Fields Used:
-> Annual Income (k$)
-> Spending Score (1-100)

**Tech Stack:**
-> Python
-> Pandas, NumPy
-> Matplotlib, Seaborn
-> Scikit-learn (KMeans, StandardScaler)
-> Jupyter Notebook

**Elbow Method – Choosing Optimal Clusters:**
We used the Elbow Method to determine the best value for k (number of clusters). The point where the inertia starts to flatten out indicates a good choice for k.
(image of the elbow method's graph has been uploaded in the images folder for reference)(@ /images/elbow_method.png)
-> Final Clustering Result (k = 5)

**Applying KMeans clustering with k=5**
The customers were segmented into 5 clusters based on their income and spending habits.
(image @ /images/kmeans_clusters)

**Key Learnings:**
-> How to apply K-Means Clustering in Python
-> Importance of data standardization for distance-based models
-> Using the Elbow Method to find optimal k
-> Interpreting clusters to drive business insight

