# Credit Risk Classification

# Introduction
Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data


# DESCRIPTION

Credit Risk Analysis Report

# TABLE OF CONTENTS
Introduction
Description
Credit Risk Analysis Report
Installation/Deployment
Credits/Contribution




# Credit Risk Analysis Report

1) Split the Data into Training and Testing Sets
The first thing is to split the data using the train_test_split function


2) Create a Logistic Regression Model with the Original Data
Using the X_train and y_train, we will then train the model for a Logistical Regression.

After this we saved the prediction, calculated the accuracy score of 94.4%. From here, we generated a confusion matrix for 
the Healthy Loans and the High Risk loans. Both loans scored high, as the Healthy loan had a perfect score of 100% (1) and 
the High Risk loan had a score of 87%. This means that the variables used in the dataset are very accurate, including the 
High Risk loans.

The reason the High Risk loans was not perfect, may be because their could be minor external factors in determining 
High risk loans, which is very common in this sector. 



Predict a Logistic Regression Model with Resampled Training Data
Use RandomOverSampler module. 

Even with the Random Over Sampler data, the data was not different. 

It is safe to conclude that these variables are accurate and are fairly common factors to use when determining the status of a loan. 
In the financial industry, financial advisors would use these variables (using computers obviously) to calculate the loan status on a daily basis.
Due o the fact that the accuracy was very high initially, the Random Over Sampler data did not any effect on the analysis. 

# Installation

Jupyter Notebook - dev environment
RandomOverSampler, Logistic Regression 

# Credits

Arun Balaram
Ask BCS 
