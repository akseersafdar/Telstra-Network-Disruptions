# Telstra-Network-Disruptions Challenge

Telstra is the largest Telecom Service Provider in Australia. They posted this challenge on kaggle.com few years ago as part of their recruitment exercise to hire potential data scientists.

In this challenge we are required to predict the fault severity i.e, if the fault is a normal glitch or it is critical and will result in total loss of service. As we know that Telecom Service Providers strive to provide the best possible service to customers and network outages are taken very seriously as they effect user experience and also impact the revenue.

We are given a training data where the fault_severity is already provided (labels). And we are required to predict the fault severity (ranging from 0 to 2) for the test data. Fault severity of 0 means no fault and 2 means critical (total loss of service).

# My Approach

I have done data cleaning/ pre-processing, Exploratory Data Analysis (EDA), Model building and then making predictions on test data.
Two models were tried (catboost and random forest). Catboost gave better results. Kaggle submission score has been uploaded to this repo.

# Kaggle link for this competition and my python notebook.

https://www.kaggle.com/c/telstra-recruiting-network/overview

https://www.kaggle.com/akseersafdar/telstra-nw-disruptions-using-catboost


