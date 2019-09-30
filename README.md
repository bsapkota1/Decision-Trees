#Decision Trees: Basic Machine Learning 

This project focuses on decision trees and starts with the titanic data set. \n
First, separates the data into training and test sets. The test set is 20% of the total data. 
Second, builds a decision tree based on the training data. The defaults for building a tree are fine (gini impurity). 
Third, produces a confusion matrix from the trees predictions on the test data. From the matrix it calculates performance measures from the confusion matrix, especially f1 score. 
Fourth, builds a second decision tree. This tree will be restricted to have a max-depth of one. This pre-pruning results in a much smaller tree. 
Fifth, produces a confusion matrix and calculate performance measures for this second tree. 
Here the accuracy from the first decision tree is 76.87 % and the second decision tree is 76.19%. We don't see much difference in the accuracy. However, the decision tree is very small and we can read it better than the first decision tree. 
