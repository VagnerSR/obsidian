The **Conditions for Sampling Distribution of the Sample Proportion (SDSP)** are the criteria we must check to ensure that the sampling distribution of the sample proportion behaves approximately normally. This is important when we want to use statistical techniques that rely on normal distribution properties, such as hypothesis testing and confidence intervals.

Here are the conditions:
### 1. Random Condition

- The sample must be selected **randomly** from the population. This ensures that the sample is representative of the population, and the sample proportion is an unbiased estimator of the population proportion.
- If the sampling is not random, the sample might not represent the true variability of the population, leading to inaccurate conclusions.

**Why it's important**: Ensures that results generalize to the population, reducing bias.

### 2. Normal Condition (Large Counts Condition)

- The sample size n must be large enough so that the sampling distribution of the sample proportion is approximately normal. For this, we use the **Large Counts Rule**, which requires that both of the following conditions hold: np ≥ 10 and n(1−p) ≥ 10
- Where:
    - p is the population proportion of success.
    - n is the sample size.
    - np represents the expected number of successes.
    - n(1−p) represents the expected number of failures.

**Why it's important**: Ensures that the sample proportion distribution can be approximated by a normal distribution, which is critical for making reliable inferences.

- If both np ≥ 10 and n(1−p) ≥ 1, we can assume the distribution of the sample proportion is approximately normal.
- If either condition is not met, the distribution may be skewed, and the normal approximation may not be accurate.

### 3. Independence Condition (10% Rule)

- If sampling is done **without replacement**, the sample size must be no more than 10% of the population. This ensures that the observations in the sample are approximately independent of one another. n ≤ 0.10N
- Where:
    - N is the population size.
    - n is the sample size.

**Why it's important**: Ensures that the probability of success in each trial doesn't change significantly due to sampling without replacement. This keeps the assumption of independence in place.

- If the sample is more than 10% of the population, the probabilities can change significantly from one selection to the next, which violates the assumption of independent trials. When this condition is violated, the **finite population correction factor** can sometimes be used to adjust for it.

[[Sampling Distribution of the Sample Proportion]]
[[Conditions for Inference with the SOSM]]