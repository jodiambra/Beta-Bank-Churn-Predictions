# Beta-Bank-Churn-Predictions

The purpose of this project is to investigate the churn of Beta Bank customers. The bank has noticed customers are slowly leaving, month over month. The most cost effective solution is to retain existing customers, rather than recruit new customers. The bank needs a model that will predict whether a customer will leave the bank soon. The model will be trained on data from clients' past behavior and termination of contracts with the bank. The goal of the project is to build a model with an F1 score of at least 0.59. 

This is a binary classification problem, therefore, we will be focussing on that class of modeling. This is the case because the target is categorical: churn or not. The F1 score is an appropriate indicator of our model, because we care about both precision and recall. We care about precision because we want to capture as many true positive occurrences of churning. Recall is also crucial, as we want to capture as many occurrences of churning as possible. 