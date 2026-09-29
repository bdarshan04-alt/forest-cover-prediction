# Forest Cover Type Prediction

A machine learning classification project that predicts forest cover types from cartographic and environmental features.

The project follows an end-to-end machine learning workflow, including data exploration, preprocessing, model development, evaluation, model persistence, and prediction generation.

---

## Project Overview

Forest ecosystems are influenced by geographical and environmental conditions such as elevation, slope, aspect, soil characteristics, hydrology, and surrounding terrain.

This project uses these features to build a multiclass classification model capable of predicting the forest cover type associated with a given observation.

The dataset contains seven possible forest cover classes, making this a multiclass classification problem.

### Objective

The primary objectives of this project are to:

- Understand the structure and characteristics of the dataset
- Perform exploratory data analysis
- Identify relationships between features and forest cover types
- Prepare the data for machine learning
- Develop and compare multiple classification models
- Evaluate model performance using appropriate metrics
- Select a suitable model for prediction
- Save the trained model and preprocessing objects
- Generate predictions for unseen test data

---

## Dataset

The dataset contains **15,120 observations** and **55 columns** initially.

After removing the `Id` column, the modelling dataset contains:

- **54 input features**
- **1 target variable**
- **7 target classes**

### Target Variable

`Cover_Type`

The target variable represents the forest cover type and contains seven classes:

```text
1
2
3
4
5
6
7

