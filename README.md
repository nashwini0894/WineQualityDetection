# WineQualityDetection
Predicting Quality of Wine using Stochastic Gradient Descent Classifier and Support Vector Classifier
 
# About the dataset
The dataset used is the Wine Quality dataset for red wine variant of the Portuguese "Vinho Verde" wine. The input variables of the dataset are:
1 -  fixed acidity 
2 - volatile acidity 
3 - citric acid 
4 - residual sugar 
5 - chlorides 
6 - free sulfur dioxide 
7 - total sulfur dioxide 
8 - density 
9 - pH 
10 - sulphates 
11 - alcohol 
Output variable: 
quality (score between 0 and 10) 

# About the code
I have done some exploration on the data using matplotlib and seaborn, to understand the dependency of the quality of wine on the various inputs available. Then used Stochastic Gradient Descent and Support Vector Classifier to predict the quality of the wine.
To classify the quality of the wine, I have considered an initial good:
if 0> quality > 6.5, then qualify quality as bad
if 6.5 > quality > 10, then qualify quality as good
