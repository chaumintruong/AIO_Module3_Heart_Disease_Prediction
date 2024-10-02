# AIO_Module3_Heart_Disease_Prediction_Project

## Introduction
This project focuses on data analysis and building predictive models to assess the risk of heart disease based on patients' medical parameters. The exercises in this project utilize various techniques, ranging from exploratory data analysis to machine learning model construction, to make predictions.

## Exercise Content

### Exercise 1: Data Analysis
- **Objective**: Use the Seaborn library to visualize the relationship between age and the likelihood of heart disease.
- **Explanation**: In this exercise, patients will be classified by age and their heart disease status (target = 1 indicates the presence of heart disease, target = 0 indicates the absence).

### Exercise 2: Data Analysis
- **Objective**: Visualize the relationship between age, gender, and the likelihood of heart disease.
- **Explanation**: This exercise expands upon Exercise 1 by incorporating gender into the analysis, providing deeper insights into how gender affects heart disease risk.

### Exercise 3: Heart Disease Prediction Using KNN
- **Objective**: Use the KNN (K-Nearest Neighbors) algorithm to predict the likelihood of heart disease.
- **Parameters**: n_neighbors=5, weights='uniform', algorithm='auto', leaf_size=30, p=2, metric='minkowski'.

### Exercise 4: Heart Disease Prediction Using SVM
- **Objective**: Use the SVM (Support Vector Machine) algorithm to predict the likelihood of heart disease.
- **Parameters**: kernel='rbf', random_state=42.

### Exercise 5: Heart Disease Prediction Using Naive Bayes
- **Objective**: Use the Naive Bayes algorithm to predict the likelihood of heart disease.
- **Parameters**: kernel='rbf', random_state=42.

### Exercise 6: Heart Disease Prediction Using Decision Tree
- **Objective**: Use the Decision Tree algorithm to predict the likelihood of heart disease.
- **Parameters**: criterion='gini', max_depth=10, min_samples_split=2.

### Exercise 7: Heart Disease Prediction Using Random Forest
- **Objective**: Use the Random Forest algorithm to predict the likelihood of heart disease.
- **Parameters**: criterion='gini', max_depth=10, min_samples_split=2, n_estimators=10, random_state=42.

### Exercise 8: Heart Disease Prediction Using Adaboost
- **Objective**: Use the Adaboost algorithm to predict the likelihood of heart disease.
- **Parameters**: n_estimators=50, learning_rate=1.0.

### Exercise 9: Heart Disease Prediction Using Gradient Boosting
- **Objective**: Use the Gradient Boosting algorithm to predict the likelihood of heart disease.
- **Parameters**: learning_rate=0.1, n_estimators=100, subsample=1.0, min_samples_split=2, max_depth=3, random_state=42.

### Exercise 10: Heart Disease Prediction Using XGBoost
- **Objective**: Use the XGBoost algorithm to predict the likelihood of heart disease.
- **Parameters**: objective="binary:logistic", random_state=42, n_estimators=100.

### Exercise 11: Heart Disease Prediction Using Stacking Technique
- **Objective**: Use the Stacking technique with various machine learning models to predict the likelihood of heart disease.
- **Explanation**: This exercise applies a heterogeneous stacking approach to combine different models to improve prediction accuracy.

## Conclusion
This project provides insights into how data analysis and machine learning techniques can be employed to address real-world healthcare issues, specifically predicting heart disease. Through each exercise, we have learned the workings of various algorithms and how to apply them to specific datasets.
