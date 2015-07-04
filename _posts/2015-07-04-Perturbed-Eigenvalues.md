---
layout: post
title: First Post
---

In this post we list some facts about the behavior of the eigenvalues of matrices when those matrices are perturbed.

**Theorem** Let $$A$$ be a real symmetric matrix, then the eigenvectors of $$A$$ are orthogonal with respect to the standard inner product on $$\mathbb{R}^n$$.

>**Definition:** The spectral norm $$\| A\|_2$$ of a square matrix $$A$$ is the square root of the maximum eigenvalue of $$A^HA$$.

Note that $$\|\cdot \|_2$$ is invariant under unitary transformations. Further, we can write this another way, following Strang *Linear Algebra and Applications* sec. 7.2:
$$ \lambda_{max}(A^TA)=\frac{x^T\lambda_{max}x}{x^Tx}=\frac{x^TA^TAx}{x^Tx}=\max \frac{\|Ax\|_2}{\|x\|_2},$$
where $$\|\cdot \|_2$$ is the standard $$L^2$$-norm.

[Wikipedia: Eigenvalue Perturbation](https://en.wikipedia.org/wiki/Eigenvalue_perturbation)

[Spectral Norm](http://mathworld.wolfram.com/SpectralNorm.html)

[SS90], [Par98], [Bha96], [Bau85], and [Kat70]
