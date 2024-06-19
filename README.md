# CSCI316-Individual-Assignment-1

**Task 1**

Data set: Customer Churn Dataset
https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset

Customer churn refers to the phenomenon where customers discontinue their relationship or subscription with
a company or service provider. It represents the rate at which customers stop using a company's products or
services within a specific period. Churn is an important metric for businesses as it directly impacts revenue,
growth, and customer retention.

In the context of the Churn dataset, the churn label indicates whether a customer has churned or not. A churned
customer is one who has decided to discontinue their subscription or usage of the company's services. On the
other hand, a non-churned customer is one who continues to remain engaged and retains their relationship with
the company.

Understanding customer churn is crucial for businesses to identify patterns, factors, and indicators that
contribute to customer attrition. By analysing churn behaviour and its associated features, companies can
develop strategies to retain existing customers, improve customer satisfaction, and reduce customer turnover.
Predictive modelling techniques can also be applied to forecast and proactively address potential churn,
enabling companies to take proactive measures to retain at-risk customers.
Objective

Use Pandas in Python to clean and pre-process this dataset. You cannot use any ML library (including Sci-kit
Learn) for this task.

Requirements
1) Create one Pandas dataframe for both the training and test data.
2) Identify the missing values. Propose a method to clean the missing values.
The following steps are performed based on the cleaned data.
3) Perform z-score normalization of the values in the attribute “Last Interaction”. Show the mean and
variance of the normalized values.
4) Create five bins for the attribute “Total Spend” such that the bins contain (approximately) equivalent
numbers of records.
5) Apply one-hot-encoding to the attribute “Contract Length”.
6) Define at least one new attribute based on existing attribute, and explain your reason behind your
definition.

For the requirements (2) – (5), append the new columns to the existing Pandas dataframe.

**Task 2**

Data set: Customer Churn Dataset
https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset

Objective
The objective of this task is to implement from scratch a Decision Tree classifier to predict the churn label.
You cannot use any ML library for this task.

Requirements
1) Implement three DT models by the split criteria of Information Gain, Gain Ratio and Gini Index. You
can use either binary-split or multiple-split.
2) It is recommended that your implementation includes a “tree induction function”, a “classification
function” and other functions (which are up to you).
3) After implementing the three DT models, use a simple ensemble method to build a new classifier. This
new classifier just utilises a voting function on the prediction outcomes of the three DT models.
4) Present clear and accurate explanation of your implementation and results in text. In particular, report
the accuracy of the models, and report whether an improvement the ensemble method can achieve.
5) Note. You can (but not must) use any suitable pre-processing method. You also can (but not must) use
any reasonable early stopping criteria (pre-pruned parameters such as number of splits, minimum data
set size, and split threshold) to improve the training speed. If you do so, you must explain the criteria
clearly.
