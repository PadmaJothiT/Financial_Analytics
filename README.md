# Financial_Analytics

This project involves analyzing and predicting financial metrics of the top 500 companies in India. The dataset includes market capitalization and quarterly sales data, categorized into different quartiles, and the goal is to develop machine learning models to understand trends and make sales predictions.

## Data Structures

The dataset contains:

Market capitalization (in crores)
Quarterly sales (in crores)
Categorized quartile information
The data is used to analyze the relationship between market cap and sales while leveraging machine learning models to predict sales using both supervised and unsupervised methods.

## Problem Statements

The goal of the project is to: Predict **quarterly sales** based on **market capitalization** and other financial metrics.

## Steps involved in this Project:

### Extracting the Datset

The Dataset has been extracting from the Kaggle website:**https://www.kaggle.com/datasets/michaeldsouza16/financial-data-analysis/data**

### Exploratory Data Analysis (EDA):

Analyze the distribution of market capitalization and sales across different companies.
Visualize the quartiles to understand the relationship between different financial metrics.
Converting the float datatype columns into integer datatypes.

### Data Preprocessing:

Handling missing values, outlier removal, and scaling data using StandardScaler.

### Encoding

Encoding the categorical columns into numerical using **LabelEncoder**

### Model Selection

Trained three models: **RandomForestRegressor, DecisionTreeRegressor, and XGBoostRegressor**.
Evaluated models using metrics like **Mean Squared Error (MSE)** and **R² Score**.

### Model Evaluation

RandomForestRegressor: **MSE: 336.94, R²: 0.93**
DecisionTreeRegressor: **MSE: 530.44, R²: 0.89**
XGBRegressor: **MSE: 369.82, R²: 0.92**

### Conclusion

This project used to predict the quarterly sales based on historical data by using the three models evaluation. In this one of the Ensemble model-RandomForest gives the more accuracy comparitively the others.While the current models provide reasonable performance, there is room for improvement through additional data, feature engineering, and advanced modeling techniques.
