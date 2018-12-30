# Titanic-Survival-Prediction
Implementing Machine Learning Algorithm in Python on Titanic Dataset

## Dataset Overview
The data has been split into two groups:

**1. Training set (train.csv)**  
**2. Test set (test.csv)**  

The training set is used to build the machine learning models. Our model will be based on “features” like passengers’ gender and class. 

The test set should be used to see how well our model performs on unseen data. For the test set, the ground truth (Survived) for each passenger is not provided. It is our job to predict these outcomes. For each passenger in the test set, we use the trained model to predict whether or not they survived the sinking of the Titanic.

## Variable Notes
**Survived** - Whether the passenger survived (1) or not (0)

**pclass**: A proxy for socio-economic status (SES)  
1st = Upper  
2nd = Middle  
3rd = Lower  

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp**: The dataset defines family relations in this way...  
Sibling = brother, sister, stepbrother, stepsister  
Spouse = husband, wife (mistresses and fiancés were ignored)  

**parch**: The dataset defines family relations in this way...  
Parent = mother, father  
Child = daughter, son, stepdaughter, stepson  
Some children travelled only with a nanny, therefore parch=0 for them.  

**Embarked** - Port where the passenger embarked. Can be:  
C - Cherbourg  
Q - Queenstown  
S - Southampton  

## Objective
To predict whether the passanger will survived or not using Machine Learning algorithm
