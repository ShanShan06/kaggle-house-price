# kaggle-house-price

![](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)

# House prices prediction with LR/Ridge/RF/RFR/XGBoost and Optuna

## Goal
Predict sales prices and practice feature engineering, RFs, and gradient boosting. Link for Kaggle competition. 
> Link for the Kaggle competition: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

## Implementation
Use common Machine Learning algorithm to predict the house price and use Optuna for hyperparameter tuning.

The jupyter notebook used can be viewed [here](house-prices-prediction-with-optuna.ipynb).

## Dependencies:
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [scikit-learn](https://scikit-learn.org/stable/)
* [seaborn](https://seaborn.pydata.org/index.html)
* [optuna](https://optuna.org/)

## TODO
* Some numerical features can be normalized
* Pool related features are currently dropped
