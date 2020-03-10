# AQI-Project

The below model helps us in predicting the Air quality index for delhi region.

1.We have scraped the previous year Air quality index data from the website https://en.tutiempo.net/climate .

2.Once we scraped the data from 2013 to 2018 we have uploaded the CSV and cleaned the data.

3.visualize the features provided T,TM,Tm,SLP,H,VV,V,VM and to predict PM2.5 AQI factor.

4.we have used below regression models to predict the independent variable given dependent variable.

    ->Linear Regression
    ->Lasso Regression
    ->Decision Tree Regressor
    ->KNN Regressor
    ->RandomForestRegressor
    ->Xgboost Regressor
    ->Hyperparameter Tuning
    ->ANN- Artificial Neural Network

5.After running all models with hyperparameter tuning we got a better RMSE with RandomForest Regressor with hyperparameters.
