# Phase 3 Project

Author: Nobert Akwir

## Project Overview

This project seeks to provide a classification model, based on SyriaTel Customer dataset, a tellecomunication company to predict whether a customer will ("soon") stop doing business with itself. We are interested in reducing how much money is lost because of customers who don't stick very long with the company.

### Business Problem

Churn rate, in its broadest sense, is a measure of the number of individuals or items moving out of a collective group over a specific period. It is most commonly exppressed as the percentage of service subscribers who discontinue their subscriptions within a given time period. A high churn rate could adversely affect profits and impede growth.

Churn rate is an important factor in the tellecommunications industry. The mobile Telecommunication industry is becoming more saturated, with more and more customers swapping their registered services between competing companies.The churn rate not only includes when customers switch carriers but also includes when customers terminate service without switching. This measurement is most valuable in subscriber-based businesses in which subscription fees comprise most of the revenues.

Therefore, companies like SyriaTel, have realized thet they should focus their marketing efforts on customer retention rather than customer acquisition. In fact, it is less profitable for providers to attract new customers than prevent current customers from quitting. Hence, providers are engaged more and more in building predictive models in order to identify which customers are most likely to leave or churn, so that they offer them promotions to persuade them to keep using their lines.

Churn prediction is a management science problem for which a machine learning approach can be adopted. Based on Historical data, a model can be trained to classify customers as future chunners or non-chunners. Research shows that customer's behavioural features such as calls duration, calls count, refill/bill amount etc. , are good predictiors of churn.



### Modelling

For our iterative approach of modelling, we apply a logistic regression model, tune it to try see which one of it will be best. First we use a base model where we only encode the categorical values, then we scale the numerical values for our second model and finally penalize our model using the Lasso method. We also apply a KNN classifier and a Naive Bayes model.

### Evaluation

We note that our three Logistic regression models perform the same and really poorly. The KNN Classifier performs slightly better than the Logistic Regression models and this is due to its acxuracy score and f1_score. The Naive Bayes Model has a slightly lower accuracy score than the KNN Classifier but a better f1_score indicating slightly higher values on the pecision and recall scores to. Therefore the Naive Bayes model is the best model to adopt going foward before other models are applied to our dataset.

## Recommendations

For future model building, the Telco company could provide more data.   
Other classification algorithms should be applied to try predict the churn rate since the one’ applied currently haven’t really performed very well.   
There should be more metadata on the data so as to help undertand each variable.

