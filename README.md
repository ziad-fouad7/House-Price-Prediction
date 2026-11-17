# House Price Prediction 🏠

## Project Overview
This project aims to predict house prices using Machine Learning.
A Linear Regression model is developed to estimate house prices based on selected property features.

The project also compares model performance using different train-test split ratios.

## Dataset
- Dataset: House Prices Dataset
- Number of Rows: 1,460
- Number of Columns: 81
- Target Variable: SalePrice

## Features Used
The model uses five features:

- GrLivArea
- BedroomAbvGr
- FullBath
- OverallQual
- YearBuilt

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow
1. Data Loading
2. Data Exploration
3. Feature Selection
4. Missing Values Analysis
5. Data Preprocessing
6. Building a Linear Regression Model
7. Model Evaluation
8. Train-Test Split Comparison
9. House Price Prediction

## Model Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Model Performance Comparison

| Train-Test Split | R² Score | MAE | RMSE |
|---|---:|---:|---:|
| 80/20 | 0.77 | 27820.40 | 41891.41 |
| 70/30 | 0.78 | 26832.18 | 39613.15 |
| 60/40 | 0.78 | 26229.54 | 40295.56 |

## Prediction Examples

The model was tested with two different house examples:

- First Prediction: 250095.40
- Second Prediction: 269602.41

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   pip install -r requirements.txt

3. Make sure train.csv is in the same directory as the notebook.
4. Open House_price_prediction.ipynb using Jupyter Notebook or Google Colab.
5. Run the notebook cells.

## Author
Ziad Fouad
