# Sales Prediction Using Machine Learning

## Project Overview

Sales prediction is a crucial task for businesses that want to estimate future product demand and optimize their marketing strategies. By analyzing advertising expenditures and their impact on sales, companies can make informed decisions about budget allocation and business growth.

This project uses Machine Learning techniques to predict product sales based on advertising investments across different media channels.

---

## Objective

The primary objective of this project is to develop a machine learning model that can accurately predict sales based on advertising budgets spent on different platforms such as TV, Radio, and Newspaper.

---

## Problem Statement

Businesses spend large amounts of money on advertising to increase product awareness and boost sales. However, understanding which advertising channels contribute the most to sales is important for maximizing return on investment (ROI).

This project aims to:

* Analyze advertising data.
* Identify relationships between advertising spending and sales.
* Build a predictive machine learning model.
* Evaluate model performance using regression metrics.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab / Jupyter Notebook

---

## Dataset Information

The dataset contains advertising expenditure and sales information.

### Features

* TV Advertising Budget
* Radio Advertising Budget
* Newspaper Advertising Budget

### Target Variable

* Sales

### Example Data

| TV    | Radio | Newspaper | Sales |
| ----- | ----- | --------- | ----- |
| 230.1 | 37.8  | 69.2      | 22.1  |
| 44.5  | 39.3  | 45.1      | 10.4  |

---

## Project Workflow

### 1. Data Collection

* Load dataset from CSV or ZIP file.

### 2. Data Preprocessing

* Handle missing values.
* Remove unnecessary columns.
* Prepare data for training.

### 3. Exploratory Data Analysis (EDA)

* Correlation Heatmap
* Data Distribution Analysis
* Feature Relationships
* Sales Trend Analysis

### 4. Feature Selection

* Select advertising channels as input features.
* Select sales as the target variable.

### 5. Model Training

* Split dataset into training and testing sets.
* Train a Linear Regression model.

### 6. Model Evaluation

Evaluate model performance using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 7. Prediction

* Predict future sales based on advertising budgets.

---

## Machine Learning Algorithm

### Linear Regression

Linear Regression is a supervised machine learning algorithm used to model the relationship between independent variables (advertising budgets) and the dependent variable (sales).

---

## Results

The model successfully predicts sales based on advertising expenditures.

### Key Findings

* TV advertising has the strongest influence on sales.
* Radio advertising contributes significantly to product sales.
* Newspaper advertising generally has a smaller impact.
* Increasing advertising budgets can improve sales performance.

---

## Project Structure

KamilGol_Task5/

├── Sales_Prediction.ipynb

├── advertising.csv

├── README.md

├── requirements.txt

└── screenshots/

---

## Installation

Install the required Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

---

## How to Run

1. Open Google Colab or Jupyter Notebook.
2. Upload the notebook file.
3. Upload the dataset (CSV or ZIP).
4. Run all notebook cells.
5. View model evaluation metrics and sales predictions.

---

## Evaluation Metrics

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## Future Improvements

* Random Forest Regressor
* XGBoost Regressor
* Hyperparameter Optimization
* Streamlit Dashboard Deployment
* Real-Time Sales Forecasting

---

## Conclusion

This project demonstrates how machine learning can be used to forecast product sales using advertising expenditure data. Accurate sales prediction helps businesses optimize marketing budgets, improve decision-making, and increase profitability.

---

## Author

Kamil Gol

Task 5 – Sales Prediction Using Machine Learning
