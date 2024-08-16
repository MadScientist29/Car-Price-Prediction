# Predicting Car Prices with Machine Learning: Linear Regression and Lasso Models 🚗🔍

## Introduction to Car Price Prediction 📈
Explore the world of car price prediction using machine learning techniques. Accurate price forecasting is crucial in the automotive industry for better decision-making and valuation.

## Setting up the Environment 🛠️
- **Libraries Used**: Pandas, Matplotlib, Seaborn, scikit-learn
- **Models**: Linear Regression, Lasso

## Data Collection and Preparation 📊
1. **Loading the Dataset**: Import and inspect the data.
2. **Handling Missing Values**: Address any missing values in the dataset.
3. **Exploring Categorical Variables**: Examine and encode categorical data for machine learning.

## Splitting Data for Model Training 🧩
1. **Organizing Data**: Separate features (X) and target variable (Y).
2. **Data Splitting**: Use `train_test_split` to create training and testing sets, essential for model performance evaluation.

## Model Training with Linear Regression 🔎
1. **Training the Model**: Fit the Linear Regression model to the training data.
2. **Model Evaluation**: 
   - Calculate R squared error for model accuracy.
   - Visualize actual vs. predicted prices for training data using scatter plots.

### Predictions on Testing Data 🧪
1. **Testing Predictions**: Predict car prices on testing data (X_test).
2. **Evaluation**: 
   - Calculate R squared error for testing data.
   - Visualize actual vs. predicted prices for testing data with scatter plots.

## Model Training with Lasso Regression 🧠
1. **Loading Lasso Regression Model**: Initialize with `Lasso()`.
2. **Fitting the Model**: Train on the training data (X_train, Y_train).

### Model Evaluation
1. **Training Data Predictions**: Predict on the training data.
2. **Calculate R squared error**: Assess how well predictions match actual values.
3. **Visualization**: Scatter plot of actual vs. predicted prices for training data.

### Predictions on Testing Data 🔮
1. **Testing Data Predictions**: Predict car prices on the testing data.
2. **Visualization**: Scatter plot of actual vs. predicted prices for testing data.

## Usage
To run this project locally:
1. Clone this repository:
   ```bash
   git clone https://github.com/MadScientist29/Car-Price-Prediction.git
