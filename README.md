# Neural_Network_Charity_Analysis

## Overview of Analysis
The purpose of the analysis was to use features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicatns will be successful if funded by Alphabet Soup

## Results
### Data Preprocessing
1 - What variable(s) are considered the target(s) for your model?
The "IS_SUCCESSFUL" column is the target for the models. 

2 - What variable(s) are considered to be the features for your model?
Features include 
 - Application Type
 - Income Amount
 - Special Consideration
 - Ask Amount
 - Status

3 - What variable(s) are neither targets nor features, and should be removed from the input data?
Variables that are neither targets nor variables would include Affiliation, Use Case, & Organization.

### Compiling, Training, and Evaluating the Model
4 - How many neurons, layers, and activation functions did you select for your neural network model, and why?
I chose to do 100/80/40 nodes within the 3 layers. 

5 - Were you able to achieve the target model performance?
No, I was able to improve it but did not achieve the goal. 

6 - What steps did you take to try and increase model performance?
I attempted to increase the model performance by increasing the neurons, adding hidden layers, and changing the activation in the 2nd and 3rd layer to sigmoid. 

## Summary
I was able to acheive an accuracy score of 0.72676 but my loss was 0.5601. I would recommend creating groups for "Approved Amount" or normalizing that variable to improve the results. 
