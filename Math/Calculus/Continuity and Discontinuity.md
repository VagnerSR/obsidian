Continuity is a fundamental concept in calculus that describes whether a function behaves "smoothly" at a given point or over an interval.

### **Definition of Continuity**

A function f(x) is said to be **continuous** at a point x=c if the following three conditions are satisfied:

1. **The function is defined at x=c:**
    
    $$f(c) \text{ exists.}$$
2. **The limit of f(x) as x→c exists:**
    
    $$\lim_{x \to c} f(x) \text{ exists.}$$
3. **The value of the limit equals the value of the function:**
    $$\lim_{x \to c} f(x) = f(c).$$

If any of these conditions fail, the function is **discontinuous** at x=c.

### Types of Discontinuity

Discontinuities can be classified into several types based on how the function "breaks":

#### 1. Removable Discontinuity

Occurs when a hole exists in the graph of the function. This happens if:

$$\lim_{x \to c} f(x) \text{ exists, but } f(c) \text{ is not defined or } \lim_{x \to c} f(x) \neq f(c).$$

Example:

$$f(x) = \begin{cases} x^2 & \text{if } x \neq 2 \\ 5 & \text{if } x = 2 \end{cases}​$$

Here, lim⁡x→2f(x)=4, but f(2)=5, so there is a removable discontinuity at x=2.

---

#### 2. Jump Discontinuity

Occurs when the left-hand limit (LHL) and right-hand limit (RHL) at x=cx = cx=c are not equal:

$$\lim_{x \to c^-} f(x) \neq \lim_{x \to c^+} f(x).$$

Example:

$$f(x) = \begin{cases} 1 & \text{if } x < 0 \\ 2 & \text{if } x \geq 0 \end{cases}​$$

Here, lim⁡x→0−f(x)=1 and lim⁡x→0+f(x)=2, so there is a jump discontinuity at x=0.

---

#### 3. Infinite Discontinuity

Occurs when f(x) approaches infinity (∞) or negative infinity (−∞) as x→c:

$$\lim_{x \to c^-} f(x) = \infty \quad \text{or} \quad \lim_{x \to c^+} f(x) = -\infty.$$

Example:

$$f(x) = \frac{1}{x}​$$

At x=0, the function has an infinite discontinuity because lim⁡x→0−f(x)=−∞ and lim⁡x→0+f(x)=∞.

---

#### 4. Oscillatory Discontinuity

Occurs when f(x) oscillates infinitely as x→c, preventing the limit from existing.

Example:

$$f(x) = \sin\left(\frac{1}{x}\right)$$

As x→0, the function oscillates increasingly rapidly, so there is an oscillatory discontinuity at x=0.

---

### Graphical Interpretation

- **Continuous**: A graph that can be drawn without lifting the pencil.
- **Discontinuous**: A graph with a "break," "jump," or "hole."

---

### Formal Test for Continuity

To check whether f(x) is continuous at x=c:

1. Evaluate f(c) (exists?).
2. Compute lim⁡x→c−f(x) and lim⁡x→c+f(x).
3. Check if: $$\lim_{x \to c} f(x) = f(c).$$