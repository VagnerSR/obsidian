### 1. **Critical Points**

#### Definition:

A critical point of a function f(x) occurs where:

1. f′(x)=0, or
2. f′(x) is undefined.

Critical points are candidates for:

- **Local maxima**
- **Local minima**
- **Points of horizontal tangency**

#### How to Find Critical Points:

1. Compute the first derivative, f′(x).
2. Solve f′(x)=0.
3. Check where f′(x) is undefined.
4. Verify these points lie within the domain of f(x).

---

### 2. **Inflection Points**

#### Definition:

An inflection point of a function f(x) occurs where the concavity of the function changes, i.e.:

1. The second derivative, f′′(x), changes sign (from positive to negative or vice versa).
2. The second derivative f′′(x)=0 or f′′(x) is undefined at that point.

#### How to Find Inflection Points:

1. Compute the second derivative, f′′(x).
2. Solve f′′(x)=0 or find where f′′(x) is undefined.
3. Test the sign of f′′(x) on either side of these points to confirm a change in concavity.

---

### Key Concepts

#### **Critical Points vs. Inflection Points:**

- Critical points involve the first derivative (f′(x)), often related to the slope of the function.
- Inflection points involve the second derivative (f′′(x)), related to the concavity of the function.

---

### Example: f(x)=x³−6x²+9x+1

#### Step 1: Find Critical Points

1. Compute f′(x):
    
    $$f'(x) = 3x^2 - 12x + 9$$
2. Solve f′(x)=0:
    
    $$3x^2 - 12x + 9 = 0 \implies (x - 1)(x - 3) = 0$$
    
    Critical points: x=1, 3.
    
3. Check where f′(x) is undefined: None, since f′(x) is a polynomial.
    

---

#### Step 2: Find Inflection Points

1. Compute f′′(x):
    
    $$f''(x) = 6x - 12$$
2. Solve f′′(x)=0:
    
    $$6x - 12 = 0 \implies x = 2$$
3. Test the sign of f′′(x) around x=2:
    
    - For x<2, f′′(x)<0 (concave down).
    - For x>2, f′′(x)>0 (concave up).

Inflection point: x=2.

---

#### Step 3: Conclusion

- Critical points: x=1, 3.
- Inflection point: x=2.

By plugging these values back into f(x), you can find their corresponding y-coordinates if needed.

---

### Visualization

1. **Critical points** mark where the function's slope is zero or undefined (possible peaks, valleys, or flat regions).
2. **Inflection points** mark where the curvature changes from concave up to concave down or vice versa.