---
mathLink: auto
Date created: 2024-10-19 21:34
tags:
  - Type/Theorem
cssclasses:
---

---

Proved by: %%_Statements in which `proof` depends crucially on._%%
References: %%_Notes in which the proofs of `statement` (or corollaries thereof) are delegated to._%%
Justifications: %%_Proofs of implicit assumptions of `object`/`notion` in `statement`._%%   

Specializations: %%_Reformulations/proofs of instances of `statement`._%%
Generalizations: %%_Statements and proofs of abstractions of `statement`._%%

---

> [!quote] Theorem:
> Let $\det: M_{n\times n}(F)\to F$ be the determinant map, then $\det$ satifsfies: 
> 1. $\det(\mathbb{I}_{n})=1$
> 2. $\det(C_{ij}A)=-\det (A)$
> 3. $\det$ is multilinear over the rows of $A$


 >[!quote]
 >We start with property 1. Notice that for every permutation $\sigma\in S_{n}$, the product of elements $\prod_{1\leq i\leq n}(\mathbb{I}_{n})_{i\sigma(i)}$ is always equal to zero, unless the permutation is exactly the identity permutation $\text{Idx}$. Thus $$ \det(\mathbb{I}_{n})=\text{sgn}(\text{Idx})\prod_{1\leq i\leq n}(\mathbb{ I}_{n})_{ii}=1 $$ We proceed with property $2$. Let $\tau_{ij}: \mathbb{N}^{*}_{\leq n}\to \mathbb{N}^{*}_{\leq n}$ be the transposition transposing $i$ with $j$. Then we define $\sigma':=\tau_{ij}\circ \sigma$ for every $\sigma\in S_{n}$, this means $\tau_{ij}^{-1}\circ \sigma'= \tau_{ij}\circ \sigma'=\sigma$. Now we have $$ \det(C_{ij}A) =\sum^{}_{\sigma\in S_{n}}\text{sgn}(\sigma)\prod_{1\leq k\leq n}a_{\tau_{ij}(k)\sigma(k)}$$ By substituting we get $$\sum^{}_{\sigma\in S_{n}}\text{sgn}(\sigma)\prod_{1\leq k\leq n}a_{\tau_{ij}(k)\sigma(k)}= \sum^{}_{\sigma'\in S_{n}}\text{sgn}(\tau_{ij}\circ \sigma')\prod_{1\leq k\leq n}a_{\tau_{ij}(k)\tau_{ij}\circ \sigma'(k)}  $$ Notice now that the product  $\prod_{1\leq k\leq n}a_{\tau_{ij}(k)\tau_{ij}\circ \sigma'(k)}$ is exactly equal to $\prod_{1 \leq k  \ \leq n}a_{k\sigma'(k)}$. We also have that $\text{sgn}(\tau_{ij}\circ \sigma')=- \text{sgn}(\sigma')$, thus $$\sum^{}_{\sigma'\in S_{n}}\text{sgn}(\tau_{ij}\circ \sigma')\prod_{1\leq k\leq n}a_{\tau_{ij}(k)\tau_{ij}\circ \sigma'(k)}= -\sum^{}_{\sigma'\in S_{n}} \text{sgn}(\sigma')\prod_{1 \leq k  \ \leq n}a_{k\sigma'(k)}=-\det(A) $$
 
 