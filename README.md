
# Big Mart Sales Prediction

This project is focused on predicting sales for a Big Mart dataset using machine learning techniques. The dataset includes features like item weight, visibility, outlet type, and more. The main goal is to predict the `Item_Outlet_Sales` using various regression models, including Linear Regression and XGBoost.

## Features
- Data cleaning and handling missing values.
- Exploratory Data Analysis (EDA) with visualizations.
- Encoding categorical variables.
- Model training using Linear Regression and XGBoost.
- Evaluation of model performance.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/BigMart-Sales-Prediction.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Place the dataset file `Big_mart.csv` in the project directory.
2. Run the script to train the model and make predictions:
   ```
   python bigmart_sales_prediction.py
   ```
3. The model will predict `Item_Outlet_Sales` for the test set.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Acknowledgements
The dataset is based on a fictional Big Mart store's sales data.
