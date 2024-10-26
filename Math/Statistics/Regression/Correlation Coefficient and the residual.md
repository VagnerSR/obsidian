### Correlation Coefficient (r)

The **correlation coefficient**, denoted as r, measures the strength and direction of the linear relationship between two variables, x and y. Its value ranges from −1- to 1, where:

- r=1: Perfect positive linear relationship (as x increases, y increases).
- r=−1: Perfect negative linear relationship (as x increases, y decreases).
- r=0: No linear relationship between x and y.

The formula for r is:
$$r=\frac{1}{n-1}\sum(\frac{x_i-\bar{x}}{s_x})(\frac{y_i-\bar{y}}{s_y})$$

Where:

- n is the number of data points.
- xi​ and yi are the individual data points for the variables x and y, respectively.
- x\ba and y\bar are the means (averages) of the xxx and y values.
- sx​ and sy​ are the standard deviations of the x and y values.

### Explanation of the Formula:

- xi−x\bar/sx​​ and yi−y\bar/sy​​​ are the **standardized values** (z-scores) of xxx and y, which tell us how far each data point is from the mean in terms of standard deviations.
- The product of the standardized values for each data point is calculated and summed.
- The sum is then divided by n−1 to account for sample size, which gives the average of the product of standardized values.

### Interpretation of r:

- r > 0: Indicates a positive correlation (both variables tend to increase together).
- r < 0: Indicates a negative correlation (as one variable increases, the other tends to decrease).
- r = 0: No linear correlation between the variables (although there might still be some other type of relationship).

The closer r is to 1 or −1, the stronger the linear relationship between the variables.

---

### Residual

The **residual** is the difference between the actual value and the predicted value from a regression model. It measures how far off a model's prediction is from the observed data. Residuals are used to assess the accuracy of a regression model.

$$Residual = Actual - Predicted$$
- **Actual Value** (yi​): The observed data point for y.
- **Predicted Value** (y\hat ​i​): The value of y predicted by the regression line for a given x.

### Interpretation of Residuals:

- **Positive residual**: The actual value is greater than the predicted value (the model under-predicted).
- **Negative residual**: The actual value is less than the predicted value (the model over-predicted).
- **Residual of 0**: The model's prediction is exactly correct for that point.

The sum of all residuals is typically 0 in a least-squares regression, but the **squared residuals** help measure the overall error of the model. If residuals are randomly scattered around 0, the model fits well; patterns in residuals suggest that the model may be missing some aspect of the data.



[[Correlation coefficient]]