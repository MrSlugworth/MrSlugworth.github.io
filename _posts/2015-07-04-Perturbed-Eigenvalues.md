---
layout: Some Notes About Matrix Perturbation
title: First Post
---

In this post we list some facts about the behavior of the eigenvalues of matrices when those matrices are perturbed.

**Theorem** Let $$A$$ be a real symmetric matrix, then the eigenvectors of $$A$$ are orthogonal with respect to the standard inner product on $$\mathbb{R}^n$$.

>**Definition:** The spectral norm $$\| A\|_2$$ of a square matrix $$A$$ is the square root of the maximum eigenvalue of $$A^HA$$.

Note that $$\|\cdot \|_2$$ is invariant under unitary transformations. Further, we can write this another way, following Strang *Linear Algebra and Applications* sec. 7.2:

$$ \lambda_{max}(A^TA)=\frac{x^T\lambda_{max}x}{x^Tx}=\frac{x^TA^TAx}{x^Tx}=\max \frac{\|Ax\|_2}{\|x\|_2},$$

where $$\|\cdot \|_2$$ is the standard $$L^2$$-norm.

Now note that if our matrix $$A$$ is symmetric then $$\|A\|_2$$ is equal to the maximum of its eigenvalues. To see this note that if $$\{v_1,...,v_n\}$$ is an orthogonal eigenbasis for $$A$$, which exists by the theorem, then $$A(c_1v_1+c_nv_n)$$ will be maximized when all of the $$c_i$$ are $$0$$ except for those at the maximum eigenvalue. 

Now from Stewart and Sun's *Matrix Perturbation*, p. 192, we have the following theorem:

**Theorem:** If $$A$$ is a normal matrix and $$\tilde{A}=A+E$$, then 

$$
\text{sv}_A(\tilde{A})\le \|E\|_2,
$$
where 

$$\text{sv}_A(\tilde{A}):=\max_i \min_j \left|\tilde{\lambda}_i-\lambda_j \right|. $$


[Wikipedia: Eigenvalue Perturbation](https://en.wikipedia.org/wiki/Eigenvalue_perturbation)

[Spectral Norm](http://mathworld.wolfram.com/SpectralNorm.html)

[SS90], [Par98], [Bha96], [Bau85], and [Kat70]
