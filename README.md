# ML
Machine Learning Projects

# Perceptron Learning Algorithm for Binary Classification

Problem Scenario: 

In this problem scenario, you are required to implement the learning algorithm for the Perceptron, specifically the on-line version. 
The goal is to train the perceptron using ten different training sets and evaluate its performance on a separate test set. 
You will analyze the decision boundaries learned by the perceptron and compute the misclassification error for each training set.

Tasks:

1) Download Data: Retrieve the training and test datasets from the provided source (e.g., BB). 
The folder contains ten training sets named set1.train, set2.train, ..., set10.train, and one test set named set.test. 
Each training set consists of 40 two-dimensional points, along with their corresponding class labels (0 or 1). 
The test set contains 2000 points with associated class labels.

2) Implement Perceptron Learning Algorithm: Implement the Perceptron learning algorithm in your preferred programming language. 
The algorithm should be the online version, where weights are initialized randomly before each training phase. 
Train the perceptron using each of the ten training sets and record the number of iterations required during training.

3) Compute Misclassification Error: Utilize the trained perceptrons to classify the points in the test set. 
Calculate the misclassification error by comparing the predicted labels with the actual labels provided in the test set. 
Record the error rate for each trained perceptron.

4) Plot Decision Boundaries: Use scatterplots to visualize the training sets along with their corresponding decision boundaries. 
For each trained perceptron, plot the learned decision boundary separately alongside the test set. 
This will provide a visual representation of how the perceptron separates the data points based on their class labels.

5) Analyze Results: Comment on the obtained results. Examine the training data sets and determine if any patterns or differences exist. 
Evaluate whether the solution found by the perceptron changes for different training data. 
Analyze the misclassification error rates and provide a reasoned interpretation of the findings.


By implementing the Perceptron learning algorithm and analyzing the training and test data, you will gain insights into the 
capabilities and limitations of the Perceptron model. Through plotting decision boundaries and computing misclassification errors, 
you can evaluate the effectiveness of the perceptron on different datasets. Use these findings to discuss the behavior of the 
perceptron and its performance in classifying the given data points.
