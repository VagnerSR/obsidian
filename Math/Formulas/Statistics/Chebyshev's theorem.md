**Chebyshev's Theorem** provides a way to determine the minimum proportion of data that falls within a certain number of standard deviations from the mean, regardless of the shape of the distribution. It applies to all data sets, whether normally distributed or not.

### Chebyshev's Theorem:

For any data set, at least 1-1/k² of the data values will lie within **k** standard deviations of the mean, where **k** is any number greater than 1.

### Formula:
$$k = \frac{x - \mu}{\sigma}$$

$$1-\frac{1}{k²}$$
### Key Points:

- **k** is the number of standard deviations from the mean.
- This theorem applies to **any distribution**, whether it's normal, skewed, or irregular.

### Examples:

1. For **k=2** (within 2 standard deviations of the mean):
    
    $$1-\frac{1}{2²}=0.75$$
    
    At least **75%** of the data lies within 2 standard deviations of the mean.
    
2. For **k=3** (within 3 standard deviations of the mean):
    
    $$1-\frac{1}{3²}=0.889$$
    
    At least **88.9%** of the data lies within 3 standard deviations of the mean.
    

### Application:

Chebyshev’s theorem is useful when the distribution is not known or not normal. It guarantees that, for example, at least 75% of the data will be within 2 standard deviations from the mean in any data set. This can help understand data dispersion even without assuming a specific distribution shape.

### Chebyshev vs. Empirical Rule:

- The **empirical rule** applies specifically to normal distributions and provides more precise percentages (68%, 95%, 99.7%).
- **Chebyshev’s theorem** is more general and applies to any distribution, though it provides a minimum percentage (e.g., at least 75% within 2 standard deviations).