When using the **sampling distribution of the sample mean** to make inferences about a population, certain conditions must be met to ensure the validity of the results. These conditions are necessary for using the normal approximation and calculating the probability or confidence intervals based on the sample mean. Let’s break them down:

### **1. Random Sample**:

The sample must be **randomly selected** from the population. Random sampling ensures that every individual has an equal chance of being included in the sample, which helps reduce bias and makes the sample more representative of the population.

---

### **2. Normality (Large Counts)**:

According to the **Central Limit Theorem (CLT)**, if the sample size n ≥ 30, the sampling distribution of the sample mean x\bar will be approximately normal, even if the population distribution is not normal.

- If the population itself is known to be **normally distributed**, then this condition is automatically met, regardless of the sample size.
- For smaller sample sizes (n < 30), it is important that the population is normal or close to normal for this approximation to hold.

This ensures the reliability of using normal distributions for inference.

---

### **3. Independence (10% Rule)**:

The observations must be **independent** of each other. This condition is often satisfied if the sample is small relative to the population.

- When sampling **without replacement**, we use the **10% rule**, which states that the sample size n should be no more than 10% of the population size N. In other words, n ≤ 0.10. This ensures that the probabilities of individual outcomes remain roughly constant.

---

### **Standardized Test Statistic for the Sample Mean**:

Once the conditions for inference are satisfied, we can use the **Z-test statistic** to determine how far the sample mean x is from the population mean μ in terms of standard errors.

The formula for the **Z-test statistic** for the sample mean is:

$$Z_\bar{x} = \frac{\bar{x} - \mu}{\sigma_\bar{x}} = \frac{\bar{x} - \mu}{\frac{\sigma}{\sqrt{n}}}$$
Where:

- x is the sample mean.
- μ is the population mean.
- σx​ is the standard error of the sample mean, calculated as σ/sqrt of n​, where σ is the population standard deviation and n is the sample size.

This **Z-score** tells us how many standard deviations the sample mean x is away from the population mean μ. If the Z-score is large, it suggests that the sample mean is significantly different from the population mean.


[[Sampling Distribution of the Sample Mean]]
[[Empirical Rule - Normal distributions and Z-score]]