When we take random samples from a population and calculate the sample proportion (denoted as p\hat, the proportions from different samples form their own distribution, known as the **sampling distribution of the sample proportion**. This distribution allows us to make inferences about the population proportion p using the sample proportion p\hat​.

### Mean of the Sampling Distribution of the Sample Proportion:

The mean of the sampling distribution of the sample proportion p\hat​ is equal to the true population proportion p.

$$\mu_{\hat{p}} = p$$

This means that, on average, the sample proportion p\hat​ will be equal to the population proportion p, given that the sample is random and large enough.
### Standard error
The **standard error** (SE) of the sample proportion tells us how much variability we can expect in the sample proportion p\hat​ from one sample to another. It depends on both the population proportion p and the sample size n. The formula for the standard error is:

$$SE = \sigma_{\hat{p}} = \sqrt{\frac{p(1 - p)}{n}}$$

Where:

- SE or σp\hat​​ is the standard error of the sample proportion.
- p is the true population proportion.
- n is the sample size.

This formula shows that the standard error decreases as the sample size increases, meaning larger samples provide more precise estimates of the population proportion. It also reflects that the variability depends on how close the proportion p is to 0.5. When p is close to 0 or 1, the variability is smaller.

### Conditions for Using the Standard Error:

For the standard error formula to provide a good approximation, two conditions must be met:

1. **Random Sample**: The sample must be randomly selected from the population.
2. **Large Sample Size (Normal Approximation)**: The sample size must be large enough for the sampling distribution to be approximately normal. This is typically satisfied if: np ≥ 10 and n(1−p) ≥ 10. This ensures there are enough successes and failures in the sample to use the normal approximation.


[[Sampling Distribution of the Sample Mean]]