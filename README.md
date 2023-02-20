# Neural_Network_Charity_Analysis
The purpose of this project is to use skills to work by helping the foundation predict where to make investments.

With machine learning and neural networks, I was able to use the features in the provided dataset to help  create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years and within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns

APPLICATION_TYPE—Alphabet Soup application type

AFFILIATION—Affiliated sector of industry

CLASSIFICATION—Government organization classification

USE_CASE—Use case for funding

ORGANIZATION—Organization type

STATUS—Active status

INCOME_AMT—Income classification

SPECIAL_CONSIDERATIONS—Special consideration for application

ASK_AMT—Funding amount requested

IS_SUCCESSFUL—Was the money used effectively


The IS_SUCCESSFUL column: was the target of this model

Other variables considered for the model features were: every column except IS_SUCCESSFUL which is our goal so the other ones will be dropped.

There were a few variables that were not either targets or feautres for the dataset: we dropped the EIN, NAME columns because there was no impact to the outcome.

