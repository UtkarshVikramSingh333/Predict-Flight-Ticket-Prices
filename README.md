# Predict-Flight-Ticket-Prices
Used ML model to predict the Flight prices 
In this project, I developed a machine learning model to predict the price of flight tickets based on various features such as the airline name, date of journey, source and destination, route, departure time, arrival time, flight duration, and the total number of stops. The primary objective was to build a robust model capable of accurately forecasting flight prices by learning patterns from the data.

The project began with data preprocessing, where I handled missing values, encoded categorical features (like airline name, source, destination, and route) using techniques such as One-Hot Encoding. For features like departure and arrival times, I performed feature engineering by extracting useful information such as the hour of the day to capture the influence of peak times on flight pricing. The journey date was also decomposed into day, month, and year to account for seasonal variations and weekday effects.

After preprocessing, I explored various supervised learning algorithms to solve this regression problem, including Linear Regression, Random Forest Regression, Gradient Boosting, and XGBoost. Feature scaling was applied to numerical columns such as flight duration and total number of stops to ensure uniformity and improve model performance.

The model was trained using cross-validation to prevent overfitting and ensure generalization to unseen data. I used Grid Search CV for hyperparameter tuning, optimizing factors such as the depth of trees and learning rates for gradient-boosted models. The performance of the models was evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to assess the model's accuracy and prediction reliability.

By analyzing the feature importance from models like Random Forest and XGBoost, I gained insights into which factors (e.g., total number of stops, airline name, flight duration) have the most significant influence on flight ticket prices. The final model was deployed to predict future flight prices, providing an accurate and scalable solution for forecasting airfare.

This project demonstrates the application of machine learning techniques such as regression, feature engineering, and hyperparameter tuning in the travel industry, leading to predictive insights that can help customers and airlines make informed decisions regarding flight pricing.
