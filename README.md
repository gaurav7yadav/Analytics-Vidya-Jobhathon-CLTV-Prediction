# Analytics-Vidya-Jobhathon-CLTV-Prediction
It was a Jobhackathon in which we were asked to predict Customer life time value for identifying most potential customer for an insurance company.


### Problem Statement

VahanBima is one of the leading insurance companies in India. It provides motor vehicle insurances at best prices with 24/7 claim settlement. It offers different types of policies for both personal and commercial vehicles. It has established its brand across different regions in India.

Around 90% of the businesses today use personalized services. The company wants to launch different personalized experience programs for customers of VahanBima. The personalized experience can be dedicated resources for claim settlement, different kinds of services at doorstep, etc. Inorder to do so, they would like to segment the customers into different tiers based on their customer lifetime value (CLTV).

Inorder to do it, they would like to predict the customer lifetime value based on the activity and interaction of the customer with the platform. So, as a part of this challenge, your task at hand is to build a high performance and interpretable machine learning model to predict the CLTV based on the user and policy data.

### About the Dataset

We are provided with the sample dataset of the company holding the information of customers and policy such as highest qualification of the user, total income earned by a customer in a year, employee status, policy opted by the user, type of policy and so on and the target variable indicating the total customer lifetime value.

### Data
You are provided with 3 files - train.csv, test.csv and sample_submission.csv

##### Train Set
You are provided with around 90K records containing the attributes of the user and policy and the target variable cltv indicating the total customer lifetime value.
##### Test Set
You are provided with around 60K records containing only the attributes of the user and policy and you need to predict the target variable cltv indicating the total customer lifetime value.
##### Submission File Format
The solution file must contain the format similar to that of sample submission. sample_submission.csv contains 2 variables - id and cltv.

### Evaluation metric
The evaluation metric for this hackathon would be r2_score.
