# study-hours-score-regression
A beginner-friendly Python project demonstrating linear regression using NumPy, pandas, scikit-learn, and matplotlib.

# Linear Regression From Scratch

This project demonstrates how to build, train, and evaluate a simple **linear regression model** in Python using a small dataset.  
It is intended as a **beginner-friendly introduction** to machine learning concepts and workflows.

---

## Project Overview

The model predicts a student's exam score based on the number of hours studied.  
The project walks through a complete ML pipeline:

- Creating a dataset
- Splitting data into training and testing sets
- Training a linear regression model
- Making predictions
- Evaluating model performance
- Visualizing results

---

## Technologies Used

- Python
- NumPy
- pandas
- scikit-learn
- matplotlib

---

## Dataset

The dataset is a simple, manually created example:

| Hours Studied | Score |
|--------------|-------|
| 1            | 12    |
| 2            | 25    |
| ...          | ...   |
| 10           | 90    |

---

## How It Works

1. Load and structure the data using pandas
2. Define features (`Hours_Studied`) and target (`Score`)
3. Split the data into training and testing sets
4. Train a linear regression model
5. Make predictions on unseen data
6. Evaluate performance using Mean Squared Error
7. Visualize the regression line and actual data points

---

## Visualization

The final output includes a scatter plot of actual scores and a regression line showing the model’s predictions.
