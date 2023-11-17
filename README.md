# Stock-Price-Predictor
In this project, we will predict the stock prices of gold. We will develop out stock price predictor using two predictors i.e., linear regression and support vector machine (SVM). In research papers, SVM, Regression algorithms works the best compared to any other machine learning algorithms.

## Usage

1 Input the stock code when prompted.
2. Visualize historical stock prices through plots and histograms.
3. Train and evaluate machine learning models for stock price prediction.

## Data 

- The project utilizes the yfinance library to download historical stock price data.
- Data is fetched between the specified date range and auto-adjusted for splits and dividends.

## Exploratory Data Analysis (EDA)

- The notebook/script includes exploratory data analysis, visualizing stock price trends and distributions.

## Model Training

- Linear Regression, Lasso Regression, Ridge Regression, and SVR models are trained on the data.
- Hyperparameter tuning for the SVR model is performed using GridSearchCV.

## Model Evaluation

- Model performance is assessed using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared score.

