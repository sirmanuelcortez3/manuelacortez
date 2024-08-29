---
date: "2023-12-10T00:00:00Z"
summary: Analysis of Mushroom Toxicity
title: Mushroom Classifier
---
In this project, I focused on predicting whether a mushroom is poisonous or not using K-Nearest Neighbors (KNN) and Principal Component Analysis (PCA). The mushroom dataset was downloaded from the UCI library. Upon discovering missing data, I split the dataset into two parts: one with missing data (used as the test set) and one without (used as the training set). I then one-hot encoded the feature data and label encoded the response variable.

After ensuring that the feature-training and feature-testing data were consistent, I trained a KNN model on the training data and used it to impute the missing values. I verified that the imputed values matched the original number of missing entries, then reintegrated them into the dataset. Next, I split the data into features and response variables and used `train_test_split()` to further divide it into training and testing sets.

I trained a Random Forest classifier and a Logistic Regression model on the data, calculating their accuracy, precision, and recall. To optimize the models, I applied PCA to reduce the dimensionality of the feature data, retaining 95% of the variance. I re-ran the models and recalculated their performance metrics. Finally, I tabulated the results, including accuracy, precision, recall, and computation time, and provided a detailed explanation as to which model was preferable.

See [github repository](https://github.com/sirmanuelcortez3/Mushroom-Classifier.git) for full project. Available upon request.