# Telecom Users Churn Machine Learning model

**This notebook looks into using Python-based Machine-learning and Data Science libraries in an attempt to build a machine learning model capable of identifying whether or not people will renew their contract.**

Any business wants to maximize the number of customers. To achieve this goal, it is important not only to try to attract new ones, but also to retain existing ones. Retaining a client will cost the company less than attracting a new one. In addition, a new client may be weakly interested in business services and it will be difficult to work with him, while old clients already have the necessary data on interaction with the service.

Accordingly, predicting the churn, we can react in time and try to keep the client who wants to leave. Based on the data about the services that the client uses, we can make him a special offer, trying to change his decision to leave the operator. This will make the task of retention easier to implement than the task of attracting new users, about which we do not know anything yet.

## 1. Problem Definition
**Statement :**
> The task is to analyze the data and predict the churn of users (to identify people who will and will not renew their contract).

### Churn : 

Churn is a measurement of the percentage of accounts that cancel or choose not to renew their subscriptions. Churn is the measure of how many customers stop using a product. This can be measured based on actual usage or failure to renew (when the product is sold using a subscription model).

## 2. Data

The data we are using comes from Kaggle: <br>
https://www.kaggle.com/radmirzosimov/telecom-users-dataset


## 3. Evaluation
> If we can reach maximum accuracy at predicting whether or not a patient will renew his subscrption.
 
## 4. Features

1. customerID - customer id
2. gender - client gender (male / female)
3. SeniorCitizen - is the client retired (1, 0)
4. Partner - is the client married (Yes, No)
5. tenure - how many months a person has been a client of the company
6. PhoneService - is the telephone service connected (Yes, No)
7. MultipleLines - are multiple phone lines connected (Yes, No, No phone service)
8. InternetService - client's Internet service provider (DSL, Fiber optic, No)
9. OnlineSecurity - is the online security service connected (Yes, No, No internet service)
10. OnlineBackup - is the online backup service activated (Yes, No, No internet service)
11. DeviceProtection - does the client have equipment insurance (Yes, No, No internet service)
12. TechSupport - is the technical support service connected (Yes, No, No internet service)
13. StreamingTV - is the streaming TV service connected (Yes, No, No internet service)
14. StreamingMovies - is the streaming cinema service activated (Yes, No, No internet service)
15. Contract - type of customer contract (Month-to-month, One year, Two year)
16. PaperlessBilling - whether the client uses paperless billing (Yes, No)
17. PaymentMethod - payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
18. MonthlyCharges - current monthly payment
19. TotalCharges - the total amount that the client paid for the services for the entire time
20. Churn - whether there was a churn (Yes or No)
 
The work should include the following ma*ndatory items:**

* Description of the data (with the calculation of basic statistics);
* Research of dependencies and formulation of hypotheses;
* Building models for predicting the outflow (with justification for the choice of a particular model) based on tested hypotheses and identified relationships
* Comparison of the quality of the obtained models.
