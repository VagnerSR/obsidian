A confidence interval provides a range of values within which the true population parameter (e.g., mean or proportion) is expected to fall, with a certain level of confidence. The general form of a confidence interval for a population mean is:

$$(a, b) = \bar{x} \pm Z_{\alpha/2}\;\sigma_{\bar{x}}$$
Where:

- x-bar is the sample mean.
- Zα/2 (or Z∗) is the critical value corresponding to the confidence level.
- σx-bar​ is the standard error of the sample mean.

### Common Confidence Levels:
| Confidence Level (CL) | Alpha (α) | Z-Value (Zα/2​) | t-Value (tα/2​) (for n−1 degrees of freedom)                |
| --------------------- | --------- | --------------- | ----------------------------------------------------------- |
| 90%                   | 0.10      | 1.65            | t0.05​ (varies by n, for n=10, t=1.833; for n=30 t=1.699)   |
| 95%                   | 0.05      | 1.96            | t0.025​ (varies by n, for n=10, t=2.262; for n=30, t=2.045) |
| 99%                   | 0.01      | 2.58            | t0.005​ (varies by n, for n=10, t=3.169; for n=30, t=2.756) |
### Margin of Error (ME)

The margin of error represents the amount of error expected in a sample estimate due to sampling variability. It is calculated using:
$$ME=Z_{\alpha/2}\;\sigma_{\bar{x}}$$

Where Zα/2​ is the Z-score for the desired confidence level, and σx-bar​ is the standard error of the sample mean.


### Standard Error (σx-bar​)

The standard error measures the variability of the sample mean and is given by:
$$\sigma_\bar{x} = \frac{\sigma}{\sqrt{n}}$$
Where σ is the population standard deviation and n is the sample size.

### Sample Size Calculation

To calculate the required sample size n for a given margin of error (ME), you can use the following formula:
$$n=(\frac{Z^*\sigma}{ME})²$$
Where:

- Z∗ is the Z-score corresponding to the confidence level.
- σ is the population standard deviation.
- ME is the desired margin of error.

### Finite Population Correction Factor

If you're sampling without replacement and your sample size is more than 5% of the total population, use the **finite population correction factor** to adjust the standard error:
$$\sqrt{\frac{N-n}{N-1}}$$

Where N is the population size, and n is the sample size.

### Confidence Interval for Small Samples (n < 30)

When the sample size is smaller than 30 and the population standard deviation is unknown, use the **t-distribution** instead of the Z-distribution. The formula becomes:
$$(a, b) = \bar{x} \pm t_{\alpha/2}\;s_{\bar{x}}$$
Where:

- tα/2 is the critical value from the t-distribution with n−1 degrees of freedom.
- sx-bar​ is the sample standard error
$$s_\bar{x} = \frac{s}{\sqrt{n}}$$
In this case, s is the sample standard deviation. The t-distribution accounts for the added uncertainty due to the small sample size.


[[Empirical Rule - Normal distributions and Z-score]]
[[T-distribution]]
[[Confidence Interval (CI) of the Proportion]]