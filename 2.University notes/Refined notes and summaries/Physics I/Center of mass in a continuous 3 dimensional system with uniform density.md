---
Date created: 2024-09-28 13:46
tags:
  - Type/Refined_Note
  - Topic/Physics
---

---

Types: _Not applicable_
Examples: [[Center of mass in a semi circle with uniform density]]
Properties: [[Partitioning of continuous systems with uniform density for easier computing of the center of mass]]

Justifications: [[Center of mass in a discrete system]]
Specializations: [[Center of mass in a discrete system]]
Generalization: [[Center of mass in a continuous 3 dimensional system with variable density]]

---

Let $A\subset \mathbb{R}^{3}$ be a a continuous system of particles$^{[1]}$ with total mass $M$ and volume $V_{A}$ and uniform density $\rho$, noting that per definition of density $dm=\rho  dV$. We now generalize the center of mass from a discrete system to a continuous system by $$ \sum^{k}_{i=1}m_{i}(p_{i}-R)\longrightarrow  \int_{A}  (r-R) \;dm =\int_{A} (r-R)\rho \;dV=0$$Where the particles $p_{i}$ with their respective weight $m_{i}$ become$^{[2]}$ arbitrary particles $r$ with their respective infinitesimal weight $dm$. Do note that $r$ is considered a variable in this context, whilst $R$ is some fixed point or in other words a constant. We can now solve for $R$, since $$ \begin{align} \int_{A} (r-R)\rho \;dV=0 \end{align}  $$We know that $$ \int_{A} r\rho\; dV=\int_{A} R\rho\; dV $$We can now pull $R$ and $\rho$ out of the integral since it is just some constant, and we are left with $$ \int_{A} r\rho\; dV=R\rho\int_{A} \; dV  $$But the integral $\int_{A} \; dV$ is just equal to the entirety of the volume of $A$, namely $V_{A}$. And since $\rho V_{A}=M$, we end up with $$ R=\frac{1}{M}\int_{A} r\rho \; dV  $$

---

**_Remark_**$^{[1]}$: For the sake of ease we will not define what a continuous system of particles is, and just let our intuition speak regarding the type of systems we are studying. If you want examples, think any standard solid for example, like a sphere or cube or triangle etc...

**_Remark_**$^{[2]}$: Since this is physics and not mathematics we can do the transition from a sum to an integral in this hand-wavery manner without bothering with the associated formalities. As rule of thumb, in physics we may often make the following transform $$ \sum^{}_{}\Delta x \longrightarrow \int_{} \;dx$$