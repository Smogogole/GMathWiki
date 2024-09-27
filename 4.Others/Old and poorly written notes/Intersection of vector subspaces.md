
---

mathLink: auto

---
Date created: 2023-11-26 23:31
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







The next theorem also holds:
If $V$ and $W$ are both subspaces of $U$, then $V\cap W$ is also a subspace of $U$       
Why doesn't this hold for union ? -> closure is not guaranteed when a vector that is unique to $V$ interacts with a vector unique to $W$, which isn't the case with an intersection because of the fact that the vectors there are closed under both [[Sets|sets]].



##### Proof of subspace intersection.

$V$ and $W$ are both subspaces of $U$ and all vectors in $V\cap W$ are in $V$ and in $W$. Because of that the vectors in $V\cap W$ are closed under the operations of $U$ , since the vectors were already closed when in $V$ and $W$.
Thus:
$$V\cap W \rightharpoonup_{ss}U$$
**Q.E.D.**


