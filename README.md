# Pricing Optimization with Random Forest

## Overview

This project focuses on optimizing product pricing using machine learning techniques. The objective is to predict optimal pricing for products by analyzing various factors and leveraging advanced interpretability methods.

## Contents

1. [Exploratory Data Analysis (EDA)](#1-exploratory-data-analysis-eda)
2. [Modeling and Performance](#2-modeling-and-performance)
3. [Feature Importance and Interpretation](#3-feature-importance-and-interpretation)

## 1. Exploratory Data Analysis (EDA)

- **Objective:** Analyze product categories, pricing distribution, trends, and relationships.
- **Approach:** Conducted thorough data analysis and visualized findings to gain a comprehensive understanding of the data.

## 2. Modeling and Performance

- **Model Used:** Random Forest Regression
- **Performance Metrics:**
  - **R² Score:** 0.97
  - **Mean Absolute Error (MAE):** 10.04
- **Objective:** Predict the optimal price for a given product using the Random Forest model.

## 3. Feature Importance and Interpretation

- **Techniques Used:**
  - **Permutation Importance:** Assesses the impact of each feature on the model’s performance.
  - **SHAP (SHapley Additive exPlanations):** Interprets model predictions and understands feature significance.
- **Objective:** Provide insights into pricing strategies by understanding which features most influence the model's predictions.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `shap`

## Usage

1. **Data Preparation:** Load the dataset and perform necessary preprocessing.
2. **EDA:** Run the EDA scripts to visualize and analyze the data.
3. **Model Training:** Train the Random Forest model with the provided scripts.
4. **Interpretation:** Use SHAP and permutation importance to interpret the model's predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors and resources that supported the development of this project.
