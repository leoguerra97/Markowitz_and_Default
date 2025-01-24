# Markowitz Optimization and Bank Default Prediction

This repository contains two distinct tasks focused on financial analytics and predictive modeling. It demonstrates the application of optimization techniques and machine learning to solve real-world financial problems.

---

## Project Overview

### Task 1: Markowitz Portfolio Optimization
This task focuses on portfolio optimization using the **Markowitz framework**. Key features include:
- **Optimization Constraints**: Implements and visualizes the impact of constraints such as **no short selling**.
- **Regularization Techniques**: Explores the effects of **Lasso** and **Ridge regularization** on portfolio weights to achieve robust solutions.
- **Rolling Window Approach**: Employs a **rolling train-test window** to analyze portfolio performance over time, mimicking real-world market conditions.
- **Optimization Algorithm**: Utilizes the **SLSQP (Sequential Least Squares Programming)** algorithm from `scipy.optimize.minimize` for efficient constrained optimization.

**Visualizations**: The notebook provides clear and intuitive plots for:
- Efficient frontiers under different constraints and regularization methods.
- Portfolio weight trajectories across time.

### Task 2: Bank Default Prediction
This task builds a predictive model to identify the likelihood of bank defaults. Highlights include:
- **Data Preprocessing**: Includes handling missing values, feature scaling, and encoding categorical variables.
- **Model Development**: Implements various machine learning models and compares their performance on classification metrics.
- **Visualization of Results**: Visualizes key results such as feature importance, confusion matrices, and ROC curves for interpretability and evaluation.

---

## Repository Structure

- **`Task1.ipynb`**: Contains the code and visualizations for Markowitz optimization with no short-selling constraints, regularization, and rolling window analysis.
- **`Task2.ipynb`**: Includes the complete pipeline for bank default prediction, from preprocessing to model evaluation.

---

## Getting Started

### Prerequisites
To run the notebooks, ensure you have the following dependencies installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

### Installation
Clone the repository and install the required packages:
```bash
git clone https://github.com/leoguerra97/MarkowitzOptimization_BankPrediction.git
cd MarkowitzOptimization_BankPrediction
pip install -r requirements.txt
