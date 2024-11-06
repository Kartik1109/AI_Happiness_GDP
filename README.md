# Happiness and GDP Linear Regression Model

This project aims to explore the relationship between happiness scores and GDP of various countries. The analysis involves building a linear regression model using Gradient Descent (GD) to determine how wealth correlates with life satisfaction. By experimenting with different learning rates and iteration counts, the model fine-tunes the relationship between GDP and happiness.

## Table of Contents

- [Context](#context)
- [Challenge](#challenge)
- [Dataset](#dataset)
- [Goal](#goal)
- [Implementation](#implementation)
- [Results](#results)
- [Requirements](#requirements)
- [Usage](#usage)

---

## Context

Understanding the factors that lead to a happy life is essential for creating meaningful societal structures. By identifying and prioritizing these factors, we can better address the challenges in achieving a high life satisfaction.

## Challenge

In this assignment, we implement a linear regression model using Gradient Descent to find the relationship between happiness and GDP (richness) of countries. The model will be tested on a dataset of happiness scores and GDP from 2018.

## Dataset

The dataset used for this project is available in the Week 1 folder in Lectures on Avenue, preprocessed with code provided in `Linear_Regression.py`. This dataset provides happiness scores and GDP data, which we’ll use as the target variable (`happiness`) and feature (`GDP`), respectively.

## Goal

The objective is to:

1. **Build a Linear Regression Model** that predicts happiness based on GDP.
2. **Experiment with Different Learning Rates and Iterations** to find the best model.
3. **Compare Gradient Descent and OLS Results** to observe the goodness of fit.

## Implementation

### Gradient Descent Model

The Gradient Descent model iteratively optimizes the weights (θ values) to minimize the error in predictions. The code experiments with 5 different learning rates and 5 iteration counts (epochs) to evaluate performance across multiple settings.

### Visualization and Comparison

1. **Multiple Regression Lines**: A scatterplot of the dataset, with 4-8 regression lines overlaid, shows the effect of various learning rates and epochs on the goodness of fit.
2. **Best Fit Comparison**: Plots the best fit line derived from Gradient Descent against the Ordinary Least Squares (OLS) fit.

### Outputs

- **Plot 1**: Scatterplot with multiple regression lines from different GD experiments.
- **Plot 2**: Comparison of the best GD-derived line against the OLS-derived line.
- **Print Statements**: Display θ values for each learning rate and epoch combination, and the best θ values.

## Results

After experimenting with multiple learning rates and iteration counts, the best θ value is identified. This θ is plotted alongside the OLS solution, showcasing the effectiveness of the Gradient Descent model.

## Requirements

To run the code, you will need:

- Python 3.x
- `matplotlib` for plotting
- `numpy` for calculations

Install dependencies with:
```bash
pip install numpy matplotlib
