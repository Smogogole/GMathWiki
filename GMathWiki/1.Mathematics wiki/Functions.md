
---

mathLink: auto

---
Date created: 2023-10-22 10:29
Tags: #Type/Object #Topic/Set_Theory  

Types: [[Inverse functions]], [[Partial functions]]
Examples: [[Inclusion and identity maps]], [[Coordinate functions]], [[Empty functions]]
Construction: [[Graph (functions)]]
Generalization: [[Binary relations]]

Properties: [[Inverse functions]], [[Function composition]]
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: [[Function equality is well defined]]

---  

We can define functions as follows:

> [!quote] Definition: Function
> Let $X$, $Y$ be [[Sets|sets]], and let $P(x,y)$ be a property pertaining to an object $x\in X$ and an object $y \in Y$, such that for every $x\in X$, there is exactly one $y\in Y$ for which $P(x,y)$ is true. Then we define the function/map/transformation $f: X \rightarrow Y$ defined by $P$ on the domain $X$ and range $Y$ to be the object which, given any input $x\in X$, assigns an output $f(x) \in Y$, defined to be the unique object $f(x)$ for which $P(x,f(x))$ is true. Thus for any $x\in X$ and $y \in Y$ we have: $$y=f(x) \iff P(x,y)\;\text{is true}$$

Defining function equality can be a bit more sensitive, to avoid paradoxal situations one might want to take this definition on as an axiom$^{1}$.

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

---

**_Remark_**$^1$: Consult this link for more information on the matter: https://math.stackexchange.com/questions/2225251/how-to-write-the-definition-of-a-function-axiomatically
