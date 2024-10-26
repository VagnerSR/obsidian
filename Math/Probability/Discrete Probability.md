### Mean (expected value)
The mean, or expected value μ_x​, of a random variable X is a measure of the central tendency, or the "average" value, that X takes on, weighted by the probabilities of each outcome.

The formula for the **expected value** is:

$$\mu_x= E(X) = \sum X_i P(X_i)$$

Where:

- X_i​ are the possible values of the random variable X.
- P(X_i​) is the probability of each value X_i​.

The formula means that you multiply each possible value of X by its probability, and then sum those products.

#### Example:

Let’s say X is the number of heads in two coin flips, and the probabilities of getting 0, 1, or 2 heads are given as follows:

- P(0) = 0.25
- P(1 )= 0.50
- P(2) = 0.25

The expected value would be:

$$\mu_x=0⋅0.25+1⋅0.50+2⋅0.25=0+0.50+0.50=1$$

So, the expected number of heads in two coin flips is 1.

### Variance and Standard Deviation

Variance σ²_x​ is a measure of how spread out the values of X are around the mean μ_x​. Standard deviation σ_x​ is the square root of the variance and provides a measure of the average distance from the mean.

The formula for **variance** is:
$$\sigma²_x= \sum(X_i-\mu_x)²P(X_i)$$

Where:

- X_i are the possible values of the random variable X.
- μ_x​ is the mean (expected value) of X.
- P(X_i) is the probability of each value X_i​.
- (X_i−μ_x)² is the squared deviation of each value from the mean.

The variance is found by calculating the squared deviations from the mean for each value, weighting them by the probabilities of each outcome, and then summing them.

#### Example:

Using the same example as above with X as the number of heads in two coin flips:

- X=0, 1, 2 with probabilities 0.25, 0.50, 0.25, and the expected value μ_x=1.

Now, calculate the variance:

$$\sigma²_x=(0−1)²⋅0.25+(1−1)²⋅0.50+(2−1)²⋅0.25 = 0.50$$

So, the variance σ²_x=0.50.

The **standard deviation** is the square root of the variance:

$$\sigma_x=\sqrt{\sigma²_x}=\sqrt{0.50}≈0.707$$