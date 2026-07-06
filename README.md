# 🏠 House Price Prediction using Multiple Linear Regression from Scratch

## Project Overview

This project implements a **Multiple Linear Regression** model to predict the sale price of residential properties. The model analyzes features such as **lot area, street frontage, number of bedrooms, neighborhood, house style, overall quality, and house age** to estimate house prices. Such models can assist real estate professionals in property valuation and help buyers make informed decisions.

The project demonstrates the complete machine learning workflow, including **data preprocessing, feature selection, feature engineering, feature scaling, model training using Gradient Descent, model evaluation, and visualization**.

> **Note:** The Multiple Linear Regression model and Gradient Descent algorithm were implemented from scratch using **NumPy**. **scikit-learn** was used only for train-test splitting, feature scaling, and evaluation metrics.

---

## Features

- Multiple Linear Regression implemented from scratch using NumPy
- Gradient Descent optimization
- Data preprocessing
- Feature selection
- Feature engineering
- Feature scaling using StandardScaler
- Model evaluation using Mean Absolute Error (MAE) and R² Score
- Model performance visualization

---

## Dataset

This project uses the **House Prices: Advanced Regression Techniques** dataset from Kaggle.

**Target Variable**
- `SalePrice`

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## Project Workflow

1. Load and explore the dataset.
2. Select features for the baseline model.
3. Encode categorical features.
4. Split the data into training and testing sets.
5. Scale numerical features using StandardScaler.
6. Implement Multiple Linear Regression and Gradient Descent from scratch.
7. Train the baseline model.
8. Perform feature engineering to improve model performance.
9. Train the optimized model.
10. Compare the performance of both models.

---

## Results

| Model | MAE | R² Score |
|:------|----:|---------:|
| **Baseline Model** | **33,638.92** | **0.5769** |
| **Optimized Model** | **28,532.53** | **0.7009** |

The optimized model achieved a lower prediction error and a higher R² score, demonstrating the positive impact of feature selection and feature engineering.

---

## Model Visualizations

The notebook includes the following visualizations:

- Cost Function Convergence
- Actual vs Predicted Values
- Baseline vs Optimized Model Performance
- Residual Plot
- Feature Importance

---

## License

This project is licensed under the **MIT License**.
