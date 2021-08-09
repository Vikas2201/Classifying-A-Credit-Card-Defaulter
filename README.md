# Classifying-A-Credit-Card-Defaulter
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![1_ncw88R85hT-4r2wHyaFZ-w](https://user-images.githubusercontent.com/76476273/128662207-b58427ad-30bf-4afe-a5e0-c44186c2e834.jpeg)

# Project Objective
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This project aims to bridge this gap of uncertainty by utilizing a data-driven approach by using past data of credit card customers in conjunction with machine learning to predict whether or not a consumer will default on their credit cards.

The goal behind using this model is to achieve two things:
 * Bring more consistency to the loaning process and;
 * Investigate what the key drivers are behind a potential defaulter

![1_uZyt9Z189siaNsAlIDtjEg](https://user-images.githubusercontent.com/76476273/128662556-9a09cff8-4a39-4a6f-9de3-fac43dbc620f.jpeg)

# Problem Statement
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Financial Threats Are Displaying A Trend About The Credit Risk Of Commercial Banks As The Incredible Improvement In The Financial Industry Has Arisen. In This Way, One Of The Biggest Threats Faces By Commercial Banks Is The Risk Prediction Of Credit Clients. The Goal Is To Build A Classification Methodology To Determine Whether A Person Defaults The Credit Card Payment For The Next Month.

# Architecture
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/76476273/128662765-d390eb73-6e01-4b2a-8b61-0c86777227cf.png)


# Dataset Description
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The client will send data in multiple sets of files in batches at a given location. The data has been extracted from the census bureau. 

* Features:

1.	LIMIT_BAL: continuous.Credit Limit of the person.
2.	SEX: Categorical: 1 = male; 2 = female
3.	EDUCATION: Categorical: 1 = graduate school; 2 = university; 3 = high school; 4 = others
4.	MARRIAGE: 1 = married; 2 = single; 3 = others
5.	AGE-num: continuous. 
6.	PAY_0 to PAY_6: History of past payment. We tracked the past monthly payment records (from April to September, 2005)
7.	BILL_AMT1 to BILL_AMT6: Amount of bill statements.
8.	PAY_AMT1 to PAY_AMT6: Amount of previous payments. 


* Target Label:
Whether a person shall default in the credit card payment or not.
9.	default payment next month:  Yes = 1, No = 0.

# Tools And Libraries Used
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
 * Flask is for creating the application server and pages.
 * matplotlib , seaborn , plotly are used for data Visualization
 * numpy is for arrays computations and mathematical operations
 * pandas is for Manipulation and wrangling structured data
 * scikit-learn is used for machine learning tool kit
 * pickle is used for saving model
 * SQLite is for database operation
 * josn is for data validation processes
 * os is used for creating and deleting folders
 * csv is used for creating .csv format file

# Algorithms Used
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 * KMeans Clustering Algorithm
 * Naïve Bayes
 * XGBoost Classifier
 * GridSearch CV

# Model Evaluation Metric
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 * F1 score 
 * Recall
 * Precision
 * ROC AOC Curve
 * Confusion Metric
 
