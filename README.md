## Stock Price Prediction
To predict the closing price of Apple Inc. (AAPL) using machine learning regression models (Linear Regression and Random Forest).
## Dataset
- **Source**: Yahoo Finance via `yfinance` API.
- **Features**: Open, High, Low, Volume.
- **Target**: Close Price.
## Models Used
1. **Linear Regression**: A simple statistical model for finding linear relationships.
2. **Random Forest Regressor**: An ensemble learning method using 100 decision trees for higher accuracy.
## Results
The models were visualized using a 'Separated Comparison View' with a $5 offset to clearly show how both models track the Actual Price trend. Random Forest provided a robust fit for the stock's volatility.
## House Price Prediction
To predict the market value of residential properties using machine learning regression models (Linear Regression and XGBoost) based on physical features and location.
## Dataset
- **Source**: Synthetic dataset generated with 2,000 rows to simulate real estate market trends.
- **Features**: Square Feet, Bedrooms, Bathrooms, Location (City, Suburbs, Rural).
- **Target**: House Price.
## Models Used
1. **Linear Regression**: A baseline statistical model used to identify linear relationships between property size and price.
2. **XGBoost Regressor**: An advanced gradient boosting ensemble model designed to capture complex patterns and improve prediction accuracy.
## Results
The models achieved high precision with an **R2 Score of 0.99**. Linear Regression provided a slightly lower Mean Absolute Error (MAE) of **$11,604**, while XGBoost demonstrated strong stability across the 2,000-row dataset. An interactive **IPyWidgets dashboard** was implemented to allow real-time price estimation based on user input.
4. **Interactive Interface**: A custom-built Jupyter Notebook UI featuring real-time animations and automated smooth scrolling.
