# CROPS-DAMAGE-
Used an ML model to predict damaged and healthy crops within the dataset, applied Voter classifier to maximize output between Random forest and Decision tree models

Many factors lead to a succesful harvest , while alot of these factors are difficult to control, measures can be taken to improve the potential of a succesful yield. Factors such as soil type,soil fertility ,Favourable weather condition , season and pesticides/pest control among others are factors Farmers pay keen interest to as they are more within their control and professional judgement.

This project takes look at most of these conditions , with focus on pesticide use, type and frequency. Pestiscide use must be controlled as too much deem crops damaged and unperishable , too little defeats the purpose of its use which is pest control.

This data is based on crops harvested by various farmers at the end of harvest season and our desire to predict the outcome of these harvest taking into account the factors presented to us. As well as the cause for the crop damages recorded

# ML models

## K FOLD CROSS VALIDATION

Cross validation is a technique to evaluate predictive models by dividing the original data into training set to train the model and test set to evaluate it.The test set is considered as validation set here. In K-Fold cross validation, the original sample is divided randomly into k equal subsamples.From which one subsample is considered as validation set and rest k-1 are taken as training set. The sample step is repeated for all the subsamples. The advantages of this are :- It prevents overfitting. Reduced bias. Variance is reduced. Less Computation time

## DESICION TREE

It is a surpervised ML algorithm.It uses the tree representation to solve the problems where leaf node corresponds to class label and internal node of tree corresponds to attributes.Its main objective is to have pure nodes. Gini imurity and information gain are the best methods to get best split points.

Gini impurity = 1-Gini ; Information Gain = 1-Entropy

## RANDOM FOREST

It is a supervised ML algorithm which creates desicion trees on data samples and predict from each of them. After that selects the best by votting. It reduces overfitting by averaging the result.

## VOTING CLASSIFIER

It is a wrapper for set of different algorithms that are trained and valuated in parallel in order to exploit the different peculiarities of each algorithm. It chooses the best predicting model for the dataset.It yields better performance than any single algorithm.
