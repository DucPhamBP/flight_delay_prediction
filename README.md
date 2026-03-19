# Flight Delay Analysis and Prediction

This is the final project for the course "Distributed Data Analysis and Mining" (University of Pisa, MSc Data Science and Business Informatics).In this project, we use distributed machine learning techniques to analyze a large-scale flight dataset and predict flight delays.
The main goal is to understand delay patterns and identify the key factors that affect flight performance.

## Business Questions
1. What are the main factors that influence flight delays?  
2. How can we predict arrival delay time, and which features are most important?

## Dataset
The dataset was obtained from Kaggle, based on data from the Bureau of Transportation Statistics (BTS).
- 2,000,000 records  
- 32 features  
- Time range: January 1, 2019 – August 31, 2023  
- 18 airline companies  
- 380 routes across 52 U.S. states  
Each row represents a flight and includes operational and delay information.
## Tech Stack

### Framework
- Apache Spark (PySpark)

### Algorithms
- Supervised Learning:
  - Logistic Regression
  - Linear Regression  
  - Random Forest Regressor  
- Unsupervised Learning:
  - K-Means Clustering (Elbow Method and Silhouette Score)

### Data Preprocessing
- Data cleaning (missing values, data quality)
- Distribution and correlation analysis
- Outlier detection
- Feature engineering

## Goal
The project aims to:
- Understand flight delay behavior  
- Build predictive models for delay  
- Identify the most important factors affecting delays  

These insights can help airlines and airports improve scheduling and operations.
