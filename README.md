
## Introduction
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Findings

### Data Preprocessing

#### What variable(s) are the target(s) for your model?
* The 'IS_SUCCESSFUL' column from application_df.
  
#### What variable(s) are the features for your model?
* The feature variables used were:
  1. AFFILIATION—Affiliated sector of industry
  2. CLASSIFICATION—Government organization classification
  3. USE_CASE—Use case for funding
  4. ORGANIZATION—Organization type
  5. STATUS—Active status
  6. INCOME_AMT—Income classification
  7. SPECIAL_CONSIDERATIONS—Special considerations for application
  8. ASK_AMT—Funding amount requested

#### What variable(s) should be removed from the input data because they are neither targets nor features?
The "EIN" and "NAME" columns have no direct impact on the target variable and can be dropped.


#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
* In my first neural network model, I used a two-layer architecture with a specific choice for the number of neurons, layers, and activation functions.

* Additionally, I used a single neuron in the output layer with a sigmoid activation functio") to model the binary classification problem. 


#### Were you able to achieve the target model performance?
* I was only able to achieve 73%


#### What steps did you take in your attempts to increase model performance?
1. Increasing the number of neurons and epochs:
   
2. Adding more layers to the model:

3. Using a different activation function (tanh for the second layer):
  

4. Utilizing an Automated Optimiser (such as a hyperparameter tuner):
   

## Summary
The deep learning model was unable to achieve accuracy higher than 73%. To further improve the model's performance, I could

1. Add more data
  
  
2. Explore alternative machine learning algorithms


3. Identify feature importance and selecting relevant attributes

  
4. Address outliers
