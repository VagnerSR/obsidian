If y = f(g(x)), then the derivative of y with respect to x is:

$$\frac{dy}{dx} = f'(g(x)) \cdot g'(x)$$
where:

- f′(g(x)) is the derivative of the outer function f(u), evaluated at u = g(x),
- g′(x) is the derivative of the inner function g(x).
### Example: y=(3x²+2)⁴

#### Step 1: Identify the inner and outer functions:

- Outer function: f(u)=u⁴,
- Inner function: g(x)=3x² + 2.

#### Step 2: Differentiate the outer function:

$$\frac{d}{du}[u^4] = 4u^3$$

Replace u with g(x):

$$f'(g(x)) = 4(3x^2 + 2)^3$$

#### Step 3: Differentiate the inner function:

$$g'(x) = \frac{d}{dx}[3x^2 + 2] = 6x$$

#### Step 4: Multiply the results:

$$\frac{dy}{dx} = f'(g(x)) \cdot g'(x) = 4(3x^2 + 2)^3 \cdot 6x$$

Simplify:

$$\frac{dy}{dx} = 24x(3x^2 + 2)^3$$