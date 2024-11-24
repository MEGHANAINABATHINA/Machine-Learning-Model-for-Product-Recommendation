Skincare Product Recommendation System
This project develops a machine learning-based recommendation system for skincare products using customer behavior data. It uses collaborative filtering and machine learning to suggest products that align with a user’s preferences.

Project Overview
This repository demonstrates how machine learning can enhance the retail experience by providing personalized product recommendations. Using a dataset of skincare products, the system predicts relevant items based on past user behavior, product categories, and other attributes.

Features
Exploratory Data Analysis (EDA) for understanding customer trends.
Preprocessing and handling missing data.
Multi-output neural network to predict:
Product preferences.
Brand choices.
Skin type compatibility.
Price expectations.
Model evaluation using precision, recall, and F1-score.
Dataset
The dataset includes:

Fields:
User ID
Product
Brand
Skin Type
Price
Sold By
Preprocessing Steps:
Imputation of missing values (mode for categorical data, median for numerical data).
Label encoding for categorical fields.
Scaling of numeric values using MinMaxScaler.
How It Works
Data Processing:

Handles missing values.
Encodes categorical features for machine learning.
Splits data into training and testing sets.
Model Training:

Embedding layers for product, brand, and skin type.
Concatenation of embeddings and dense layers for predictions.
Outputs for:
Product category.
Brand name.
Skin type.
Price prediction.
Model Evaluation:

Metrics used: Precision, Recall, F1-score, Mean Absolute Error (MAE).
Visualization:

Accuracy and loss trends over training epochs.
Evaluation metrics comparison using bar charts.
Model Performance
Metric	Score
Precision (Product)	0.85
Recall (Product)	0.83
F1-Score (Product)	0.84
Mean Absolute Error (Price)	5.20
