# mall-customer-clustering
K-means clustering of mall customer data using R programming. This repository clusters customers based on three key features: age, annual income, and spending score.

## Data Source

The data used in this project is from the Kaggle website:

- https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?resource=download

## Method

The clustering is done using k-means clustering. The optimal number of clusters is defined using four different methods: Elbow method, Silhouette method, Calinski-Harabasz Index and Gap statistic. Based on those the optimal number of clusters is 6.

## Results

The clusters are visualized using two components in the code, but the centroids of the clusters are as follows:

| Age (years) | Annual income (k$) | Spending_score (0-100) |
|-------|-------|-------|
| 47.63 | 27.32 | 19.00 |
| 56.33 | 54.27 | 49.07 |
| 25.52 | 26.30 | 78.57 |
| 44.00 | 90.13 | 17.93 |
| 32.88 | 86.10 | 81.53 |
| 25.77 | 55.77 | 43.37 |



