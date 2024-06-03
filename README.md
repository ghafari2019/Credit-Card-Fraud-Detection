# Credit-Card-Fraud-Detection
## In this data science project, we will predict the credit card fraud in the transactional dataset using some of the predictive models. 

# Credit Card Fraud Detection Dataset

The dataset you are referring to is well-known in the machine learning community for credit card fraud detection. Here is a detailed breakdown of the dataset and its characteristics:

## Dataset Description
- **Time Period**: Transactions made by European cardholders in September 2013.
- **Duration**: Transactions over two days.
- **Number of Transactions**: 284,807 transactions.
- **Fraudulent Transactions**: 492 transactions.
- **Class Distribution**: The dataset is highly imbalanced.
  - **Non-fraudulent Transactions**: 284,315
  - **Fraudulent Transactions**: 492
  - **Fraud Percentage**: 0.172%

## Features
The dataset consists of 30 features:
- **V1 to V28**: These are the result of a PCA transformation. Due to confidentiality issues, the original features are not provided.
- **Time**: The seconds elapsed between this transaction and the first transaction in the dataset.
- **Amount**: The transaction amount.
- **Class**: The response variable, with 1 representing fraud and 0 representing non-fraud.

## Data Characteristics
- **Highly Imbalanced**: Only 0.172% of the transactions are fraudulent, making it a challenging task for machine learning algorithms to detect fraud accurately.
- **PCA Transformation**: The use of PCA-transformed features helps in maintaining the confidentiality of the data while providing a reduced feature space that still retains most of the variance.
- **Time Series Nature**: The 'Time' feature suggests a temporal aspect to the transactions which might be useful for certain types of analyses.

* Understanding the problem

* Importing required libraries and understanding their use

* Importing data and learning its structure

* Performing basic EDA

* Scaling different variables

* Outlier treatment

* Building a basic Classification model with Random Forest

* Nearmiss technique for undersampling data

* SMOTE for oversampling data

* cross-validation in the context of undersampling and oversampling

* Pipelining with sklearn/imblearn

* Applying Linear model: *Logistic Regression*

* Applying Ensemble technique:  *Random Forest*

* Applying Non-Linear Algorithms: *Support Vector Machine, Decision Tree, and k-Nearest Neighbour*


* Making predictions on test sets and computing validation metrics

* ROC curve and Learning curve

* Comparison of Results and Model Selection

* Visualization with seaborn and matplotlib 
