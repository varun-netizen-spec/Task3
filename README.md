Task3: Linear Regression
Objective:
Implement and understand simple and multiple linear regression.

Preprocess the dataset.

Evaluate model performance using different metrics.

Visualize the results.

Tools Used:
Python

Pandas

Numpy

Scikit-learn

Matplotlib

Seaborn

Steps:
Import libraries and load the dataset (housing.csv).

Preprocess the data:

Fill missing values in total_bedrooms with the mean.

Convert the ocean_proximity categorical column using one-hot encoding.

Select features and target variable.

Split the data into training and testing sets (80% train, 20% test).

Fit a Multiple Linear Regression model using LinearRegression from scikit-learn.

Predict and evaluate the model using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared Score (R2)

Plot:

Actual vs Predicted house prices using Seaborn.

Residuals vs Predicted values using Matplotlib.

Results:
The model achieved an R² score around 0.6.

Error metrics were calculated and printed.

Visualization showed the model predictions are reasonably close to actual values.
