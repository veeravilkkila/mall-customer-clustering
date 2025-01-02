# mall-customer-clustering
K-means clustering of mall customer data using R programming. This repository clusters customers based on three key features: age, annual income, and spending score.

## Data Source

The data used in this project is from the Kaggle website:

- https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?resource=download

## Method

The clustering is done using k-means clustering. The optimal number of clusters is defined using four different methods: Elbow method, Silhouette method, Calinski-Harabasz Index and Gap statistic. Based on those the optimal number of clusters is 6.

## Results

The clusters can be seen visualized using two components in the code. But the centroids of the clusters are as follows:

| Age | Annual income | Spending_score |
|----------|----------|----------|
| 47.63158 | 27.31579 | 19.00000 |
| 56.33333 | 54.26667 | 49.06667 |
| 25.52174 | 26.30435 | 78.56522 |
| 44.00000 | 90.13333 | 17.93333 |
| 32.87500 | 86.10000 | 81.52500 |
| 25.76744 | 55.76744 | 43.37209 |



