When we take multiple random samples from a population and calculate the mean of each sample, these sample means form their own distribution, known as the **sampling distribution of the sample mean**. This distribution helps us understand the behavior of the sample mean in relation to the population mean. Even if the population distribution is not normal, the sampling distribution of the sample mean will approach normality as the sample size increases, thanks to the **Central Limit Theorem (CLT)**.

### Central Limit Theorem
The **Central Limit Theorem** states that if you take a sufficiently large random sample (n ≥ 30 is often used as a rule of thumb) from any population with a finite mean μ and finite standard deviation σ, the sampling distribution of the sample mean x\bar will be approximately normally distributed, regardless of the shape of the population distribution.

- This is powerful because it allows us to make inferences about population parameters using the normal distribution, even if the original data isn't normally distributed.


### Variance of the Sample Mean
The variance of the sample mean is smaller than the variance of the population because the sample mean is an average of n observations. The formula is:
$$\sigma²_\bar{x} = \frac{\sigma²}{n}$$
Where:

- σ²x​ is the variance of the sample mean.
- σ² is the population variance.
- n is the sample size.

### Standard Deviation of the Sample Mean (Standard Error)
The **standard deviation** of the sample mean is called the **standard error** (SE). It represents how much variability there is in the sample mean from one sample to another. The formula is:
$$\sigma_\bar{x} = \frac{\sigma}{\sqrt{n}}$$
Where:

- σx is the standard error (SE).
- σ is the population standard deviation.
- n is the sample size.
### Variance (Sample Estimate)
If we don't know the population variance σ, we use the **sample variance** S² to estimate it:
$$S²_\bar{x} = \frac{S²}{n}$$

Where:

- S²x is the sample variance of the sample mean.
- S² is the sample variance.
- n is the sample size.

### Standard Deviation (Sample Estimate)
The **standard error** of the sample mean can also be estimated using the sample standard deviation S, which is denoted as:
$$S_\bar{x} = \frac{S}{\sqrt{n}} = SE$$

Where:

- Sx is the estimated standard error.
- S is the sample standard deviation.
- n is the sample size.
###  Finite Population Correction Factor
When sampling without replacement from a **finite population** (with population size N), the **finite population correction factor** adjusts the standard error to account for the fact that sampling without replacement reduces variability. The correction factor is applied when the sample size is relatively large compared to the population size (typically when n≥5% of N).

The correction factor is:

$$* = \sqrt{\frac{N-n}{N-1}}$$
Where:

- N is the total population size.
- n is the sample size.

This factor reduces the standard error to account for the fact that a large sample relative to the population size reduces variability.