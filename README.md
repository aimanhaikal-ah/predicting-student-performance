# predicting-student-performance

## Overview

This project analyses kindergarten reading and mathematics outcomes using data from the Tennessee Project STAR experiment. Multiple econometric and machine learning models were evaluated to identify the key drivers of student achievement.

## Dataset

- 4,638 kindergarten students
- Student demographics
- Teacher characteristics
- School characteristics
- Class size information

## Models Evaluated

- Ordinary Least Squares (OLS)
- Ridge Regression
- LASSO Regression
- Elastic Net
- Random Forest
- Neural Network

## Evaluation Method

- Five-fold Cross Validation
- Out-of-sample Mean Squared Error (MSE)

## Key Findings

- Random Forest achieved the strongest predictive performance.
- School quality, teacher experience, and socioeconomic background were the most influential predictors.
- Small class sizes showed positive effects on academic outcomes.
- Mathematics outcomes exhibited greater complexity than reading outcomes.

## Files

- student_performance_prediction.ipynb
- Student_Performance_Prediction_Report.pdf
