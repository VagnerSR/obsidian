The Chi-square test is a statistical method that evaluates whether there is a significant difference between observed and expected frequencies in categorical data. The general formula:

$$\chi²=\sum \frac{(observed-expected)²}{expected}$$
measures how well the observed data fits the expected distribution. When the calculated χ² value is large, it suggests that the observed data deviates significantly from the expected data, pointing to a potentially non-random effect.

### Inference Conditions for Chi-square Tests

For Chi-square tests to be valid, several inference conditions should be met:

1. **Random**: The sample data should be collected randomly to ensure that it is representative of the population.
    
2. **Normal**: In the context of Chi-square, "normal" doesn’t refer to a normal distribution but rather to expected frequency. Each category should have a sufficiently large expected frequency, typically at least 5. If expected frequencies are too low, the Chi-square test may not be reliable.
    
3. **Independent**: Observations within the sample should be independent of each other. This condition is especially important to avoid overcounting or dependent measures.
    

### Types of Chi-square Tests

1. **Test of Homogeneity**:
    
    - **Purpose**: Determines if the distribution of a categorical variable is the same across multiple groups.
    - **Setup**: Involves two or more groups with a single categorical variable.
    - **Example**: Testing whether different regions have similar distributions of customer satisfaction ratings.
2. **Test of Association (or Independence)**:
    
    - **Purpose**: Determines if there is an association between two categorical variables within a single group.
    - **Setup**: Typically uses a contingency table (like a 2x2 table) to see if the occurrence of one variable is independent of the other.
    - **Example**: Testing if gender and preference for a particular product are related in a single group of survey respondents.
3. **Goodness of Fit**:
    
    - **Purpose**: Tests whether an observed frequency distribution matches a specified theoretical distribution.
    - **Setup**: Compares observed counts for a single categorical variable to expected counts based on a known distribution.
    - **Example**: Testing if the roll results of a six-sided die match an expected uniform distribution (1/6 chance for each number).

### Degrees of Freedom and Confidence Level

1. **Degrees of Freedom (df)**:
    
    - The degrees of freedom depend on the Chi-square test being used:
        - **Goodness of Fit**: df = k−1, where k is the number of categories.
        - **Test of Homogeneity and Association**: df = (r−1)×(c−1), where r is the number of rows and c is the number of columns in a contingency table.
2. **Confidence Level**:
    
    - Chi-square tests use a confidence level to determine significance. Typically, a 95% confidence level (or α = 0.05) is chosen. If the p-value from the Chi-square test is less than the significance level, we reject the null hypothesis, indicating a significant difference between observed and expected values.
