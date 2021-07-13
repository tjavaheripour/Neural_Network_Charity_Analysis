# Neural_Network_Charity_Analysis

## Overview of the project:

In this project, we use Deep Machine Learning and Neural Networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, we received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

-	EIN and NAME—Identification columns
-	APPLICATION_TYPE—Alphabet Soup application type
-	AFFILIATION—Affiliated sector of industry
-	CLASSIFICATION—Government organization classification
-	USE_CASE—Use case for funding
-	ORGANIZATION—Organization type
-	STATUS—Active status
-	INCOME_AMT—Income classification
-	SPECIAL_CONSIDERATIONS—Special consideration for application
-	ASK_AMT—Funding amount requested
-	IS_SUCCESSFUL—Was the money used effectively


This project consists of three technical analysis deliverables to analyze and classify the success of charitable donations:

- Preprocessing Data for a Neural Network Model
- Compile, Train, and Evaluate the Model
- Optimize the Model


## Results :

### Data Preprocessing :

-	The target variable for my model is the "Is_Successful" column which tells us whether the money was used effectively.
-	The features variables in this model are every column for the target, the name and EID columns:
       - APPLICATION_TYPE
       - AFFILIATION
       - CLASSIFICATION
       - USE_CASE
       - ORGANIZATION
       - STATUS
       - INCOME_AMT
       - SPECIAL_CONSIDERATIONS
       - ASK_AMT

-	The name and EID columns are neither targets nor features, and should be removed from the input data.


### Compiling, Training, and Evaluating the Mode :



| Model | Accuracy | Layers | Hidden Layer1 Neurons | Activation Function1 | Hidden Layer2 Neurons | Activation Function2 | Hidden Layer3 Neurons | Activation Function3 | Hidden Layer4 Neurons | Activation Function4 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Model1 | 74% | 2 | 80 | relu | 30 | relu | - | - | - | - |
| Model2 | 74% | 3 | 80 | relu | 30 | relu | 20 | relu | - | - |
| Model3 | 74% | 3 | 80 | relu | 30 | tanh | 20 | tanh | - | - |
| Model4 | 74% | 3 | 80 | relu | 40 | tanh | 20 | tanh | 10 | tanh |
## Summary :
