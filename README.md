# TITANIC DATA ANALYSIS

Problem Statement: Use the Titanic passenger data (name, age, price of ticket, etc.) and predict who will survive and who will die.

Key Points:
1) We imported the Titanic dataset using pandas library and performed EDA
1) We performed data visualiztion using seaborn and matplotlib.
2) In data visualzation we found that:
        a) Target(Survived) column is unbalanced.
        b) Women were more likely to survive than men
        c) Survival also depends on the Pclass 
3) We performed data wrangling and handled NaN and missing values
4) By EDA we found a strong impact of features like Sex, Age, Embarked on the target.
5) We then built a model with scikit learn library, using these features. We built Decision Tree, Random Forest and Logistic Regression model.
6) We calculated accuracy, F1 score, Precision and Recall of each model
7) Deciding by k fold cross validation score, best model was Random Forest model
