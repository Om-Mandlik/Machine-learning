# Naive Bayes Classifier

## Overview
Naive Bayes is a family of probabilistic machine learning algorithms based on **Bayes' Theorem**. It is "naive" because it assumes that the presence of a particular feature in a class is **unrelated** to the presence of any other feature. Despite this simplistic assumption, it performs remarkably well in many real-world applications.

## How It Works
The algorithm calculates the probability of a data point belonging to a specific class given its features.

### The Mathematical Foundation
The core formula is based on Bayes' Theorem:

$$P(C|X) = \frac{P(X|C)P(C)}{P(X)}$$

Where:
* **$P(C|X)$ (Posterior):** The probability of the class ($C$) given the features ($X$).
* **$P(X|C)$ (Likelihood):** The probability of seeing these features ($X$) given the class ($C$).
* **$P(C)$ (Prior):** The initial probability of the class ($C$) occurring.
* **$P(X)$ (Evidence):** The probability of the features ($X$) occurring across all classes.

---
