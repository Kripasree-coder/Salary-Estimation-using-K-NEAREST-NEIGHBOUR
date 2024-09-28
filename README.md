**Salary Estimation using K-Nearest Neighbour (KNN)
Overview**
This project implements a K-Nearest Neighbour (KNN) algorithm to estimate salaries based on various features such as years of experience, education level, job role, and other relevant factors. 
The KNN algorithm is a simple, non-parametric method used for both classification and regression problems.
In this case, we use it to perform regression to predict the salary of an individual based on their input features.
**Features**
Predicts salary based on multiple factors such as years of experience, education level, and job role.
Implements K-Nearest Neighbour (KNN) for regression.
Feature scaling and normalization for better model performance.
Hyperparameter tuning to find the optimal value of K (number of neighbors).
Visualization of model performance and error metrics.
**Dependencies**
Python 3.x
NumPy
Pandas
scikit-learn
Matplotlib

**KNN Algorithm**
K-Nearest Neighbour is a supervised learning algorithm where an input is classified or predicted based on the majority label (classification) or average (regression) of its K-nearest neighbors in the feature space.

**Key Steps in KNN:**
Choose the value of K (number of neighbors).
Calculate the distance (e.g., Euclidean distance) between the input data point and all other points in the dataset.
Sort the distances and select the K nearest neighbors.
For regression, take the average of the K nearest neighbors' salary values as the predicted salary.
Evaluate the model using appropriate metrics (e.g., Mean Squared Error).

**Results**
After training and testing the model, we obtained the following results:

Best K Value: 6
Accuracy of the model:80%
