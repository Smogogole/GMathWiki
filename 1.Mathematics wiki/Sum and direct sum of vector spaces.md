
---

mathLink: auto

---
Date created: 2023-12-19 19:33
Tags: #Type/Notion #Topic/Linear_Algebra 

Types: _Not applicable_
Examples: _Not applicable_
Construction: [[Properties of dimensionality]], [[Product and direct product of vector spaces]]
Generalization: _Not applicable_

Properties: [[Vector spaces can be written as a direct sum given a subspace]]
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Vector subspaces]]

---  


> [!quote] Notion: Sum of vector spaces
> Given two subspaces $U$,$W$ of a vector space $V$, we define their direct sum: $$U+W:=\{ v:\exists u\in U, w\in W: v=u+w \}$$

Notice that this is essentially equivalent to: $$\text{Span}(U\cup W)=U+W$$This thus per definition proves us that the sum of two subspaces forms a subspace.

If the elements defining vectors $v\in U+W$ are unique (only one $u$ and $w$ such that $v=u+w$), then we say $V$ is the *direct* sum and write: $$V= U\oplus W$$ We also notice that:$$V=U+W \land U\cap W=\{ O_{V} \} \implies V=U \oplus W$$ Which can be easily shown