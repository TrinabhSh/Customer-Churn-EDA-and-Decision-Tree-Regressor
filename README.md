# # Customer Churn Prediction

![3 SaaS Churn Calculations Everyone Needs to Learn and Use](https://d2mkz4zdclmlek.cloudfront.net/images/articles/what-is-customer-churn.png)

Technological advance has deeply changed the way customers and companies interact.

Currently, it is possible to predict the possible churn rate of a customer and, thus, define better business strategies.

Churn is a metric that indicates the percentage of customers who canceled a given service in a given period of time. It has become very popular in the last few years among all sorts of companies, specially those with recurrent income.

This project covers the EDA of the **Bank Customers Churn Dataset** through which I suggested the business how to reduce churn by observing the insights i got from the analysis. After the EDA I have also fitted a Decision Tree Classifier which will predict weather the customer churn is "Yes" or "No".

## Overview
![Bank-exit GIFs - Get the best GIF on GIPHY](https://media3.giphy.com/media/3o6Ztm0VpFKWc5YSUE/giphy.gif)

1. This dataset pertains to a bank, its customers and their banking habits. Some background information is given about the customers such as their age, gender, country and income, which may be used by the bank to better understand their customers.

2. From the banks point of view, details haven been mentioned about the their transactional habits such as the time members have been active, their salary and their churn status.

# Who can use this dataset?

1. Any bank manager who wants to understand the behaviour of their customers and better their services in general.

2. Some of the visualisations depicted in this project may be used to deduce some key insights and may beget some eureka moments.

3. Any bank teller who want to present his boss with some valuable insights may refer this project.


# About the Dataset

So far we can see that this dataset is consistent and "ready to go". We have 10.000 entries and 12 columns, including the target variable. There are no missing values, nor duplicate rows.

## We will structure the code as follows

1.  Loading the data
    
2.  Preparing the data
    
3.  Exploratory Data Analysis
    
4.  Building the model and accuracy analysis
    
5.  Final Analysis of the model

# Insights
![Insights](https://www.europeandepositarybank.com/media/ekndplcb/digital-banking_1220x593.jpg?anchor=center&mode=crop&width=520&rnd=132730755939300000)
- Half of the customers are from France. The other half is equally divided between Spain and Germany. Gender shows a slight predominance of males. 
-  churn rate in Germany is the highest among countries. 
- Every 5 out 1 Customer has been Churned
-   Men are 10% higher then female
-   Churn rate is high in female, every 4 out of 1 female churned (need to focus more on female customers)
-   Where in male customers every 6 out of 1 male customer churned.
-   Around 50% total customers belong to France and rest 25%-25%
- Estimated salary of customers lies between 0 to 2,00,000 with count of most less than 500.
- There are some outlier scores below 400 score.
- Around half the customers are non active members.
- Count of customers with tenure of 1 and 10 are the least in number.
- Most Customers have a tenure of 2 years.

 - Those who are using product 1 are almost 28% churned. Those who are using product 2 have 7.5% customers churned. Those who are using product 3 are 83% churned, (need to focus on this product or stop giving this product to customers) and lastly 100% customer are churned who were using product 4, means not a single person is interested in this product.

-   as suggestion bank should improve product number 3 and 4, as very few customers are interested in it.

# FIN










