# Titanic Survival Prediction Project

_Overview :
-This project analyzes the Titanic dataset to predict passenger survival using various machine learning models. The dataset includes features like passenger class, age, sex, fare, and more. We perform data preprocessing, feature engineering, and model training/evaluation to identify the best-performing classifier.
-The main goal is to predict whether a passenger survived (1) or not (0) based on historical data from the Titanic disaster.

_Key Features:
-Data exploration and visualization using Pandas, NumPy, Seaborn, and Matplotlib.
-Handling missing values, encoding categorical variables, and feature scaling.
-Training multiple ML models including Random Forest, XGBoost, CatBoost, LightGBM, SVM, KNN, and ensemble methods like Stacking and Voting.
-Model evaluation using Accuracy and F1 Score.
-Hyperparameter tuning with GridSearchCV and RandomizedSearchCV.


_Dataset
Source: train.csv (included in the repository or from Kaggle's Titanic competition).

Columns:
PassengerId: Unique ID.
Pclass: Ticket class (1, 2, 3).
Name: Passenger name.
Sex: Gender.
Age: Age in years.
SibSp: Number of siblings/spouses aboard.
Parch: Number of parents/children aboard.
Ticket: Ticket number.
Fare: Passenger fare.
Cabin: Cabin number.
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
Survived: Target variable (0 = No, 1 = Yes).


# 🤖 Models
-   Hist Gradient Boosting  (**best performing**)  
-   Gradient Boosting
-   Grid Search CV  
-   Stacking  
-   Cat Boost Classifier
-   SVM  
-   Cat Boost
-   random_search_Boost  
-   Random Forest Classifier  
-   KNN  
-   XG Boost random_state
-   grid_search_Boost
-   Voting Classifier  
-   Extra Trees
-   XG Boost  
-   MLP Neural Net
-   Random Forest Classifier
-   Light GBM
-   Stacking Classifier  
-   Logistic Regression

----------------------------------------------------------------------------------------------

# Results

Model,                       Accuracy,                    F1 Score

Hist Gradient Boosting,      0.843575,                    0.810811

Gradient Boosting,           0.837989,                    0.805369

Grid Search CV,              0.832402,                    0.802632

Stacking,0.                  832402,                      0.794521

Cat Boost Classifier,        0.832402,                    0.794521

SVM,                         0.826816,                    0.783217

Cat Boost,                   0.826816,                    0.786207

random_search_Boost,         0.826816,                    0.791946

Random Forest Classifier,    0.826816,                    0.786207

KNN,                         0.821229,                    0.786667

XG Boost random_state,       0.821229,                    0.783784

grid_search_Boost,           0.821229,                    0.780822

Voting Classifier,           0.821229,                    0.780822

Extra Trees,                 0.821229,                    0.780822

XG Boost,                    0.821229,                    0.783784

MLP Neural Net,              0.821229,                    0.783784

Random Forest Classifier,    0.815642,                    0.775510

Light GBM,                   0.810056,                    0.767123

Stacking Classifier,         0.810056,                    0.770270

Logistic Regression,         0.804469,                    0.761905

                                                                                            The best model is Hist Gradient Boosting with an accuracy of ~84.36%.