A **Geometric Random Variable** models the number of **independent Bernoulli trials** required to get the first success, where each trial has only two possible outcomes: **success** or **failure**. The probability of success p remains constant across trials.

### Key Properties of Geometric Random Variables:

1. **Independent Trials**: Each trial is independent, meaning the outcome of one trial doesn't affect the others.
2. **Outcome**: Each trial results in either a "success" (coded as 1) or "failure" (coded as 0).
3. **Constant Probability**: The probability of success, p, stays the same for each trial.

The probability mass function (PMF) of a geometric random variable gives the probability of getting the first success on the n-th trial:
### Probability Mass Function (PMF):

$$P(X=n) = p(1-p)^{n-1}$$
Where:
- n is the number of trials until the first success.
- p is the probability of success on each trial.
- 1−p is the probability of failure.
### Example for Finding Probability:

If p=0.2 and you want to find the probability of having the first success on the 4th trial:

$$P(X=4)=0.2×(1−0.2)^{4−1}=0.2×0.8³=0.2×0.512=0.1024$$

Thus, the probability of getting the first success on the 4th trial is about **0.1024** or **10.24%**.

### Less than/At most
If you want the probability of getting the first success **within the first n trials** (i.e., at most n), you sum the probabilities for the first n trials:

$$P(X≤n)=P(X=1)+P(X=2)+⋯+P(X=n)$$

Alternatively, this can be calculated using the cumulative distribution function (CDF):

$$P(X≤n)=1−(1−p)^n$$

This formula gives the probability of achieving success in the first n trials.

### More than/At least

If you want the probability of having **more than n trials before the first success** (i.e., at least n+1 trials), this is the complement of having success within the first n trials:

$$P(X>n)=(1−p)^n$$

### Mean
$$E(X) = \frac{1}{p}$$
This tells us, on average, how many trials are needed before the first success occurs. For example, if p=0.2, the expected number of trials before success is 
$$E(X)=\frac{1}{0.2} = 5$$ trials.

### Variance and Standard Deviation

$$\sigma²_x= \frac{1-p}{p²}$$

These formulas show how the spread of outcomes is related to the probability of success p. A smaller p (low probability of success) increases both the expected number of trials and the variability in the number of trials needed to get the first success.