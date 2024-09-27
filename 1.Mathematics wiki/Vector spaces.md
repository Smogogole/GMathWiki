
---

mathLink: auto

---
Date created: 2023-11-26 17:14
Tags: #Type/Object #Topic/Linear_Algebra 

Types: [[Function spaces]], [[Perp(v)]], [[Matrix vector space M(F)]]
Examples: _Not applicable_
Construction: [[Vector subspace]], [[Linear maps]]
Generalization: [[Modules]]

Properties: _Not applicable_
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: _Not applicable_

---  

We define a vector space $(V,+,*)$ over a [[Fields|field]] $F$ is defined as follows:

> [!quote] Definition: Vector space
> A vector space $(V,+,*)$ over a Field $F$ is a set $V$ on which we define the following operations, which must satisfy the vector space axioms:
> $$\begin{align}
> +:V\times V\rightarrow V&: (v_1,v_2)\mapsto v_1+v_2\\
> *:V\times F\rightarrow V&: (v,f)\mapsto f*v
> \end{align}
> $$ 

The vector space axioms the operations must satisfy are the following:

>[!quote]- Notion: Vector space axioms
>- Additive and scalar closure:$$v_1+v_2\in V\land f*v\in V$$
>- Associative and commutative addition:$$(v_1+v_2)+v_3=v_1+(v_2+v_3)\land v_1+v_2=v_2+v_1$$
>- Associative scaling:$$f_2*(f_1*v)=(f_2*_Ff_1)v$$
>- Existence of additive and scalar identity:$$v+O_V=v\land I_F*v=v$$
>- Existence of additive inverse:$$v+(-v)=O_V$$
>- Distributivity of scaling with regards to addition:$$f*(v_1+v_2)=f*v_1+f*v_2$$
>- Distributivity of scaling with regards to field addition:$$(f_1+_Ff_2)v=f_1*v+f_2*v$$

From this we can derive the following basic consequences as well:
$$\begin{align}
f*v=O_V &\implies f=O_F\lor v=O_V\\
-(-v)&=v\\
-I_Fv&=-v\\
-f*v&=f*-v\\
\end{align}$$

---
**_Remark_**: More concise would be to say that a vector space is a [[Modules|module]] over a [[Fields|field]].   