
---

mathLink: auto

---
Date created: 2023-10-22 11:27
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


##### Proof that functions obey the axiom of substitution

In order for the axiom of substitution to hold we must have $x=x' \implies f(x)=f(x')$ . This must be true by definition of a function, since $x=x'$ it must map to the same object to otherwise it simply wouldn't be a function by definition.

**Q.E.D.**


##### Proof that function equality obeys usual axioms

Suppose two functions $f,g,h:X \rightarrow Y:x\mapsto f(x)$.
Frist we check for symmetry, is $f=f$ ?. According to the definition of function equality yes since for all $x\in X$ we have $f(x)=f(x)$ which means indeed that $f=f$. We then check for reflexivity, $f=g \iff g=f$ ? According to the definition of function equality this statement is true as $f(x)=g(x)$ which implies $g(x)=f(x)$ . Now we just have to check for transitivity, $f=g\land g=h\implies f=h$ ? According to the definition of function equality we get $f(x)=g(x) \land g(x)=h(x)$ which according to normal equality means $f(x)=h(x)$ for all $x$ meaning that by the definition once again we have $f=h$. This closes the proof.

**Q.E.D.**
