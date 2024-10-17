---
mathLink: auto
Date created: 2024-10-09 14:27
tags:
  - Type/Object
  - Topic/Set_Theory
cssclasses:
---

---

Types: [[Inverse functions]], [[Partial functions]]
Examples: [[Inclusion and identity maps]], [[Coordinate functions]], [[Empty functions]]
Construction: [[Graph (functions)]]
Generalization: [[Binary relations]]

Properties: [[Inverse functions]], [[Function composition]]
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Function equality is well defined]]

---  

> [!quote] Definition: Function
>Let $X$ and $Y$ be sets, and let $R$ be a relation on $X\times Y$ such that for every $x\in X$ there exists exactly one $y\in Y$ for which $$ xRy $$We then write $$ f:X\to Y: x\mapsto f(x) $$With $xRf(x)$

We define function equality as

>[!quote] Definition: Function equality
>We define two functions $f,g:X\rightarrow Y$ with the same domain and range to be equal if and only if $\forall x\in X:f(x)=g(x)$.

We then define the following classifications on functions:

>[!quote]- Notion: Bijection, injection and surjection 
>- A function $f$ is said to be injective if different elements map to different elements: $x\neq x'\implies f(x)\neq f(x')$. And equivalently: $f(x)=f(x')\implies x=x'$. Sometimes we refer to this as the first horizontal line test
>- A function $f$ is said to be surjective if $f(X)=Y$ or: $\forall y \in Y:\exists x\in X:f(x)=y$
>- A function $f$ is said to be bijective if it is surjective and injective. We also call this a perfect matching and change how we denote the mapping as such $x\leftrightarrow f(x)$. 

To finish of we can also subject [[Sets]] to functions or [[Inverse functions]]:

>[!quote]- Notion: Sets under functions
>The Image of a set $S$ under $f$ is the set $f(S)$ such that $f(S) := \{f(x):x\in S\}$ with $f$ being a map from $X\rightarrow Y$ and $S\subseteq X$ . $y∈ f(S) \iff \exists x\in S:y = f(x)$. From this definition follows the definition of the inverse image, note that the concept of an inverse functions get developed later down in the note. If $U\subseteq Y$ then we define the set $f^{-1}(U)$ to be the set such that $f^{-1}(U):=\{x\in X: f(x)\in U\}$ 

Note that $f$ doesn't have to be [[Inverse functions|invertible]] in order for $f^{-1}(U)$ to make sense, but this does mean that one has to be careful with [[Inverse functions|cancellation]].

