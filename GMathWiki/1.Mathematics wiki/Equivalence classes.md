
---

mathLink: auto

---
Date created: 2023-10-24 16:02
Tags: #Type/Unfinished 

%%For Definition/Example of a notion/object%%

Types: %%_Objects/notions of type `object`/`notion` with additional restrictions._%% 
Examples: %%_Specific examples or counterexamples of `object`/`notion` (but not of any of its `types`)._%%
Construction: %%_Objects/notions derived from `object`/`notion`._%%
Generalization: %%_Abstractions of `object`/`notion`._%%

Properties: %%_Statements regarding `object` or necessary conditions of `notion`._%%
Sufficiencies: %%_Proofs that other objects are of type `object` or sufficient conditions of `notion`._%%
Equivalences: %%_Equivalent definitions for `object` or biconditionals between notions and `notion`._%%
Justifications: %%_Proofs of well-definition of `object`/`notion`._%%

%%For Proposition/Theorem of a notion/object including both`statement`/`proof` regarding `object`/`notion` it links to %%

Proved by: %%_Statements in which `proof` depends crucially on._%%
References: %%_Notes in which the proofs of `statement` (or corollaries thereof) are delegated to._%%
Justifications: %%_Proofs of implicit assumptions of `object`/`notion` in `statement`._%%   

Specializations: %%_Reformulations/proofs of instances of `statement`._%%
Generalizations: %%_Statements and proofs of abstractions of `statement`._%%

---  



> [!quote] Definition
> Lorem ipsum dolor sit amet


If $R$ is an equivalence relation on a set $S$ and $a\in S$, then the set $[a]=\{x\in S: xRa\}$ is called the equivalence class of $S$ containing $a$.


The equivalence classes of an equivalence relation on a set $S$ constitute a partition of $S$ conversely, for any partition $P$ of $S$, there is an equivalence relation on $S$ whose equivalence classes are the elements of $P$


#### *Proof*

Let $\sim$ be an equivalence relation on a set $S$. For any $a\in S$ the reflexive property states that $a\in [a]$. So, $[a]$ is non-empty and union of all equivalence classes is $S$, the only thing we are left to prove is that for any $a,b$ we have that $[a]\cap[b]=\emptyset$. Assume that it is not the case and that thus we have a $c$ such that $c\in [a]\cap[b]$. We will show that $[a]\subseteq [b]$. Let $x\in [a]$. Then we have $c\sim a$,$c\sim b$ and $x\sim a$. By symmetry we have that $a\sim c$ which thus gives us by transitivity $x\sim c$. Once again by transitivity we have that $x\sim b$ and thus $[a]\subseteq [b]$. This argument can also be made to show that $[b]\subseteq [a]$ and thus we have that $[a]=[b]$. Meaning that the set of all equivalency classes a partition forms of $S$. To prove the converse, let $P$ be a collection of non-empty disjoint subsets of $S$ whose union is $S$. Define $a\sim b$ if $a$ belongs to the same subset than $b$ in the collection. One can easily check this is an equivalence relation.


#### *Consequence*

We can also essentially derive the following exciting fact: