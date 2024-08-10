# Sindian House Price Regression

This repository contains the implementation of a linear regression model for real estate valuation using a dataset collected from Sindian District, New Taipei City, Taiwan.

## Objective

The objective of this project is to build and evaluate a linear regression model to predict the house price of a unit area based on various features related to real estate properties in Sindian District.

## Dataset

The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set). It contains various features such as size, number of rooms, location coordinates, and other relevant attributes of real estate properties in Sindian District, New Taipei City, Taiwan.
### Data Exploration and Preprocessing

1. **Data Exploration:**
   - The dataset is loaded into a pandas DataFrame to explore its structure and basic statistics.
   - Checked for missing values, and handled them appropriately if necessary (if any missing values were present).

2. **Data Preprocessing:**
   - Normalized numerical features to ensure all features are on the same scale.
   - No categorical features were present in this dataset, so no encoding was necessary.
   - Split the dataset into features (X) and the target variable (Y).

### Feature Selection/Engineering

1. **Feature Selection:**
   - Analyzed the correlation between features and the target variable (house price).
   - Selected relevant features that showed high correlation with the target variable.

2. **Feature Engineering:**
   - Considered adding new features or feature combinations to potentially improve model performance.

### Model Training and Evaluation

1. **Model Training:**
   - Split the dataset into training and testing sets (e.g., 80% for training, 20% for testing).
   - Initialized and trained a linear regression model using scikit-learn.

2. **Model Evaluation:**
   - Evaluated the trained model using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.
   - Visualized the actual vs. predicted house prices to understand the model's performance visually.

### Hyperparameter Tuning (Optional)

1. **Hyperparameter Tuning:**
   - Experimented with different hyperparameters of the linear regression model or other variants to improve performance.
   - Utilized techniques like cross-validation and grid search to find optimal hyperparameters.

### Conclusion and Further Analysis

1. **Conclusion:**
   - Summarized the findings from the model evaluation.
   - Discussed any limitations or assumptions made during the modeling process.

2. **Further Analysis:**
   - Proposed potential avenues for further analysis or model improvement.

### Score: 9/10
