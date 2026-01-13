## Theory

### Introduction to Regression and Curve Fitting
Regression and curve fitting are statistical techniques used to model the relationship between an independent variable and a dependent variable using experimental or observed data. In practical situations, data points rarely lie exactly on a straight line or smooth curve due to measurement errors, noise, or inherent variability. Regression analysis aims to find a mathematical model that best represents the underlying trend of the data.

Curve fitting involves selecting an appropriate mathematical function and estimating its parameters so that the difference between the observed data and the predicted values is minimized.

### Least-Square Method
The Least-Square method is one of the most widely used techniques for curve fitting. The objective of this method is to determine the parameters of a model such that the sum of the squares of the errors between the observed values and the predicted values is minimized.

For a linear regression model:

𝑦 = 𝑚𝑥+𝑐

the error at a data point 𝑖 is:

ei​=yi​−(mxi​+c)

The least-square criterion minimizes:

<img width="78" height="87" alt="image" src="https://github.com/user-attachments/assets/a14bae44-a93f-40ec-819f-c0e353955630" />

This approach ensures that the fitted curve has the smallest overall deviation from the observed data points.

### Weighted Least-Square Method
The Weighted Least-Square method is an extension of the least-square technique in which different weights are assigned to different data points. This is useful when some observations are more reliable than others.

The objective function becomes:

<img width="111" height="85" alt="image" src="https://github.com/user-attachments/assets/79efd187-9e45-4fdc-a1c7-a9597861d413" />

where 𝑤𝑖 represents the weight associated with the 𝑖-th data point. Higher weights give greater importance to more reliable measurements, improving the accuracy of the fitted model when data uncertainty varies.

### Regression Models Used

#### Linear Regression
Linear regression models a straight-line relationship between variables and is expressed as:

<img width="137" height="26" alt="image" src="https://github.com/user-attachments/assets/e9197ea5-9147-44aa-b4c6-43ac2941d00f" />

It is suitable when the data exhibits a linear trend.

#### Polynomial Regression
Polynomial regression fits a curve of degree 𝑛 and is expressed as:

<img width="359" height="33" alt="image" src="https://github.com/user-attachments/assets/71fdf0c2-7fe9-4af8-8edb-cd0ab73fbe07" />

This model is useful for capturing nonlinear relationships in the data.

#### Exponential Regression
Exponential regression models growth or decay behavior and is given by:

<img width="101" height="37" alt="image" src="https://github.com/user-attachments/assets/cb8363cd-1518-43be-a100-a7414f9a25f9" />

It is commonly used in population growth, radioactive decay, and financial modeling.

### Conceptual Comparison of Fitted Curves (Schematic Description)
Conceptually, regression analysis can be visualized by plotting experimental data points on a graph and overlaying different fitted curves. A linear fit appears as a straight line passing close to the data points, while polynomial and exponential fits appear as curved lines that better follow nonlinear trends. Comparing these curves helps in selecting the most appropriate model for the given dataset.

### Degree of Fit (Coefficient of Determination, R²)
The quality of a fitted regression model is commonly evaluated using the coefficient of determination, denoted as R². It measures how well the regression model explains the variability of the data.

<img width="247" height="82" alt="image" src="https://github.com/user-attachments/assets/44cbf1f3-d6a1-4a7d-b057-79daa362b1eb" />

where:

<img width="348" height="99" alt="image" src="https://github.com/user-attachments/assets/1767890c-f1ef-4e4d-a76e-f8b471a57982" />

An R² value close to 1 indicates a good fit, while a value close to 0 indicates a poor fit.

### Applications of Regression and Curve Fitting
Regression and curve fitting techniques are widely used in engineering, data science, economics, medical research, machine learning, and predictive analytics. These methods enable trend analysis, parameter estimation, and future prediction based on observed data.
