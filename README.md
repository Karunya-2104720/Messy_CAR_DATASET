# Messy_CAR_DATASET
# Used Cars Price Analysis

## Overview

This project analyzes a dataset of used cars and builds a simple baseline model to predict selling prices.

## Dataset

The dataset contains information about used cars, including:

* Brand
* Mileage
* Selling Price
* Other features

## Steps Performed

### 1. Data Exploration

* Checked dataset shape and structure
* Identified missing values and incorrect data types

### 2. Data Cleaning

* Removed rows with missing selling price
* Standardized brand names
* Converted mileage to numeric values
* Converted selling price to numeric
* Filled missing values using median

### 3. Baseline Model

* Predicted selling price using mean value
* Evaluated model using Mean Absolute Error (MAE)

## Result

* A baseline MAE score was calculated to serve as a benchmark for future models

## Files

* `used_cars_analysis.ipynb` → Jupyter Notebook with full code
* `README.md` → Project documentation

## How to Run

1. Open the notebook in Jupyter Notebook or Google Colab
2. Run all cells in order

## Tools Used

* Python
* Pandas
* Scikit-learn
