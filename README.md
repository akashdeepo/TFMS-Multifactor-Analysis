# Multifactor Analysis Model for Stock Market Prediction
This is the code for the multifactor analysis model presented in the paper "A Multifactor Analysis Model for Stock Market Prediction" by Akash Deep from Texas Tech University. The model combines technical analysis, fundamental analysis, machine learning, and sentiment analysis to predict stock prices based on multiple factors.

## Requirements
The code requires the following Python packages:

pandas
numpy
scikit-learn
keras
matplotlib

## Usage
To run the code, simply execute the main.py script. The script loads the historical stock data for five American companies (Apple, Amazon, Alphabet, Microsoft, and Tesla) from Yahoo Finance, preprocesses and cleans the data, trains the random forest regressor and LSTM models, performs sentiment analysis using the NewsAPI and TextBlob libraries, and outputs the predicted stock prices and sentiment scores.

The script also includes a section for predicting the stock price for the next day, which can be used to make short-term investment decisions.

## Results
The model's performance is evaluated using mean squared error (MSE) and mean absolute error (MAE) metrics. The results show that the proposed model provides improved accuracy in predicting future stock prices compared to traditional methods.

## Future Work
Possible future improvements to the model include:

Implementing reinforcement learning to train the weights of the output values from the proposed models of other new methods, to better capture the correlations between the scores.
Using large language models to improve sentimental analysis, to extract more insights from neutral data/news.
Adding more features, such as technical indicators and economic indicators, to improve the accuracy of the predictions.

This code is released under the MIT license.
