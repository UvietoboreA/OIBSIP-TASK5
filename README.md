# Task 5: Sales Prediction Using Multiple Regression Models

This project predicts sales based on advertising spend across three platforms: TV, Radio, and Newspaper. It uses multiple regression models and evaluates their performance through metrics such as R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Cross-Validation Score.

## Features
1. **Data Preprocessing**:
   - Rename columns for better readability.
   - Drop unnecessary columns (`Id`).
   - Check for missing values and summary statistics.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualize correlations using heatmaps.
   - Analyze data distribution using histograms.
   - Visualize pairwise relationships using pair plots.
   - Explore the impact of `TV`, `Radio`, and `Newspaper` on `Sales` using scatter plots.

3. **Modeling**:
   - Split the dataset into training (70%) and testing (30%) sets.
   - Train multiple regression models:
     - **Linear Regression**
     - **Ridge Regression**
     - **Lasso Regression**
     - **Random Forest Regressor**
     - **Decision Tree Regressor**
   - Evaluate models using R² Score, MAE, RMSE, and cross-validation.

4. **Visualization**:
   - Visualize performance metrics using bar plots.
   - Compare actual and predicted values using line plots and scatter plots.

## Dataset
The dataset used is Advertising.csv, which contains:
1. TV: Advertising spend on TV.
2. Radio: Advertising spend on Radio.
3. Newspaper: Advertising spend on Newspapers.
4. Sales: Sales generated as a result of advertising.

## Results
### Model Performance Metrics
Each model will output the following metrics:
1. R² Score: Measures how well the predictions match the actual values.
2. MAE: Average of the absolute differences between actual and predicted values.
3. RMSE: Square root of the average squared differences between actual and predicted values.
4. Cross-Validation Score: Average performance across 5 cross-validation folds.

### Visualization
1. Bar Plots: Compare metrics across models.
2. Line Plots: Compare actual vs. predicted sales across models.
3. Scatter Plots: Visualize the relationship between actual and predicted sales across models.
