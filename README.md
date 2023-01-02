# Distance Metrics - Euclidean vs Mahalanobis

In this short notebook, we compare the Euclidean distance metric with the Mahalanobis distance metric among the data points of two different 2D datasets:
- Dataset 1: features covary
- Dataset 2: no covariance

Our goal is to determine the best distance metric function when features have large covariance.

We will see that in dataset 1, due to large covariance between the features, Eluclidean distance metric doesn't provide the true distance between two data points. We have to use the Mahalanobis distance metric.

Mahalanobis distance metric function: 
- Diagonalizes the covariance matrix (features are decorrelated).
- Then, it scales the features.

<img src="http://engineering.unl.edu/images/uploads/Mahalanobis.png" width=800, height=400>
