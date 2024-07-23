---
title: Gromov-Witten invariants
---

*Gromov-Witten invariants* count (in a loose sense only) holomorphic maps from genus $g$ Riemann surfaces to a variety $X$ which pass through a given collection of cycles on $X$. In order to define these, we compactify the space of maps from a variable pointed curve $C$ to $X$ by allowing the domain curve to degenerate to a nodal curve so that the corresponding map always has finite automorphism group. For a fixed genus $g$, image homology class $\beta$, and number of marked points $n$, this gives the moduli space of stable maps $\overline{\mathcal{M}}_{g,n}(X,\beta)$ which is typically a highly singular [[Deligne-Mumford stack]]. The Gromov-Witten invariants of $X$ are given by integrals

$$
\displaystyle \int_{[\overline{\mathcal{M}}_{g,n}(X,\beta)]^\mathrm{vir}}
ev_1^*(\alpha_1) \cdots ev_n^*(\alpha_n)
$$

where $ev_i: \overline{\mathcal{M}}_{g,n}(X,\beta) \to X$ is evaluation at the $i^{th}$ marked point and the $\alpha_i$ are elements of $H^*(X;\mathbb{Q})$. An important point of the theory is that this integral is defined via cap product with a distinguished homology class known as the virtual fundamental class of $\overline{\mathcal{M}}_{g,n}(X,\beta)$. The descendent Gromov-Witten Invariants are obtained by inserting monomials in the [[Witten classes]] $\psi_i$ into the integral.
