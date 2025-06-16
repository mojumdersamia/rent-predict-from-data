# Simple House Price Prediction using Linear Regression

This is a beginner-friendly Python project demonstrating a basic data science workflow using linear regression to predict house prices based on the living area (square footage).

## Project Overview

The script reads housing data from a CSV file, trains a linear regression model on the relationship between house price and living area (`sqft_living`), and then allows the user to input a square footage value to predict the corresponding house price.

## Features

- Load and preview data using `pandas`
- Train a linear regression model with `scikit-learn`
- Interactive user input to predict house price
- Simple and easy-to-understand implementation ideal for beginners in data science and machine learning

## How to Use

1. Ensure you have a CSV file named `data.csv` in the same directory with at least the following columns:
   - `sqft_living` (feature)
   - `price` (target variable)

2. Install the required libraries if you haven't already:
   ```bash
   pip install pandas scikit-learn
Run the Python script:

BASH

python your_script_name.py
When prompted, enter the square footage value (e.g., 1500).

View the predicted house price output.

## Example
PLAINTEXT

Data Preview:
   sqft_living    price
0         1340  550000
1         1690  650000
2         2720  1200000
3         1870  700000
4         2500  950000

Enter Square Footage (sqft_living): 2000
Predicted Price: TK 800,000.00
## Notes
This is a simplified example for educational purposes.
Accuracy depends on the quality and quantity of the input data.
Feel free to extend the project by adding more features and improving the model.
## License
MIT License
