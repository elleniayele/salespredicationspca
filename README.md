
# Prediction-of-Product-Sales with pca modeling
## Project Desciption
### Project overview
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a model and predict the sales of each product at a particular outlet.

The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.

There are 8523 rows, and 12 columns. The rows represent 8523 observations, and the columns represent 11 features and 1 target variable.
# outlets
## Total outlet by sales
![image](https://github.com/elleniayele/salespredicationspca/assets/61632568/cc3aea92-75c9-4542-a636-a590499c1ffd)


Outlet OUT027 significantly outperformed the other outlets with 3,453,926.05 dollars of total sales.

Outlets OUT010 and OUT019 significantly underperformed the other outlets, having only 188,340.17 dollars and 179,694.09 dollars in total sales respectively.

# Outlet Types
Supermarket Type1 outlets may have contributed the most to Total Company Sales, however they do not have the highest Average Outlet Sales.

Supermarket Type3 has only only one outlet, and it has the highest Outlet Sales , and they have the least Outlet Sales.

![image](https://github.com/elleniayele/salespredicationspca/assets/61632568/115c792d-3647-40ed-ad60-9b89cb93cc18)




Outlet Location Types
image Tier 3 Outlet Location Types contributed the most to Total Company Sales. Though Tier 2 Outlet Location Types contributed a lessor amount than either Tier 3 to Total Company Sales, their Average Outlet Sales were higher.

Items
image

# Model Performance based on better model for this data, which is random forest model

As the name suggests, random forest is nothing but a collection of multiple decision tree models. Random forest is a supervised Machine Learning algorithm. This algorithm creates a set of decision trees from a few randomly selected subsets of the training set and picks predictions from each tree. Then by means of voting, the random forest algorithm selects the best solution.
# Coefficient of Determination (r2)
The Coefficient of Determination is the proportion (%) of the variation in the dependent variable, or target variable, that a model is able to predict, or explain, from the independent variables, or features.
# mean sqare error
To calculate the MSE, you take the difference between your model's predictions and the ground truth, square it, and average it out across the whole dataset.
# evaluate the performance based on rmse
Root mean square error or root mean square deviation is one of the most commonly used measures for evaluating the quality of predictions. It shows how far predictions fall from measured true values using Euclidean distance. it is the square root of MSE.
# evaluate the performance based on mae(mean absolute error)
Mean Absolute Error calculates the average difference between the calculated values and actual values.
lets evaluate the metrics of the best model i chose:

model Scores

### MAE: 303.0307 
### MSE: 194,495.5551 
### RMSE: 441.0165 
### R2: 0.9343

model Scores

### MAE: 771.2808 
### MSE: 1,263,310.4449 
### RMSE: 1,123.9708 
### R2: 0.5421
since it has better r2 score,mae,mse and rmse, random forest model has the better scores to predict the outlet sales by looking at  the other factors of the data.
i would recommend using random forst model to use to get better pridictions for the sales.
