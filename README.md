# Titanic
This is my First Hands on Work on Machine Learning.
This is my solution for Kaggle titanic problem.
It passed it with a score of 76.55%
# Process
Began by preprocessing on data by identifiying missing data,categorical data etc.
Filled the missing data of age using mean.
Encoded categorical data using one hot encoder.
After all the preprocessing,split the data into training and test sets in a 80:20 ratio.
Used classification as the result is a binary value(dead or alive).
Trained the model on 7 different classification techniques and observed its accuracy using confusion_matrix and accuracy_score.
Logistic and Linear SVM produced best results with accuracy of 83.14%
Finally trained the test set on Linear SVM.
Downloaded the results of it and uploaded it on kaggle along with PassengerId.
