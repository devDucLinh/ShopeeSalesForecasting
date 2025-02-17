# APPLICATION OF MACHINE LEARNING IN PREDICTING PRODUCT SALES ON E-COMMERCE PLATFORMS

## Overview

This project aims to apply machine learning algorithms to predict the number of products sold on e-commerce platforms, focusing on the Vietnamese e-commerce platform, Shopee. The goal is to build models that can predict sales volume using data from product listings, customer reviews, and promotions.

## Objective

The main objectives of this thesis are:

- Build and evaluate machine learning models for predicting sales volumes on e-commerce platforms.
- Explore both traditional algorithms (Linear Regression, Decision Trees, KNN) and advanced models like LSTM and XGBoost.
- Integrate customer sentiment analysis (from product reviews) to improve prediction accuracy.
  
## Data Sources

- **Product Data**: Collected from Shopee, including product details, ratings, prices, and promotion periods.
- **Customer Reviews**: Text reviews on products that are analyzed using sentiment analysis techniques.
  
## Methodology

### 1. Data Collection
- **Shopee Data Crawling**: We used web scraping tools (Selenium) to collect product and sales data from the Shopee platform.
- **Review Data**: We collected customer feedback from Shopee’s API endpoints.

### 2. Data Preprocessing
- Cleaned and transformed raw data into a suitable format for machine learning models.
- Handled missing values, outliers, and feature engineering.

### 3. Machine Learning Models
- **Linear Regression**: A baseline model to predict sales using linear relationships between features.
- **Decision Trees**: A more flexible model for capturing non-linear relationships.
- **K-Nearest Neighbors (KNN)**: For predicting sales based on similarity to other products.
- **LSTM (Long Short-Term Memory)**: A deep learning model suitable for time series data and sequential predictions.
- **XGBoost**: A gradient boosting algorithm known for its performance in structured data.

### 4. Sentiment Analysis
- Used **PhoBERT**, a pre-trained BERT-based model for Vietnamese, to classify customer reviews into positive, negative, and neutral sentiments, then integrated these sentiments into the machine learning models as additional features.

### 5. Evaluation
- Models were evaluated using metrics like RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).
- Cross-validation and hyperparameter tuning were applied to optimize model performance.

