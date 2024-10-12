# Deepcraft Recruitment Assignment: Time Series Forecasting (AI Engineer)

## Overview
This project aims to analyze and forecast oil temperature (OT) using time series data. It employs various techniques, including exploratory data analysis (EDA), data processing, feature engineering, model training, and evaluation using multiple machine learning models and deep learning methods.

## Contents
- Data Loading and Exploration
- Exploratory Data Analysis (EDA)
- Data Integrity Checks
- Seasonal and Temporal Features
- Correlation Analysis
- Model Selection and Training
- Evaluation Metrics
- Improvements and Model Retraining
- Additional Forecasting Techniques (LSTM and ARIMA)

## Requirements
Ensure you have the following libraries installed in your Python environment:
- pandas
- numpy
- seaborn
- matplotlib
- statsmodels
- sklearn
- tensorflow (for LSTM)
- missingno (for visualizing missing data)

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib statsmodels scikit-learn tensorflow missingno
```

## Data
The dataset used in this project is named `ett.csv`. It contains historical oil temperature readings and related features. Ensure that this file is present in your working directory.

## Usage
1. Load the Jupyter Notebook: Open `AI_test.ipynb` in Jupyter Notebook or Google Colab.
2. Run the Code: Execute each cell sequentially to perform data analysis, processing, model training, and evaluation. 
3. Visualize Results: The notebook contains visualizations comparing actual and predicted oil temperatures, as well as various statistical evaluations of the models.

## Model Training
The following models are implemented for forecasting:
1. Random Forest Regression
2. Gradient Boosting Regression
3. LSTM (Long Short-Term Memory) Neural Network
4. ARIMA (AutoRegressive Integrated Moving Average)

## Evaluation
The models are evaluated using metrics such as:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R2 Score

Cross-validation is also performed to assess the models' performance robustness.

## Improvements
To enhance model performance and reduce overfitting, the following strategies were applied:
- Regularization of model parameters
- Feature engineering, including the creation of cyclical features and additional lag features
- Testing and implementing advanced models like LSTM and ARIMA for time series forecasting

## Conclusion
This project showcases a comprehensive approach to time series forecasting using a variety of techniques. The results demonstrate the effectiveness of different models and highlight areas for potential improvements.

## License
This project is a test assignment from Deepcraft for recruitment as AI Engineer.
##
Feel free to contact me for any furthur clarification
