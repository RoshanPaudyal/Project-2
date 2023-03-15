# Project-2

Reasons for creating trading bot:

1. Efficiency: Algorithmic trading bots can execute trades much faster than human traders can, and they can do so with minimal errors. This is because they operate on pre-defined sets of rules and conditions, and can process large amounts of data in a short amount of time.

2. Emotion-free trading: Humans are prone to emotions such as fear and greed, which can influence their trading decisions. Algorithmic bots, on the other hand, are completely emotion-free and can execute trades based solely on pre-defined rules and conditions. This can help eliminate some of the biases and mistakes that human traders are prone to.

3. 24/7 trading: Algorithmic trading bots can be programmed to operate 24/7, allowing for trades to be executed even when the trader is asleep or otherwise unavailable. This can help take advantage of trading opportunities that may arise outside of regular trading hours.

4. Backtesting and optimization: Algorithmic trading bots can be backtested on historical data to see how they would have performed in the past. This can help traders optimize their strategies and improve their overall performance.

5. Diversification: Algorithmic trading bots can help traders diversify their portfolio by allowing them to execute trades across multiple assets and markets simultaneously. This can help reduce risk and increase overall returns.


Summary template (EXAMPLE ONLY):

The daily time frame provides a longer-term perspective and helps filter out noise and volatility that can occur on shorter time frames. This can result in more reliable and accurate signals for trading decisions based on RSI.

RSI is a momentum indicator that measures the strength of price movements over a given period of time. Daily time frames allow for a longer period of data to be analyzed and can provide a more accurate reflection of overall market sentiment and momentum.

Using Bollinger Bands on a daily time frame can help identify major trend changes and market turning points. This can be particularly useful for swing traders who are looking to capture medium-term price movements.

Backtesting results suggest that the model including RSI and daily time frames was more profitable and had a higher score than the other models tested. This indicates that the combination of RSI and daily time frames may be a more effective strategy for trading than the other combinations tested.


## Project Overview
The goal of this project is to build and evaluate machine learning models to predict the buy and sell signal. The project uses historical stock price data and various technical indicators as features to train and test several classification models.

## Data
The data used for this project was obtained from Alpaca and consists of historical price data for the selected company. In addition, technical indicators such as moving averages and relative strength index (RSI) were calculated and used as features in the models.

## Methodology
#### The project involved the following steps:

Data cleaning and pre-processing: The data was cleaned and pre-processed to remove missing values and ensure consistency in the data types.

Feature engineering: Technical indicators were calculated and added as features to the dataset.

Splitting the data: The data was split into training and testing datasets.

#### Model building: The following classification models were trained and evaluated using the training data:

Support Vector Machine (SVM)
Random Forest Classifier (RFC)
Model evaluation: The performance of each model was evaluated using classification reports and visualizing the actual versus strategy returns using the testing dataset.

### SVM Model:

              precision    recall  f1-score   support

        -1.0       0.80      0.68      0.73      7884
         0.0       0.95      0.97      0.96     85198
         1.0       0.76      0.69      0.72      5485

    accuracy                           0.93     98567
   macro avg       0.83      0.78      0.80     98567
weighted avg       0.93      0.93      0.93     98567

### SVM Backtest Model:

              precision    recall  f1-score   support

        -1.0       0.80      0.68      0.73      7884
         0.0       0.95      0.97      0.96     85198
         1.0       0.76      0.69      0.72      5485

    accuracy                           0.93     98567
   macro avg       0.83      0.78      0.80     98567
weighted avg       0.93      0.93      0.93     98567

### RFC Model:


              precision    recall  f1-score   support

        -1.0       0.79      0.67      0.73      7884
         0.0       0.94      0.97      0.96     85198
         1.0       0.76      0.64      0.69      5485

    accuracy                           0.93     98567
   macro avg       0.83      0.76      0.79     98567
weighted avg       0.93      0.93      0.93     98567
