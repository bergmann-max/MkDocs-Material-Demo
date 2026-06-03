---
tags:
  - Reference
---

# Math

[KaTeX](https://katex.org/) is a fast, lightweight library for typesetting mathematical expressions. Material for MkDocs integrates with both KaTeX and [MathJax](https://www.mathjax.org/).

=== "Block syntax"

    ````
    $$
    \cos x = \sum_{k=0}^{\infty} \frac{(-1)^k}{(2k)!} x^{2k}
    $$
    ````

    $$
    \cos x = \sum_{k=0}^{\infty} \frac{(-1)^k}{(2k)!} x^{2k}
    $$

=== "Inline syntax"

    ````
    The homomorphism $f$ is injective if and only if its kernel is only the
    singleton set $e_G$, because otherwise $\exists a, b \in G$ with
    $a \neq b$ such that $f(a) = f(b)$.
    ````

    The homomorphism $f$ is injective if and only if its kernel is only the
    singleton set $e_G$, because otherwise $\exists a, b \in G$ with
    $a \neq b$ such that $f(a) = f(b)$.

=== "More examples"

    **Quadratic formula:**

    ````
    $$
    x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
    $$
    ````

    $$
    x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
    $$

    **Matrix multiplication:**

    ````
    $$
    \begin{pmatrix}
    a & b \\
    c & d
    \end{pmatrix}
    \begin{pmatrix}
    e & f \\
    g & h
    \end{pmatrix}
    =
    \begin{pmatrix}
    ae + bg & af + bh \\
    ce + dg & cf + dh
    \end{pmatrix}
    $$
    ````

    $$
    \begin{pmatrix}
    a & b \\
    c & d
    \end{pmatrix}
    \begin{pmatrix}
    e & f \\
    g & h
    \end{pmatrix}
    =
    \begin{pmatrix}
    ae + bg & af + bh \\
    ce + dg & cf + dh
    \end{pmatrix}
    $$

    **Bayes' theorem:**

    ````
    $$
    P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
    $$
    ````

    $$
    P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
    $$
