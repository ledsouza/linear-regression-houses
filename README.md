<h1 align="center">House Price Prediction with Linear Regression</h1>

<div align="center">

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Statsmodels](https://img.shields.io/badge/statsmodels-white?style=for-the-badge&logo=statsmodels&logoColor=blue&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-white?style=for-the-badge&logo=matplotlib&logoColor=blue)
![Seaborn](https://img.shields.io/badge/Seaborn-white?style=for-the-badge&logo=seaborn&logoColor=blue)

</div>

## Description

This project is an educational material designed to teach the fundamentals of linear regression for predicting house prices. Through a series of lessons, it guides learners through the process of data analysis, variable transformation, model building, and results interpretation using a practical example of house price prediction.

## Motivation

Understanding linear regression is crucial in data science and machine learning. This material addresses the need for a clear and step-by-step guide to applying linear regression in a real-world scenario. Many learners find the practical application of statistical models challenging, and this project aims to bridge that gap by demonstrating how to transform variables and interpret model outputs in the context of predicting house prices. The goal is to provide a solid foundation in regression analysis, empowering learners to tackle similar predictive modeling tasks.

## Quick Start

To get started with this educational material, you will need Python and the following libraries installed. It is recommended to use a virtual environment to manage dependencies.

### Set up a Python environment:

1. **Install Python**:
   Ensure you have Python 3.x installed. You can download it from the official website: [https://www.python.org/](https://www.python.org/)

2. **Create a virtual environment** (Optional but recommended):
   Open your terminal and navigate to your project directory. Then run:
   ```bash
   python -m venv venv
   ```
   Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`

3. **Install required libraries**:
   You can install all necessary libraries using pip:
   ```bash
   pip install pandas numpy statsmodels matplotlib seaborn
   ```

### How to use this material:

This material is structured as a series of lessons, each focusing on a specific aspect of linear regression.

1. **Preliminary Analysis**: Learn how to perform initial data exploration using boxplots and frequency distributions to understand the dependent variable and its distribution.
2. **Graphical Analysis**: Explore scatter plots to visualize the relationship between variables and identify potential transformations needed for linear regression.
3. **Variable Transformation**: Understand the concept of log transformation and its application in linear regression, specifically the Log-Log model. See how transforming variables can improve model fit.
4. **Multiple Linear Regression**: Learn to build a multiple linear regression model and understand the model equation in the context of transformed variables.
5. **Understanding the Results**:  Interpret the coefficients of the regression model, analyze residuals, and compare predicted values against real values to evaluate model performance.

## Detailed Features

This educational material is divided into five key modules, systematically covering the process of linear regression:

### Preliminary Analysis
* **Boxplot of the dependent variable:** Visualizing the distribution and identifying potential outliers in house prices.
* **Frequency distribution of the dependent variable:** Understanding the spread and central tendency of house prices.
* **Frequency distribution of independent variables:** Examining the distributions of features that might influence house prices.

### Graphical Analysis
* **Scatter plots of variables:** Exploring the relationships between independent variables and the dependent variable (house prices) to assess linearity and identify potential transformations.
* **Dispersion between Variables:** Analyzing scatter plots to understand the direction and strength of relationships.

### Variable Transformation - Log-Log Model
* **Introduction to Log Transformation:** Understanding the concept and benefits of logarithmic transformation for variables in regression models.
* **Log-Log Model Formulation:** Learning how to formulate a Log-Log regression model:  `lnY = ln(β₀) + β₁lnX₁ + β₂lnX₂ + ... + u`.
* **Frequency Distribution of Log-transformed Dependent Variable:** Observing how the log transformation changes the distribution of house prices, aiming for a more symmetrical normal distribution.
* **Verifying Relationships after Transformation:** Using scatter plots to check if the log transformation improves the linearity of relationships between variables.

### Multiple Linear Regression
* **Model Building:** Constructing a multiple linear regression model using the transformed variables.
* **Model Preview:** Presenting the structure of the built regression model.

### Understanding the Results
* **Obtaining Regression Coefficients:** Extracting and interpreting the coefficients from the fitted linear regression model.
* **Model Equation Interpretation:**  Understanding the final regression equation in the form: `lnY = 11.175 + 0.5 ln(X₁) + 0.188X₂ + 0.079 ln(X₃) - 0.261 ln(X₄)`.
* **Prediction vs. Real Values:** Comparing the model's predictions with actual house prices to assess model accuracy.
* **Distribution of Residuals:** Analyzing the distribution of residuals to check for model assumptions and identify potential issues.
* **Residual Dispersion:** Visualizing the dispersion of residuals to further evaluate model fit and identify patterns.
