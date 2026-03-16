# resume-hiring-prediction-ml
AI-Based Resume Screening and Hiring Prediction System

Dataset Source: AI-Powered Resume Screening Dataset (2025), Kaggle.
Available at: https://www.kaggle.com/datasets/mdtalhask/ai-powered-resume-screening-dataset-2025

## 1. Data Cleaning and Feature Preparation
- Load and inspect the dataset
- Clean the data (handle missing values, remove unnecessary columns)
- Detect and handle outliers in numeric features
- Encode categorical variables
- Convert text features into numerical representations using TF-IDF
- Perform feature engineering when necessary
- Split the data into training and testing sets
- Save processed features

## 2. Modeling and Evaluation
- We used MinMax scaling to normalize the feature values.
- Train and compare multiple machine learning models:
    - Logistic Regression
    - Perceptron
    - Linear SVM
    - Multinomial NB
    - KNN (cosine)
    - Decision Tree
    - Random Forest
    - XGBoost
- Evaluate model performance using the F1-score
    - Using cross-validation to improve the evaluation reliability.
    - Address class imbalance using SMOTE.
    - Report ROC-AUC and PR-AUC
- Identify the best-performing model: XGBoost
  
## 3. Ablation and Analysis
We will compare model performance using different feature groups:
- Numeric-only model
- Text-only model
- Combined model

We also included:
- Performance comparison table

## Discussion:
- Best performing model
- Effect of different feature groups
- Limitations of the current approach
- Possible improvements
