The derivative of a function represents the **rate of change** of the function with respect to its input variable. It tells us how the function f(x) behaves locally around a point x.

### Difference Quotient

The formula:
$$\frac{f(c+\Delta x) - f(c))}{\Delta x}$$
represents the **average rate of change** of f(x) over the interval c,c + Δx.

---

### Derivative Definition

The derivative of f(x) at a point c is obtained by taking the limit as Δx→0 (or equivalently h→0):
$$f^{\prime}(c) = \lim_{\Delta x \to 0} \frac{f(c+\Delta x) - f(c))}{\Delta x}$$
We can generalize this to any x:
$$f^{\prime}(x) = \lim_{h \to 0} \frac{f(x+h) - f(x))}{h}$$
This is the **instantaneous rate of change** of f(x) at x, or the slope of the tangent to the graph of f(x) at x.

### Exemple:
$$f(x)=x²-5x+6$$
#### Step 1: Write the difference quotient

$$f^{\prime}(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$

#### Step 2: Compute f(x+h)

Substitute x+h into f(x) = x² − 5x + 6:

$$f(x+h) = (x+h)^2 - 5(x+h) + 6$$

Expand:

$$f(x+h) = x^2 + 2xh + h^2 - 5x - 5h + 6$$

#### Step 3: Compute f(x+h)−f(x)

Subtract f(x)= x² − 5x + 6:

$$f(x+h) - f(x) = \left(x^2 + 2xh + h^2 - 5x - 5h + 6\right) - \left(x^2 - 5x + 6\right)$$

Simplify:

$$f(x+h) - f(x) = 2xh + h^2 - 5h$$

#### Step 4: Form the difference quotient

Divide by h:

$$\frac{f(x+h) - f(x)}{h} = \frac{2xh + h^2 - 5h}{h}$$

Simplify:

$$\frac{f(x+h) - f(x)}{h} = 2x + h - 5$$

#### Step 5: Take the limit as h→0

$$f^{\prime}(x) = \lim_{h \to 0} (2x + h - 5) = 2x - 5$$

---

### Final Answer

The derivative of f(x) = x2 − 5x + 6 is:

$$f^{\prime}(x) = 2x - 5$$


[[Slope Intercept]] [[Point slope]]