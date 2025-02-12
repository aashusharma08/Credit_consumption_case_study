# Customer Data Analysis and Prediction

## Overview
This project focuses on analyzing customer demographics, behavior, and credit consumption patterns to build a predictive model using a Random Forest Regressor. The dataset consists of customer details, spending habits, and financial behavior data.

## Dataset
The project utilizes three datasets in Excel format:
1. **Demographic Data** - Contains customer personal details.
2. **Behavioral Data** - Tracks customer spending habits.
3. **Credit Data** - Includes financial history and credit consumption patterns.

## Data Preprocessing
1. **Loading Data**: The datasets are loaded using `pandas.read_excel()`.
2. **Checking for Missing Values**: The `.info()` method is used to inspect missing values.
3. **Cleaning Data**: Missing values are dropped to ensure data integrity.
4. **Exploratory Data Analysis (EDA)**:
   - `.describe()` is used to understand statistical distribution.
   - `.info()` is used to validate data types and missing values.

## Model Building
1. **Feature Selection & Engineering**:
   - Identifying relevant features for prediction.
   - Encoding categorical variables if necessary.
2. **Random Forest Regressor**:
   - Splitting the data into training and testing sets.
   - Training a `RandomForestRegressor` model.
   - Evaluating model performance using suitable metrics.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn (for visualization)

## How to Run
1. Install dependencies using `pip install -r requirements.txt`.
2. Run the script `analysis.py` to preprocess and analyze the data.
3. Train the model by executing `train_model.py`.

## Future Improvements
- Implementing better missing value handling (imputation instead of dropping).
- Optimizing feature selection and engineering.
- Hyperparameter tuning for Random Forest.
- Visualizing customer spending patterns using Matplotlib/Seaborn.


