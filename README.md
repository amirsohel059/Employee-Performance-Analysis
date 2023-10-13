# Employee Performance Analysis

![Employee Performance]
## Project Overview

This project aims to analyze and predict employee performance within the context of a fictional organization, INX Future Inc. The goal is to provide insights into the factors affecting employee performance, identify department-wise performances, and develop a machine learning model that predicts employee performance ratings. The insights gained from this analysis can be used for informed hiring decisions and strategies to enhance employee performance.

The project is conducted in a Jupyter Notebook using Python and leverages various data science and machine learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Data Overview](#data-overview)
- [Insights](#Insights)
- [Top Factors Affecting Employee Performance](#top-factors-affecting-employee-performance)
- [Data  preprocessing](#Data-Preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Conclusion](#conclusion)
- [Recommendations](#Recommendations)
- [Tools and Libraries](#Tools-and-Libraries)
- [How to Contribute](#How-to-Contribute)
- [How to Use](#how-to-use)
- [License](#license)

## Introduction
Employee performance prediction is a critical task for organizations to enhance productivity and job satisfaction. This project analyzes the factors affecting employee performance and builds predictive models using machine learning techniques.

## Data Overview
- **Data Source**: The dataset used for this analysis contains 1200 rows and 28 columns. It includes both quantitative and qualitative features, such as employee demographics, work-related factors, and performance ratings.

## Insights
Some key insights from the analysis include:
- Age and total work experience tend to be positively correlated with higher performance ratings.
- The department and job role of employees have an impact on performance ratings.
- Employee satisfaction, job involvement, and salary hike percentages are important factors affecting performance.
- The number of training sessions and work-life balance also influence performance.


## Top Factors Affecting Employee Performance

1. **Employee Environment Satisfaction**: The majority of employees with higher satisfaction levels tend to perform better.

2. **Employee Last Salary Hike Percent**: Employees with a higher salary hike percentage are more likely to achieve better performance ratings.

3. **Employee Work-Life Balance**: Maintaining a satisfactory work-life balance plays a crucial role in boosting employee performance.

Data Preprocessing
## 
The data preprocessing steps include handling missing values, encoding categorical data, and addressing outliers using the IQR method. Principal Component Analysis (PCA) is used to reduce dimensionality, and data is balanced using SMOTE (Synthetic Minority Over-sampling Technique).

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


## Recommendations
Based on the insights from the analysis, the project suggests recommendations to improve employee performance. These include focusing on employee satisfaction, salary hikes, work-life balance, and providing regular promotions. Special attention is suggested for employees with lower job satisfaction and relationship satisfaction.


## Tools and Libraries
The project utilizes the following tools and libraries:
- Jupyter Notebook
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Scikit-Learn
- Pickle

## How to Contribute
Feel free to contribute to this project by opening issues, providing suggestions, or creating pull requests. Your contributions are welcome and will help improve this analysis.

## How to Use
1. Clone this repository to your local machine.
2. Make sure you have Python and the required libraries installed.
3. Run the Jupyter Notebook to replicate the analysis and models.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
