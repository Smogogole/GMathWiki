
---

mathLink: auto

---
Date created: 2023-12-15 11:58
Tags: #Type/Notion #Topic/Linear_Algebra 

Types: _Not applicable_
Examples: _Not applicable_
Construction: [[Bases of vector spaces]]
Generalization: _Not applicable_

Properties: _Not applicable_
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Linear combinations of vectors]], [[Vector spaces]]

---  

In order to develop a notion of [[Bases of vector spaces]] we first discuss span.

> [!quote] Notion: Span of a set
> The span of a set $V' \subseteq V$ is defined as the set:
> $$\text{Span}(V')=\left\{v:v=\sum_{1\leq i\leq\text{card}(V')}f_i*v_i \;\text{with}\; v_i\in V'\land (f_i)_{1\leq i\leq n}\in \prod_{1\leq i\leq n} F\right\}
$$

One can easily verify this forms a [[Vector subspace]] of the [[Vector spaces|vector space]] $V$.

Alternatively, the following definitions is also valid:

>[!quote] Definition: Alternative definition for span
>$$ \text{Span}(V)=\bigcap_{V\subseteq Y_{\alpha}\leq X} Y_{\alpha}
$$ 

Where $\leq$ denotes the subspace relation. One would obviously want to construct a prove to check these are equivalent