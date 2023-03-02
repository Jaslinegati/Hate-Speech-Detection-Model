# Hate-Speech-Detection-Model

## Overview
This project involved building a hate speech detection model using twitter data sentiment analysis. I compared the performance of three ML models (Random forest, XGB, and Logistic regression) on twitter data. I analyzed the data, did cleaning and visualizations, which helped me realize that the data was imbalanced. I upsampled the data as it was heavily skewed towards data that didn't have hate speech, and this would make the model biased in its prediction.

## Methodology
I used k-fold cross-validation to tune both XGB and random forest to find the best parameters, then using them to predict hate speech on untrained data after training. After comparing the performance of the three models, I found that Logistic regression model on oversampled data had the highest F1 score on validation data and had the second-best recall after XGB. I convinced my team to choose it as the best model.

## Key Highlights
Data cleaning and visualization helped identify imbalanced data
Upsampling helped to reduce model bias
Used k-fold cross-validation to tune the models
Found Logistic regression model on oversampled data to be the best performing model

## Conclusion
This project demonstrates the effectiveness of using Logistic regression model for hate speech detection on twitter data. The approach used in this project can be applied to other classification problems as well.
