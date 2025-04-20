# E-commerce-Delivery-Delay-prediction-Using-Machine-learning

This project predicts the number of days a product delivery might be delayed using real-world e-commerce data from the Olist dataset. We used a Stacking Regressor to combine multiple models for better performance.

# **Dataset**

The dataset used is a merged E-commerce dataset stored in the file:
combined_data.csv
It includes customer, order, product, payment, and delivery-related features such as:
- Order timestamps
- Freight value
- Product weight and volume
- Payment details
- Delivery timelines

# **Model Used**
We trained a Stacking Regressor with the following components:
*Base Models:*
- XGBRegressor (with best parameters from RandomizedSearchCV)
- GradientBoostingRegressor

*Meta Model:*
- LinearRegression
