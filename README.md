# CAPSTONE PROJECT
# Customer Churn Prediction 

## Problem Statement

A DTH (Direct to Home) service provider in the market is facing challenges to retain existing customers since there is heavy competition in the current situation. In this company, one account can have multiple customers tagged to it. Hence, by losing one account, the company may lose more than one customer. As a result, account churn is a major problem that the company should focus on at present.

## Objective

- Build a prediction model to identify the customers who will potentially churn
- Provide insights to the company to minimize the churn
- Provide recommendations to the company on segmented offers to better market and service the potential churners

## Contents of the dataset

- The data provided is of various customers of the DTH service provider including their personal information, financial attributes and customer interaction data. 
- The dataset consists of 11260 rows and 19 columns, with 'Churn' being the target variable

### Data Description

- AccountID : account unique identifier
- Churn : account churn flag (Target) (0:No, 1:Yes) 
- Tenure : Tenure of account (in months)
- City_Tier : Tier of primary customer's city (Tier1 > Tier2 > Tier3)
- CC_Contacted_LY : Number of times all the customers of the account has contacted the customer care in the last 12 months
- Payment : Preferred payment mode of the customers in the account
- Gender : Gender of the primary customer of the account
- Service_Score : Satisfaction score given by customers of the account on the service provided by company
- Account_user_count : Number of customers tagged with this account
- account_segment :  Account segmentation on the basis of spend. These are the packages provided by the company based on the spending of the customers
- CC_Agent_Score : Satisfaction score given by customers of the account on customer care service provided by company
- Marital_Status : Marital status of the primary customer of the account
- rev_per_month : Monthly average revenue generated by account in the last 12 months (in thousands of INR)
- Complain_ly : Any complaints has been raised by the account in the last 12 months (0:No, 1:Yes)
- rev_growth_yoy : Revenue growth percentage of the account in the last 12 months vs the last 24-13 months for the account. It basically indicates how profitable the account has been to the company over the last year compared to its previous year
- coupon_used_for_payment : How many times customers have used coupons to do the payment in the last 12 months
- Day_Since_CC_connect : Number of days since no customers in the account has contacted the customer care
- cashback : Monthly average cashback generated by account in the last 12 months in INR
- Login_device : Preferred login device of the customers in the account
