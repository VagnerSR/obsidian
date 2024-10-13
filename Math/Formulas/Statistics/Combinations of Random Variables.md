### Mean
$$\mu_A = \mu_x + \mu_y$$

### Standard deviation
$$\sigma²_A = \sigma²_x + \sigma²_y$$


### Example

A popcorn company fills each of its variety popcorn tins with three flavors of popcorn: white cheddar, caramel, and chocolate covered. The amount of each flavor of popcorn that gets packed in the tin is normally distributed with a mean of 1 pound and a standard deviation of 0.1 pounds. The amount of each popcorn flavor is independent from the other flavors.
If W is the total weight of popcorn in a randomly selected tin, find the probability that the tin contains less than 3.25 pounds. We have three normally distributed variables, one for each flavor. Their means are

White cheddar μ_D = 1 
Caramel μ_M = 1 
Chocolate covered μ_C = 1

Therefore, the mean of the combination (the mean weight of a full tin) is 
$$μ_W = μ_D + μ_M + μ_C $$
$$ μ_W = 1 + 1 + 1 $$
$$μ_W = 3 $$

The standard deviations of the three normally distributed variables are
White cheddar σ_D = 0.1 
Caramel σ_M = 0.1 
Chocolate covered σ_C = 0.1

To find the standard deviation of the combination (the standard deviation of the weight of a full tin), we’ll find the variance of the combination.
$$σ²_W = σ²_D + σ²_M + σ²_C $$
$$σ²_W = 0.1² + 0.1² + 0.1² $$
$$σ²_W = 0.01 + 0.01 + 0.01 $$
$$σ²_W = 0.03 $$

So the standard deviation is
$$\sigma_w = \sqrt{0.03} ≈ 0.1732$$

Now that we have the mean μ_W = 3 and standard deviation σ_W ≈ 0.1732 of the normally distributed weight of the full tin, we can answer probability questions about the combined normal distribution. We want to find the probability that the tin contains less than 3.25 pounds, so we’ll calculate the z-score for 3.25.

$$Z = \frac{x - \mu_w}{\sigma_w}$$
$$Z = \frac{3.25 - 3}{0.1732} ≈ 1.44 $$
If we look up z = 1.44 in a z-table, we find the value 0.9251, which means there’s an approximately 93 % chance that the weight of the full tin is less than 3.25 pounds.


[[Empirical Rule - Normal distributions and Z-score]]