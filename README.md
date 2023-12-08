In this challenge, your objective is to employ diverse techniques to train and assess a model focused on evaluating loan risk. Utilizing a dataset derived from historical lending activity from a peer-to-peer lending services company, the goal is to construct a model capable of discerning the creditworthiness of borrowers.

The instructions for this challenge are segmented into the subsequent sections:

Data Splitting:
Open the provided starter code notebook.
Read the 'lending_data.csv' data from the Resources folder into a Pandas DataFrame.
Construct the labels set (y) from the “loan_status” column and create the features (X) DataFrame from the remaining columns.
Employ the train_test_split function to divide the data into training and testing datasets.
Logistic Regression Model:
Leverage your understanding of logistic regression to execute the following steps:
Fit a logistic regression model using the training data (X_train and y_train).
Save predictions for the testing data labels by utilizing the testing feature data (X_test) and the fitted model.
Evaluate the model's performance by:
Generating a confusion matrix.
Printing the classification report.
Address the question: How effectively does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Credit Risk Analysis Report:
Draft a concise report encapsulating a summary and analysis of the machine learning models used in this task. This report should be presented as the README.md file within your GitHub repository.
Organize your report using the provided report template in 'Starter_Code.zip,' ensuring it covers the following:
Overview of the Analysis:
Clarify the purpose of the analysis.
Results:
Describe the accuracy score, precision score, and recall score of the machine learning model in a bulleted format.
Summary:
Summarize the findings from the machine learning model.
Provide justification for recommending or not recommending the model for use by the company. If not recommended, elucidate the reasoning behind this decision.
