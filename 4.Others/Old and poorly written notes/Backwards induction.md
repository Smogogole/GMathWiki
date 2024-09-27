
---

mathLink: auto

---
Date created: 2023-10-21 22:09
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



## *Backwards induction

Exercise from the book Terence Tao Analysis I:

Let $n$ be a natural number, and let $P(m)$ be a property pertaining to the natural numbers such that whenever $P(S(m))$ is true, then $P(m)$ is true. Suppose that $P(n)$ is also true. Prove that $P(m)$ is true for all natural numbers $m ≤ n$

#### *Proof*

Let $P$ be a property pertaining to the [[Natural numbers]] such that when $P(S(m))$ is true, then $P(m)$ is true
We first define the property $Q(n)$ that states that if $P(n)$ is true, then $P(m)$ is true for all $m \leq n$.

We shall show that $Q(n)$ is true for all $n$ by induction. We first study the base case $n=0$, this means $Q(0)$. So suppose that $P(0)$ is true. We want to show that $P(m)$ is true for all $m \leq 0$. By definition we have that $0=m+a$  and by properties of [[Addition]] we have that $m=0$, but we already know that $P(0)$ is true. This closes the base case.

Now suppose $Q(n)$ is true, we must show that $Q(S(n))$ is true. $Q(S(n))$ means that if $P(S(n))$ is true, then $P(m)$ is true for all $m \leq S(n)$, so suppose $P(S(n))$ is true. We know that whenever $P(S(m))$ then $P(m)$ is true, so for $m=n$ in particular this means that if $P(S(n))$ is true then $P(n)$ is true. So $P(n)$ is true because we assumed the truth of $P(S(n))$. By the induction hypothesis we thus have $P(m)$ for all $m \leq n$. Now let $m\leq S(n)$. We want to show that $P(m)$ is true. If we can show that $m\leq n$ or $m=S(n)$, then we will be done, because in either case we have already shown that $P(m)$ is true (either by induction hypothesis or assumption). In order to show this we will prove that $m \neq S(n) \implies m \leq n$. BY trichotomy of order and context we know that $m<S(n)$ but by properties of order we have $S(m) \leq S(n)$ which on it's turn implies $m\leq n$. This closes induction.

Now let $n$ be a natural number, and suppose $P(n)$ is true. By our work above, we know that $Q(n)$ is true. This means that $P(m)$ is true for all natural numbers $m\leq n$ as required.

**Q.E.D.**