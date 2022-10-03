# NEURAL NETWORK CHARITY ANALYSIS

## OVERVIEW
The purpose of this project is to build, train, test and in the end optimize a neural network that predicts the success rates of charities for loan application purposes.
## RESULTS
**DATA PROCESSING**<br>
* What variable(s) are considered the target(s) for your model?<br>
The target variable for our model is IS_SUCCESSFUL<br>
* What variable(s) are considered to be the features for your model?<br>
The feature variables are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE_ORGANIZATION, STATUS, INCOME_AMT.<br>
* What variable(s) are neither targets nor features, and should be removed from the input data?<br>
The variables that were removed were EIN and NAME.<br>

**COMPILING, TRAINING & EVALUATING THE MODEL**<br>
* How many neurons, layers, and activation functions did you select for your neural network model, and why?<br>
80 neurons and three hidden layers were used because during the original evaluation two layers did not achieved the 75% accuracy the project intended to get.<br>
* Were you able to achieve the target model performance?<br>
Although the optimization model seemed to approach the desired 75% accuracy level it ended up being around the same percentage as the original model.
* What steps did you take to try and increase model performance?<br>
Different number of layers and epochs were tested to increase model performance.
## SUMMARY
As a recommendation I would suggest trying other classification algorithms such as the Decision Tree Classification Algorithm since it might be better suited for this project. This classification machine learning algorithm involves dividing a dataset into segments based on certain feature variables from the dataset.
