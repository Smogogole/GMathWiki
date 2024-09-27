
---

mathLink: auto

---
Date created: 2023-11-24 22:42
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





For any [[Sets|sets]] $X$ and $Y$ we call the coordinate [[Functions|function]]  $\mathcal{C}$ the function that maps any $(x,y)$ to $x$ or $y$, in other words:
$$\mathcal{C}_{X\times Y \rightarrow X}:X\times Y\rightarrow X:(x,y)\mapsto x$$
$$\mathcal{C}_{X\times Y \rightarrow Y}:X\times Y\rightarrow Y:(x,y)\mapsto y$$

Just like [[Inclusion and identity maps|inclusion maps]] these functions have the special property that given two functions $f:Z\rightarrow X$ and $g:Z\rightarrow Y$ there exists a unique function $h:Z\rightarrow X\times Y$ such that $\mathcal{C}_{X\times Y\rightarrow X} \circ h=f$ and $\mathcal{C}_{X\times Y\rightarrow Y} \circ h=g$. The function $h$ is also known as the direct sum of $f$ and $g$ is is also denoted by $h=f\oplus g$


#### *Proof*

We first prove the existence of $h$ by giving an example of a function that satisfies the properties, we will then prove it's uniqueness.
Let $h$ be the function $h:Z\rightarrow X\times Y:z\mapsto (f(z),g(z))$ . One can easily check that's it's composition with the respective coordinate function gives us an equivalent function. Now suppose we had two functions $h$ and $h'$ which both obey the properties. Then evaluated at $z$ we know that $\mathcal{C}_{X\times Y\rightarrow X} \circ h(z)=f(z)$, but since $\mathcal{C}$ only removes a element of the pair we know that $h$ and $h'$ still both have to map $z$ to $f(z)$ in the $X$ spot in order for there to be equality and since the argument can be reproduced for $g$ we know that $h$ and $h'$ must have the same mapping thus confirming that $h=h'$ and that $h$ is unique.

**Q.E.D.**

#completed 