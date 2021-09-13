# TITANIC DATA ANALYSIS

Problem Statement: Use the Titanic passenger data (name, age, price of ticket, etc.) and predict who will survive and who will die.

Key Points:
1) Imported the Titanic dataset using pandas library and performed EDA
1) Performed data visualiztion using seaborn and matplotlib.
2) In data visualzation it was found that:
        a) Target(Survived) column is unbalanced.
        b) Women were more likely to survive than men
        c) Survival also depends on the Pclass 
3) Performed data wrangling and handled NaN and missing values
4) By EDA it was found a strong impact of features like Sex, Age, Embarked on the target.
5) Built the models (Decision Tree, Random Forest and Logistic Regression model) with scikit learn library, using these features.
6) Calculated accuracy, F1 score, Precision and Recall of each model
7) Deciding by k fold cross validation score, best model was Random Forest model
