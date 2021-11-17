# BigFridaySales-Prediction-Elastic-Beanstalk-Deployment-
The dataset used for the project comprises of sales transactions captured at a retail store. It has 550,068 rows and 12 columns. For each transaction row, age of the customer, city category, occupation, marital status, product category, etc. are captured. The target variable is the purchase amount,
or the money spent on each transaction by the customer
1>The entire dataset was then clustered using Kprototypes, following models were developed for each specific cluster.
2>The machine learning algorithms used for the implementation of the system are Multiple Regression, Lasso Regression, Regressor Tree, Random Forest Regression, and Deep learning algorithm like the Multi-Layer Perceptron Model.
3>The best model for each cluster was the MLP model. The best model was then saved in a binary format and exposed as a web application on the Amazon Beanstalk where users can input the variable values and predict the purchase amount for that combination of variables.
