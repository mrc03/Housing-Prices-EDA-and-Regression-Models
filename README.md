/*

    Author :: Raj Mehrotra
    Date :: 10-12-2018
    
*/

# Housing-Prices-EDA-and-Regression-Models

The famous Housing Price Advanced Regression competition on Kaggle. 

The dataset contains of training and testing sets each with about 1.46K rows and 81 features pertaining to a house The task is to predict the SalePrice for each house in the test set. 

I have first performed an exhaustive EDA to identify the underlying trends in the data. I have also removed outliers to make the regression models more robust. Also proper missing values treatment has been done with imputation being done wherever needed. 

Lastly I have deployed various regression models like Lasso,Ridge etc... from scikit and have also tuned their parameters from the GridSearchCV module.

Finally achieved a RMSE of  little more than 0.12 which is pretty decent.
