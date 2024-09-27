
---

mathLink: auto

---
Date created: 2023-12-03 12:41
Tags: #Type/Object #Topic/Linear_Algebra 

Types: [[Space of linear functions from V to V']]
Examples: _Not applicable_
Construction: _Not applicable_
Generalization: [[Vector spaces]]

Properties: _Not applicable_
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Fields]], [[Sets]], [[Algebraic structures]], [[Functions]]

---  

A function space is a special kind of [[Vector spaces|vector space]] where the elements are functions.

> [!quote] Definition: Function space
> Given a field $F$ and a set $X$, we define the function space to be the [[Algebraic structures|algebraic structure]] defined by the set $F^X$ and the operation of direct sum and scalar product of functions given by: $$\begin{align} +_{f}:(f+g)(x)&:=f(x)+g(x) \\ *_{f}:(cf)(x)&:=cf(x)
\end{align}$$ And where the set $F^X$ denotes functions from $X$ to $F$: $$f\in F^X\iff f:X\rightarrow F$$

We also say that $f$ is $F$-valued. Notice that we can easily verify that $(F^X,+_f, *_{f})$ does indeed form a vector space over $F$.
