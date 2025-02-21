# Water Potability Prediction

This project aims to predict water potability (safe or unsafe for drinking) using a Decision Tree Classifier. The dataset `water_potability.csv` contains various water quality parameters, and the goal is to classify water samples based on these features.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Results](#results)
- [License](#license)

## Project Overview
The code performs the following steps:
1. **Data Loading and Exploration**: Loads the dataset, checks for missing values, and visualizes data distributions and correlations.
2. **Preprocessing**: Handles missing values by filling them with column means.
3. **Modeling**: Trains a Decision Tree Classifier and evaluates its performance.
4. **Hyperparameter Tuning**: Uses GridSearchCV to find the best model parameters.
5. **Evaluation**: Reports accuracy, confusion matrix, and classification metrics.

## Dataset
The dataset (`water_potability.csv`) contains water quality metrics such as pH, hardness, solids, etc., with a target column `Potability` (0 = not potable, 1 = potable). Key details:
- Rows: Determined by `df.shape`
- Columns: 10 (9 features + 1 target)
- Missing Values: Handled by filling with mean values

## Requirements
Ensure you have the following Python libraries installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
  

