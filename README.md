# Machine-Learning-for-a-Marketing-Campaign

**Author:**

I am Álvaro Orgaz Expósito, a data science student at KTH (Stockholm, Sweden) and a statistician from UPC-UB (Barcelona, Spain).

**Abstract:** 

This repository contains the final project of the Data Mining course in my bachelor's degree in statistics at UPC-UB (Barcelona, Spain).

The main aims of this project are:
- Preprocessing and exploratory data analysis of a dataset with customer characteristics for a marketign campaign
- Apply unsupervised ML algorithms for develeping the exploratory data analysis
- Apply supervised ML algorithms for predicting the probability of being good customer and comparing the predictive behaviour between models

**Files in main folder:**
- R Markdown files with the code of the project (numerically ordered by logical steps in a data science project)
- *Data.xlsx*: this is the raw data
- *Data.RData*:
  + *data*: dataframe with raw data preprocessed in file  *1. Preprocessing and Exploratory Data Analysis (EDA)*
  + *data_train*: dataframe with train data splitted in file *3.1. Supervised ML Validation Protocol*
  + *data_test*: dataframe with test data splitted in file *3.1. Supervised ML Validation Protocol*
  + *data_train_folds*: list with 5 validation folds or splits of the train data created in file *3.1. Supervised ML Validation Protocol*
  + *AUC*: function of the performance metric used for validation
- *Outputs* folder with outputs of the code (numerically ordered as the code):
  + *.pdf* files with graphics and tables of results
  + *.RData* one file for each model containing a dataframe with the validation results (AUC by 5-Fold Cross-Validaton)

**Code:** 

The project has been developed in R Markdown.
