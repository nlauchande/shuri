# Machine Learning Engineer Nanodegree
## Capstone Proposal
Natu Lauchande
March 11th, 2019


## Proposal
Santander Customer Transaction Prediction (Kaggle Competition)

### Domain Background
Financial services are at the cornerstone of the modern society opportunity value chain for indivuals and business. Santander is a bank 




### Problem Statement

The goal of this project is to predict which type of transactions belongs each observation of the dataset and create a prototype of open source re-usable pipeline for the same type of problems. 

### Datasets and Inputs

The datasets are provided by Santander on Kaggle competition website.

_Input Data fields_

- id - the id of a training/test set
- var0..var199 - unitentified numeric features presented on the dataset.

There is no hint on the datasets on the meaning of the features so exploratory analysis on variable ranking and importance needs to be considered.

### Solution Statement

The solution for this project will consistist of the following : 

1. The solution will be predictions of each feature of the dataset with the test set data submitted to the kaggle competion.
2. A notebook depicting the solution process.
3. A software protype of an ML system that will productionize the solution.

### Benchmark Model

The benchmark model will be a simple logistic regression model trained from the training data .

### Evaluation Metrics

A set of metrics will be used to optimize and choose between the different modules. 

- AUC ROC curve metric ( as suggested in the official competition)
- F1 Score 
- Matthew correlation coefficient : {\displaystyle {\text{MCC}}={\frac {{\mathit {TP}}\times {\mathit {TN}}-{\mathit {FP}}\times {\mathit {FN}}}{\sqrt {({\mathit {TP}}+{\mathit {FP}})({\mathit {TP}}+{\mathit {FN}})({\mathit {TN}}+{\mathit {FP}})({\mathit {TN}}+{\mathit {FN}})}}}}

### Project Design

#### Step 1 : Domain literature review
Look at relevant papers in the literature around techniques and applications on the domain of the problem.

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

- [Kaggle](https://www.kaggle.com/c/santander-customer-transaction-prediction)
- [Data Science Design Manual]
