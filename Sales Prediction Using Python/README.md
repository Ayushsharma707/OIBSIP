# Task 3: Sales Prediction Using Python    
![Description](https://www.google.com/url?sa=i&url=https%3A%2F%2Fmedium.com%2F%40alidu143%2Fbuilding-a-sales-prediction-app-with-streamlit-and-machine-learning-31746625d6ca&psig=AOvVaw12tn15QH2JE0JqFFLLhysr&ust=1720263814688000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCJC_1aPgj4cDFQAAAAAdAAAAABAE)  

**Dataset: [Here](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)** 

## Project Overview:
Sales prediction involves forecasting how much of a product people will buy based on various factors like advertising expenditure, target audience demographics, and the advertising platform. This is a crucial task for businesses as it helps them optimize their marketing strategies and budget allocations. This project is designed to help you learn how to build a model for sales prediction using Python

## Key Objectives:
* Explore the factors affecting product sales.
* Create a machine learning model to predict future sales.
* Gain valuable experience in the field of machine learning and sales forecasting.

## Steps Involved

1. **Data Collection**:
   - Gathered a dataset containing historical sales data and relevant features.

2. **Data Exploration and Visualization**:
   - Conducted exploratory data analysis (EDA) to understand the dataset's structure and identify key patterns.
   - Created various visualizations using Matplotlib and Seaborn to explore relationships between features and the target variable (sales).

3. **Data Preprocessing**:
   - Handled missing values and outliers to ensure data quality.
   - Converted categorical variables into numerical values using techniques such as one-hot encoding.
   - Standardized numerical features to improve model performance.

4. **Feature Engineering**:
   - Created new features based on existing ones to provide additional information to the models.
   - Selected the most relevant features for predicting sales using feature selection techniques.

5. **Model Training and Evaluation**:
   - Trained multiple regression models: Linear Regression, Random Forest Regression, Ridge Regression, Lasso Regression, Gradient Boosting Regression, and XGBoost Regression.
   - Evaluated the models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) score.


### Model Performance Comparison

| MODEL                        | r²            |
|------------------------------|---------------|
| Linear Regression Model      | 0.885284      |
| Random Forest Regression Model| 0.966239    |
| Ridge Regression Model       | 0.885302      |
| Lasso Regression Model       | 0.893786      |
| Gradient Boosting Regression Model | 0.970089 |
| XGBoost Regression Model     | 0.965348      |


### Conclusion

Based on the evaluation metrics, the **Gradient Boosting Regression Model** demonstrated the best performance with an R² score of 0.970089.    
This model is recommended for predicting car prices due to its high accuracy and robust performance across various evaluation metrics.   

**Notebook Link:** [Here](https://github.com/Ayushsharma707/OIBSIP/blob/main/Sales%20Prediction%20Using%20Python/Notebook.ipynb)         

