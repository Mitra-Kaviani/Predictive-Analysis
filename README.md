Propensity to Churn Modeling
Introduction

The Propensity to Churn Modeling is a machine learning technique used to predict whether a customer is likely to churn (i.e. cancel or stop using) a service or product. In this analysis, a Random Forest algorithm was used to build a predictive model that estimates the likelihood of a customer to leave in the next period of time.
Data Description

The dataset used for this analysis includes a number of variables related to customers of a certain service, such as age, gender, account age, monthly charges, contract type, and others. The target variable is a binary variable indicating whether a customer has churned or not.
Model Building

To improve the performance of the model, hyperparameters tuning was performed using GridSearchCV and RandomizedSearchCV techniques to find the optimal values for hyperparameters such as the number of trees, the depth of the trees, the minimum number of samples required to split a node, and the number of features to consider when splitting a node.

The best performing model was trained with the optimal hyperparameters, which resulted in a high accuracy of 0.9 and an ROC value of 0.89.
Outputs

The model outputs include a predicted churn value by Machine learning algorithm, propensity to churn, and rank of propensity to churn for each user/customer. The rank is calculated based on deciles of the propensity score.
Conclusion

The Propensity to Churn Modeling is a powerful technique to predict customer churn, which can help businesses to take proactive measures to retain customers. The Random Forest algorithm, when optimized using hyperparameters tuning, can provide high accuracy and reliable predictions.
