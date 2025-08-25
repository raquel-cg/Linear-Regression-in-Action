# Linear-Regression-in-Action
## Overview:
This project implements a predictive model for residential property prices using the Ames Housing dataset. It focuses on cleaning and preparing the dataset, analyzing key variables such as living area size and garage size, and training a multiple linear regression model. Model accuracy is assessed through train-test splits, error metrics, and residual analysis, providing insights into the main factors driving property values and supporting data-driven decisions in the real estate market.

## Tools & Technologies Used:
- Python (pandas, numpy, scikit-learn)
- Jupyter Notebook
- Matplotlib & Seaborn for visualisation
- Linear Regression for predictive modeling

## Project Structure:
linear-regression-ames/
│── data/
│   └── ames.csv                  # Dataset
│── notebooks/
│   └── Linear_Regression_Ames.ipynb   # Main analysis notebook
│── README.md                     # Project overview
│── requirements.txt              # Python dependencies

## Features: 
- Data cleaning and preparation of housing dataset
- Exploratory Data Analysis (EDA) with visualizations
- Multiple linear regression model for predicting house prices
- Train-test split with model evaluation using RMSE
- Coefficient interpretation to assess variable importance
- Residual error plots to visualize prediction performance

## Key Insights:
- Living area size (Gr_Liv_Area) showed the strongest positive impact on sale prices.
- Garage area (Garage_Area) also influenced sale prices, though less significantly.
- The regression model provided a reasonable fit, with performance measured using RMSE.
- Residual analysis indicated the model captured main trends but struggled with extreme outliers.
- Results highlight how property size and features play a key role in real estate pricing, supporting better pricing and investment strategies.
