# Predict Bike Sharing Demand with AutoGluon

## Overview

A project I completed in fulfilment of the requirements for the AWS Machine Learning Engineer Nanodegree on Udacity. The end-goal of the project is to submit a model to a kaggle [competition](https://www.kaggle.com/c/bike-sharing-demand). The objective of the competition is to predict daily demand for bikes in a bike-sharing business.

The project involves: 
* Using AutoGluon (an AutoML library) to build and train an initial set of models
* Improving the score by pre-processing the dataset using Pandas
* Further improving the score by tuning the AutoGluon hyperparameters
* Implementing this entire workflow in AWS SageMaker
* Submitting the model to Kaggle

The project consists of the following files:
* Jupyter [notebook](project.ipynb) with code run to completion
* HTML export of the jupyter notebbook
* Markdown of the [report](report.md)

### Dependencies

```
Python 3.8
MXNet 1.9
Pandas >= 1.2.4
AutoGluon 0.2.0 
```



## Project Instructions

1. Create an account with Kaggle.
2. Download the Kaggle dataset using the kaggle python library.
3. Train a model using AutoGluon’s Tabular Prediction and submit predictions to Kaggle for ranking.
4. Use Pandas to do some exploratory analysis and create a new feature, saving new versions of the train and test dataset.
5. Rerun the model and submit the new predictions for ranking.
6. Tune at least 3 different hyperparameters from AutoGluon and resubmit predictions to rank higher on Kaggle.
7. Write up a report on how improvements (or not) were made by either creating additional features or tuning hyperparameters, and why you think one or the other is the best approach to invest more time in.


