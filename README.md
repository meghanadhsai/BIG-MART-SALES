Big Mart Sales Prediction

This project predicts product sales using the Big Mart dataset. The dataset includes product details, store information, and sales figures.

Steps

Data Loading: The dataset is loaded using Pandas.

Data Cleaning: Handled missing values in Item_Weight (using the mean) and Outlet_Size (using mode).

Preprocessing: Replaced inconsistent labels and applied label encoding to categorical variables.

Model Training: Used an XGBoost Regressor to predict Item_Outlet_Sales.

Evaluation:

Training R²: 0.8762

Testing R²: 0.5017
