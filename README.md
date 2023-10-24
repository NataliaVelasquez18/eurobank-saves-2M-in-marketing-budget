# Eurobank Saves 2M+ in Marketingn Budget with Machine Learning

---

## Business Problem

The European Bank uses telemarketing campaigns to promote their product Bank Term Deposit.  It currently uses a predictive model to help them determine, in advance, clients who will be receptive to such marketing campaigns.  The bank wants to evaluate the current model, it's implications, and determine **whether or not the current model should be replaced**.

---

## Executive Summary

* By replacing the current model the bank will reduce by 68% of the current marketing efforts invested in phone marketing campaigns that represent $2.2 M

* The new predictive model can help the bank to enhance the customer experience by saving  27,250 of the current clients receiving unwanted calls compared to the current model

* Monday and Friday are the least ideal days of the week to generate client conversions compared to the rest of the weekdays.  The best days for contacting clients were Thursday, Tuesday, and Wednesday respectively

* Clients who have converted in previous marketing campaigns might be significantly more receptive to a new marketing campaign

---

## Backgroung

The European Bank uses telemarketing campaigns to promote their product Bank Term Deposit. The campaign has two possible outcomes: **either the client will subscribe or will not subscribe to the campaign**.

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/1.png" width="550" height="550" />

#### Need to segment the database

The challenges of a telemarketing campaign are three: 
  
  * There are limited resources in the contact center when comparing against the client database.
  * The campaign should be deployed in maximum of two months.
  * We need to make sure the client experience does not suffer whe calling over the phone.

The solution is to build a machine learning model that segments the database, takes client attribuetes and helps us predict the **propensity of a client to subscribe to a telemarketing campaign**.

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/2.png" width="350" height="580" />

---

## Overview of Approach

* This [Python file](https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/EDA_Machine_Learning.ipynb) contains a complete analysis and visualization of [The Eurobank dataset](https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/DSA_Data_Set.csv).

1. Exploratory Data Analysis, Statistical Analysis, and Data Cleanse (Pandas, Seaborn, Matplotlib)
2. Create New Predictive Models (scikit-learn, Logistic Regression, used resampling techniques to solve class imbalance)
3. Chose the best performing model according to the metrics (accuracy score, f1-score)
4. Naive Random Oversampling technique gave us the best performing model
5. Recommend whether or not Eurobank should change the current model

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/3.png" width="510" height="300" />

---

## Analysis

#### The current model 
Suggested to contact 98% of the database suggesting almost no **segmentation**.

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/current_model.png" width="450" height="350" />

Out of this 98% of clients contacted, only 11% actyally subscribed.

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/actuals.png" width="450" height="350" />

#### The new model: segments the database
* Addresses the customer experience because it is only suggesting to contact 30% of the clients in the database
* Reduces the bank’s efforts invested in marketing campaigns because the number of calls is reduced by a large amount
* Reduces the opportunity cost of investing too many resources in a given campaign and allows agility in the execution

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/new_model.png" width="450" height="350" />

#### Current vs new model

As we can see the new model proposes a more segmented approach.  It only suggests to contact 30% of the database vs 98% of the current model.  This has huge business implications for the large amount of resources it can save Eurobank in the long run.

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/currentvsnew.png" width="700" height="350" />

#### Accuracy

*New model advantage: It is more efficient and more accurate at predicting a conversion=YES

* NEW model disadvantage: It achieves 719 less client conversions

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/accuracy.png" width="700" height="350" />


#### Client experience

New model advantage: Balances in between achieving results and preserving the customer experience

<img src= "https://github.com/NataliaVelasquez18/eurobank-saves-2M-in-marketing-budget/blob/main/Resources/savedunwantedcall.png" width="700" height="280" />

---

## Conclusions:

* There is a trade-off between customer conversions, the customer experience, and cost savings 

* The current model generates  719 more conversions but it also generates 27,250 of our clients unnecessarily contacted affecting the customer experience and increasing cost

* The new model proposes a more segmented and efficient approach for our marketing campaigns. We can reduce by 68% our efforts and reduce cost, increase our customer experience, and reduce opportunity costs.

---

## Recommendations:

* Prioritize the customer experience and either enhance the current model or replace it by our model that does a better job in predicting clients who will not convert

* Analyze contact center costs and determine the cost savings by having 68% less effort invested from our team in phone marketing campaigns

* Compare the cost reduction generated by less effort against the extra revenue generated by the 719 extra conversions that generates the current model

* Perform a customer survey to measure the perception of the banks’s brand and the customer’s experience when contacted for marketing purposes

* Performing the majority of client calls during Tuesdays, Wednesdays, and Thursdays respectively. Avoid Mondays and Fridays.

* Prioritize calling clients who subscribed past marketing campaigns in order to increase conversions

* Investigate outliers and unknown data and its causes and explore the possibility of replacing them

---

## Author

Natalia Velasquez

