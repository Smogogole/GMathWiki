
---

mathLink: auto

---
Date created: 2023-12-15 18:51
Tags: #Type/Notion #Topic/Linear_Algebra 

Types: _Not applicable_
Examples: _Not applicable_
Construction: _Not applicable_
Generalization: _Not applicable_

Properties: _Not applicable_
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Cardinality of a set]], [[Bases of vector spaces]], [[Vector spaces]], [[Steinitz lemma]]

---  

We define a notion of dimensionality in terms of bases as follows:

> [!quote] Notion: Dimension of a vector space
> Given a vector space $V$ and a basis of that space $S$, we define: $$\dim V := \text{Card}(S)$$

In order for this to be a meaningful definition we must have that the dimension of $V$ is consistent regardless of the basis. This can easily be proven by considering [[Steinitz lemma|this]] property for two bases of size $n$ and size $k$ respectively. Proving us that $k=n$.

Here are some basic properties that follow from this definition:

>[!quote] Properties: Dimension of a vector space
>1. $\dim(V)=n \land \{ v_{i} \}_{1\leq i\leq n} \; \text{independant} \implies \{ v_{i} \}_{1\leq i\leq n}\;\text{is a basis}$
>2. $W \subseteq V \land \dim(V)=\dim(W) \implies V=W$
>3. $W \subseteq V \land \dim(V)=n \land \{ v_{i} \}_{1\leq i \leq n}\;\text{a basis for } V\implies \exists \{ w_{i} \}_{1\leq i\leq m}\; \text{is a basis for}\; W \land \dim(W)=m$

