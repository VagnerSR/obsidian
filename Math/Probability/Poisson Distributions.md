A **Poisson distribution** is used to model the number of times an event occurs within a fixed interval of time or space. The events must happen independently of each other, and the average rate (mean) of occurrences is constant. It's often used for situations where events happen at random but at a known average rate.

- Counts occurrences over some measurement
- Same mean for every interval
- Event count is independent for each interval
- Non-overlapping intervals

$$P(x) = \frac{\lambda^{x} e^{-\lambda}}{x!}$$

Where:

- P(x) is the probability of observing exactly x events.
- λ is the **average number of events** occurring in the interval (also called the rate).
- x! is the **factorial** of x, which counts how many ways x events can occur.
- e is Euler's number (approximately 2.71828), the base of the natural logarithm.

### **Breaking down the formula:**

- **λ^x**: This represents the rate λ raised to the power of x. It reflects the probability that exactly x events happen given an average rate of λ occurrences.    
- **e^−λ**: This part accounts for the **Poisson decay**, meaning that the likelihood of many events happening decreases as λ increases.    
- **x!**: This is the factorial of x, representing the number of ways x events can happen.    

### **Example:**

A carpenter is able to build 3 chairs per day, on average. Find the probability that he can build 5 chairs tomorrow.

$$P(5) = \frac{3^{5} e^{-3}}{5!} ≈ 0.1008$$

The probability that the carpenter will build exactly 5 chairs tomorrow is approximately **0.1008**, or **10.08%**.