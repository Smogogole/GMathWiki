
---

mathLink: auto

---
Date created: 2023-11-13 12:08
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

[[Boundedness of sequences]]

> [!quote] Definition
> Lorem ipsum dolor sit amet


## *Boundedness*

Let $M\geq0$ be rational/real. A finite sequence is bounded by $M$ if and only if $|a_i|\leq M$ for all $1\leq i\leq n$ and a infinite sequence is bounded by $M$ in the same case ass long ass $|a_i|\leq M$ for all $i\geq 1$. We thus also say a sequence is bounded if and only if it is bounded by some $M$.

From this definition flow a few theorems. Namely that all finite sequences are bounded and that all Cauchy sequences are bounded.


#### *Proof that all finite sequences are bounded*
WRIIIIOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOONG

We prove this by induction on $n$. When $n = 1$ the sequence $a_1$ is clearly bounded, for if we choose $M := |a_1|$ then clearly we have $|a_i| ≤ M$ for all $1 ≤ i ≤ n$. Now suppose that we have already proved the lemma for some $n ≥ 1$; we now prove it for $n + 1$, i.e., we prove every sequence $a_1, a_2,...,a_{n+1}$ is bounded. By the induction hypothesis we know that $a_1, a_2,...,a_n$ is bounded by some $M ≥ 0$; in particular, it must be bounded by $M + |a_{n+1}|$. On the other hand, $a_{n+1}$ is also bounded by $M + |a_{n+1}|$. Thus $a_1, a_2,...,a_n, a_{n+1}$ is bounded by $M + |a_{n+1}|$, and is hence bounded. This closes the induction.

**Q.E.D.**

#### *Proof that every Cauchy sequence is bounded*

Since our sequence is Cauchy we know that eventually our sequence will be eventually be $\varepsilon_M$-steady where $\varepsilon_M >0$. We can thus "split up" our sequence in a finite part and a non-finite part. We know the finite part is bounded by some $M$, and we know that starting from some $N\geq 0$ we have that $|a_j-a_k|\leq \varepsilon_M$ and $j,k\geq N$. This implies that $-\varepsilon_M\leq a_j-a_k\leq \varepsilon_M$. We can now add $a_k$ everywhere since addition preserves order. (Note that $k$ and $j$ are totally arbitrary and only greater or equal to $N$). We thus have $-\varepsilon_M+a_k\leq a_j\leq \varepsilon_M+a_k\implies |a_j|\leq \varepsilon_M +a_k$ which means that indeed the infinite sequence is bounded since, once again, $k$ and $j$ are totally arbitrary. And thus we have that the overall Cauchy sequence is bounded by $M$ if $M>\varepsilon_M$ or by $\varepsilon_M$ if $\varepsilon_M> M$ or by both if they are equal. 

**Q.E.D.**

Additional property


- If $(a_n)^\infty_{n=1}$ and $(b_n)^\infty_{n=1}$ are eventually epsilon close for a $\varepsilon>0$ and one of them is bounded, then the other one is too.
	We have that $|b_n|=|b_n-a_n+a_{n}|\leq|b_n-a_{n}|+|a_n|$ and since the $a$ sequence is bounded by $M_a$ we have that $|b_n-a_{n}|+|a_{n}|\leq |b_n-a_n|+M_a$. Now since $b$ and $a$ are eventually epsilon close for $n$ greater or equal to some $N$ we know that for every $n\geq N$ we have that $|b_{n}|\leq \varepsilon+M_a$. We also know that the sequence $(b_i)^N_{n=1}$ is finite and thus bounded by $M_b$ and thus we know that the whole sequence $(b_i)^\infty_{i=1}$ is bounded because $|b_{n}|\leq max(M_b,\varepsilon+M_a)$ for all $1\leq n$.
	
	**Q.E.D.**