## Porto Seguro’s Safe Driver Prediction

<b>Competition Goal</b>: help car insurance company (Porto Seguro) to improve their model for predicting incident probability based on customer's profile. More accurate prediction will allow them to offer auto insurance policy at competitive customer-specific price point. <br>

### Action Plan
1. run an exploratory analysis on the dataset;
2. set up and train XGBoost model with stratified KFold;
3. stack KFold predictions, evaluate the submission;
4. tune XGBoost model parameters; repeat.

### Steps

- set up the environment
- read in the data
- split features and target variable
- check if the class distribution is balanced
- explore correlation matrix
- define the gini metric for model evaluation
- define training, prediction and submission datasets
- set stratified KFold training structure
- set XGBoost parameters
- train XGBoost model
- make ensemble prediction
- Put submission into csv format
