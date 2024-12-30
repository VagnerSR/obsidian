A **limit** describes the behavior of a function f(x) as the input x approaches a specific value a, which might or might not be in the domain of the function. Formally, we write:

$$\lim_{x \to a} f(x) = L$$

if f(x) gets arbitrarily close to L as x gets arbitrarily close to a from both the left (LHL) and the right (RHL).

For your function:

$$f(x)=\sqrt{x(5-x)}$$

it is defined only when x(5−x) ≥ 0, which simplifies to 0 ≤ x ≤ 5. Outside this interval, f(x) is not real-valued.

### Limits at Specific Points

#### 1. lim⁡x→4f(x)

Since x=4 lies within the domain [0,5], we calculate the function value and check the behavior around this point:

$$f(x) = \sqrt{4(5-4)} = \sqrt{4 \cdot 1} = 2$$

As x approaches 4 from either direction, the function smoothly approaches 2:

$$\lim_{x \to 4} f(x) = 2$$

**LHL (x→4−)**: Approaching from the left (x<4), the function approaches 2.  
**RHL (x→4+)**: Approaching from the right (x>4), the function also approaches 2.  
Since LHL = RHL, the limit exists, and lim⁡x→4f(x)=2.

---

#### 2. lim⁡x→−4f(x)

For x=−4, the point is outside the domain [0,5], so f(x) is not defined here.

lim⁡x→−4f(x) does not exist (undefined).

---

#### 3. lim⁡x→5f(x)

At x=5, the function's value is:

$$f(5) = \sqrt{5(5-5)} = \sqrt{0} = 0$$

**LHL (x→5−)**: Approaching from the left (x<5), f(x) = \sqrt{x(5-x)} → 0.  
**RHL (x→5+)**: Approaching from the right (x>5), f(x) is undefined since x>5 lies outside the domain.

Thus, the limit from the left exists and is 0, but the limit from the right does not exist. Therefore:

$$\lim_{x \to 5} f(x) \text{ does not exist.}$$
### Limits of combinations

For limits of combinations like sums, differences, products, and quotients of functions, use the following properties:

$$\lim_{x \to a} [f(x) + g(x)] = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$$
$$\lim_{x \to a} [f(x)  g(x)] = \lim_{x \to a} f(x) . \lim_{x \to a} g(x)$$
$$\lim_{x \to a} [\frac{f(x)}{g(x)}] = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}, if \; \lim_{x \to a} g(x) \neq 0$$

### Limits of composites

For composite functions f(g(x)), we use the rule:

$$\lim_{x \to a} f(g(x)) = f\left(\lim_{x \to a} g(x)\right)$$

provided f is continuous at lim⁡x→ag(x). For your function, if a composition arises, ensure the inner limit is within the domain of the outer function.
