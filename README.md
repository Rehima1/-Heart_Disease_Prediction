# Heart Disease Prediction🫀

## Overview

This project aims to predict the presence of heart disease using various machine learning models. It involves a comprehensive process of data loading, preprocessing, visualization, model building, and evaluation. By leveraging the power of ML, this project aim to provides valuable insights into heart disease prediction and contributes to the development of effective diagnostic tools.

## Project Details

**Objective:** To accurately predict the presence or absence of heart disease based on patient data.

**Dataset:** The project utilizes the "heart.csv" dataset, which contains a collection of medical features and a target variable indicating the presence or absence of heart disease. Kaggle dataset link: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

**Methodology:**

1. **Data Loading and Exploration:**
   - I started by importing necessary libraries such as pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.
   - import the dataset.
   - I performed data exploration using functions to understand the data structure, identify data types, and check for missing values.

2. **Data Preprocessing:**
   - Numerical columns are identified for further analysis.
   - Missing values are imputed with a 'mean' strategy, ensuring that all data points are utilized for training.
   -  I identified Outliers in the 'chol' and 'trestbps' columns and handled it by femoving them. This step ensures that extreme values do not unduly influence the model's performance.

3. **Data Visualization:**
   - for the visualizing I used many visual graphs to understand the dataset cols, their distribution and relationships between numerical features. These visualizations help me in identifying potential patterns and correlations among the variables.
   
4. **Model Building:**
   - I split the dataset into training and testing sets to evaluate the model's performance on unseen data.
   - then I scaled  the data to standardize the features and prevent any single feature from dominating the model's learning process.
   - Several machine learning models are trained, including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Gradient Boosting, AdaBoost, and Naive Bayes. These models represent a diverse range of algorithms, allowing me to compare their performance and identify the most suitable one for this task.

5. **Evaluation:**
   - Model performance is evaluated using accuracy and confusion matrices. Accuracy measures the overall correctness of the model's predictions, while confusion matrices provide a detailed breakdown of true positive, true negative, false positive, and false negative predictions.
   - I generated a classification reports to provide detailed performance metrics such as precision, recall, F1-score, and support for each class.
   - then a bar chart is created to visually compare the accuracy of different models, facilitating easy interpretation and comparison.
   ![image](https://github.com/user-attachments/assets/1aa7b5be-1eb6-4e8c-9e8a-dcf1312c70cf)

## Conclusion

This project demonstrates the application of ML for heart disease prediction. The results showcase the accuracy of different models, offering valuable insights into their effectiveness in identifying heart disease. The project's findings can be leveraged to develop more accurate and reliable diagnostic tools for heart disease, ultimately contributing to improved patient care and outcomes.

