# Linear Regression

## 1 Overview

### 1.1 Regression

Regression is defined as explaining the variance in $y$ using the variance observed in $x$.

### 1.2 Evaluation Metrics

#### Summary

<div style="display: inline-block">

|   # | Metric     |           Range |
| --: | :--------- | --------------: |
|   1 | MAE        |  $[0,\,\infty)$ |
|   2 | MSE        |  $[0,\,\infty)$ |
|   3 | RMSE       |  $[0,\,\infty)$ |
|   4 | $R^2$      | $(-\infty,\,1]$ |
|   5 | Adj. $R^2$ | $(-\infty,\,1]$ |
|   6 | V.I.F      |  $[1,\,\infty)$ |

</div>

### 1.3 Model Diagnostic

#### Assumptions of Linear Regression

<div style="display: inline-block">

|   # | Assumption              | Variables involved                                                        |
| --: | :---------------------- | :------------------------------------------------------------------------ |
|   1 | Assumption of Linearity | Between Independent variables $X$ and Target variable $y$                 |
|   2 | No Multicollinearity    | Among Independent variables $X$                                           |
|   3 | No Heteroscedasticity   | Between Residuals $(y\,-\,\hat{y})$ and Predicted Target values $\hat{y}$ |
|   4 | No Autocorrelation      | Between Residuals $(y\,-\,\hat{y})$ and Actual Target values $y$          |
|   5 | Normality of Residuals  | Distribution of Residuals $(y\,-\,\hat{y})$                               |

</div>

### 1.4 Hyperparameters

List of most common hyperparameters that can be tuned for Linear Regression:

1. Learning Rate
2. Regularization parameter
