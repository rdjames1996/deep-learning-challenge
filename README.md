# deep-learning-challenge
# Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to determine the variables in the dataset that are the most important for Alphabet Soup to focus on in order to select the applicants with best chance of success for their ventures.

# Results: Using bulleted lists and images to support your answers, address the following questions:

## Data Preprocessing
## What variable(s) are the target(s) for your model?
The target variable for the model is the "Is-Successful column.

## What variable(s) are the features for your model?
The variables which are the features for the model are the NAME, APPLICATION_TYPE, AFFILIATION, CLASIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and ASK_AMT columns.
## What variable(s) should be removed from the input data because they are neither targets nor features?
The variable that should be removed from the input data are EIN. This is because they are only identifiers, making them insignificant - they should not be mixed in with the data. 

# Compiling, Training, and Evaluating the Model
## How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used 2 hidden layers and a lot of neurons to make the neural network model accurate (78%).

## Were you able to achieve the target model performance?
I was able to achieve target model performance.
## What steps did you take in your attempts to increase model performance?
In order to increase model performance, I added the NAME column to the analysis.
# Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

The overall accuracy was improved from 72% to 78%, with a reduction in model loss from 55% to 45%. For Alphabet Soup's success, I reccomend that they use this model to select the applicants which will bring them the most success.
