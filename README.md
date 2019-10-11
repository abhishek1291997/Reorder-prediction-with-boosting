# Reorder-prediction-with-boosting
Predicting the action of customer whether the product is reorder or not

## Getting Started
Use the Anaconda navigator to open the Jupyter notebook and start implementing it.

## Pre-requisites
* Numpy
* Pandas
* Scikit-learn
* XGBoost

## Installing
* Numpy
``` conda install -c anaconda numpy ```
* Pandas
``` conda install -c anaconda pandas ```
* Scikit-learn
``` conda install -c anaconda scikit-learn ```
* XGBoost
``` conda install -c anaconda py-xgboost ```

## Working 
Firstly, I downloaded the dataset from [instacart-market-basket-analysis](https://www.kaggle.com/c/instacart-market-basket-analysis)
Then, this dataset is all about whether the customer reorder the previously purchased items or not. 
First challenge is about sorting the dataset which file is useful or not, then finding the columns which are present in different csv files.
Then merging mutiple files with each other to cleanse the dataset and making ready for prediction.

After choosing columns which are choosed as features and labels , start training it with XGB Classifier to achieve the prediction.

Reason behind choosing XGB classifier is that this classifier is fast , reliable and update the gradient frequently which ultimately helps in achieving the best accuracy among the other classifiers.

## Acknowledgement
Used the dataset from kaggle [instacart-market-basket-analysis](https://www.kaggle.com/c/instacart-market-basket-analysis)

Inspiration behind that is to prepare a model which will help the online shopping better and recommendable.
