# Feature-reduction

In regression, "multicollinearity" refers to predictors that are correlated with other predictors.  Multicollinearity occurs when your model includes multiple factors that are correlated not just to your response variable, but also to each other. In other words, it results when you have factors that are a bit redundant.

In this repository, correlation matrix is used to determine the most correlated features in auto-mpg data set. Then, the most correlated features has been removed and linear regression has been applied and RMSE(Root Mean Squared Error) is calculated.

Later, PCA is applied to check the most correlated features in the dataset. PCA has an attribute called ‘explained_variance_ratio’ 
It has been confirmed with PCA that same attributes were the most correlated as correlation matrix revealed in the first step. 
