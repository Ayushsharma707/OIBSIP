# Iris Flower Classification      
![Image](https://i.pinimg.com/564x/e6/24/29/e624298a65b4216fe7e0ffd14b003c2b.jpg)
## Project Description:     
The Iris Flower Classification project aims to create a machine learning model for identifying different species of iris flowers based on their unique measurements. Iris flowers, specifically setosa, versicolor, and virginica, display distinct characteristics that can be quantified and used for classification purposes.      

## Objective:     
The primary objective of this project is to utilize machine learning techniques to develop a robust classification model capable of accurately distinguishing between various species of iris flowers using their measurements. The project seeks to automate and streamline the process of iris species identification, providing a practical and efficient solution.   

## Key Project Details:   
* Iris flowers are categorized into three species: setosa, versicolor, and virginica. 
* Species differentiation is based on measurements including sepal length, sepal   width, petal length, and petal width.   
* The project entails training a machine learning model using a dataset comprising iris flower measurements and their corresponding species labels.   
* Upon training, the model will accurately classify iris flowers into one of the three species based on their measured attributes.

## Steps Involved:
1. Data Exploration and Visualization:
   * Explored the dataset to understand the distribution and relationships of the 
    features.  
    * Created various plots using Matplotlib and Seaborn to visualize the data, 
    including pair plots, histograms, and scatter plots.

2. Data Preprocessing:   
   * Handled any missing values (if present) and standardized the feature values for 
     better model performance.    
    * Split the dataset into training and testing sets for model evaluation.
  
3. Model Training and Evaluation:   
   * Trained multiple classification models: Logistic Regression, Decision Tree, 
     Random Forest, SVC, Gaussian Naive Bayes, and K-Nearest Neighbors.          
    * Evaluated the models using accuracy score and cross-validation score.
    * Identified the best-performing model based on the smallest difference between 
      accuracy score and cross-validation score.

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
