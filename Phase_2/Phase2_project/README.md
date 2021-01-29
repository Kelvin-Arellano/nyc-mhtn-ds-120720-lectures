# Kings County Housing Bake-off

## Overview

For this project we were asked to build a linear regression mondel and predict how much someone would pay for a house in Kings County Seattle, Washingtion. Upon intial exploritory data analysis some of the most important predictors were zipcode,renovation,waterfron views, number of bedrooms and grade. 
![Histogram_of_features](./visualizations/Initial_data_exploration.39.53 PM.png)

This project builds a linear regression model to predict how much someone will pay for a house in King County Seattle, Washington. Initial exploratory data analysis shows the higher the interior sqft, the higher the selling price. Also, the total property size does not determine whether a house sells for higher. Finally, the least profitable month to see a house on average is February. It's actually the most profitable in April to June. 

Based on that discovery, the model included those features to determine house prices based on unseen data. Each iteration of the model used feature selection to determine which model predicted most accurately. After three iterations, the final model has an **RMSE of 214529.8727, when predicting on testing data** that was split from `kc_house_data_train.csv'. The final model's predictions on the holdout set can be found in housing_predictions.csv.

## Business Questions
Before building the model, three main questions were investigated through exploratory data analysis.
1. Do houses sell for more money when they have more interior sqft space?
2. Do houses with higher total property size sell for more?
3. On average, what is the most profitable month to sell a house?

## Data & Methods
