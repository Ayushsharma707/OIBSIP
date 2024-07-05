# Task 2: Car Price Prediction with Machine Learning     
![Description](https://repository-images.githubusercontent.com/286819592/b82e14cf-3c85-4f91-84c0-bea095c353a8)  

**Dataset: [Here](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars)** 

## Project Overview:
In the automotive industry, determining the price of a car involves various factors, such as brand reputation, car features, horsepower, and fuel efficiency. Car price prediction is a crucial application of machine learning. This project is designed to help you learn how to build a model for car price prediction.

## Key Objectives:
* Explore the factors affecting car prices.
* Create a machine learning model to predict car prices.
* Gain valuable experience in the field of machine learning and automotive pricing.  

### Steps Involved:

1. **Data Collection**:
   - Gathered a dataset containing car prices and related features.

2. **Data Exploration and Visualization**:
   - Conducted exploratory data analysis (EDA) to understand the dataset's structure and identify key patterns.
   - Created various visualizations using Matplotlib and Seaborn to uncover relationships between features and the target variable (car price).

3. **Data Preprocessing**:
   - Handled missing values and outliers to ensure data quality.
   - Converted categorical variables into numerical values using techniques such as one-hot encoding.
   - Standardized numerical features to improve model performance.

4. **Feature Engineering**:
   - Created new features based on existing ones to provide more information to the model.
   - Selected the most relevant features for predicting car prices using feature selection techniques.

5. **Model Training and Evaluation**:
   - Trained multiple regression models: Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Regression.
   - Evaluated the models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) score.
   - Compared the performance of different models to select the best one for car price prediction.

6. **Model Deployment**:
   - Saved the trained model for future predictions.
   - Created a simple web application using Flask to allow users to input car details and get price predictions.

### Model Performance Comparison   

| MODEL                  | r²            | CV Score      | MAE          | MSE          |
|------------------------|---------------|---------------|--------------|--------------|
| Linear                 | 1.000000e+00  | 1.000000e+00  | 1.277427e-14 | 2.796657e-28 |
| Random Forest          | 0.911591      | 0.879377      | 0.661425     | 2.643953     |
| Decision Tree          | 0.897369      | 0.868293      | 0.829011     | 3.069295     |
| Ridge                  | 1.000000e+00  | 1.000000e+00  | 3.850307e-06 | 4.267472e-11 |
| Lasso                  | 1.000000      | 1.000000      | 0.001429     | 0.000006     |

  
### Conclusion

Based on the evaluation metrics, the **Linear Regression** model demonstrated the best performance with a perfect r² score and minimal MAE and MSE values. Both **Ridge** and **Lasso Regression** also performed exceptionally well, achieving near-perfect scores.   

The **Random Forest** and **Decision Tree** models, while not as accurate as the linear models, still showed good performance, with r² scores above 0.85 and reasonably low MAE and MSE values. These models are robust and can be useful when dealing with more complex and non-linear relationships in the data.   

Overall, the Linear Regression model is recommended for car price prediction due to its high accuracy and consistency across various evaluation metrics. This model can provide valuable insights for car buyers and sellers by estimating the value of a car based on its attributes.      

 **[Notebook](https://github.com/Ayushsharma707/OIBSIP/blob/main/Car%20Price%20Prediction%20With%20Machine%20Learning/car_price_prediction_notebook.ipynb)** 
