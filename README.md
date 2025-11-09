 The dataset used for this project is a customer churn dataset that was downloaded from Kaggle. 
It focuses on understanding customer behaviour and identifying patterns that lead to customer 
churn, which refers to customers discontinuing a company’s service or subscription. The dataset 
simulates data from a subscription-based service and is designed to help data analysts and 
machine learning practitioners build predictive models that can classify whether a customer is 
likely to leave or stay. It is part of a collection of openly available datasets on Kaggle intended for 
churn analysis and customer retention modelling.
 The dataset contains 64,374 customer records and 12 features. Each record represents a unique 
customer identified by a CustomerID. The variables can be grouped into demographic, 
behavioural, and account-related attributes. The demographic features include Age and Gender. 
The behavioural and service-related features include Usage Frequency, Support Calls, Payment 
Delay, and Last Interaction, which together provide insights into how customers interact with 
the service. Account-related features include Subscription Type, Contract Length, Total Spend, 
and Tenure (the length of time the customer has been subscribed). The target variable, Churn, 
indicates whether a customer has left the service (1) or remained (0).
 The dataset has no missing values across any of its columns, which makes it complete and ready 
for analysis. All numerical features, such as Age, Tenure, Usage Frequency, and Total Spend, are 
already in integer format, which simplifies preprocessing and feature engineering. Categorical 
features like Gender, Subscription Type, and Contract Length are stored as text and would 
require encoding before being used in machine learning models. The absence of missing data 
and the balanced structure of both categorical and numerical variables indicate good data 
quality.
 In terms of accuracy and reliability, while this dataset is synthetic and does not represent real 
customers from a specific company, it has been designed to closely mimic real-world churn 
behaviour. The distributions of features such as Age, Tenure, and Spend appear realistic, and the 
inclusion of customer activity metrics like support calls and payment delays makes the dataset 
suitable for advanced churn prediction and retention strategy analysis. The data quality is high, 
with consistent entries, appropriate ranges for numeric values, and no evident outliers or errors.
Overall, this dataset is well-structured, clean, and suitable for churn analysis. It provides a good 
balance between complexity and usability, allowing meaningful insights into customer retention 
trends. It can be combined with similar datasets for comparative studies or used independently 
for end-to-end machine learning pipelines that involve data cleaning, feature selection, model 
training, and performance evaluation.
