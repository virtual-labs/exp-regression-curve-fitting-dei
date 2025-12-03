### Procedure

1. **Enter X and Y Data Points**
   - Input the dataset in the text box using the format:
     ```
     x1, y1
     x2, y2
     x3, y3
     ...
     ```
   - Ensure that each line contains a valid pair of numerical values.

2. **Enter Data Weights (Optional)**
   - Provide one weight value per line corresponding to each data point.
   - If equal contribution is needed, assign weight = 1 for all points.
   - This step enables **Weighted Least-Square Regression**.

3. **Select Regression Type**
   - Choose one of the available curve fitting models from the dropdown menu:
     - Linear Regression (y = mx + b)
     - Polynomial Regression (2nd degree)
     - Exponential Regression (y = a e^(b x))

4. **Run Curve Fitting**
   - Click the **Simulate** button.
   - The system will compute regression coefficients using the selected method.

5. **View Results**
   - Observe the fitted curve displayed graphically in the results section.
   - Numerical outputs such as slope, intercept, regression equation, and errors (if provided) will also appear.

6. **Analyze Model Performance**
   - Evaluate how closely the fitted curve matches the observed data points.
   - Modify the dataset, change regression type, or adjust weights to compare outcomes.

7. **Optional Validation**
   - Test multiple regression models to identify which provides the best fit.
   - Check residuals to assess accuracy and curve alignment.
