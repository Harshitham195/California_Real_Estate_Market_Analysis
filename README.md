# Customer_churn_prediction

**Background:** 
The telecommunication industry is facing a critical challenge in drawing customers and facing customer churn. Since subscribers are switching between various service providers, it has turned out to be an essential element for telecom companies to proactively identify and address factors that lead to customer weakening. 

**Problem Statement:**
The project aims to examine customer churn within a telecommunication company (Telco Systems). Studying customer churn determines if changes are within or beyond the company’s control. This helps in understanding the reasons for customer departures.

**DataSet:** [Customer Churn Dataset](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset/data)

**Key Attributes:**
Churn value - This indicates whether customers have resigned their service within the last month where the value ‘Yes’- means the customers are leaving , ‘No’ means customers are not leaving.

Senior Citizen, Dependents- This indicates demographic and beneficiary details of customers.

Phone service, Internet Service, Online Security, Tech Support - This indicates the services that each customer has been tied to.

**Methods:**
The project involves customer churn prediction in the telecommunication sector using telco customer data. Initial data preprocessing includes Exploratory Data Analysis (EDA) for understanding data structure and handling missing values.
Categorical variables are converted to numerical format, and outliers are addressed. A decision tree classification model is implemented, followed by ensemble methods like Random Forests and Gradient Boosting for enhanced accuracy. 
Model evaluation, using confusion matrices on a validation dataset, guides strategy derivation based on decision tree rules.

**Expected Outcome:**
By developing this model, we can predict which customers are at risk of churning based on their satisfaction level, enabling providers to develop targeted marketing strategies and attractive discount offers to retain these valuable customers.
