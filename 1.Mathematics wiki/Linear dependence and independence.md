
---

mathLink: auto

---
Date created: 2023-11-27 00:08
Tags: #Type/Notion  #Topic/Linear_Algebra 

Types: _Not applicable_
Examples: _Not applicable_
Construction: [[Coordinates with respects to a basis]], [[Bases of vector spaces]]
Generalization: _Not applicable_

Properties: [[Condition of linear dependence]], [[Maximal subset of linearly independent vectors]]
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Vector spaces]], [[Every vector space has a basis]]

---  

Given a vector space $V$ we can develop a notion of dependence.

> [!quote] Definition: Linear dependence
> A set of vectors $V'$ are said to be linearly dependent if there exists a set of scalars which are not all $O_{F}$ such that: $$ \sum^{\text{card} (V')}_{i=1} f_{i}v_{i}=O_{V}
$$

If those scalars don't exists then we say the vectors of $V'$ are linearly independent. 

In addition, if we have: $$
\forall v \in V\backslash\text{Span}(V')\;\text{we have} \; V' \cup\{v\} \;\text{are linearly dependant}
$$
Then we say that the subset is maximal. We can then easily prove that maximal subsets form a [[Bases of vector spaces|bases for vector spaces]]. 




