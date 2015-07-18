---
layout: post
title: CA 6.1
date: 2015-07-13 21:53:00 +04:00
---

The Rational Root Theorem
--------------------------

Let $$f(x)=a_{n}x^n+a_{n-1}x^{n-1}+...+a_0$$ be an integer polynomial. Then the rational roots theorem states that all rational roots of $$f$$ have the form $$p/q$$ where $$p\mid a_0$$ and $$q\mid a_{n}$$. To see that $$p\mid a_0$$, plut $$p/q$$ into $$f$$ and then clear the denominator so that we have

$$
p^na_n+\cdots+q^na_0=0,
$$
so then considering the equation modulo $$q$$ gives the result. For the other result, consider the equation modulo $$p$$. 

Here is an easy application:

Let $$f(x)=x^3+6x^2-32$$. Define $$T_{c,f}(x)=\sum_{n=0}^\infty a_n(x-c)^n$$ to be the Taylor series centered at $$c$$ of $$f$$. For what values does $$a_0=0$$. 

* $$c=3,2$$
* $$c=-3,3,-2$$
* $$c=4,2$$
* $$c=-4,2,-2$$
* $$c=-4,2$$

The term $$a_n$$ is $$f^{(n)}(c)$$, so this is just asking for where $$f(x)=0$$. Now we are only presented with integer roots, So, by the rational roots theorem, we see that these roots must be divisors of $$32$$. So, we nede only check $$\pm 2,4$$. In particular we know that only one of each of these will be a root because the leading term is odd and the remaining terms are even. Now plugging in $$4$$ and $$2$$, we find the roots $$-4$$ and $$2$$.
