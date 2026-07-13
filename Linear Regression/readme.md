# **Linear Regression on Boston Housing Dataset**

## *Overview*

This project demonstrates the implementation of **Linear Regression** using the **Boston Housing Dataset** to predict housing prices based on various features such as crime rate, number of rooms, property tax rate, and more. The project covers data preprocessing, model training, prediction, and evaluation using standard regression metrics.

## *Dataset*

The dataset used in this project is the **Boston Housing Dataset**, which contains information collected by the U.S. Census Service concerning housing in the Boston area.


<h4>Features</h4>

Some important features include:

- **CRIM** — Crime rate by town
- **ZN** — Proportion of residential land zoned
- **INDUS** — Non-retail business acres per town
- **CHAS** — Charles River dummy variable
- **NOX** — Nitric oxide concentration
- **RM** — Average number of rooms per dwelling
- **AGE** — Proportion of owner-occupied units built before 1940
- **DIS** — Weighted distance to employment centers
- **RAD** — Accessibility to radial highways
- **TAX** — Property tax rate
- **PTRATIO** — Pupil-teacher ratio
- **B** — Proportion of Black residents (transformed variable)
- **LSTAT** — Percentage of lower-status population

## *Target Variable*

- **MEDV** — Median value of owner-occupied homes (in \$1000s)

## *What is Linear Regression?*

Linear Regression is one of the simplest and most widely used **supervised machine learning algorithms** for solving **regression problems**. It models the relationship between one or more independent variables (features) and a dependent variable (target) by fitting the best possible straight line through the data.

The goal of Linear Regression is to find the line that minimizes the difference between the actual values and the predicted values.

### Linear Regression Equation

For a single feature:

$$
y = mx + c
$$

Where:

- **y** — Predicted value
- **x** — Input feature
- **m** — Slope (coefficient)
- **c** — Intercept

For multiple features (Multiple Linear Regression):

$$
y = \beta_0 + \beta_1x_1 + \beta_2x_2 + \cdots + \beta_nx_n
$$

Where:

- **β₀** — Intercept
- **β₁...βₙ** — Feature coefficients
- **x₁...xₙ** — Input features
- **y** — Predicted output

---


## *Technologies Used*

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


## *Results*

The trained model predicts housing prices based on the given input features. The performance is evaluated using regression metrics, and visualizations are used to compare the actual and predicted values.

## *Conclusion*

This project serves as a beginner-friendly introduction to regression analysis using the Boston Housing Dataset. It demonstrates the complete machine learning pipeline—from data preprocessing and model training to evaluation and prediction—providing a solid foundation for building more advanced regression models.
