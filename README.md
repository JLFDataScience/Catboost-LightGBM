<img src="https://storage.googleapis.com/kaggle-organizations/141/thumbnail.jpg?r=890" alt="Kitten" title="Santander Bank"
width="100" height="100" align="left"/>
<img src="https://miro.medium.com/max/837/1*Ab299OETAeuTEiGg5TwpMQ.png" alt="Kitten" title="Santander Bank"
width="150" align="center"/>
# Santander Customer Transaction Prediction  
### Comparison & Performance new generation of GBDT´s prediction model
##### Introduction  

Getting data from a Kaggle's competition, let's compare the performance between classic and new  generation of gradient boosting decision trees (GBDTs).

Reference: https://www.kaggle.com/c/santander-customer-transaction-prediction

In this competition proposed by **Santander Bank**, invites Kaggle users to predict which customers will make a specific transaction in the future💳, regardless of the amount of money made. The data provided for this contest has the same structure as the actual data they have available to solve the problem in the bank, which makes us address a real problem with a demanding dataset by number of records and characteristics, by which will test the performance of classic algorithms versus next-generation algorithms.

The data is anonymised, where each row contains 200 discrete variables and no categorical variables📈.

Next we'll do a data exploration, readiness to apply the model, and analyze which algorithms get the best performance with low overfitting and compare the results between them.

### Content🔍
1. Libraries
2. Data extraction
3. Data exploration
4. Unbalanced Data and Resampling
5. Feature selection
6. Binary classification models
7. Hyperparameter optimization
8. Detection of the most influential variables
