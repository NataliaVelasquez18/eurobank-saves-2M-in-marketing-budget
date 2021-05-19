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

* By replacing the current model the bank might liberate about 70% of the contact center resources while maintaining a similar conversion rate

* The new predictive model can help the bank to maintain the customer experience by avoiding  27,244 of the current clients receiving unwanted calls

* Mondays was the least ideal day of the week to generate client conversions compared to the rest of the weekdays.  The best days for contacting clients were Thursday, Tuesday, and Wednesday respectively.

* Clients who have converted in previous marketing campaigns might be significantly more receptive to a new marketing campaign 

---

## Conclusions:

* There is a trade-off between client conversions, the customer experience, and cost savings 

* The current model generates  719 more conversions but it also generates that 27,244 of our clients might receive unwanted calls affecting the customer experience

* The new model proposes a more efficient approach.  Approximately 70% of the contact center resources might be liberated to execute other campaigns


---

## Recommendations:

* Prioritize the customer experience and either enhance the current model or replace it by another model that does a better job in predicting client conversions

* Analyze contact center costs and determine the cost savings with the current model

* Performing the majority of client calls during Tuesdays, Wednesdays, and Thursdays. Avoid Mondays.

* Prioritize calling clients who subscribed in past marketing campaigns in order to increase conversions

* Investigate outliers and unknown data its causes and explore the possibility of replacing them


---

## Author

Natalia Velasquez

