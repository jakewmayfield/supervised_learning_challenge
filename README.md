# Supervised Learning Challenge - Credit Risk Predictor
In this assignment, I build two machine learning models (Logistic Regression & Random Forest Classifier) that attempts to predict whether a loan from LendingClub will be high risk or not. 

## Background
LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

## Process
I use an entire year's worth of data (2019) to predict the credit risk of loans from the first quarter of the next year (2020).

## Predictions & Final Thoughts
I predicted that RF would be the best overall model given the noisiness of the data.  Before the data was scaled, this proved true. 

Surprisingly, LR had the best final model, after the data was scaled.  RF remained mostly unchanged by the data being scaled, which matches initial prediction that it handles noise well.  Where it performed differently, was less noise did not translate to a better score.

---

In this scenario, I would use LR with a scaled data set as it provided the highest accuracy with a test score of .72, meaning that nearly 3 out of 4 loan requests are correctly classified with the right risk score, an acceptable measure that rules out human emotion in deciding whether or not to give a loan.


