
---

mathLink: auto

---
Date created: 2023-10-23 19:01
Tags: #Type/Object #Topic/Logic #Topic/Abstract_Algebra

Types: [[Equivalence relationships]], [[Functions]]
Examples: _Not applicable_
Construction: _Not applicable_
Generalization: [[Relations]]

Properties: [[Properties of relations]]
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Sets]], [[Cartesian product]]

---  

Given a [[Sets|set]] $A$ and $B$, we define a relation $R$ from $A$ to $B$ as follows: 

> [!quote] Definition: Relation
> $$R\subseteq \{(a,b):a\in A \land b\in B\}\iff R\subseteq A\times B$$

If $A=B$ we say $R$ is a relation **onto** $A$. We usually define a property to rule out what elements from the [[Cartesian product]] are in $R$. 

The statement $(x,y) ∈ R$ reads "$x$ is $R$-related to $y$" and is denoted as $xRy$

In a similar fashion to functions we can now add some terminology to our relations:

>[!quote] Notion: Terminology
>$$\begin{align}
\text{Dom}(R)&=\{a\in A:\exists b\in B((a,b)\in R)\}\\
\text{Ran}(R)&=\{b\in B:\exists a\in A((a,b)\in R)\}\\
R^{-1}&=\{(b,a)\in B\times A:(a,b)\in A\times B\}\\
S\circ R&=\{(a, c) \in A \times C : ∃ b ∈ B((a, b) ∈ R \land (b, c) ∈ S)\}
\end{align}$$

Now one can notice that if every $a$ in the domain of the has at most one $b$ in $B$ such that $(a,b)\in R$, then we essentially have a [[Functions|function]]. And this would look like:
$$f:A\rightarrow B:a\mapsto b \land(a,b)\in R$$
More formally, $R$ is actually the [[Graph (functions)|graph]] of a function $f$.



