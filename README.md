# Credit Card Customer Churn Prediction
<img align="right" width="275" height="275" src="https://github.com/user-attachments/assets/aef45ddd-c8fc-4de0-9c28-591437160c40" />

A predictive model to identify the likelihood existing credit card customers will churn.

A range of available customer history features were utilized to train and test a variety of models.

The final CatBoost Classifier model was able to use 70% of all customer data to train a model capable of identifying customers that would churn with 96% accuracy, 97.1% recall and 81.4% precision on the validation dataset. Out of the 488 churned customers in the validation dataset, only 14 were misclassified. Additionally, while 108 of the 582 predicted churns were misclassified, this produces a population of high risk customers most likely to churn. The resulting model possesses strong predictive power to identify most customers likely to churn, without significantly inflating the size of the class.
