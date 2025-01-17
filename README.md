# Linear Regression using Batch and Stochastic Gradient Descent on the Iris Dataset

This repository contains a project to implement Linear Regression using both **Batch Gradient Descent** and **Stochastic Gradient Descent** algorithms on the **Iris Dataset**. The project demonstrates how these two gradient descent methods can be applied to estimate the model parameters and evaluates the performance using several metrics.

## Project Overview

In this task, the following steps are performed:

1. **Loading the Iris Dataset**:
   - Two features, **Petal Length** and **Petal Width**, are selected from the dataset.
   
2. **Normalizing the Features**:
   - **Min-Max Scaling** is applied to normalize the features to a range between 0 and 1.

3. **Implementing the Gradient Descent Algorithms**:
   - **Batch Gradient Descent** is implemented to estimate the model parameters.
   - **Stochastic Gradient Descent** is implemented to estimate the model parameters.

4. **Training the Model and Estimating Parameters**:
   - Both **Batch Gradient Descent** and **Stochastic Gradient Descent** are used to train the linear regression model and estimate the parameters (coefficients).

5. **Evaluating the Model Performance**:
   - The model performance is evaluated using the following metrics:
     - **Mean Absolute Error (MAE)**
     - **Mean Squared Error (MSE)**
     - **Root Mean Squared Error (RMSE)**
     - **R² (Coefficient of Determination)**
     - **Adjusted R²**

6. **Visualizing the Cost Function Convergence**:
   - The convergence of the cost function over iterations is plotted for both **Batch Gradient Descent** and **Stochastic Gradient Descent**.

## Requirements

- Python 3.x
- Required libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `sklearn`

You can install the necessary libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn
