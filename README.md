# Gold Price Prediction using Random Forest Regression

## Overview
This project builds a machine learning model to predict gold prices using **Random Forest Regression**. The dataset includes various financial and economic indicators that influence gold prices, such as stock indices and currency exchange rates.

## Dataset
The dataset used for this project contains features like:
- Date
- Opening price
- Closing price
- Highest price
- Lowest price
- USD/INR exchange rate
- Stock market indices (e.g., S&P 500, NASDAQ)
- Crude oil prices
- Interest rates
- Gold price (target variable)

## Dependencies
To run this project, install the required Python libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Implementation Steps
1. **Data Preprocessing**
   - Load the dataset using pandas.
   - Handle missing values and outliers.
   - Convert date to a suitable format and extract relevant time-based features.
   - Normalize or standardize numerical features if needed.
   
2. **Exploratory Data Analysis (EDA)**
   - Analyze trends and correlations between features and gold prices.
   - Visualize the data using line plots and heatmaps.
   - Check for seasonality and time-series patterns.
   
3. **Model Training**
   - Split the dataset into training and testing sets.
   - Train the **Random Forest Regression** model on the training set.
   - Optimize hyperparameters using GridSearchCV.
   
4. **Evaluation**
   - Calculate performance metrics such as RMSE, MAE, and R².
   - Compare predicted vs. actual prices using visualization.
   
## Usage
Run the following script to train and evaluate the model:
```bash
python train_model.py
```

## Results
- The model achieves an R² score of **XX%**.
- Important factors affecting gold prices include **currency exchange rates, stock indices, and crude oil prices**.

## Conclusion
This project successfully predicts gold prices using **Random Forest Regression**, demonstrating the impact of economic indicators on gold price fluctuations.
