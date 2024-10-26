$$(a, b) = \hat{p} \pm Z_{\alpha/2}\;\sqrt{\frac{\hat{p}(1-\hat{p})}{n}}$$


### Margin of Error (ME)
$$ME = Z_{\alpha/2}\;\sqrt{\frac{\hat{p}(1-\hat{p})}{n}}$$

### Finite Population Correction Factor
$$\sqrt{\frac{N-n}{N-1}}$$


### Common Confidence Levels:
| Confidence Level (CL) | Alpha (α) | Z-Value (Zα/2​) | t-Value (tα/2​) (for n−1 degrees of freedom)                |
| --------------------- | --------- | --------------- | ----------------------------------------------------------- |
| 90%                   | 0.10      | 1.65            | t0.05​ (varies by n, for n=10, t=1.833; for n=30 t=1.699)   |
| 95%                   | 0.05      | 1.96            | t0.025​ (varies by n, for n=10, t=2.262; for n=30, t=2.045) |
| 99%                   | 0.01      | 2.58            | t0.005​ (varies by n, for n=10, t=3.169; for n=30, t=2.756) |
### Sample Size Calculation
$$n = \left( \frac{Z^* \cdot \sqrt{p(1 - p)}}{ME} \right)^2$$
Where:

- n is the minimum sample size.
- Z∗ is the critical Z-value corresponding to the desired confidence level (e.g., for 95% confidence, Z∗ = 1.96).
- p is the estimated proportion (or if you don't know p, you can use p=0.5 for maximum variability, which gives the largest sample size).
- 1−p is the complement of the proportion.
- ME is the desired margin of error.


[[Confidence Interval (CI) of the Mean]]