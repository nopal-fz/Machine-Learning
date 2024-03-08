# Machine Learning Model Repository
![1_c_fiB-YgbnMl6nntYGBMHQ](https://github.com/nopal-fz/Machine-Learning/assets/145373069/43f2ab0b-0102-4589-b33f-25d130e90505)
This repository contains various machine learning models developed using various supervised and unsupervised learning techniques.

## Supervised Learning
In this section, you can find models developed using supervised learning techniques. These models take labeled data as input and learn to predict corresponding outputs.

### Regression
- **Linear Regression:** A linear regression model used to predict continuous values. It fits a linear relationship between input features and the target variable.
- **Logistic Regression:** A logistic regression model used to predict the probability of binary classes. It estimates the probability that a given input belongs to a particular class.
- **Polynomial Regression:** A regression model that fits a nonlinear relationship between the independent and dependent variables by adding polynomial terms to the model.
- **Ridge Regression (L2 Regularization):** A regression technique that adds a penalty term to the linear regression to prevent overfitting by shrinking the coefficient estimates.
- **Lasso Regression (L1 Regularization):** A regression technique that adds a penalty term to the linear regression to encourage sparsity in the coefficient estimates, often used for feature selection.
- **ElasticNet Regression:** A regression technique that combines L1 and L2 regularization penalties to balance between Ridge and Lasso regression.
- **Support Vector Regression (SVR):** A regression model based on support vector machines that finds the hyperplane that best fits the data while minimizing prediction errors.

### Classification
- **Decision Tree Classifier:** A classification model that uses a tree-like structure to make decisions and predict the target class.
Random Forest Classifier: An ensemble classification model that utilizes multiple decision trees to improve prediction accuracy. It combines the predictions of multiple individual trees to generate a final prediction.
- **Support Vector Machine (SVM):** A classification model that separates classes by finding the best hyperplane. It aims to maximize the margin between classes while minimizing classification errors.
- **Random Forest Classifier:** An ensemble classification model that utilizes multiple decision trees to improve prediction accuracy. It combines the predictions of multiple individual trees to generate a final prediction.
- **K-Nearest Neighbors (KNN):** A classification algorithm that assigns a class label to an input by a majority vote of its k nearest neighbors in the feature space.
- **Naive Bayes Classifier:** A probabilistic classification model based on Bayes' theorem that assumes independence between features. It calculates the probability of each class given the input features and selects the most probable class.
- **Gradient Boosting Classifier:** A classification ensemble technique that builds a series of weak learners (usually decision trees) sequentially, where each tree corrects the errors of its predecessor.
- **Neural Network Classifier:** A classification model inspired by the structure and function of the human brain, composed of interconnected layers of neurons. It learns complex patterns in the data through forward and backward propagation of signals.

## Unsupervised Learning
In this section, you can find models developed using unsupervised learning techniques. These models do not require labeled data and learn to discover patterns or structures within the data.

### Clustering
- **K-Means Clustering:** A clustering model that partitions data into k clusters based on similarity characteristics. It aims to minimize the intra-cluster distance and maximize the inter-cluster distance.
Hierarchical Clustering: A clustering model that builds a hierarchy of clusters using a tree-based approach. It iteratively merges or splits clusters to form a hierarchical structure.
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise):** A clustering model that identifies clusters based on the density of data points in the feature space. It groups together closely packed points while marking outliers as noise.
- **Hierarchical Clustering:** A clustering model that builds a hierarchy of clusters using a tree-based approach. It iteratively merges or splits clusters to form a hierarchical structure.
- **Gaussian Mixture Model (GMM):** A probabilistic model that assumes that the data is generated from a mixture of several Gaussian distributions. It assigns probabilities to each point belonging to each cluster.
