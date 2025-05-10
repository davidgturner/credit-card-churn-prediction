# credit-card-churn-prediction
A predictive analytics project to identify at-risk credit card users and reduce churn using classification models and behavioral analysis.

Problem Statement and details

## Background & Context

Credit card churn is a significant challenge for financial institutions, as it directly impacts revenue streams from various fees such as annual fees, balance transfer fees, cash advance fees, and more. Understanding why customers discontinue their credit card services is crucial for improving customer retention and optimizing service offerings.

This project aims to provide a reusable and scalable solution for predicting credit card churn. By analyzing customer data, the goal is to identify at-risk users and uncover actionable insights to enhance customer satisfaction and reduce churn rates. The solution leverages classification models and behavioral analysis to help financial institutions make data-driven decisions and improve their services.

This aims to create a classification model that will help a bank improve its services so that customers do not renounce their credit cards

You need to identify the best possible model that will give the required performance
Objective
1.	Explore and visualize the dataset.
2.	Build a classification model to predict if the customer is going to churn or not
3.	Optimize the model using appropriate techniques
4.	Generate a set of insights and recommendations that will help the bank



Data Dictionary:
•	CLIENTNUM: Client number. Unique identifier for the customer holding the account
•	Attrition_Flag: Internal event (customer activity) variable - if the account is closed then "Attrited Customer" else "Existing Customer"
•	Customer_Age: Age in Years
•	Gender: Gender of the account holder
•	Dependent_count: Number of dependents
•	Education_Level:  Educational Qualification of the account holder - Graduate, High School, Unknown, Uneducated, College(refers to a college student), Post-Graduate, Doctorate.
•	Marital_Status: Marital Status of the account holder
•	Income_Category: Annual Income Category of the account holder
•	Card_Category: Type of Card
•	Months_on_book: Period of relationship with the bank
•	Total_Relationship_Count: Total no. of products held by the customer
•	Months_Inactive_12_mon: No. of months inactive in the last 12 months
•	Contacts_Count_12_mon: No. of Contacts between the customer and bank in the last 12 months
•	Credit_Limit: Credit Limit on the Credit Card
•	Total_Revolving_Bal: The balance that carries over from one month to the next is the revolving balance
•	Avg_Open_To_Buy: Open to Buy refers to the amount left on the credit card to use (Average of last 12 months)
•	Total_Trans_Amt: Total Transaction Amount (Last 12 months)
•	Total_Trans_Ct: Total Transaction Count (Last 12 months)
•	Total_Ct_Chng_Q4_Q1: Ratio of the total transaction count in 4th quarter and the total transaction count in 1st quarter
•	Total_Amt_Chng_Q4_Q1: Ratio of the total transaction amount in 4th quarter and the total transaction amount in 1st quarter
•	Avg_Utilization_Ratio: Represents how much of the available credit the customer spent


## Export notebook to a HTML file

``` cd .\credit-card-churn-prediction\ ```
``` jupyter nbconvert --execute --to html .\AML_Project_LearnerNotebook_FullCode.ipynb ```