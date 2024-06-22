Aim of this project to predict whether a given passenger survived or not using machine learning algorithms.
Key components of this project include:
Data preprocessing and cleaning. 
Exploratory Data Analysis (EDA) to gain insights into the dataset
Making effective prediction Model which having best prediction accuracy rate.
Passengers in higher classes had higher survival rates.
- Women and children had higher survival rates compared to men.
- Age and fare also had some influence on survival probability.
- We use simple logistics Regression model to find the accuracy rate which is 62% not to accurate.
- After We try finding the accuracy by GridsearchCV model whis 82% on the test set.
- We find that the GridsearchCV model is more time consuming with some best accuracy
- Then we find that The Random Forest model achieved an accuracy of 84% on the test set and also it is not too much time takes as compared to GridsearchCV.
