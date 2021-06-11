# Prediction using unsupervised learning ML<br>
In this task, we need to find the optimal number of clusters and cluster the data.<br>
Here, we have used the 'Elbow method' to determine the optimal number of clusters.<br>
Import the required libraries. Retrieve the data and prepare it for the data training.<br>
Train the clustering model using any algorithm of your choice. k-means clustering algorithm is used in this code.<br>
The number of clusters must be equal to the value inferred from Elbow method.<br>
After fitting and predicting the data, plot the data on a graph.<br>
The data can be plotted as sepal length vs sepal width, petal length vs petal width, sepal length vs petal length or sepal width vs petal width in clusters by representing the 
cluster's centroids.<br>
After plotting the data, we need to find the accuracy of our model.<br>
To find accuracy, we need to compare the labels in the test set with the labels of predicted set.<br>
Since our model predicts the values as 0,1,2 we can use any type of label encoder to encode the flower species into 0,1,2. Here, we have used preprocessing label encoder 
from sklearn module.<br>
After encoding the data, compare the two data sets and compute the number of matches. Divide the computed value with the length of the dataset to get the accuracy of our model.
