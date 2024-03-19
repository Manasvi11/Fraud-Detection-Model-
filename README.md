# Fraud-Detection-Model
Fraud Detection Model using Python 

1. Dataset from Kaggel
2. Algorithms - Decision Tree & Random Forest                              
3. Evaluation done using confusion matrix

# Results I got 
THE AUC for both Decision Tree and Random Forest is equal, so both models are pretty good at what they do.

In a fraud detection model, Precision is highly important because rather than predicting normal transactions correctly we want Fraud transactions to be predicted correctly and Legit to be left off.
If either of the 2 reasons are not fulfiiled we may catch the innocent and leave the culprit.
This is also one of the reason why Random Forest and Decision Tree are used unstead of other algorithms.
The reason I have chosen this model is because of highly unbalanced dataset and Random forest makes multiple decision trees which makes it easier for model to understand the data in a simpler way since Decision Tree makes decisions in a boolean way.


What are the key factors that predict fraudulent customer?

1. The source of request is secured or not

2. Is the name of organisation asking for money is legit or not

3. Transaction history.


What kind of prevention should be adopted while company update its infrastructure?

1. Browse through secured websites.

2. Use secured internet connections.

3. Don't respond to unsolicited calls/SMS/E-mails.

4. If you feel like you have been tricked or security compromised, contact your bank immidiately.


Assuming these actions have been implemented, how would you determine if they work?

1. Bank sending E-statements and keeping log of payments.

2. Customers keeping a check of their account activity.
