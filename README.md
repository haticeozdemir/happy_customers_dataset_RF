# BSdzxwn7iJ16OwcA

The algorithm I use for the dataset is the Random Forest algorithm. The random forest algorithm consists of many decision trees and determines the result based on the predictions of the decision trees.

Before I started training the dataset, I separated the variables in the dataset into dependent and independent. Then I divided the dataset into two, 80% training and 20% testing. I then scaled the dataset using the Scikit-Learn StandardScaler class. I trained the dataset with RandomForestRegressorClassifier. Here, I set the most important max_depth, ie the maximum depth of the tree, to 12. I set n_estimors, that is, the number of trees in the forest as 400. As a result of the training, I saw the success rate as 73%.
