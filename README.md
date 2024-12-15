# House Price Prediction with Multicollinearity Check (VIF)

This project focuses on building a regression model to predict house prices, while addressing multicollinearity among features using Variance Inflation Factor (VIF).

---

## Overview
- **Objective**: Predict house prices based on multiple features while ensuring a robust and interpretable model.
- **Key Steps**:
  1. Data Preprocessing
  2. Multicollinearity Check using VIF
  3. Model Building and Evaluation

---

## Steps Performed

### 1. Data Preprocessing
- **Handling Missing Values**: Imputed missing values using appropriate techniques based on the nature of the data.
- **Encoding Categorical Variables**: Converted categorical features into numerical format using encoding techniques.
- **Feature Scaling**: Scaled numerical features to standardize the range, improving model performance.

### 2. Multicollinearity Check
- Used **Variance Inflation Factor (VIF)** to detect multicollinearity among independent variables.
- Features with high VIF values were removed iteratively to ensure that only independent variables remained in the final model.
- This step improved model stability and interpretability.

### 3. Model Building
- **Regression Model**: A regression model was trained on the preprocessed dataset.
- Evaluated the model using **R² scores**:
  - Training Set R²: 0.6800
  - Test Set R²: 0.6713
- Consistent R² scores indicate a robust model that generalizes well to unseen data.

---

## Key Findings
- **Multicollinearity**: Addressing multicollinearity using VIF helped reduce redundancy in the features, improving the model’s reliability.
- **Model Performance**: The model explains ~67% of the variance in house prices, demonstrating good predictive capability.
- **Insights**: The preprocessing and feature selection steps played a crucial role in achieving these results.

---

## Tools and Libraries Used
- **Python**
  - pandas
  - numpy
  - statsmodels
  - scikit-learn

---

## Next Steps
- Explore advanced regression techniques such as Ridge or Lasso to further improve performance.
- Experiment with feature engineering to capture more variance in house prices.
- Perform hyperparameter tuning for the regression model.
