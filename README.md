# Car Price Prediction using Machine Learning

The objective of this project is to build a machine learning model to predict car prices based on features such as age, mileage, fuel type, and transmission.
-------------------

## Dataset
The dataset contains information about used cars, including:
- Year
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner
---------------------

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
----------------------

## Workflow
- Data loading
- Data preprocessing
- Feature selection
- Model training
- Prediction
- Evaluation
--------------------------

## Models Used
Three regression models were trained and compared:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
---------------------------

## Evaluation
Model performance was evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score
These metrics help measure prediction accuracy and how well the model fits the data.
-------------

## Result
All models performed well on the dataset. Random Forest Regressor achieved the best performance with the lowest error and highest R² score (~0.95), making it the most reliable model for predicting car prices.
-------------------------

## Model Comparison
- Linear Regression provides a baseline but is limited to linear relationships
- Decision Tree captures complex patterns but may overfit
- Random Forest achieves the best performance due to its ensemble nature and ability to generalize well
Based on evaluation metrics, Random Forest is selected as the best model for this task.
-------------------------

## Conclusion
This project demonstrates how machine learning can be used for price prediction in real-world scenarios such as used car valuation.
--------------------
## Author
Bishwash Acharya  
CodeAlpha Data Science Intern
