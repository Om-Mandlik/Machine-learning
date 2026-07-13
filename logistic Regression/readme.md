**Logistic Regression on Titanic Dataset**


## Overview
This project demonstrates the implementation of **Logistic Regression** using the **Titanic Dataset** to predict whether a passenger survived or not based on different features.

The model is trained using supervised machine learning techniques and evaluated using classification metrics.

---
## Dataset
The Titanic Dataset contains information about passengers aboard the Titanic, including demographic details and travel information.

### Features
- PassengerId - Unique passenger ID
- Pclass - Passenger class
- Sex - Gender of passenger
- Age - Age of passenger
- SibSp - Number of siblings/spouses aboard
- Parch - Number of parents/children aboard
- Fare - Ticket fare
- Embarked - Port of embarkation

### Target
- Survived - Survival status (0 = No, 1 = Yes)

---
## *What is Logistic Regression?*

Logistic Regression is a **supervised machine learning classification algorithm** used to predict the probability of a categorical outcome. Unlike Linear Regression, which predicts continuous values, Logistic Regression predicts the probability that an input belongs to a particular class.

It is commonly used for **binary classification** problems, where the target variable has two possible outcomes (e.g., Yes/No, True/False, 0/1).

---

### Logistic (Sigmoid) Function

The core of Logistic Regression is the **Sigmoid Function**, which converts any real-valued number into a probability between **0** and **1**.

$$
\sigma(z)=\frac{1}{1+e^{-z}}
$$

Where:

- **σ(z)** — Predicted probability
- **e** — Euler's number (≈ 2.718)
- **z** — Linear combination of input features

---

### Linear Model

Before applying the sigmoid function, Logistic Regression computes a linear combination of the input features:

$$
z=\beta_0+\beta_1x_1+\beta_2x_2+\cdots+\beta_nx_n
$$

Where:

- **β₀** — Intercept (bias)
- **β₁, β₂, ..., βₙ** — Feature coefficients (weights)
- **x₁, x₂, ..., xₙ** — Input features

---

### Logistic Regression Equation

The predicted probability is calculated as:

$$
P(y=1|x)=\frac{1}{1+e^{-(\beta_0+\beta_1x_1+\beta_2x_2+\cdots+\beta_nx_n)}}
$$

If the predicted probability is:

- **≥ 0.5** → Class **1** (Survived)
- **< 0.5** → Class **0** (Did Not Survive)

---

