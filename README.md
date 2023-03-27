# House-Prices-Advanced-Regression-Techniques

My best score on Kaggle Leaderboard : 0.11901 (TOP 10%)

"I would improve my model performance by fixing some feature engineering issues and experimenting with stacking methods."

## Description

### Data Correlation:
Identify correlations among the features in the data.

### SalePrice Transformation:
Transform the SalePrice data using log transformation to improve the model performance.

### Data Cleaning
        
Clean the data by performing the following operations:

* Convert numerical features that should be categorical to the categorical data type.
* Replace missing values in the objective feature with 'NA' or 'None' and numerical missing values with 0.
* Fill some object data with mode data.

### Skewed Features Transformation
* Transform skewed features with boxcox transformation.

### Feature Engineering

Perform feature engineering by using the following techniques:

* Label Encoder
* One Hot Encoder

### Modeling

Train the model using the following regressors:

* Gradient Boosting Regressor
* XGBoost Regressor
* Catboost Regressor
* LightGBM Regressor
* Random Forest Regressor
* Stacking model
