# Car Price Prediction

This project predicts the selling price of a used car using Machine Learning.

## Project Overview

The model predicts car prices based on features such as:

- Car name
- Year
- Kilometers driven
- Fuel type
- Seller type
- Transmission
- Owner
- Mileage
- Engine
- Max power
- Seats

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Streamlit

## Machine Learning Model

Linear Regression is used to predict the selling price.

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(x_train, y_train)
