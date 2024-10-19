---
mathLink: auto
Date created: 2024-10-19 11:59
tags:
  - Type/Object
cssclasses:
---

---  

Types: _Not applicable_
Examples: _Not applicable_
Construction: [[Quotient set]]
Generalization: _Not applicable_

Properties: [[Equivalence classes (properties)]]
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Equivalence relations]]

---

> [!quote] Definition
> Let $R$ be a equivalence relation on some set $S$ and $a\in S$, then we define the equivalence class of $a$ as $$[a]=\{x\in S: x\sim a\}$$




The equivalence classes of an equivalence relation on a set $S$ constitute a partition of $S$ conversely, for any partition $P$ of $S$, there is an equivalence relation on $S$ whose equivalence classes are the elements of $P$


#### *Proof*

Let $\sim$ be an equivalence relation on a set $S$. For any $a\in S$ the reflexive property states that $a\in [a]$. So, $[a]$ is non-empty and union of all equivalence classes is $S$, the only thing we are left to prove is that for any $a,b$ we have that $[a]\cap[b]=\emptyset$. Assume that it is not the case and that thus we have a $c$ such that $c\in [a]\cap[b]$. We will show that $[a]\subseteq [b]$. Let $x\in [a]$. Then we have $c\sim a$,$c\sim b$ and $x\sim a$. By symmetry we have that $a\sim c$ which thus gives us by transitivity $x\sim c$. Once again by transitivity we have that $x\sim b$ and thus $[a]\subseteq [b]$. This argument can also be made to show that $[b]\subseteq [a]$ and thus we have that $[a]=[b]$. Meaning that the set of all equivalency classes a partition forms of $S$. To prove the converse, let $P$ be a collection of non-empty disjoint subsets of $S$ whose union is $S$. Define $a\sim b$ if $a$ belongs to the same subset than $b$ in the collection. One can easily check this is an equivalence relation.
