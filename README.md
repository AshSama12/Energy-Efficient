# Energy Efficiency Prediction Using Machine Learning

This project focuses on predicting the **Heating Load** and **Cooling Load** of buildings using multiple machine learning models. The objective is to compare model performances and identify the best-performing algorithm for energy efficiency predictions.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Performance Metrics](#performance-metrics)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Conclusion](#conclusion)

---

## Overview

Energy efficiency in buildings is critical for reducing operational costs and minimizing environmental impacts. This project utilizes machine learning to analyze and predict the heating and cooling loads of buildings based on their structural and environmental features.

---

## Dataset

The dataset contains the following features:

- **Input Features**:
  - Relative Compactness
  - Surface Area
  - Wall Area
  - Roof Area
  - Overall Height
  - Glazing Area
  - Glazing Area Distribution
  - Orientation

- **Target Variables**:
  - Heating Load
  - Cooling Load

---

## Models Used

The following regression models were implemented and compared:

1. **Linear Regression**
2. **Decision Tree**
3. **Random Forest**
4. **Gradient Boosting**
5. **Support Vector Regression (SVR)**
6. **Neural Network**

---

## Performance Metrics

The models were evaluated using the following metrics:

- **Mean Absolute Error (MAE)**: Measures average absolute difference between actual and predicted values.
- **Mean Squared Error (MSE)**: Penalizes large prediction errors more than MAE.
- **R² Score**: Represents the proportion of variance explained by the model.

---

## Results

| Model               | MAE     | MSE       | R²     |
|---------------------|---------|-----------|--------|
| Linear Regression   | 2.736e+18 | 8.732e+22 | 0.879  |
| Decision Tree       | 1.569    | 5.666     | 0.941  |
| Random Forest       | 1.507    | 2.867     | 0.965  |
| Gradient Boosting   | 1.501    | 2.782     | 0.966  |
| SVR                 | 1.832    | 8.381     | 0.914  |
| Neural Network      | 1.567    | 5.606     | 0.942  |

---

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/energy-efficiency-prediction.git
