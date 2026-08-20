# 🌸 Iris Logistic Regression — Binary Classification

> A hands-on Machine Learning project implementing **Logistic Regression** for a binary classification problem using the classic Iris dataset.

---

## 📌 Project Overview

This project focuses on understanding and implementing **Logistic Regression**, one of the fundamental supervised learning algorithms used for classification problems.

The **Iris dataset** is loaded directly from the Seaborn library and explored through basic Exploratory Data Analysis (EDA). The original multi-class dataset is converted into a **binary classification problem**, followed by data preparation, model training, prediction, hyperparameter exploration, and model evaluation.

The main objective of this project was to understand how a classification model works in practice — from exploring the dataset to training and evaluating the model.

---

## 🎯 Objectives

Through this project, the following concepts were explored:

- Understanding Logistic Regression
- Understanding Binary Classification
- Performing basic Exploratory Data Analysis
- Visualizing feature relationships using Pairplot
- Preparing data for Machine Learning
- Splitting data into training and testing sets
- Training a Logistic Regression model
- Understanding Logistic Regression hyperparameters
- Making predictions
- Evaluating model performance

---

## 📊 Dataset

The **Iris dataset** contains measurements of iris flowers belonging to different species.

It consists of four numerical features:

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |

The original dataset contains three classes. For this project, it was converted into a **binary classification problem** by selecting two classes.

### Dataset Loading

The dataset was loaded directly using Seaborn:

```python
import seaborn as sns

df = sns.load_dataset("iris")
