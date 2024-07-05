# Iris Flower Classification      
![Description](https://repository-images.githubusercontent.com/286819592/b82e14cf-3c85-4f91-84c0-bea095c353a8)   

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
## Model Performance Comparison  

| MODEL                  | Accuracy Score | CV Score  | Difference |
|------------------------|----------------|-----------|------------|
| Logistic Regression    | 1.000000       | 0.860000  | 0.140000   |
| Decision Tree          | 1.000000       | 1.000000  | 0.000000   |
| Random Forest          | 1.000000       | 0.993333  | 0.006667   |
| SVC                    | 0.966667       | 0.946667  | 0.020000   |
| Gaussian Naive Bayes   | 1.000000       | 0.991667  | 0.008333   |
| KNeighbors Classifier  | 0.966667       | 0.946667  | 0.020000   |

  
 ### Conclusion:
The Decision Tree model demonstrated the best performance with a perfect accuracy score and no difference between its accuracy and cross-validation scores, indicating robust generalization.   

 **[Notebook](https://github.com/Ayushsharma707/OIBSIP/blob/main/Iris%20Flower%20Classification/Notebook.ipynb)** 
