# Machine Learning Project: Credit_Card_Default_Prediction

This project is a "classification model to predict credit card defaults. The goal is to "create a reliable model to identify potential defaults based on user data". The project includes data exploration, preprocessing, model selection, training, and evaluation.

## Table of Contents
### 1.Project Description
### 2.Data
### 3.Exploratory Data Analysis (EDA)
### 4.Preprocessing
### 5.Modeling
### 6.Evaluation
### 7.Results and Insights
### 8.Future Work
### 9.Setup
### 10.Usage

#### Dataset: "UCI Credit Card Dataset"
#### Source: https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset
#### Features:PAY_0,BILL_AMT1,PAY_AMT2,PAY_AMT1,BILL_AMT2,BILL_AMT3,PAY_2,LIMIT_BAL. DataTypes:- int64, float64
#### Target: "default.payment.next.month, which indicates whether a user defaulted"]
### Exploratory Data Analysis (EDA)
This section includes data exploration and visualizations:

#### Missing Values: Identified and handled missing values in columns like job_type and company_type.
#### Data Visualization: Used various plots (heatmaps, histograms, etc.) to understand relationships and detect any patterns.
### Preprocessing
Steps taken to prepare the data for modeling:

#### Encoding: Converted categorical variables, e.g., gender and lung cancer, into numerical values.
#### Outlier Detection and Removal: Used IQR to identify and handle outliers.
#### Feature Scaling: Applied StandardScaler to scale numerical features for model compatibility.
Modeling
#### Algorithms: Used Logistic Regression, Decision Trees.
#### Training and Testing: Split the dataset into training and test sets using train_test_split.

### Evaluation
#### Metrics: Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.
Confusion Matrix: Visualized the confusion matrix to understand the model’s performance on each class.

#### Future Work
#### Improvements: Possible model improvements, such as additional feature engineering or using a different algorithm.
#### Additional Data: Mentioned Features:PAY_0,BILL_AMT1,PAY_AMT2,PAY_AMT1,BILL_AMT2,BILL_AMT3,PAY_2,LIMIT_BAL have high importance, we can use 
only these features to train the machine learning model to get higher accuracy comparing to previous 80%.
Setup
#### Prerequisites
Python
Libraries: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, and others as listed in requirements.txt
