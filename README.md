# Neural_Network_Charity_Analysis

## Project Overview
I have been recruited to use machine learning and neural network algorithms to figure out which combination of those can best be used to determine the worthiest causes for receiving Alphabet Soup grant money.

## Resources
- Data Source: charity_data.csv

- Software: Python 3.9.4 via Anaconda Jupyter Notebook

## Results
What I was able to discover was the following:

### *Data Preprocessing*
- The variable I considered as targets for my model was the IS_SUCCESSFUL column.

- The variables I considered as features for my model were the APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL columns.

- The variables I didn't consider as either targets or features, and were subject for removal, were the EIN and NAME columns.

### *Compiling, Training, and Evaluating*

- For my neural network model I selected, I chose _ neurons, _ layers, and _ activation functions, to assess which combination brought the model to the minimum target model performance of 75% accuracy.

- Unfortunately, irrespective of which parameter I adjusted and how many of them were adjusted at once before each attempt, I was unable to achieve the target model performance of 75% accuracy.

- The steps I took to increase model performance involved the following: Removing additional column features, increasing the binning thresholds for APPLICATION_TYPE and CLASSIFICATION features, adding the number of nodes to the two hidden layers, adding an additional hidden layer, using different activation functions (e.g. tanh) for the hidden layers, and adding the number of epochs to the training regimens (I noted that the accuracy of results started to peak downward after 7 epochs, no matter what other combination of parameters I tried.)

## Summary
Additional work needs to be done to better determine which model can be used that would generate results that yield the desired minimum target model performance of 75% accuracy.  After much testing with many different parameters being adjusted, I was unable to find the correct model that could do so, and I am going to move to recommend additional research to find a model that meets the required criteria.
