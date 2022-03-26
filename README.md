# Neural_Network_Charity_Analysis

# Overview 
- With knowledge of machine learning and neural networks,the features in the provided dataset to help create a binary classifier that is capable of predicting whether   applicants will be successful if funded by Alphabet Soup.

- CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture   metadata about each organization, such as the following:

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

- This new assignment consists of three technical analysis deliverables and a written report.


Deliverable 1: Preprocessing Data for a Neural Network Model

Deliverable 2: Compile, Train, and Evaluate the Model

Deliverable 3: Optimize the Model

Deliverable 4: A Written Report on the Neural Network Model (README.md)

# Results:

## Data Preprocessing
- What variable(s) are considered the target(s) for your model?
  The variable IS_SUCCESSFUL should be the target variable as it contains the binary data 

- What variable(s) are considered to be the features for your model?
  APPLICATION_TYPE, AFFILIATION_TYPE, USE_CASE, CLASSIFICATION, ORGANISATION, STATUS,INCOME_AMT_, SPECIAL_CONSIDERATION, ASK_AMT

- What variable(s) are neither targets nor features, and should be removed from the input data?
  The Variables EIN and Name should be removed as they carries identification information

## Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions have been selected for the neural network model, and why?
  The model is made with 2 hiden layers with 80 and 30 neurons.The output layer is made of a unique neuron as it is a binary classification. ReLu function has been   used to speed up the model with sigmoid function ,binary_crossentropy and adam functions.

- Were the analysis able to achieve the target model performance?
  The model accuracy is under 75% and this is not a satisfied performance.

- What steps have been taken to try and increase model performance?
  The bucketing have been applied to the feature ASK_ME . Also the number of neurons have been increased on one of the hidden layers and used model with 3 hidden     layers. 


# Summary: 
The deep llearning neural network model did not reach the target of 75% accuracy. The model is underperforming. As the output is binary the analysis could be done with random forest model and compare and anayse the performance. 

![image](https://user-images.githubusercontent.com/93173498/160222269-cbfbcd47-3c1c-4ab2-a390-c880dbf2a5db.png)


