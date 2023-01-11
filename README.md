# text_classification

Implement a spam/ham classifier by building a logistic regression classifier.


Steps followed:


1. Data Preprocessing:
– Load data into sentences and labels, split into training, validation, and test set. Report
the data distribution in a table.
– Remove punctuation, urls, and numbers. Change text to lower case.
– Tokenize input text into tokens, including word stemming and removing stopwords.
– Feature extraction: build your TF-IDF feature extractor for the provided dataset.

2. – Derive the gradient of the objective function of LR with respect to w. Please write
down detailed steps.
– Implement this Logistic Regression model. This step includes writing code for initial-
ization, objective function, gradient, and gradient descent.
– Implement evaluation metrics, including accuracy, precision, recall, and F1 score.
– Stochastic Gradient Descent (SGD): fill the code for the function of SGD.
– Mini-batch Gradient Descent: fill the code for the function of mini-batch GD.
– Evaluation your model on the test set.
