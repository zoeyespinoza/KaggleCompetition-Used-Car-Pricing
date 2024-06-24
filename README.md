# KaggleCompetition-Used-Car-Pricing

Competition skill assessment, given a dataset of 36183 entries, must predict the price of a used vehicle.

https://www.kaggle.com/competitions/kagglex-cohort4

- Submissions were scored on the root mean squared error. RMSE is defined as:

- RMSE=(1𝑁∑𝑖=1𝑁(𝑦𝑖−𝑦ˆ𝑖)2)12

- where 𝑦ˆ𝑖
- is the predicted value and 𝑦𝑖 is the original value for each instance 𝑖.


*submission 1* - Initial process with RandomForestRegressor

*submission 2* *best* - Using HistGradientBoostingRegressor

*submission 3* - Using RandomizedSearchCV and stack ensemble

Placed **top 25%** in global competition.
