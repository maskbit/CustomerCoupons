# Customer Coupon Acceptance - Data Analysis


## Overview

In this data analysis, the problem is to seek the answer to the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

## Data

This data is from  UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

## Notebook

Data was analyzed using pandas dataframes and visualized using seaborn. Notebook reference  [Here](https://github.com/maskbit/CustomerCoupons/blob/main/notebook/prompt.ipynb)

## Analysis and Observations of Bar Coupon users

To narrow down and focus on a particular segment, bar coupons were analyzed more detailed. Here are the observation

Criteria     | Acceptance Rate
-------- | -----
Went to bar more than once and are over 25 years of age | 0.14532148457919497
Went to bar more than once and had passengers that were not a kid and had occupations other than farming, fishing or forestry | 0.0705697856769472
Went to bars more than once a month, had passengers that were not a kid, and were not widowed| 0.0705697856769472
Went to bars more than once a month and are under the age of 30| 0.12336644014636697

Criteria     | Acceptance Rate
-------- | -----
Number of individuals who go to cheap restaurants more than 4 times a month and income is less than 50K | 0.07945635128071092


## Additional Analysis and Observations of Coffee House users
 

Criteria     | Acceptance Rate
-------- | -----
Number of individuals who go to CoffeeHouse more than once a month and age less than 25 | 0.098
Number of individuals who go to CoffeeHouse more than once a month and age more than 25    | 0.22


Younger generation (less than 25) coffee drinkers tend to go to coffee house and use the coupon more than individuals who are above age 25.
