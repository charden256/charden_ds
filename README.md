# 8oCFG7wRAydqWFCG
As a logistics and delivery company we are needing to find ways to meet and address challenges to our customers, especially during the COVID-19 pandemic. We are trying to make our customers happy and predict what will do it. The dataset provided has 126 records of customer feedback. We are conductiing a feedback survey with 6 metrics to predict what will make our customers happy, so we can choose to focus on those areas. 

The 6 categories are:
Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers
X1 = my order was delivered on time
X2 = contents of my order was as I expected
X3 = I ordered everything I wanted to order
X4 = I paid a good price for my order
X5 = I am satisfied with my courier
X6 = the app makes ordering easy for me 

To solve the problem lazy predict, logistic regression, and random forest were used. Choosing a good seed allowed for lazy predict to choose different methods with more accuracy. The goal was 73% accuracy, but the more accurate methods allowed for 85%. Several predicted methods showed 77%. SVM acheived 88%. The voting and stacking ensemble methods were used with the more accurate methods. 

To solve the problem, Random Forest was used to find the important features. The features 1, 3, and 4 are the important features that performed the best with 69% accuracy compared to the other three features which were 62% accuracy. In the test performed with the three important features used, there was a recall value of 1.00 on one of them.
Feature 1 = my order was delivered on time
Feature 3 = I ordered everything I wanted to order
Feature 4 = I paid a good price for my order
So the best course of action is to have a good price with everyhing ordered and on time.
