### Permutations
$$nP_k = \frac{n!}{(n-k)!}$$


- **Permutations** are used when the order of the items **matters**.
- **n** is the total number of items you have to choose from.
- **k** is the number of items you are choosing.
- **(n−k)!** accounts for the leftover items you are **not** choosing.

If k = n, then just calculate n!.

The formula calculates the number of ways to choose and arrange k items from n items **in a specific order**.
#### Example:

How many ways can you arrange 3 books from a shelf of 5 books?

Here n=5 and k=3:

$$5P_3=\frac{5!}{(5−3)!}=\frac{5!}{2!}=\frac{5×4×3×2×1}{2×1}=\frac{120}{2}=60$$

So, there are 60 ways to arrange 3 books out of 5.

### Combinations
$$nC_k = \frac{n!}{k!(n-k)!}$$


- **Combinations** are used when the order of the items **does not matter**.
- n is the total number of items.
- k is the number of items you are choosing.
- n! accounts for all possible ways to arrange n items.
- k! adjusts for the fact that the order of the chosen k items doesn’t matter.
- (n−k)! accounts for the leftover items you are not choosing.

The formula calculates the number of ways to choose k items from n items **without regard to order**.
#### Example:

How many ways can you choose 3 books from a shelf of 5 books, if the order doesn’t matter?

Here n=5 and k=3:

$$5C_3=\frac{5!}{3!(5−3)!}=\frac{5!}{3!2!}=\frac{5×4×3×2×1}{(3×2×1)(2×1)}=\frac{120}{12}=10$$

So, there are 10 ways to choose 3 books from 5, if the order doesn't matter.