Introduction

This project aims to predict whether a passenger on the Titanic survived or not using machine learning techniques. The dataset used for this project contains information about individual passengers, such as their age, gender, ticket class, fare, cabin, and whether or not they survived.

Dataset

The dataset used for this project is the Titanic dataset, which is available on Kaggle. The dataset contains the following features:

PassengerId: Unique identifier for each passenger
Survived: Whether the passenger survived (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name: Passenger's name
Sex: Passenger's sex
Age: Passenger's age
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Libraries Used

numpy
pandas
matplotlib
seaborn
scikit-learn
Models Used

Random Forest Classifier
Logistic Regression
Code Overview

Importing Required Libraries and Dataset
Data Preprocessing
Handling Missing Values
Encoding Categorical Variables
Exploratory Data Analysis (EDA)
Visualizing Data
Feature Engineering
Model Building
Random Forest Classifier
Logistic Regression
Model Evalution
Both Random Forest Classifier and Logistic Regression models were evaluated using accuracy, confusion matrix, and classification report.
Conclusion

In this project, we developed machine learning models to predict whether a passenger on the Titanic survived or not. We used the Random Forest Classifier and Logistic Regression algorithms for prediction and evaluated their performance. The Random Forest Classifier achieved an accuracy of 77%, while the Logistic Regression model achieved an accuracy of 77%.
