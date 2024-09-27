
---

mathLink: auto

---
Date created: 2023-11-14 19:51
Tags: #Type/Object #Topic/Topology 

Types: [[Open balls]]
Examples: _Not applicable_
Construction: _Not applicable_
Generalization: [[Sets]]

Properties: _Not applicable_
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Interior points]]

---  

Using the notion of [[Interior points]] we can develop a notion of open subsets, which intuitively are sets that don't contain their own "border".

> [!quote] Definition: Open subset
> A subset $Y$ of $(X,d)$ is said to be open if and only if:$$\text{int}(Y)=Y$$

From this definition we can derive the following properties:

>[!quote] Notion: Properties of open subsets
>1. $\text{int}(\text{int}(Y))=\text{int}(Y)$
>2. $\{U_i\}_{i\in I}$ where all $U_i$ are open in a [[Metric spaces|metric space]] $X$ $\implies \bigcup_{i\in I}U_i$ is open.
>3. $U$ is open in a [[Metric spaces|metric space]] $X$ $\iff U=\bigcup_{x\in U}B(x,r(x))$
>4. $\{U_i\}_{i\in I}$ with all $U_i$ open in a [[Metric spaces|metric space]] $X$ and $I$ is finite $\implies \bigcap_{i\in I}U_i$ is open.
>5. Given $Y$ a subspace of the [[Metric spaces|metric space]] $X$, a subset $U$ of $Y$ is open in $Y$ if and only if $U=V\cap Y$ for some open subset $V$ in $X$

Which are all pretty straight forward to prove and can be found in the book "Introduction to topology" by Gamelin and Greene.




