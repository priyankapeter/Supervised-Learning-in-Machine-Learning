# Supervised-Learning-in-Machine-Learning
Supervised Learning in Breast Cancer Dataset

Objective:
The objective of this evaluate to understanding and ability to apply supervised learning techniques to a real-world dataset.

Dataset:
Use the breast cancer dataset available in the sklearn library.
1. Loading and Preprocessing 
Load the breast cancer dataset from sklearn.
2. Classification Algorithm Implementation 
Implement the following five classification algorithms:
For each algorithm, provide a brief description of how it works and why it might be suitable for this dataset.
1. Logistic Regression
   Logistic Regression is a linear model used for binary classification tasks. It calculates the probability that a given instance belongs to a particular class using the logistic function.
    It is simple, interpretable, and effective when the relationship between features and the target variable is roughly linear.
2. Decision Tree Classifier
   Decision Tree Classifier splits the data recursively into subsets based on feature values. It builds a tree structure where internal nodes represent decisions based on feature values, and leaf nodes represent the class labels.
   Decision Tree Classifier splits the data recursively into subsets based on feature values. It builds a tree structure where internal nodes represent decisions based on feature values, and leaf nodes represent the class labels.
3. Random Forest Classifier
   Random Forest is an ensemble method that combines multiple decision trees. Each tree is trained on a random subset of data and features.
   The breast cancer dataset contains numerous features, and Random Forest’s ability to handle feature interactions and outliers makes it highly effective.
4. Support Vector Machine (SVM)
   SVM works by finding the hyperplane that best separates the data into two classes. It maximizes the margin between the nearest points of the classes
   SVM is well-suited for binary classification tasks with a clear distinction between classes.
5. k-Nearest Neighbors (k-NN)
   k-NN is a simple, instance-based learning algorithm that classifies a sample based on the majority class among its k-nearest neighbors in the feature space. 
   k-NN works well when there’s a clear local structure in the data. 
3. Model Comparison 
Compare the performance of the five classification algorithms.
Which algorithm performed the best and which one performed the worst?
Best Performing Model: In the example, the Random Forest Classifier has the highest accuracy (0.92) and balanced precision and recall, suggesting it performs the best overall.
Random Forest likely performed the best due to its ensemble nature, which combines multiple decision trees and reduces overfitting.
Worst Performing Model: Based on the  accuracy, the SVM classifier seem to have slightly lower performance compared to the others.
SVM classifier could be considered the worst based on slightly lower accuracy 
