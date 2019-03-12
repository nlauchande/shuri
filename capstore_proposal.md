# Machine Learning Engineer Nanodegree
## Capstone Proposal
Natu Lauchande
March 11th, 2019


## Proposal
Santander Customer Transaction Prediction (Kaggle Competition)

### Domain Background


### Problem Statement

The goal of this project is to predict which type of transactions belongs each observation of the dataset.

### Datasets and Inputs

The datasets are provided by Santander on Kaggle competition website.

_Input Data fields_

- id - the id of a training/test set
- var0..var199 - unitentified numeric features presented on the dataset.

There is no hint on the datasets on the meaning of the features so exploratory analysis on variable ranking and importance needs to be considered.

### Solution Statementt

The solution will be predictions of each feature of the dataset.

### Benchmark Model

My benchmark model will be a simple logistic regression model with the existing variables.

### Evaluation Metrics

Prediction results are evaluated on the area under the ROC curve metric as suggested by the competition .

The approach will be based on taking the score of the competition as evaluation.

### Project Design

#### Step 1 : Domain literature review
Variables will be explored and analysed using Pandas and visualisations will be constructed using a suitable visualizatio tool like Seaborn.

#### Step 2 : Exploratory Data Analysis
Variables will be explored and analysed using Pandas and visualisations will be constructed using a suitable visualizatio tool like Seaborn.

#### Step 3 : Data cleaning and preparation
Datasets will be checked for quality and issues including missing values , duplicate data and outliers.

#### Step 4 : Build baseline/benchmark model 
A baseline model will be created using a very simple logistic regression model and the most important features.

#### Step 5 : Feature analysis and exploration
            
#### Step 6 : Iterate on model development :
   For each method cross validation and hyparameter random search will be used to find the best model in class.

      a. Evaluate tree based boosting methods ( GBM's, XGboost, Catboost).
      b. Evaluate suitability of deep learning methods.
      c. Explore most promising alternative.
      d. Submit to Kaggle leader the most promising solution.

#### Step 7 : Write final report and conclusions
  Analyse and compare performance of different methods chosen on step 7. A generic prototype standalone pipeline system will be created that will accept unidenfied variables and allow for a Machine Learning API for transaction type prediction :
        - Trained 
        - Predicted with batch inference
        - Served with an API

### Reference

- [Kaggle](https://www.kaggle.com/c/santander-customer-transaction-prediction#evaluation)
