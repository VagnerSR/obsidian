
$$f(x)=\frac{N(x)}{D(x)}​$$
where N(x) and D(x) are polynomials.

### 1. **Vertical Asymptotes (VA)**

#### **Definition**:

A vertical asymptote occurs at the values of x where the function is undefined due to division by zero in the denominator, provided that the numerator does not also become zero (i.e., no cancellations).

#### **Steps**:

1. Set the denominator D(x)=0.
2. Solve for x.
3. Check that these roots do not cancel with roots of the numerator N(x).

#### Example:

$$f(x) = \frac{x}{x^2 - 4}$$

1. Set D(x)=0: x² -4 = 0 gives x = ±2.
3. These are vertical asymptotes because the numerator does not cancel with the denominator.

---

### 2. **Horizontal Asymptotes (HA)**

#### **Definition**:

A horizontal asymptote describes the behavior of f(x) as x→∞ or x→−∞. The horizontal asymptote depends on the **degree** of N(x) (numerator) and D(x) (denominator):

#### **Rules**:

1. If deg⁡(N) < deg⁡(D): y = 0 (horizontal asymptote at zero).
2. If deg⁡(N) = deg⁡(D): $$y = \frac{\text{leading coefficient of } N}{\text{leading coefficient of } D}$$
3. If deg⁡(N) > deg⁡(D): No horizontal asymptote (but see **Slant Asymptotes** below).

#### Example:

$$f(x) = \frac{2x^2 + 3x}{x^2 - 1}$$

1. deg⁡(N) = deg⁡(D) = 2, so horizontal asymptote: 
2. $$y = \frac{\text{leading coefficient of } N}{\text{leading coefficient of } D} = \frac{2}{1} = 2$$

---

### 3. **Slant (Oblique) Asymptotes**

#### **Definition**:

A slant (or oblique) asymptote occurs when the degree of N(x) is **exactly one more than** the degree of D(x). The slant asymptote is found by performing polynomial long division on $$\frac{N(x)}{D(x)}$$

#### **Steps**:

1. Perform polynomial long division of N(x) by D(x).
2. The quotient (ignoring the remainder) is the equation of the slant asymptote.

#### Example:

$$f(x) = \frac{x^2 + 2x + 1}{x + 1}$$

1. Perform division: 
 $$\frac{x^2 + 2x + 1}{x + 1} = x + 1 \quad \text{(ignoring the remainder)}$$. The slant asymptote is y = x + 1.

---

### Summary Table for Rational Functions f(x)=N(x)/D(x)

| **Asymptote Type** | **Condition**                  | **How to Find**                                                   |
| ------------------ | ------------------------------ | ----------------------------------------------------------------- |
| Vertical           | D(x)=0, N(x)≠0 at those values | Solve D(x)=0                                                      |
| Horizontal         | deg⁡(N) vs deg⁡(D):            | Compare degrees: deg⁡(N) < deg⁡(D): y = 0, etc.                   |
| Slant              | deg⁡(N) = deg⁡(D)+1            | Perform polynomial long division; use quotient for the asymptote. |

