# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis is to build a logistic regression model to predict whether a loan is high-risk or healthy based on various factors, such as loan size, interest rate, borrower income, debt-to-income ratio, and more. This will help the company make informed decisions about which loans to approve or reject, thereby minimizing the risk of default.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

![image](https://user-images.githubusercontent.com/97980927/226200816-bd728eef-df4b-468f-bfc9-832c616a0d3b.png)


Balanced Accuracy: 95%

Precision:
* Healthy Loan: 100%
* High-Risk: 85%

Recall: 
* Healthy Loan: 99%
* High-Risk: 91%


* Machine Learning Model 2:

![image](https://user-images.githubusercontent.com/97980927/226200832-b94a312d-be4a-4672-a8db-c75d17b003de.png)

Balanced Accuracy: 99%

Precision:
* Healthy Loan: 100%
* High-Risk: 84%

Recall:
* Healthy Loan: 99%
* High-Risk: 99%


## Summary

Which one seems to perform best? How do you know it performs best? 
* Model 2 seems best, but they both display high accuracy and precision so you can't really go wrong with either model of your choosing. For myself as an example, I would be using both models in this case to create a diversified set of results.


Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) 
* It would depend on "who" is trying to solve the problem. If you are a large corporation or institution in charge of lending, then yes performance would depend on many of the problems you are trying to solve. And larger corporations/institutions have the budget to pay for better performance. 
* But if you are a small, mom-and-pop shop with a lot smaller clientele list then a simple performance dataset like this could help tremendously and way moreso than writing on paper or using simple Excel functions.
