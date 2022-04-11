# Building-a-linear-regression-model

#Instructions

Import LinearRegression.
Instantiate a linear regression model.
Predict sales values using X, storing as predictions.

# Import LinearRegression
from sklearn.linear_model import LinearRegression

# Create the model
reg = LinearRegression()

# Fit the model to the data
reg.fit(X,y)

# Make predictions
predictions = reg.predict(X)

print(predictions[:5])

#output:
    [ 95491.17119147 117829.51038393 173423.38071499 291603.11444202
     111137.28167129]
