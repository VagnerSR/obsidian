### Coefficient of Determination (R²)

The **coefficient of determination**, R², measures the proportion of the variance in the dependent variable (y) that is predictable from the independent variable (x).

- **Interpretation**:
    
    - R² = 1: The model explains all the variability of the data perfectly.
    - R² = 0: The model explains none of the variability, meaning the model's predictions are no better than the mean of y.
    
    **Formula**:
    
    $$R^2 = 1 - \frac{\text{Sum of squared residuals (SSR)}}{\text{Total sum of squares (SST)}}$$
    
    Where:
    
    - **SSR** (sum of squared residuals): The sum of the squared differences between actual values and predicted values.
    - **SST** (total sum of squares): The sum of the squared differences between actual values and the mean of y.

In simpler terms, R² indicates how well the regression model fits the data.
### Root Mean Square Error (RMSE)

**RMSE** measures the average error between predicted and actual values in a regression model. It's the square root of the mean of the squared residuals (errors).

- **Formula**:
$$RMSE = \sqrt{\frac{\sum e²}{n}}$$

- Where:
    - e = residuals (difference between the actual and predicted values, i.e., e=y−y\hat​).
    - n = number of data points.

**Interpretation**:

- Lower RMSE values indicate a better fit of the model to the data.
- RMSE gives an idea of the **average size of the prediction error** in the same units as the dependent variable.

Both R² and RMSE are used to evaluate the performance of regression models, but they offer different insights: R² tells you how well the model explains the variance, while RMSE tells you the magnitude of prediction errors.