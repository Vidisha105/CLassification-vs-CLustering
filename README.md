# CLassification-vs-CLustering
Predict the wine quality using Logistic regression and knn clustering

## KNN:
K nearest neighbors is a classification algorithm that computes the nearest k neighbors for any observation using euclidean distance to compute the conditional probability for each class and assigns the observation to the class with the largest probability. It is heavily dependent on k and there is no good way to choose k.

## Multinomial logistic regression:
Multinomial logistic regression is a model which is used to predict nominal outcome variables in which the log of odds of the outcomes is expressed as a linear combination of the independent variables. It defers from the binomial regression in the fact that there can by multiple classes for the dependent variable as opposed to just two in binomial.

## K-means clustering:
K-means clustering is a clustering mechanism in which the number of clusters is pre defined and the algorithm assigns each of the observation to one of these groups or clusters. It clusters data by fitting a mixture model. The downside is that we need to choose the k manually.

KNN and Multinomial are supervised learning algorithms while K means clustering is unsupervised.

## Model Validation:
For Classification algorithm we assess the model performance using Confusion Matrix. It gives the relationship between True class and predicted class.

### Accuracy:
Accuracy tells you how many times the ML model was correct overall.
Accuracy: (TP+TN)/(TP+TN+FP+FN)

### Precision:
Precision refers to the number of true positives divided by the total number of positive predictions. It tells the quality of a positive prediction made by the model.
Precision: TP/(TP+FP)

### Recall
Recall is the measure of the ability of a system to present all relevant items. 
Recall: TP/(TP+FN)

### F1- score
F1 score is defined as the harmonic mean between precision and recall. It is used as a statistical measure to rate performance. In other words, an F1-score (from 0 to 9, 0 being lowest and 9 being the highest) is a mean of an individual's performance, based on two factors i.e. precision and recall.

F1 score: 2x(Precision)x(Recall)/(Precision + Recall)
