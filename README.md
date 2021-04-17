# Bank-Churn-Prediction
A neural network-based classifier that can determine whether Customers will leave bank or not in the next 6 months.
## Objective:
Given a Bank customer, build a neural network-based classifier that can determine whether they will leave or not in the next 6 months.

## Context: 
Businesses like banks that provide service have to worry about the problem of 'Churn' i.e. customers leaving and joining another service provider. It is important to understand which aspects of the service influence a customer's decision in this regard. Management can concentrate efforts on the improvement of service, keeping in mind these priorities.
Data Description: 
The case study is from an open-source dataset from Kaggle. The dataset contains 10,000 sample points with 14 distinct features such as CustomerId, CreditScore, Geography, Gender, Age, Tenure, Balance, etc.
Link to the Kaggle project site:https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling
### Data Dictionary:
- RowNumber: Row number.
- CustomerId: Unique identification key for different - customers.
- Surname: Surname of the customer
- Credit Score: Credit score is a measure of an individual's ability to pay back the borrowed amount. It is the numerical representation of their creditworthiness. A credit score is a 3-digit number that falls in the range of 300-900, 900 being the highest.
- Geography: The country to which the customer belongs.
- Gender: The gender of the customer.
- Age: Age of the customer.
- Tenure: The period of time a customer has been associated with the bank.
- Balance: The account balance (the amount of money deposited in the bank account) of the customer.
- NumOfProducts: How many accounts, bank account affiliated products the person has.
- HasCrCard: Does the customer have a credit card through the bank?
- IsActiveMember: Subjective, but for the concept
- EstimatedSalary: Estimated salary of the customer.
- Exited: Did they leave the bank after all?

## Neural Network Architecture

![alt text](https://github.com/mathewansu/Bank-Churn-Prediction/blob/main/network_architecture.PNG)

## Results and Conclusion

- Businesses like banks that provide service have to worry about the problem of 'Churn' i.e. customers leaving and joining another service provider.
- That is our model must learn all customers who are about to leave
- That is recall value should be high.
- Balancing recall and precision is one of the major problem with imbalanced data
- We were able to balance it or increase recall(maintaing precision) by using oversampling
- Weighted class also helped to improve recall
- But Oversampling performed better in this case as it gave better values for all metrics


![alt text](https://github.com/mathewansu/Bank-Churn-Prediction/blob/main/Confusion_Matrix.PNG)
