# Investment-Recommendation-System

This project focuses on predicting stock prices using five different machine learning models. The stock data is sourced from Yahoo Finance, and the models are applied to forecast the closing price of a stock based on its opening price. The primary goal is to compare the performance of these models in terms of accuracy.

Detailed Steps
1. Data Preprocessing
The dataset for this project consists of historical stock price data sourced from Yahoo Finance for the ticker symbol LICI.NS (Life Insurance Corporation of India).

2. Exploratory Data Analysis (EDA)
Before training the models, basic statistical summaries and visualizations are performed to understand the distribution and behavior of the stock prices over time.
Descriptive statistics (mean, median, standard deviation) are calculated to get a sense of the data.
Time series plots of the stock prices are generated to visualize trends and patterns.

3. Model Selection and Training
Five machine learning models are used for stock price prediction. Each model is trained using the train_test_split method to divide the data into training and testing sets.

Random Forest Regressor: An ensemble learning method that constructs multiple decision trees during training.
Gradient Boosting Regressor: Another ensemble method, which builds trees sequentially, focusing on correcting errors made by prior models.
Linear SVR: A linear model for regression tasks, particularly useful for high-dimensional datasets.
MLP Regressor: A type of artificial neural network used for regression tasks.
KNeighbors Regressor: A simple algorithm that predicts the target by averaging the values of the nearest neighbors in the feature space.

4. Model Evaluation
After training, each model's predictions are evaluated on the test set. The primary evaluation metric is the R² score (r2_score), which measures how well the predictions match the actual stock prices. A higher R² score indicates better performance.

5. Visualizing Results
The project generates a plot comparing the actual stock prices against the predicted values from each model. This visualization helps in understanding how well each model performs in forecasting the stock's closing price.

The plotted results for each model give a visual indication of how closely the predicted stock prices align with the actual prices, helping to identify the most effective model.
