---
title: Introduction to Limits
navigation_weight: 1
---

# Introduction to Limits

The concept of a **limit** is the foundational building block of Calculus. It allows us to examine what a function approaches as the input gets closer and closer to a specific point.

### 📘 Definition of a Limit
> Let $f(x)$ be a function defined on an open interval around $a$, except possibly at $a$ itself. We say that the **limit of $f(x)$ as $x$ approaches $a$ is $L$**, written as:
>
> $$ \lim_{x \to a} f(x) = L $$
>
> if we can make the values of $f(x)$ arbitrarily close to $L$ by taking $x$ to be sufficiently close to $a$ (but not equal to $a$).

---

### 🔢 Example 1: Evaluating a Simple Limit

Let's evaluate the following limit behaviorally:

$$ \lim_{x \to 2} (3x + 1) $$

**Solution:**
As $x$ gets closer to 2, the term $3x$ gets closer to $3(2) = 6$. Therefore, adding 1 gives us:

$$ \lim_{x \to 2} (3x + 1) = 7 $$

### ✏️ Exercise 1

Evaluate $\displaystyle \lim_{x \to 3} (x^2 - 4)$.

<details>
<summary>Show Solution</summary>

Since $x^2 - 4$ is a polynomial, we can substitute $x = 3$ directly:

$$ \lim_{x \to 3} (x^2 - 4) = 3^2 - 4 = 5 $$

</details>

<details>
<summary>Hint</summary>

Try factoring the numerator.

</details>
### ✏️ Exercise 2

Evaluate $\displaystyle \lim_{x \to 3} (x^2 - 4)$.

<details>
<summary>Show Solution</summary>

$$ \frac{x^2 - 9}{x - 3} = \frac{(x-3)(x+3)}{x-3} = x + 3 $$

So the limit as $x \to 3$ is $6$.

</details>

### ✏️ Exercise 3

Evaluate $\displaystyle \lim_{x \to 3} (x^2 - 4)$.

<details>
<summary>Answer</summary>

$6$

<details>
<summary>Full Solution</summary>

Factor, cancel, then substitute $x = 3$...

</details>

</details>

