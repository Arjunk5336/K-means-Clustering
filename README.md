# Customer Segmentation using K-Means Clustering

This project performs customer segmentation using the Mall_Customers dataset. It utilizes unsupervised machine learning techniques, primarily K-Means clustering, to group customers based on their annual income and spending score. The aim is to identify distinct customer groups for targeted marketing strategies.

Dataset:

The dataset used is Mall_Customers.csv which includes:

CustomerID: Unique ID for each customer

Gender

Age

Annual Income (k$)

Spending Score (1-100)


Features and Workflow:

Data loading and exploration using pandas

Data visualization using matplotlib and seaborn

Label encoding of categorical variables

Feature scaling using StandardScaler

Dimensionality reduction with PCA

Clustering using KMeans

Evaluation of clustering with Silhouette Score

Cluster visualization


Visualizations:

Scatter plot of customers based on Annual Income vs. Spending Score

Cluster visualizations with PCA-reduced dimensions

Silhouette score plot for optimal K selection


Libraries Used:

pandas

numpy

seaborn

matplotlib

scikit-learn


Objective:

To apply K-Means clustering and gain insights into customer segments that help businesses understand purchasing behaviors and strategize marketing campaigns accordingly.
