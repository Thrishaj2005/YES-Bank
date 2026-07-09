# YES Bank Stock Price Prediction using Machine Learning

## Project Overview

This project focuses on predicting YES Bank stock closing prices using Machine Learning regression techniques. Historical stock price data is analyzed to identify trends, patterns, and relationships between different stock features.

The project includes Exploratory Data Analysis (EDA), data preprocessing, model development, evaluation, and hyperparameter tuning to build an effective stock price prediction system.

## Project Type

EDA + Regression

## Objective

The main objectives of this project are:

- Analyze historical YES Bank stock price data.
- Perform Exploratory Data Analysis to understand stock trends.
- Develop machine learning regression models for stock price prediction.
- Evaluate model performance using regression metrics.
- Improve model accuracy using hyperparameter optimization techniques.

## Dataset

**Dataset Name:** data_YesBank_StockPrices.csv

The dataset contains historical stock market information including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Volume

The target variable used for prediction is the **Closing Price** of YES Bank stock.

## Variables Description

| Variable | Description |
|----------|-------------|
| Date | Represents the date of the stock price record. It is used for analyzing YES Bank stock price trends over time. |
| Open | Represents the opening price of YES Bank stock at the beginning of the trading period. |
| High | Represents the highest stock price recorded during the trading period. |
| Low | Represents the lowest stock price recorded during the trading period. |
| Close | Represents the closing price of YES Bank stock at the end of the trading period. This is the target variable that the machine learning models aim to predict. |
| Volume | Represents the total number of YES Bank shares traded during the trading period and indicates market activity. |

## Exploratory Data Analysis

The following analysis was performed:

- Understanding dataset structure and statistical summary.
- Checking missing values and data consistency.
- Visualizing stock price trends over time.
- Analyzing relationships between stock features.
- Performing correlation analysis.
- Identifying important patterns in stock price movement.

## Data Preprocessing

The preprocessing steps include:

- Loading and understanding the dataset.
- Checking and handling missing values.
- Converting data into suitable formats.
- Extracting useful information from date features.
- Selecting relevant features for model training.
- Splitting the dataset into training and testing datasets.

## Machine Learning Models Implemented

### Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting. It learns complex patterns from historical YES Bank stock data and predicts future closing prices.

### XGBoost Regressor

XGBoost is a gradient boosting algorithm that builds multiple decision trees sequentially. It improves prediction performance by reducing errors from previous models and capturing complex relationships in stock price data.

### Support Vector Regression (SVR)

SVR is a supervised machine learning algorithm used for regression tasks. It uses kernel functions to identify non-linear patterns and predict stock prices effectively.

## Model Evaluation Metrics

The implemented models are evaluated using the following regression metrics:

**Mean Absolute Error (MAE)**

MAE measures the average difference between actual and predicted stock prices. A lower MAE indicates that the model predictions are closer to the actual values.

**Mean Squared Error (MSE)**

MSE measures the average squared difference between actual and predicted values. It gives higher importance to larger prediction errors.

**Root Mean Squared Error (RMSE)**

RMSE represents the prediction error in the same unit as the stock price, making it easier to interpret.

**R² Score**

R² Score indicates how well the model explains variations in YES Bank stock prices. A higher R² score represents better model performance.

## Hyperparameter Optimization

Hyperparameter tuning was performed to improve the performance of machine learning models.

The techniques used are:

**GridSearchCV**

GridSearchCV performs an exhaustive search over different hyperparameter combinations and selects the best parameters based on cross-validation performance.

**RandomizedSearchCV**

RandomizedSearchCV randomly searches different parameter combinations and provides efficient optimization with reduced computational time.

The tuning process helped improve model performance by reducing prediction errors and increasing accuracy.

## Results

The implemented regression models successfully predicted YES Bank stock closing prices using historical market data.

After hyperparameter tuning, the models showed:

- Reduced MAE and RMSE values.
- Improved R² score.
- Better prediction capability.
- Improved understanding of stock price trends.

The optimized model can be used as a supporting tool for financial analysis, stock market research, and investment decision-making.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Project Structure

YES-Bank-Stock-Price-Prediction/

├── data_YesBank_StockPrices.csv

├── YES_Bank_Stock_Prediction.ipynb (Google Colab Notebook)

├── README.md

└── requirements.txt

## How to Run the Project

1. Open the Google Colab Notebook.

2. Upload the dataset file:

data_YesBank_StockPrices.csv

3. Install required libraries if needed.

4. Run all cells in the notebook.

5. The notebook performs:

- Data preprocessing
- Exploratory Data Analysis
- Model training
- Model evaluation
- Hyperparameter tuning
- Stock price prediction

## Author

**Thrisha J**

MSc Data Science  
VIT Vellore

## Conclusion

This project demonstrates the application of machine learning regression techniques for YES Bank stock price prediction. By performing Exploratory Data Analysis, preprocessing, model implementation, evaluation, and hyperparameter tuning, the project shows how machine learning can be used to analyze financial data and support data-driven decision-making.

The developed models provide valuable insights into stock price patterns and demonstrate the potential of machine learning in financial forecasting. However, stock prices are influenced by various external factors, so the predictions should be considered as a supporting analytical tool rather than a guaranteed forecast.
