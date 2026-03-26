# thesis-code
## Project Description

This repository contains the implementation of numerical optimization methods applied to numerical examples and  regression problems, with a focus on solving nonlinear least squares (NLS) models. The project is part of a master's thesis in machine learning and numerical optimization.

## Objectives
Implement and analyze different optimization algorithms
Compare performance in terms of convergence speed and accuracy
Apply methods to regression problems
Evaluate results on real or synthetic datasets

Methods Used
Gradient Descent
Newton Method
Gauss-Newton Method
Levenberg Marquardt (LM) method
Quasi-Newton Methods 
BFGS Optimization

## Numerical Example
Rosenbrock function: A classic non-convex problem  with a narrow
EG2 function: A periodic function with multiple local minima from the CUTE test collection that tests robustness and global convergence properties

## Dataset
Real-world regression datasets 
The dataset used in this project may include:
 ### remote-worker-productivity: 
          hf://datasets/nprak26/remote-worker-productivity/remote_work_productivity.csv
          https://huggingface.co/datasets/nprak26/remote-worker-productivity
### elo-merchant-category-recommendation from Kaggle:  
          https://www.kaggle.com/competitions/elo-merchant-category-recommendation
### Ammok/apple_stock_price_from_1980-2021: 
            hf://datasets/Ammok/apple_stock_price_from_1980-2021/AAPL.csv
            https://www.kaggle.com/datasets/meetnagadia/apple-stock-price-from-19802021.
            https://huggingface.co/datasets/Ammok/apple_stock_price_from _1198-2021

## Results
The results demonstrate the effectiveness of second-order optimization methods (such as Newton and BFGS) compared to first-order methods in terms of convergence speed and accuracy.

## How to Run
Open the notebook in Google Colab
Run all cells sequentially
Modify parameters or dataset as needed

## Technologies Used
Python
NumPy
SciPy
Matplotlib
Scikit-learn

## Repository Structure
notebooks/ : BFGS_modify_multi_Dimantion.ipynb
             different_methods.ipynb
             regression_BFGS.ipynb
data/ : elo-merchant-category-recommendation
results/ : outputs and visualizations

## Author
Esraa Said
Master’s Student in Scientific computing

 Notes
This project is part of ongoing research and may be updated with additional experiments and improvements.
