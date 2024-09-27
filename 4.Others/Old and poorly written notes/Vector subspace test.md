
---

mathLink: auto

---
Date created: 2023-11-27 00:03
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





We can test if $W$ is a subspace by considering this:           
If $W$ is a nonempty subset of a vector space $V$, then $W$ is a subspace if and only the following closure conditions hold:
- If $u$ and $v$ are in $W$ , then $u+v$ is in $W$ (closed under addition)
- if $u$ is in $W$ and $c$ is any scalar, then $cu$ is in $W$ (closed under multiplication)
If $W$ is nonempty and $W\subseteq V$ with $V$ being a vector space, then $W$ is a subspace of $V$ if and only if the following closure conditions hold:

$W$ is closed under addition and multiplication $\Longleftrightarrow$ $W$ is a subspace of $V$ 


From right to left the proof is trivial, since it follows from the definition of a subspace of a vector space.
From left to right, we notice that for all $w\in W$ , $w$ is also in $V$. Thus axioms 2,3,7,8,9,10 hold.
Now assume $W$ is indeed closed under the operations defined on $V$. This means that:
$$\begin{align}
cv&=0 \hspace{1cm} (with\;c=0)\\
(-1)v&=v\\
&\underbrace{\text{}}_{\in \;W}

\end{align}
$$
Thus if there is closure then axioms 4 and 5 also hold. This means that assuming closure implies that all the other axioms hold as long as $W$ is a nonempty subset of $V$ ($W$ must contain $V$'s zero vector regardless)

**Q.E.D.**

