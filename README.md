# 🧠 MPHY0041 Coursework Notebook (2024/25)

This repository contains a Jupyter notebook for the **MPHY0041** module coursework. The notebook demonstrates statistical and machine learning techniques applied to a biomedical dataset, with a focus on **classification tasks for dementia diagnosis**.

---

## 📘 Notebook Overview

### `Notebook_MPHY0041_2425_CW1.ipynb`

The notebook is structured into two main exercises:

---

### 🔹 Exercise 1: Understanding Decision Boundaries

This section explores different methods for modeling decision boundaries in a classification context.

- **(a) Univariate Decision Boundary**  
  Visualization of a simple threshold-based classifier using one feature.

- **(b) Linear Regression Boundary**  
  Analysis of the inadequacy of linear regression for classification tasks using continuous decision boundaries.

- **(c) Multimodal Boundary**  
  Investigation of nonlinear or multimodal decision boundaries and how they behave across different feature spaces.

---

### 🔹 Exercise 2: Logistic Regression on Dementia Dataset

This part focuses on implementing and analyzing logistic regression using various optimization techniques. The dataset includes features extracted from patient data for dementia classification (e.g., CN vs. MCI vs. AD).

#### ✅ Tasks Covered:

- **(a) Logistic Regression via Iteratively Reweighted Least Squares (IWLS)**
  - Manual implementation of IWLS to estimate model parameters.
  - Comparison of coefficients with `sklearn`’s logistic regression output.

- **(b) Logistic Regression using Gradient Descent**
  - Implementation of logistic regression using custom gradient descent.
  - Comparison with IWLS in terms of coefficient magnitudes and convergence.

- **(c) Logistic Regression with L2 Regularization**
  - Extension of gradient descent by adding a regularization term to prevent overfitting.
  - Demonstrates the effect of regularization strength on coefficient shrinkage.

---

## 📊 Key Outputs

- **Confusion Matrix** visualizing model performance  
  ![Confusion Matrix](images/conf_matrix.png)
- Plots showing convergence of cost functions, coefficient behavior, and decision boundaries

---

## 📁 Project Files

- `Notebook_MPHY0041_2425_CW1.ipynb`: Core analysis notebook
- `Dementia_train.csv`: Training dataset used for classification (assumed)
- `images/conf_matrix.png`: Visualization output from model evaluation

---

## 🔧 Requirements

Install required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
