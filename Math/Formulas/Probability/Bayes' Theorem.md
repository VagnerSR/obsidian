Bayes' Theorem is a formula used to determine the probability of an event A happening **given** that another event B has already occurred. This is known as **conditional probability**. The formula is written as:
$$P(A|B)= \frac{P(B|A).P(A)}{P(B)}$$

Where:

- P(A∣B) is the **conditional probability** of event A occurring given that event B has occurred.
- P(B∣A) is the **conditional probability** of event B occurring given that event A has occurred.
- P(A) is the **prior probability** of event A (the probability that A will occur regardless of B).
- P(B) is the **marginal probability** of event B (the probability that B will occur).

### **Intuition Behind Bayes' Theorem**:

Bayes' Theorem allows us to update our beliefs about the probability of event A after learning that event B has occurred. In other words, it helps to refine probabilities when new information becomes available.

- **Prior probability** (P(A)): This is the original probability of event A before considering the new information (event B).
- **Likelihood** (P(B∣A)): This is how likely event B is if A has already occurred.
- **Posterior probability** (P(A∣B)): This is the updated probability of A, after considering that B has occurred.

### **Example**:

Let's say a medical test is 99% accurate in detecting a disease (i.e., 99% true positive and true negative rates), but the disease is very rare—only 0.1% of the population has it.

- A: The event that a person has the disease.
- B: The event that a person tests positive for the disease.

#### Step 1: Information needed for the formula

- P(A) = 0.001: The prior probability of having the disease (0.1% of the population has the disease).
- P(B∣A) = 0.99: The likelihood of testing positive given that a person has the disease (99% test accuracy).
- P(B): The total probability of testing positive (whether or not the person has the disease). This is calculated using the **Law of Total Probability**.

$$P(B)=P(B∣A)⋅P(A)+P(B∣¬A)⋅P(¬A)$$

Where:

- P(B∣¬A)=0.01 is the probability of testing positive when you **don’t** have the disease (false positive rate).
- P(¬A)=0.999 is the probability of not having the disease.

$$P(B)=(0.99×0.001)+(0.01×0.999)=0.00099+0.00999=0.01098$$

#### Step 2: Apply Bayes' Theorem

Now, we can calculate the probability that a person actually has the disease given that they tested positive (P(A∣B)):

$$P(A∣B)=\frac{P(B∣A)⋅P(A)}{P(B)}=\frac{0.99×0.001}{0.01098}≈0.0902$$

### **Interpretation**:

Even though the test is 99% accurate, the probability that a person who tests positive actually has the disease is only **9%**. This is because the disease is very rare, so most positive results are false positives.