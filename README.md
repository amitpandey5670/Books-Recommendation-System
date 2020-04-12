# Books-Recommendation-System
The project consists of Recommendation of different books  based on the data of customer.

# K-Nearest Neighbors Algorithm

The k-nearest neighbors (KNN) algorithm is a simple,
easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems.
A supervised machine learning algorithm (as opposed to an unsupervised machine learning algorithm) is one that relies on 
labeled input data to learn a function that produces an appropriate output when given new unlabeled data.

# Working of K-Nearest Neighbors Algorithm

K-nearest neighbors (KNN) algorithm uses ‘feature similarity’ to predict the values of new datapoints which further means that the new data point will be assigned a value based on how closely it matches the points in the training set. We can understand its working with the help of following steps −

Step 1 − For implementing any algorithm, we need dataset. So during the first step of KNN, we must load the training as well as test data.

Step 2 − Next, we need to choose the value of K i.e. the nearest data points. K can be any integer.

Step 3 − For each point in the test data do the following −

3.1 − Calculate the distance between test data and each row of training data with the help of any of the method namely: Euclidean, Manhattan or Hamming distance. The most commonly used method to calculate distance is Euclidean.

3.2 − Now, based on the distance value, sort them in ascending order.

3.3 − Next, it will choose the top K rows from the sorted array.

3.4 − Now, it will assign a class to the test point based on most frequent class of these rows.

Step 4 − End
