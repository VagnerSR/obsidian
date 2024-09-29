$$P(events)=\frac{outcomes\;that\;meet\;criteria}{all\;possible\;outcomes}$$

### The Addition Rule (for **non-mutually exclusive** events)

$$P(A\;or\;B) = P(A)+P(B) - P(A\;and\;B)$$
The addition rule is used to find the probability of **either** event A **or** event B happening. We add the probabilities of each event, but since the events could both occur, we subtract the probability of A **and** B happening together (so we don't count it twice).

### Example:

If you're rolling a 6-sided die, and event A is rolling an even number, and event B is rolling a number greater than 3, then:

- P(A) = 3/6 = 0.5 (even numbers are 2, 4, 6),
- P(B )= 3/6 = 0.5 (numbers greater than 3 are 4, 5, 6),
- P(A  and  B) = 2/6 = 1/3 (numbers that are even and greater than 3 are 4, 6).

Thus, using the addition rule:

$$P(A  or  B)=0.5+0.5−\frac{1}{3}=\frac{5}{6}≈0.833$$

### Mutually Exclusive/Disjoint  P(A and B) = 0

$$P(A\;or\;B) = P(A)+P(B)$$
When events A and B are **mutually exclusive**, they cannot happen at the same time (disjoint events). Therefore, the probability of A  and  B occurring together is 0. In this case, the probability of A  or  B happening is simply the sum of the individual probabilities.

### Example:

If you draw a card from a deck, and event A is drawing a heart, and event B is drawing a spade, these events are mutually exclusive (you can't draw a heart and a spade at the same time):

$$P(A  or  B)=P(heart)+P(spade)=\frac{13}{52}+\frac{13}{52}=\frac{26}{52}=0.5$$
### Multiplication Rule

$$P(A\;and\;B) = P(A).P(B)$$
The multiplication rule is used when events A and B are **independent**, meaning the occurrence of one does not affect the probability of the other. In this case, the probability of both events happening together is the product of their individual probabilities.

### Example:

If you flip a coin and roll a die, and event A is getting heads, and event B is rolling a 3:

$$P(A  and  B)=P(heads)×P(3)=\frac{1}{2}×\frac{1}{6}=\frac{1}{12}$$

### Dependent Events

$$P(A\;and\;B) = P(A).P(B | A)$$

For **dependent events**, the occurrence of one event affects the probability of the other. In this case, we calculate the probability of A  and  B by multiplying the probability of A by the **conditional probability** of B given A, denoted as (B|A). This represents the probability of event B occurring **after** event A has already occurred.

### Example:

If you're drawing two cards from a deck without replacement, and event A is drawing a heart on the first draw, and event B is drawing a heart on the second draw:

$$P(A  and  B)=P(heart\;on\;1st\;draw)×P(heart\;on\;2nd\;draw|heart\;on\;1st\;draw)$$
$$P(A \; \text{and} \; B)  = \frac{13}{52} . \frac{12}{51} = \frac{156}{2652} \approx 0.059$$

