# Semiconductor Manufacturing Process Yield Prediction

## Project Overview
This project focuses on building a classifier to predict the Pass/Fail yield of a semiconductor manufacturing process entity. The primary goal is to identify whether all features in the dataset are necessary for building an accurate model or if feature selection can be applied to identify the most relevant signals. By pinpointing these key signals, Process Engineers can determine factors contributing to yield excursions, thereby increasing process throughput, reducing learning time, and decreasing production costs.

## Data Description
**Dataset:** signal.csv
**Dimensions:** 1567 examples, 591 features
**Target Column:**
               -1: Pass
                1: Fail
**Features:** Sensor measurements and process signals

# Project Steps and Tasks :
1. Data Import and Exploration
    * Load and explore the dataset to understand its structure and content.
2. Data Cleansing
    * Handle missing values and drop irrelevant attributes based on functional knowledge.
    * Modify the data using logical reasoning to prepare it for analysis.
3. Data Analysis & Visualization
    * Conduct detailed statistical analysis.
    * Perform univariate, bivariate, and multivariate analysis with thorough commentary on findings.
4. Data Preprocessing
    * Segregate predictors (features) and target attributes.
    * Address class imbalance in the target variable (e.g., using SMOTE).
    * Perform train-test split and standardize the data if necessary.
    * Ensure train and test sets have similar statistical characteristics as the original data.
5. Model Training, Testing, and Tuning
    * Train multiple supervised learning models (e.g., Random Forest, SVM, Naive Bayes).
    * Use cross-validation and GridSearch for hyper-parameter tuning.
    * Apply techniques like dimensionality reduction, attribute removal, standardization/normalization, and target balancing to   enhance model performance.
    * Display and explain the classification report for each model.
    * Compare model performance on training and test data, and select the best model for future use.
6. Conclusion and Improvement
    * Summarize results and provide conclusions on the effectiveness of the selected model.
    * Suggest potential improvements for future work.

# Results and Insights :
This project demonstrates the process of building a classifier to predict yield in a semiconductor manufacturing process. By analyzing and tuning various models, the project identifies the most effective approach for predicting pass/fail outcomes based on sensor data. The best-performing model is highlighted, with detailed conclusions provided to guide further improvements.
