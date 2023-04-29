# sales-prediction
**Creating a sales volume prediction model using regression methods**

Using Mean Squared Error (MSE) as our evaluation metric, this project aims to identify and train the best model to predict the volume of sales for different e-commerce products.

## Summary
- Exploratory data analysis (EDA) identifies a relatively high correlation between `sales` and `rank`, which is expected due to how popular products can be sold more easily in higher volumes
- Random forest is a more optimal choice compared to XGBoost and multiple linear regression based on MSE
- Perfomed grid search to optimise random forest regressor and reduce MSE

