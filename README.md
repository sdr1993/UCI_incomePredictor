# UCI_incomePredictor
 Building a classification model for predicting the income using the Adult Census Income Dataset on UCI.
 
 
 ## Overview:
 In this notebook, we are going to predict whether a person's income is above 50k or below 50k using various features like age, education, and occupation.
 
 ## WebApp:
 [app link](https://uciincomepredictor.herokuapp.com/) :  https://uciincomepredictor.herokuapp.com/
 
 ![MarineGEO circle logo](C:/Users/ron23/OneDrive/Desktop/Screenshot.png "App Screenshot")
 
 
## Dataset:
This data[http://archive.ics.uci.edu/ml/datasets/Adult] was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)). The prediction task is to determine whether a person makes over $50K a year.


## Motivation:
*  Building such predictive models can help us better understand the population of a country as well as the various factors affecting the growth in the economy.

*  Governments can understand such factors and improve upon them leading to the growth of the country.

## Model Performance:
* Logistic Regression:
Accuracy score: 72.68
F1 score: 73.14
ROC AUC score: 72.69

* KNN Classifier:
Accuracy score: 84.98
F1 score: 86.02
ROC AUC score: 85.0

* Support Vector Classifier:
Accuracy score: 81.81
F1 score: 82.83
ROC AUC score: 81.82

* Decision Tree Classifier:
Accuracy score: 85.35
F1 score: 85.48
ROC AUC score: 85.35

* Random Forest Classifier:
Accuracy score: 89.6
F1 score: 89.74
ROC AUC score: 89.61

* XGBoost Classifier:
Accuracy score: 89.22
F1 score: 89.28
ROC AUC score: 89.22

* ANN Classifier:
Accuracy score: 81.74

* Ensemble Classifier:
Accuracy score: 89.32
F1 score: 89.04
ROC AUC score: 89.32

================================================================================================================
* Best Performing Model: Random Forest Classifier

## Conclusion:
* In this project, we build various models like logistic regression, knn classifier, support vector classifier, decision tree classifier, random forest classifier and xgboost classifier.
* A hyperparameter tuned random forest classifier gives the highest accuracy score of 89.6 and f1 score of 89.74 and ROC AUC score of 89.61.
