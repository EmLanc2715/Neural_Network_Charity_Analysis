# Neural_Network_Charity_Analysis

## Overview

The purpose of this project was to use neural network models to help the Alphabet Soup foundation predict where to make investments. Tensorflow was used with the neural network models to analyze and classify the success of charitable donations.

## Results

### Data Preprocessing

1. What variable(s) are considered the target(s) for the model?

The target variable for the model was the "IS_SUCCESSFUL" column. The column illustrates if a charity donation was used effectively.

2. What variable(s) are considered to be the features of the model?

The features of the model were the columns: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME-AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

3. What variable(s) are neither targets nor features, and should be removed from the input data?

EIN and NAME variables were not feautres or targets, and were consequentally removed from the inout data.

### Compiling, Training, and Evaluating the Model

1. How many neurons, layers and activation functions did you select for your neural network model, and why?

I created 3 separate neural network models, each with varying neurons, activation fucntions and layers.

#### Model 1

![Model1](https://user-images.githubusercontent.com/101427781/196234027-709d6daf-5cd0-45f2-bc69-eb18f834c9d9.png)

#### Model 2

![Model2](https://user-images.githubusercontent.com/101427781/196234059-20063765-19de-4040-b9dd-6a7901215180.png)

#### Model 3

![Model3](https://user-images.githubusercontent.com/101427781/196234096-139c318e-c8f7-463c-bb54-cc3f983e49fc.png)

2. Were you able to achieve the target model performance?

No, while my models were very close to 75% accuracy, I did not achieve this score.

Model1 accuracy_score = 73%
Model2 accuracy_score = 73%
Model3 accuracy_score = 73%

3. What steps would you take to increase model performance?

The model performance should increase if another hidden layer is added to the model.

## Summary

The neural network models that were created did not reach the targeted 75% accuracy score, meaning that the models were underperforming. To solve the classification problem, I would use the Random Forest Classifier to solve the classification problem.
