
---

mathLink: auto

---
Date created: 2023-12-22 14:51
Tags: #Type/Proof  #Topic/Linear_Algebra 

Proved by: [[Sum and direct sum of vector spaces]], [[Product and direct product of vector spaces]]
References: _Not applicable_
Justifications: [[Bases of vector spaces]], [[Dimension of a vector space]], [[Linear combinations of vectors]]

Specializations: _Not applicable_
Generalizations: _Not applicable_

---  


> [!quote]- Proof:  $V= W \oplus U \implies \dim(V)=\dim(W)+\dim(U)$
> Since $V$ is a direct sum of $U$ and $W$ we have that every $v$ in $V$ has a unique representation of the form $u+w$. Since $U$ and $W$ have bases we have that: $$ v=\left( \sum^{n}_{i=1}a_{i}u_{i} \right)+\left( \sum^{m}_{i=1} b_{i}w_{i}\right) $$ Since this holds for any vector in $v$ we have that $\{ u_{i} \}_{1\leq i\leq n}\cup \{ w_{i} \}_{1\leq i\leq m}$ forms a basis and thus has dimension $\dim(W)+\dim(U)$.
> 
> **Q.E.D**

>[!quote]- Proof: $\dim(W \otimes  U)=\dim(W)+\dim(U)$ 
>Notice that given the basis $\{ u_{i} \}_{1\leq i\leq n}$ and $\{ w_{i} \}_{1\leq i\leq m}$ we can write: $$v=(u,w)=(u,0)+(0,w)=\left( \sum^{n}_{i=1}(u_{i},0) \right)+\left(\sum^{m}_{i=1}(0,w_{i})\right)$$ Implying it the space has basis $\{ (u_{i},0) \}_{1\leq i\leq n}\cup \{ (0,w_{i}) \}_{1\leq i\leq m}$ and thus dimension $\dim(W)+\dim(U)$.
>
>**Q.E.D.**

