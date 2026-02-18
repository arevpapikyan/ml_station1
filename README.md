# Product Demand Prediction

The goal of this project is to understand how product pricing affects sales.

This dataset:
- ID: the product ID;
- Store ID: specific store ID;
- Total Price: price at which the product was sold;
- Base Price: the initial price of the product;
- Units Sold: quantity demanded.

Missing values are removed during preprocessing to ensure clean training data.

A Decision Tree Regressor is trained on historical sales data and evaluated on a test set. The accuracy is 0.3764693086638463.