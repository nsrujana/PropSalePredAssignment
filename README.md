# Advanced-Regression
> Description: House Price prediction analysis. 
## The procedure involved in preparing the regression model
* Exploratory Data analysis
* Train and test data split and Minmax scaling
* Building linear regression model using RFE
* Residual Anslysis on the test data and predicted data
* Model Evaluations for each feature-calculation of R2
* If the model overfits- build the models using Ridge and Lasso for the same features
## Conclusions
As per data given for the feature varibales, 10% of the features are eliminated based on the NaN and by droping the missing values by passing zero.
Categorical varibales are prepared and onehot encoding is implemented for 40% of features. Due to this huge data is generared.
It is identified propert saleprice is maintained good corelation with GrLivArea, LotArea, BsmtFlArea and GarageArea. Based on the higher RFE and p values the features are droped to have the bestfit. Ridge and Lasso mehtods are implemented. Compative to lasso, ridge attained good score of R2 with hyperparameter lambda 10.

