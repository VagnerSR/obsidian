A **binomial random variable** counts the number of successes in a fixed number of independent trials where each trial has two possible outcomes: **success** or **failure**. The binomial distribution models scenarios that fit the following conditions:
- Independent trials
- Success or Failure
- Fixed number of trials
- P(success) is constant

$$P(k\;success\;in\;n\;attempts) = nC_k \;p^{k}(1-p)^{n-k}$$
#### **Breaking down the formula:**

- nC_k​ is the **number of ways** to choose k successes from n trials. This is called a **combination** and is given by:
    $$nC_k = \frac{n!}{k!(n-k)!}$$
    This part of the formula calculates how many different ways k successes can occur out of n trials.
    
- p^k represents the probability of having exactly **k successes**, where each success occurs with probability p. We raise p to the power k to reflect that k successes are occurring.
    
- (1−p)^n−k represents the probability of having exactly **n−k failures**, where each failure occurs with probability 1−p. We raise 1−p to the power n−k to reflect that the remaining n−k trials are failures.

### **Example:**

Suppose we flip a coin 4 times (n = 4), and the probability of getting heads (success) on each flip is p = 0.5. What is the probability of getting exactly 2 heads?

Here:

- n = 4
- k = 2
- p = 0.5
- 1−p = 0.5

Using the binomial formula:

$$P(2  heads  in  4  flips)= 4C_2  (0.5)²(0.5)²$$

First, calculate the combination 4C_2​:

$$4C_2=\frac{4!}{2!(4−2)!}=\frac{4×3}{2×1}=6$$

Now, calculate the full formula:

$$P(2  heads)=6×(0.5)²×(0.5)²=6×0.25×0.25=6×0.0625=0.375$$

So, the probability of getting exactly 2 heads in 4 flips is 0.375, or 37.5%.


### Mean

$$E(X) = np$$

### Variance and Standard Deviation

$$\sigma² = np(1-p)$$

Where n is the number of trials and p is the probability.

[[Permutations and combinations]]