# credit-risk-classification
For Bootcamp: TCC-VIRT-DATA-PT-10-2022-U-LOLC-MTTH

Module 20 Report

**Overview of the Analysis**

The purpose of this analysis is to build a logistic regression model to predict whether a loan is high-risk or healthy based on various factors, such as loan size, interest rate, borrower income, debt-to-income ratio, and more. This will help the company make informed decisions about which loans to approve or reject, thereby minimizing the risk of default.

**Results**

**Machine Learning Model 1:**

![image](https://user-images.githubusercontent.com/97980927/226203353-45be630a-b183-4f4d-a8f7-5c828764e359.png)

![image](https://user-images.githubusercontent.com/97980927/226202989-4232eba0-a5aa-49de-9cbd-91408d7355e5.png)

Balanced Accuracy: 
* 95%

Precision:
* Healthy Loan: 100%
* High-Risk: 85%

Recall:
* Healthy Loan: 99%
* High-Risk: 91%




**Machine Learning Model 2:**

![image](https://user-images.githubusercontent.com/97980927/226203386-cc1ec4bb-31d0-4704-abf1-17f8ef10d822.png)

![image](https://user-images.githubusercontent.com/97980927/226203049-29f029c9-bf81-4201-be14-8b0c53e21560.png)

Balanced Accuracy: 
* 99%

Precision:
* Healthy Loan: 100%
* High-Risk: 84%

Recall:
* Healthy Loan: 99%
* High-Risk: 99%

**Summary:**

Which one seems to perform best? How do you know it performs best?
* Model 2 seems best, but they both display high accuracy and precision so you can't really go wrong with either model of your choosing. For myself as an example, I would be using both models in this case to create a diversified set of results.


Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's? )
* It would depend on "who" is trying to solve the problem. If you are a large corporation or institution in charge of lending, then yes performance would depend on many of the problems you are trying to solve. And larger corporations/institutions have the budget to pay for better performance.
* But if you are a small, mom-and-pop shop with a lot smaller clientele list, then a simple performance dataset like this could help tremendously and way moreso than writing on paper or using simple Excel functions to predict lending trends of your customer base.
