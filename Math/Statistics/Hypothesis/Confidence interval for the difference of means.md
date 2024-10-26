A **confidence interval for the difference of means** is used to estimate the difference between the population means of two independent groups based on sample data. The confidence interval gives a range of plausible values for the true difference between the population means.

### Formula for Confidence Interval for the Difference of Means

For two independent samples, the confidence interval for the difference of their means (μ1−μ2) can be calculated as:

$$(\bar{x}_1 - \bar{x}_2) \pm Z_{\alpha/2} \sqrt{\frac{\sigma_1^2}{n_1} + \frac{\sigma_2^2}{n_2}}$$

Where:

- x1\bar and x2\bar​ are the sample means for group 1 and group 2, respectively.
- n1​ and n2​ are the sample sizes for group 1 and group 2.
- σ²1​ and σ²2​ are the population variances (if known) or sample variances (if the population variances are unknown).
- Zα/2​ is the critical value from the Z-distribution corresponding to the confidence level. For instance, for a 95% confidence level, Zα/2=1.96.

If the **population standard deviations are unknown**, we use the **sample standard deviations** and switch to the **t-distribution**:

$$(\bar{x}_1 - \bar{x}_2) \pm t_{\alpha/2} \sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}$$

Where:

- s1​ and s2​ are the sample standard deviations.
- tα/2​ is the critical value from the t-distribution, depending on the degrees of freedom, often approximated using **Welch's t-test** or **pooled variance** methods.

### Steps to Calculate the Confidence Interval for the Difference of Means:

1. **State the confidence level**: For example, 95% confidence level implies α=0.05 and Zα/2=1.96.
    
2. **Calculate the point estimate**: This is the difference between the two sample means, x1\bar − x2\bar​.
    
3. **Find the standard error**: The standard error is the square root of the sum of the variances divided by their respective sample sizes:
    
    $$SE = \sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}$$
4. **Find the critical value**: Use Zα/2​ (if standard deviations are known) or tα/2​ (if using sample standard deviations).
    
5. **Construct the confidence interval**:
    
    $$(\bar{x}_1 - \bar{x}_2) \pm (Z_{\alpha/2} \text{ or } t_{\alpha/2}) \times SE$$

### Example:

Suppose we want to estimate the difference in mean test scores between two groups of students. We take independent random samples and get the following results:

- Group 1: xˉ1=80, s1=10, n1=30
- Group 2: xˉ2=85, s2=12, n2=35

At a 95% confidence level:

1. The point estimate is:
    
    $$\bar{x}_1 - \bar{x}_2 = 80 - 85 = -5$$
2. The standard error is:
    
    $$SE = \sqrt{\frac{10^2}{30} + \frac{12^2}{35}} = \sqrt{\frac{100}{30} + \frac{144}{35}} \approx 3.28$$
3. The critical value tα/2​ for 95% confidence and approximate degrees of freedom would be around 2.00 (using a t-table).
    
4. The confidence interval is:
    
    $$(-5) \pm 2.00 \times 3.28 = (-5) \pm 6.56$$
    
    So, the confidence interval is:
    
    (−11.56, 1.56)

### Interpretation:

We are 95% confident that the true difference in mean test scores between the two groups lies between -11.56 and 1.56. Since 0 is in this interval, we cannot conclude that there is a significant difference in means at the 95% confidence level.


### Proportion
$$z=\frac{(\hat{p}_1-\hat{p}_2)-(p_1-p_2)}{\sqrt{\hat{p}(1-\hat{p})(\frac{1}{n_1}+\frac{1}{n_2})}}$$

$$\hat{p}= \frac{\hat{p}_1 n_1+\hat{p}_2 n_2}{n_1+n_2}$$

[[Confidence Interval (CI) of the Mean]]
[[Confidence Interval (CI) of the Proportion]]
![[Hypothesis+testing+for+the+difference+of+means.pdf]]