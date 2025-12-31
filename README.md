# Stock Price Prediction Project

## Project Overview
This project focuses on predicting stock prices using historical data. The dataset is preprocessed, engineered with technical indicators, and machine learning models are trained to predict the target variable. The predictions are then compared to the actual values in a test set to evaluate model performance.

## Workflow

1. **Data Preprocessing**
   - Handled missing values.
   - Ensured consistent data types.

2. **Feature Engineering**
   - Created informative features including:  
     - **SMA 50** (50-day Simple Moving Average)  
     - **SMA 200** (200-day Simple Moving Average)  
     - **Relative Strength Index (RSI)**  
     - **Moving Average Convergence Divergence (MACD)**

3. **Categorical Encoding**
   - Encoded categorical features into numerical values using `LabelEncoder`.

4. **Data Splitting**
   - Split the dataset into features (`X`) and target (`y`).
   - Further split the target variable into `y_train` and `y_test` for training and evaluation.

5. **Model Training and Evaluation**
   - Trained multiple machine learning models:  
     - **Linear Regression**  
     - **Random Forest Regressor**  
     - **XGBoost Regressor**  
   - Predicted on `X_test` and compared predictions (`y_pred`) with `y_test`.
   - Evaluated performance using accuracy metrics.

## Tools and Technologies Used
- **Programming Language:** Python  
- **Notebook Environment:** Jupyter Notebook  
- **Data Analysis:** Pandas, NumPy    
- **Machine Learning:** Scikit-learn (Linear Regression, Random Forest), XGBoost  
- **Feature Engineering:** Custom implementations for SMA, RSI, MACD  
- **Preprocessing & Encoding:** Scikit-learn (LabelEncoder, train_test_split)  
