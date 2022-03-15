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

## Conclusion:
* In this project, we build various models like logistic regression, knn classifier, support vector classifier, decision tree classifier, random forest classifier and xgboost classifier.
* A hyperparameter tuned random forest classifier gives the highest accuracy score of 92.77 and f1 score of 93.08.
