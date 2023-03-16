# Project-2




## Project Overview
The goal of this project is to build and evaluate machine learning models to predict the buy and sell signal. The project uses historical stock price data and various technical indicators as features to train and test several classification models.

## Data
The data used for this project was obtained from Alpaca and consists of historical price data for the selected company. In addition, technical indicators such as moving averages and relative strength index (RSI) were calculated and used as features in the models.

## Methodology
#### The project involved the following steps:

- Data Cleaning and Preprocessing: We performed data cleaning and preprocessing steps including removing null values, converting data types, and calculating technical indicators such as moving averages, relative strength index (RSI), and moving average convergence divergence (MACD).

- Feature Selection: We used the correlation matrix to identify highly correlated features and removed them from the dataset to avoid multicollinearity.

- Train-Test Split: We split the data into training and testing sets using a 80:20 ratio.

- Feature Scaling: We scaled the features using the StandardScaler method from the sklearn library to ensure that all features are on the same scale.

- Model Training: We trained two machine learning models, SVM and RFC, on the training data using the sklearn library. We used the default hyperparameters for both models.

- Model Evaluation: We evaluated the performance of both models using classification reports and accuracy scores.

- Backtesting: We performed a backtest of both models on the testing data to evaluate their performance in generating trading signals and generating profitable returns.


### Results
The results of our analysis are as follows:

- SVM Model Accuracy (Training Set): 93%
- SVM Model Accuracy (Testing Set): 93%
- RFC Model Accuracy (Training Set): 90%
- RFC Model Accuracy (Testing Set): 90%

The backtesting results show that both models were able to generate profitable returns, with the SVM model outperforming the RFC model. However, it is important to note that past performance is not indicative of future results and there are many factors that can influence the success of a trading strategy.

### Conclusion
In conclusion, our analysis demonstrates that it is possible to create a successful and profitable machine learning model for predicting trading signals and generating returns. However, the success and profitability of such a model depend on several factors, including the quality and quantity of data, feature selection, algorithm selection, and evaluation metrics. Therefore, it is important to carefully evaluate and monitor the performance of any trading strategy on an ongoing basis.

#### Reasons for creating trading bot:

1. Efficiency: Algorithmic trading bots can execute trades much faster than human traders can, and they can do so with minimal errors. This is because they operate on pre-defined sets of rules and conditions, and can process large amounts of data in a short amount of time.

2. Emotion-free trading: Humans are prone to emotions such as fear and greed, which can influence their trading decisions. Algorithmic bots, on the other hand, are completely emotion-free and can execute trades based solely on pre-defined rules and conditions. This can help eliminate some of the biases and mistakes that human traders are prone to.

3. 24/7 trading: Algorithmic trading bots can be programmed to operate 24/7, allowing for trades to be executed even when the trader is asleep or otherwise unavailable. This can help take advantage of trading opportunities that may arise outside of regular trading hours.

4. Backtesting and optimization: Algorithmic trading bots can be backtested on historical data to see how they would have performed in the past. This can help traders optimize their strategies and improve their overall performance.

5. Diversification: Algorithmic trading bots can help traders diversify their portfolio by allowing them to execute trades across multiple assets and markets simultaneously. This can help reduce risk and increase overall returns.
