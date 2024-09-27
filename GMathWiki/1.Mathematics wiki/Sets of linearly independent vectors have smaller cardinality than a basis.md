
---

mathLink: auto

---
Date created: 2023-12-15 15:34
Tags: #Type/Theorem  #Type/Proof #Topic/Linear_Algebra 

Proved by: [[Linear dependence and independence]], [[Bases of vector spaces]], [[Span of a set]]
References: _Not applicable_
Justifications: _Not applicable_

Specializations: _Not applicable_
Generalizations: _Not applicable_

---  

This theorem is often used as lemma to justify the basic notion of [[Dimension of a vector space]].

> [!quote] Theorem: Sets of linearly independent vectors have smaller cardinality than a basis
> $$ \text{Span}(\left\{ v_{i} \right\}_{1\leq i\leq n} )=V \land \left\{ y_{i} \right\}_{1\leq i\leq k} \; \text{are linearly independant}\; \implies k\leq n
$$

The proof goes as follows:

>[!quote] Proof: Sets of linearly independent vectors have smaller cardinality than a basis
>Since $\left\{ v_{i} \right\}_{1\leq i\leq n}$ forms a basis we have that for all $y_\alpha$ there are some scalars $\lambda$: $$ y_{\alpha}= \sum^{}_{} \lambda_{i} v_{i}
$$ Also since all $y$ are independent we have that there is a non-zero $\lambda_{\zeta}$. This means that we can write: $$ v_{\zeta}= \left( \sum^{}_{} -\frac{\lambda_{i}}{\lambda_{\zeta}} \right)   + \frac{y_{\alpha}}{\lambda_{\zeta}}
$$ This also implies that: $$ \text{Span}(\left\{ v_{i} \right\}_{1\leq i\leq n} )=\text{Span}(\left\{  y_{\alpha} ,v_{i} \right\}_{1\leq i\leq n-1} )
$$ This process can then be repeated with another $y$, thus intuitively we can replace all $v$'s in the basis by $y$'s. We now argue by contradiction this implies that $k\leq n$. Suppose we had $k>n$, then at one we iterated this process $n-1$ times there would be one vector $v$ left to replace with two or more vectors $y$. But using the same argument stated above this would imply that: $$ \text{Span}(\left\{ y_{i}, y_{n} \right\}_{1\leq i\leq n-1} )=\text{Span} (\left\{ y_{i},y_{n} \right\}_{1\leq i\leq n-1} )
$$ And this contradicts the linear independence of the vectors $y$.  
**Q.E.D.**

