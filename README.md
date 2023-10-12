# Employee Performance Prediction Project

This project aims to predict employee performance based on various factors such as Employee Environment Satisfaction, Employee Last Salary Hike Percent, and Employee Work Life Balance. The analysis involves exploratory data analysis, model creation, and hyperparameter tuning.

## Table of Contents
- [Introduction](#introduction)
- [Data Overview](#data-overview)
- [Top Factors Affecting Employee Performance](#top-factors-affecting-employee-performance)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Support Vector Classifier (SVC)](#support-vector-classifier-svc)
- [Random Forest](#random-forest)
- [Artificial Neural Network](#artificial-neural-network)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [License](#license)

## Introduction
Employee performance prediction is a critical task for organizations to enhance productivity and job satisfaction. This project analyzes the factors affecting employee performance and builds predictive models using machine learning techniques.

## Data Overview
The dataset used in this project contains information about employees, including their performance ratings and various factors influencing their performance.

## Top Factors Affecting Employee Performance
1. **Employee Environment Satisfaction:** The majority of employees with higher satisfaction levels tend to perform better.

2. **Employee Last Salary Hike Percent:** Employees with a higher salary hike percentage are more likely to achieve better performance ratings.

3. **Employee Work Life Balance:** Maintaining a satisfactory work-life balance plays a crucial role in boosting employee performance.

## Exploratory Data Analysis
The project involved the following steps:
- Principal Component Analysis (PCA) for dimensionality reduction.
- Retention of 25 key features for analysis.

## Model Building
### Support Vector Classifier (SVC)
- Achieved good accuracy on both training and testing data.
- Hyperparameter tuning using Grid Search CV for improved model performance.

### Random Forest
- Initially achieved perfect accuracy on training data.
- Required hyperparameter tuning using RandomizedSearchCV.
- Final model performance after tuning.

### Artificial Neural Network
- Achieved high accuracy on both training and testing data.

## Conclusion
The selected model for employee performance prediction is the Artificial Neural Network (Multilayer Perceptron). It consistently performed well on both training and testing data.

## How to Use
1. Clone this repository to your local machine.
2. Make sure you have Python and the required libraries installed.
3. Run the Jupyter Notebook to replicate the analysis and models.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
