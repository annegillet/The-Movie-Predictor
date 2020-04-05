Here are the different topics we're going through :
- A little bit of scraping
- NA and Zeros Treatment
- Data Analysis and Visualising thanks to matplotlib and seaborn librairies
- ProfileReport
- apply / np.where functions
- One Hot Encoded
- Standardisation (with Standard Scaler)
- PCA - Principal Component Analysis
- 2 regression models : Linear Regression + KNN Regressor
- 4 classifier models : Logistic Regression + KNN Classifier + Random Forest Classifier + Decision Tree Classifier
- ROC and AUC
- Confusion Matrix
- Different measures : accuracy, RMSE, precision, recall, threshold

# The Movie Predictor

This project is aiming at predicting the score of a new movie (IMDB ressources).
Regressor and Classifier models are testing and the one which performs best is XG Boost Classifier.
The different models tested are the following:
> Regressor models : linear regression, SVR with different kernels(linear, polynomial, rbf), Gradient Boosting Regressor, Random Forest Regressor, XG Boost Regressor

> Classifier models : logistic regression, SVC (linear, polynomial, rbf), Gradient Boosting Classifier, Random Forest Classifier, XG Boost Classifier, KNN Classifier, Decision Tree Classifier, SGD Classifier.

The different topics treated are as follow:
> A bit of scraping

> Data Treatment: NA and Zeros, Data Analysis and Visualising thanks to matplotlib and seaborn librairies, ProfileReport

> apply / np.where functions

> Pre-processing: KBinsDiscretizer, One Hot Encoded, Standardisation (with Standard Scaler and Robust Scaler which includes the aberrant datas), PCA - Principal Component Analysis

> ROC and AUC

> Confusion Matrix

> Different evaluation measures : accuracy, MSE (for regressor models), precision, recall, threshold, OLS

> Hyperparameters : RFE, GrisSearchCV

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Jupyter is required to read the code in the file Projet P6 - révisions.ipynb

### Installing

You just have to run the Projet P6 - révisions.ipynb
