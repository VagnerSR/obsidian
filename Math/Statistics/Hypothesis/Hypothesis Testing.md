### 1. Hypotheses 
- **Null Hypothesis (H₀):** This is the default assumption that there is no effect or no difference. It is what we aim to test against.
    
- **Alternative Hypothesis (Hₐ):** This is the hypothesis that there is an effect or a difference. It’s what we hope to support with evidence from the data.
### 2. Significance 
- **Level of Confidence (1 - α):** The probability that the confidence interval will contain the true population parameter. A 95% confidence level is common, meaning there's a 5% chance of error.
    
- **Alpha Value (α):** The significance level, representing the probability of committing a **Type I Error** (rejecting the null hypothesis when it's actually true). A typical alpha value is 0.05.
    
- **Type I Error (α):** Occurs when the null hypothesis is rejected when it is true.
    
- **Type II Error (β):** Occurs when the null hypothesis is not rejected when it is false. The power of a test is 1−β, which is the probability of correctly rejecting a false null hypothesis.
### 3. Test Statistic
The test statistic helps determine whether to reject the null hypothesis. It compares the observed data with the null hypothesis.

- **Region of Rejection:** The set of all values of the test statistic that leads to the rejection of the null hypothesis.
    
- **Two-tailed test:** Used when the alternative hypothesis does not specify a direction of the effect. Both ends of the distribution are considered.
    
    - Example: Testing if the mean is not equal to a specific value.
- **One-tailed test:** Used when the alternative hypothesis specifies a direction of the effect (greater than or less than).
    
    - **Upper-tail test:** Tests if the sample mean is significantly greater than the population mean.
    - **Lower-tail test:** Tests if the sample mean is significantly less than the population mean.

### 4. Test Formulas

#### For the Mean

- When the standard deviation (**σ**) is known:
$$Z=\frac{\bar{x}-\mu}{\frac{\sigma}{\sqrt{n}}}$$
 Where x-bar is the sample mean, μ is the population mean, σ is the population standard deviation, and n is the sample size.
 
- When the standard deviation (**σ**) is unknown (large sample size) or when it is unknown (small sample size and normally distributed population):
$$t=\frac{\bar{x}-\mu}{\frac{S}{\sqrt{n}}}$$
Where S is the sample standard deviation.

#### For Proportions
$$z=\frac{\hat{p}-p}{\sqrt{\frac{p(1-p)}{n}}}$$
Where p-hat​ is the sample proportion, p is the population proportion, and n is the sample size.
### 5. Critical Values
- The **critical value** corresponds to the significance level (α) and separates the region of rejection from the region of acceptance.
    
- **P-value:** The probability of obtaining a test statistic at least as extreme as the one observed, under the assumption that the null hypothesis is true. It tells you how likely your data would occur if the null hypothesis is true.
    
    - If the **p-value** is less than or equal to α: **Reject H₀** (evidence supports Hₐ).
        
    - If the **p-value** is greater than α: **Fail to reject H₀** (not enough evidence to support Hₐ).




[[Empirical Rule - Normal distributions and Z-score]]
