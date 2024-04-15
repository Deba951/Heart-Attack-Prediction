# Heart Attack Prediction

![node-12045](https://github.com/Deba951/Heart-Attack-Prediction/assets/83878346/0622c508-84fd-4635-9751-82f9a68df723)

## Introduction

Welcome to the Heart Disease Prediction project repository. This project is aimed at predicting the likelihood of heart disease in individuals based on various health parameters. It involves data analysis, data preprocessing, and the application of machine learning models to make predictions.

## Objective
```
The main objective of this project is to create a predictive model that can help identify individuals at a higher risk of heart disease. By analyzing a dataset of health parameters, we aim to build accurate models that can assist in early detection and intervention.
```

## Brief Description of the Project

This project involves the analysis of a dataset containing various health parameters and a binary classification task to predict the presence or absence of heart disease in individuals. The project consists of the following major steps:
```
    1. Importing libraries and datasets.
    2. Data understanding and exploration.
    3. Data preprocessing and cleaning.
    4. Exploratory Data Analysis (EDA) to gain insights into the dataset.
    5. Feature selection and handling multicollinearity.
    6. Splitting the data into training and testing sets.
    7. Hyperparameter tuning for machine learning models.
    8. Model training and evaluation using three different algorithms: Logistic Regression, Decision Tree, and Support Vector Machine (SVM).
```

## Importing Libraries and Dataset

This project utilizes several Python libraries for data analysis, machine learning, and visualization. Key libraries include:
```
    - Pandas
    - NumPy
    - Seaborn
    - Scikit-learn
    - Matplotlib
    - Statsmodels
```
The dataset used in this project is stored in a CSV file named 'heart.csv'.

## Factors or Parameters Considered from the CSV File

The following factors or parameters are considered from the CSV file:
```
    - 'age': Age of the patient.
    - 'sex': Gender of the patient.
    - 'cp': Chest pain type.
    - 'trtbps': Resting blood pressure in mm Hg.
    - 'chol': Cholesterol level in mg/dL.
    - 'exng': Exercise-induced angina.
    - 'fbs': Fasting blood sugar level.
    - 'restecg': Resting electrocardiographic results.
    - 'thalachh': Maximum heart rate achieved.
    - 'slp': Slope.
    - 'caa': Number of major vessels.
    - 'thall': Thallium stress test result.
    - 'output': Target variable (0 for less chance of heart attack, 1 for more chance of heart attack).
```

## Steps Included in this Project
```
    1. Data loading and exploration.
    2. Data preprocessing, including handling outliers, missing values, and duplicates.
    3. Exploratory data analysis (EDA) to gain insights into the dataset.
    4. Feature selection based on correlation.
    5. Train-test split of the dataset.
    6. Hyperparameter tuning for multiple machine learning models:
    - Logistic Regression
    - Decision Tree
    - Support Vector Machine (SVM)
    7. Model training and evaluation.
    8. Display of confusion matrices and classification reports for model performance.
```

##  Brief Description and Insight

This project aims to identify early indicators of heart disease by analyzing various health parameters. It involves data preprocessing to clean and prepare the data for analysis. Exploratory Data Analysis (EDA) provides valuable insights into the dataset, enabling us to make informed decisions regarding feature selection and model training.

The feature selection process involves considering parameters with significant influence on heart disease prediction and handling multicollinearity to ensure model accuracy. Hyperparameter tuning is performed to optimize the machine learning models' performance.
```
Three modelling procedures are employed in this project:
1. **Logistic Regression**: A widely used classification algorithm that estimates the probability of a binary outcome. Logistic Regression is used to predict the likelihood of heart disease. The model is trained with hyperparameters optimized through grid search.
2. **Decision Tree**: A tree-structured model that makes decisions based on the input features. A Decision Tree model is employed for heart disease prediction. The model's hyperparameters are fine-tuned for optimal performance.
3. **Support Vector Machine (SVM)**: A powerful algorithm for classification and regression tasks. It is used for heart disease prediction. The model's hyperparameters are optimized through grid search.
```
The models are evaluated using confusion matrices and classification reports, providing insights into their performance in predicting heart disease.

## Conclusion

This project combines data analysis and machine learning to address the critical issue of heart disease prediction. By following the steps outlined in this repository, you can gain insights into the dataset, select the most relevant features, and create predictive models that aid in early detection and intervention for heart disease.

![648352d2cd7fec3dd50e7a783a934e2b](https://github.com/Deba951/Heart-Attack-Prediction/assets/83878346/8830bed1-049b-4e73-94ef-c425f2542bd6)

Thank you for visiting the Heart Disease Prediction project repository!
Feel free to drop a star if you like it.
