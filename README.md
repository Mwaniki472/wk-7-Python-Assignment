# Analyzing Data with Pandas and Visualizing Results with Matplotlib

## 📌 Objective
This project demonstrates how to:
- Load and explore a dataset using **pandas**.
- Perform basic data analysis (descriptive statistics, grouping).
- Visualize results with **matplotlib** and **seaborn**.

The **Iris dataset** is used in this project, loaded either from:
- `scikit-learn` (`load_iris`) **OR**
- CSV from Seaborn’s GitHub repository.


# 📊 Tasks Completed

## 🔹 Task 1: Load & Explore
- Loaded dataset (Iris).
- Displayed first rows with `.head()`.
- Checked structure with `.info()`.
- Verified missing values with `.isnull().sum()`.

## 🔹 Task 2: Basic Analysis
- Computed descriptive statistics using `.describe()`.
- Grouped by species and calculated mean values.

## 🔹 Task 3: Visualizations
- **Line Chart** – Sepal length trend across samples.
- **Bar Chart** – Average petal length per species.
- **Histogram** – Distribution of sepal width.
- **Scatter Plot** – Relationship between sepal length and petal length, color-coded by species.
"""

# Print as Markdown inside Jupyter Notebook
from IPython.display import Markdown, display
display(Markdown(tasks_completed))



