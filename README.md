# SpaceX Rocket Landing Success Prediction

# Project Overview
This project aims to predict the success of SpaceX rocket landings using various machine learning classification methods. As a Business Intelligence/Data Science company, we developed an accurate predictive model to help a competitor of SpaceX identify launches with the highest chances of successful landing.

# Table of Contents
1. Project Motivation
2. Data Collection
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Modeling
7. Model Evaluation
8. Results and Insights
9. Future Work


# Project Motivation
SpaceX has been a pioneer in the space industry, particularly in achieving reusable rocket technology. This project focuses on analyzing factors that contribute to the successful landing of SpaceX rockets and building a machine learning model to predict landing outcomes. The insights and model can help SpaceX competitors enhance their rocket landing success rates.

# Data Collection
Data was collected from publicly available sources, including:
SpaceX API: Information on past launches and their outcomes.
Web Scraping: Additional details from space-related websites.

# Data Preprocessing
Data preprocessing involved the following steps:
1. Data Cleaning: Handling missing values, correcting data types, and removing duplicates.
2. Normalization: Scaling numerical features to ensure uniformity.
3. Encoding: Converting categorical variables into numerical format using techniques such as one-hot encoding.

# Exploratory Data Analysis (EDA)
EDA was conducted to understand the underlying patterns in the data:
Descriptive Statistics: Summary statistics for numerical and categorical features.
Visualizations: Histograms, scatter plots, correlation matrices, and box plots to identify relationships between features and the target variable (landing success).

# Feature Engineering
New features were created to enhance the model's predictive power:
Launch Specific Features: Launch Site, Landing Pad, Geographic and operational characteristics of the launch site.
Rocket Specifications: Payload Mass, GridFins, Legs, Booster Version
Temporal Features: Orbit, Reused Rockets.

# Modeling
Several classification models were built and evaluated:
Logistic Regression: Baseline model to understand the impact of features.
Decision Tree : Ensemble method to improve prediction accuracy.
SVM: Advanced boosting algorithm for better performance.
K Nearest Neighbor

# Model Evaluation
Models were evaluated using appropriate metrics:
GridSearchCV was used to determine best parameters.
Accuracy: Overall correctness of the model.

# Results and Insights
Key findings from the model:
Important Features: as mentioned above.
Model Performance: DecisionTree Classifier performed the best, compared to other Models that were used in this particular scenario, with an accuracy rate of 94%.

# Recommendations for future analysis
Data Augmentation: Collecting more data to improve model accuracy.
Feature Enhancement: Exploring additional features like maintenance schedules and more detailed weather data.
Model Optimization: Fine-tuning hyperparameters and experimenting with other machine learning algorithms.
