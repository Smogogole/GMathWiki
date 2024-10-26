
---

mathLink: Space of linear functions $\mathscr L(V,V')$

---
Date created: 2023-12-28 17:30
Tags: #Type/Object #Topic/Linear_Algebra #NEEDS_REVAMP

Types: _Not applicable_
Examples: _Not applicable_
Construction: _Not applicable_
Generalization: [[Function spaces]]
Properties: _Not applicable_
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Fields]], [[Vector spaces]], [[Linear maps]]

---  

Using the fact that a [[Fields|field]] forms a [[Vector spaces|vector space]] over itself we can define the following [[Function spaces|function space]]:

> [!quote] Definition: Space of linear functions $\mathscr L(V,V')$
> Given two [[Vector spaces]] $V$ and $V'$ over a [[Fields|field]] $\mathbb F$, we define $\mathscr L(V,V')$ to be the algebraic structure defined by the set of all [[Linear maps]] from $V$ to $V'$ and the operation of direct sum and scalar product of functions given by: $$\begin{align} +_{f}:(L+T)(x)&:=L(x)+T(x) \\ *_{f}:(cL)(x)&:=cL(x)
\end{align}$$ 

Since $\mathscr L(V,V')$ is a function space we automatically know it forms a vector space $(\mathscr L(V,V'), +_{f, },*_{f})$ (alternatively one could prove it by defining the zero function and proving it is linear and then proceed to go through all the vector space axioms).

We also have that $+_{f}$  and $*_{f}$ are a linear maps since: $$
\begin{align}
(T+L)(cu+bv)&=T(cu+bv)+L(cu+bv) \\
&=cT(u)+bT(v)+cL(u)+bL(v) \\ 
&=c(T+L)(u)+b(T+L)(v)
\end{align}
$$ And: 
$$
\begin{align}
((ab+cd)T(v))&=(ab+cd)T(v) \\
&=abT(v)+cdT(v) \\
&=a(bT(v))+c(dT(v))
\end{align}
$$


---

**_Remark_**: $*_{f}$ linearity is proven only using field elements, as the scalars and vectors are the same type of element when considering a field $F$ as a vector space.


