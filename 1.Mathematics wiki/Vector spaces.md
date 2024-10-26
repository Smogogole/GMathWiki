---
mathLink: auto
Date created: 2023-11-26 17:14
tags:
  - Type/Object
  - Topic/Linear_Algebra
cssclasses:
---

---  

Types: [[Function spaces]], [[Perp(v)]], [[Matrix vector space M(F)]]
Examples: _Not applicable_
Construction: [[Vector subspace]], [[Linear maps]]
Generalization: _Not applicable_

Properties: [[Vector spaces (Properties)]]
Sufficiencies: _Not applicable_
Equivalences: _Not applicable_
Justifications: _Not applicable_

---

> [!quote] Definition: Vector space
> A vector space $(V,+,*)$ over a Field $F$ is a set $V$ on which we define the following operations, which must satisfy the vector space axioms:
> $$\begin{align}
> +:V\times V\rightarrow V&: (v_1,v_2)\mapsto v_1+v_2\\
> *:F\times V\rightarrow V&: (f,v)\mapsto f*v
> \end{align}
> $$ 

The vector space axioms the operations must satisfy are the following:

>[!quote]- Notion: Vector space axioms
>- Additive and scalar closure:$$v_1+v_2\in V\land f*v\in V$$
>- Associative and commutative addition:$$(v_1+v_2)+v_3=v_1+(v_2+v_3)\land v_1+v_2=v_2+v_1$$
>- Existence of additive and scalar identity:$$v+O_V=v\land I_F*v=v$$
>- Existence of additive inverse:$$v+(-v)=O_V$$
>- Distributivity of scaling with regards to addition:$$f*(v_1+v_2)=f*v_1+f*v_2$$
>- Distributivity of scaling with regards to field addition:$$(f_1+_Ff_2)v=f_1*v+f_2*v$$
>- Compatibility of scalar multiplication with field multiplication: $$f_{1}(f_{2}*v)=(f_{1}*_{F}f_{2})*v$$


