# Predicting Client Conversions with Scikit-learn


---

## Business Problem

The European Bank uses telemarketing campaigns to promote their product Bank Term Deposit.  It currently uses a predictive model to help them determine, in advance, clients who will be receptive to such marketing campaigns.  The bank wants to evaluate the current model, it's implications, and determine whether or not the current model should be replaced.

---


## Purpose


The purpose of this analysis is to help The European Bank to increase efficiency, enhance the customer experience, and reduce costs when executing phone marketing capaigns.

---

## Overview of Approach

1. Exploratory Data Analysis, Statistical Analysis, and Data Cleanse (Pandas, Seaborn, Matplotlib)
2. Create New Predictive Models (scikit-learn, Logistic Regression, used resampling techniques to solve class imbalance)
3. Chose the best performing model according to the metrics (accuracy score, f1-score)
4. Naive Random Oversampling technique gave us the best performing model


---

## Executive Summary:

* There is a trade-off between client conversions, cost reduction, and the customer experience

* Even though the current predictive model gets 719 more client conversions it might impact  significantly the contact center costs and the customer experience

* By replacing the current model the bank might reduce the contact center’s resources by ~70%

* The new predictive model can help the bank to enhance the customer experience by avoiding  27,244 of our clients receiving unwanted calls

* Mondays is the least ideal day of the week to generate client conversions.  The best days of the week are Thursday, Tuesday, and Wednesday respectively

* Clients who converted in previous marketing campaigns showed a great rate of conversion for the current campaign

---

## Conclusions:

* There is a trade-off between client conversions, the customer experience, and cost savings 

* The current model generates  719 more conversions but it also generates that 27,244 of our clients might receive unwanted calls affecting the customer experience

* The new model proposes a more efficient approach of utilizing the resources of the contact center and might reduce cost by 70%

---

## Recommendations:

* Prioritize the customer experience and either enhance the current model or replace it by another model that does a better job in predicting client conversions

* Analyze contact center costs and determine the cost savings with the current model

* Performing the majority of client calls during Tuesdays, Wednesdays, and Thursdays. Avoid Mondays.

* Prioritize calling clients who subscribed in past marketing campaigns in order to increase conversions

* Investigate outliers and its causes and explore the possibility of removing them

* Research unknown data and the option of replacing it


---

## Author

Natalia Velasquez

