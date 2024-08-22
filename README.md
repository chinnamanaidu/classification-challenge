# classification-challenge

Introduction: retrieve the data from the spam data url
### Classification module challenge
Retrieve the Data
The data is located at https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv
Dataset Source: UCI Machine Learning Library

Import the data using Pandas. Display the resulting DataFrame to confirm the import was successful.
# Import the data
###### ("https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv")

#### Predict Model Performance
#### You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct!

#### Write down your prediction in the designated cells in your Jupyter Notebook, and provide justification for your educated guess.

#### Replace the text in this markdown cell with your predictions, and be sure to provide justification for your guess.
## Split the Data into Training and Testing Set
####  Create the labels set `y` and features DataFrame `X`
####  Split data into training and testing
####  Check the balance of the labels variable (`y`) by using the `value_counts` function.

## Scale the Features
#### Use the StandardScaler to scale the features data. Remember that only X_train and X_test DataFrames should be scaled.
####  from sklearn.preprocessing import StandardScaler
####  Create the StandardScaler instance
####  Fit the Standard Scaler with the training data
####  Scale the training data
####  Scale the testing data


## Create and Fit a Logistic Regression Model
#### #### Create a Logistic Regression model, fit it to the training data, make predictions with the testing data, and print the model's accuracy score. You may choose any starting settings you like.
#### Make and save testing predictions with the saved logistic regression model using the test data
#### Review the predictions
#### Calculate the accuracy score by evaluating `y_test` vs. `testing_predictions`.

## Create and Fit a Random Forest Classifier Model
#### Create a Random Forest Classifier model, fit it to the training data, make predictions with the testing data, and print the model's accuracy score. You may choose any starting settings you like.
####  Train a Random Forest Classifier model and print the model score
####  Make and save testing predictions with the saved logistic regression model using the test data
####  Review the predictions
####   Calculate the accuracy score by evaluating `y_test` vs. `testing_predictions`.

#### Evaluate the Models¶
#### Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the following markdown cell.

#### Which model performed better? (5 points) 
The Random Forest Classifier Model accuracy score is much more than the LogisRegression model
### How does that compare to your prediction? (5 points)
The Random Forest accuracy scire is 0.9582  while the 
Logisregression accuracy score is 0.9226 so Random Forest model is best for the 
above scaled data.
