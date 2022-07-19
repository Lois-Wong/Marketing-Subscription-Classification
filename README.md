# Marketing-Subscription-Classification

## Project Description

Data Overview: Our dataset comes from the UCI Machine Learning repository link. The data is from a Portugese banking institution and is a collection of the results of multiple direct marketing campaigns. We will make use of the article accompanying the dataset here for more information on the data and features. In the 17 telephone marketing campaigns that took place between May 2008 - November 2010, 79354 contacts were made with the objective of subscribing clients to a bank term deposit. Clients were offered a long-term deposit with interest, and a success rate of 0.08 was observed in the entire database.

Business Objective: The goal of this project is to effectively predict whether an individual will subscribe to a bank term deposit or not, in order that marketing resources can be better distributed amongst and targeted towards clients more likely to subscribe.

Data Problem: The data task is to fit and tune multiple classification models that group individuals into subscribers vs non-subscribers. Models with high accuracy and/or recall can be used to predict the subscription status of unseen clients. Additionally, fitting regression model(s) that can be further scrutinzed for the most important features and feature values that characterize each of the two groups will indicate the profile of a subscribing client. These features will used for selecting the clients on whom resources should be focused.

## Motivation

This project is completed to fulfill part of the requirements of UC Berkeley's Professional Certificate in Machine Learning and Artificial Intelligence.

## Findings

The five most important features for predicting the subscription status of a client are the number of employees, number of days since the most recent contact, marital status, loan status, and education. In essence, a lower number of employees is correlated with a client's subscription (5099 employees has the highest subscriptions count). Clients most recently contacted 3-6 days largely accepted the subscription. Additionally, subscribers tend to be married or single, while divorced individuals are not likely to subscribe. Subscribers do not tend to have a personal loan taken out, while nonsubscribers are more likely to have either an unknown or positive loan status. Finally, the greatest proportion of subscribers has the education levels of university degree, high school, and professional course, while the lowest proportion of subscribers has the education levels of basic 9y, basic 6y, and basic 4y.

## Next Steps and Recommendations 

Because the number of employees is negatively correlated with subscribers, it is recommended that the employee count be brought towards and kept from exceeding 5,100.
Clients that have not been previously contacted do not tend to subscribe, while the majority of subscribing clients have been previously contacted 3-6 times, so multiple (at least 3, aim for 6) calls made to the same individual is highly recommended.
An overwhelming majority of divorced clients turned down the subscription offer, so employees should not target divorced individuals.
Employees should instead prioritize clients that are married or single.
Unsubscribers have a higher proportion of individuals with a personal loan, while clients without a personal loan have a higher proportion of subscribers. As a result, employees should focus on targetting individuals who do not have a personal loan.
Employees should not target individuals of basic 9y, basic 6y, or basic 4y education levels because these groups constitute the lowet proportions of subscribers.
Instead, Employes should target customers of the university degree, high school, and professional course education levels.

## Access
Link to Notebook
Part I: http://localhost:8889/lab/tree/Downloads/ML%20ipynb/Module%2017/PAA_III.ipynb

Part II: http://localhost:8889/lab/tree/Downloads/ML%20ipynb/Module%2017/PAA_III_Evaluation.ipynb

Link to Download 
Part I: http://localhost:8889/files/Downloads/ML%20ipynb/Module%2017/PAA_III.ipynb?_xsrf=2%7Cd32439ba%7C55e5dd9e25bdcda3e88c89bdae88d2dd%7C1656697969

Part II: http://localhost:8889/files/Downloads/ML%20ipynb/Module%2017/PAA_III_Evaluation.ipynb?_xsrf=2%7Cd32439ba%7C55e5dd9e25bdcda3e88c89bdae88d2dd%7C1656697969
