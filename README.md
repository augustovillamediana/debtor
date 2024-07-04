
# Debtor Data Analysis and Machine Learning

This repository contains scripts and notebooks for analyzing debtor data and applying machine learning models for predictions and insights.

## Overview

The dataset used in this project includes information on debtor actions, payment agreements, and payment confirmations. The analysis focuses on understanding debtor behaviors, predicting payment amounts, and classifying payment confirmations using machine learning techniques.

## Contents

- **Notebooks:**
  - `debtor_data_analysis.ipynb`: Jupyter Notebook for data analysis, visualization, and insights.
  - `linear_regression.ipynb`: Jupyter Notebook demonstrating a linear regression model for predicting payment amounts.
  - `logistic_regression.ipynb`: Jupyter Notebook demonstrating a logistic regression model for predicting payment confirmations.

- **Data:**
  - `debtor_data.db`: SQLite database generated for containing example debtor data.

## Analysis and Models

### Data Analysis

The `debtor_data_analysis.ipynb` notebook performs exploratory data analysis on the dataset, including:
- Count of actions by type.
- Count of agreements and confirmations by month.
- Total amount paid by month.
- Agreement vs. confirmation analysis.
- Top debtors by total amount paid.

### Machine Learning Models

#### Linear Regression (`linear_regression.ipynb`)

The linear regression model predicts payment amounts based on debtor actions and agreement details.

#### Logistic Regression (`logistic_regression.ipynb`)

The logistic regression model predicts the success of payment confirmations based on debtor actions and agreement details.

## Requirements

- Python 3.x
- Libraries: pandas, matplotlib, scikit-learn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/debtor-data-analysis.git
   cd debtor-data-analysis
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the Jupyter Notebooks using Jupyter Notebook or JupyterLab.

## License

This project is licensed under the GPL-3.0 - see the LICENSE file for details.
