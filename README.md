# Task 36 — Classification Dataset Analysis Using Python

## Project Overview

This project demonstrates the basic structure of a classification problem using the Iris Dataset.

The dataset is loaded using Scikit-learn and explored using Pandas.

The four input features and the categorical target variable are identified. The possible target classes are also extracted and analyzed.

The project explains why the dataset represents a multiclass classification problem.

## Objectives

- Understand the structure of a classification problem.
- Load and explore a classification dataset.
- Identify numerical input features.
- Identify the categorical target variable.
- Find all unique target classes.
- Calculate the number of records in each class.
- Identify binary and multiclass classification problems.
- Explain the selected features and target.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab
- Jupyter Notebook
- CSV

## Dataset Description

The Iris Dataset contains 150 flower observations.

It has four numerical input features and one categorical target variable.

| Column | Description |
|---|---|
| sepal_length_cm | Sepal length in centimetres |
| sepal_width_cm | Sepal width in centimetres |
| petal_length_cm | Petal length in centimetres |
| petal_width_cm | Petal width in centimetres |
| species | Iris flower species |

## Input Features (X)

The four input features are:

1. `sepal_length_cm`
2. `sepal_width_cm`
3. `petal_length_cm`
4. `petal_width_cm`

These measurements describe the physical characteristics of each flower.

## Target Variable (y)

The selected target variable is:

`species`

It represents the Iris flower category that a classification model would attempt to predict.

## Target Classes

The dataset contains three target classes:

1. Setosa
2. Versicolor
3. Virginica

Each class contains 50 observations.

| Target Class | Number of Records |
|---|---:|
| setosa | 50 |
| versicolor | 50 |
| virginica | 50 |
| Total | 150 |

## Classification Problem Type

This is a **Multiclass Classification** problem because the target variable contains three possible categories.

A classification algorithm could use the four numerical flower measurements to predict whether a flower belongs to Setosa, Versicolor, or Virginica.

## Project Files

- `Task_36_Classification_Dataset_Analysis.ipynb` — Complete Google Colab notebook.
- `iris_classification_dataset.csv` — Original Iris dataset.
- `selected_classification_dataset.csv` — Selected features and target.
- `classification_features.csv` — Four input feature columns.
- `classification_target.csv` — Target variable.
- `target_classes.csv` — Target classes and their sample counts.
- `feature_target_summary.csv` — Feature and target explanations.
- `requirements.txt` — Required Python libraries.
- `README.md` — Project documentation.
- `project_report.pdf` — Formal project report.
- `screenshots/` — Actual execution evidence.

## Conclusion

This project demonstrates the basic structure of a classification problem by identifying numerical input features, a categorical target variable, and its possible target classes.

The Iris Dataset contains four input features and three target classes, making it a multiclass classification dataset.

The exercise provides a foundation for understanding classification problems before developing machine-learning classification models.
