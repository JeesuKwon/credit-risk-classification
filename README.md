# credit-risk-classification

![image](https://github.com/JeesuKwon/credit-risk-classification/assets/157546001/b57e32bd-db5d-4793-bc71-b66a20419dc1)


# Background

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers


# Instructions


The instructions for this Challenge are divided into the following subsections:

* Split the Data into Training and Testing Sets
* Create a Logistic Regression Model with the Original Data
* Write a Credit Risk Analysis Report



**[Split the Data into Training and Testing Sets]**


Open the starter code notebook and use it to complete the following steps:

1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.



**[Create a Logistic Regression Model with the Original Data]**


Use your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
   * Generate a confusion matrix.
   * Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?



**[Write a Credit Risk Analysis Report]**


Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

1. An overview of the analysis: Explain the purpose of this analysis.
2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


# Results
* Overall Accuracy : 99%
* Healthy Loan
  - Precision : 100%
  - Recall : 100%
  - F1-score : 100%
* High-rist Loan
  - Precision : 87%
  - Recall : 89%
  - F1-score : 88%


# Summary
The logistic regression model predicts a healthy, low-risk loan with 100% precision. It predicts a high-risk loan with lower precision at 87% because it is imbalanced dataset with only 625 supports which is much smaller than dataset for 0 with 18759 supports. The balanced accuracy of the model is 99%.
