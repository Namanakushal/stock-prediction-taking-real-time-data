# Stock Prediction using Real-Time Data

![Stock Prediction](stock_prediction_image.png)

This project focuses on predicting stock prices using real-time data and machine learning techniques. The goal is to provide accurate predictions for stock prices, enabling investors and traders to make informed decisions in the financial market.

## Introduction

In the unpredictable and volatile world of stock markets, having the ability to forecast stock prices is crucial. This project utilizes historical and real-time data from Alpha Vantage API to train a machine learning model for stock price prediction. By leveraging features such as opening price, high price, low price, previous close, and price change, the model learns patterns and trends to make predictions.

## Features

- Historical data retrieval: Fetches historical stock prices from Alpha Vantage API to build the training dataset.
- Feature engineering: Creates additional features such as previous close and price change to enhance the predictive power of the model.
- Missing value handling: Implements SimpleImputer to handle missing values in the dataset.
- Linear regression model: Trains a Linear Regression model on the historical data to make stock price predictions.
- Real-time data prediction: Retrieves real-time stock data from Alpha Vantage API and utilizes the trained model to predict stock prices.
- Accuracy evaluation: Calculates R-squared and Mean Squared Error (MSE) to assess the accuracy of the predictions.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/stock-prediction.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Replace 'YOUR_API_KEY' in the code with your actual Alpha Vantage API key.

## Usage

1. Run the `stock_prediction.py` script:

   ```bash
   python stock_prediction.py
   ```

2. View the predicted stock prices and accuracy metrics in the console output.

3. Customize the model, features, or parameters as per your requirements.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to the terms of the license.
