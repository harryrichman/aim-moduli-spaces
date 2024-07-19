---
title: A list of open problems and questions on the moduli space of curves
short_title: Open questions
draft: false
tags: []
date: 2005-05-15
author: Jeffrey Herschel Giansiracusa
---

This document was produced as part of the activities during the Topology and Geometry of the Moduli space of Curves workshop in March 2005; it is a component of a larger resource site at [http://www.aimath.org/WWN/modspacecurves/](http://www.aimath.org/WWN/modspacecurves/)

Please send updates, additions, comments, corrections, etc. to either
- Jeff Giansiracusa ([giansira@maths.ox.ac.uk](mailto:giansira@maths.ox.ac.uk))
- or Davesh Maulik ([dmaulik@math.princeton.edu](mailto:dmaulik@math.princeton.edu)).

This document originated as a rough transcription of the problems and questions generated during a discussion session towards the close of the workshop. Hopefully it will continue to evolve into a repository of new questions about the moduli space of curves. Towards this goal, readers are encouraged to submit new questions and information regarding developments on the questions listed here.

(Some of these problems may have already been solved, and the bibliographic data here is incomplete, so the reader is advised to do the usual background reading before investing time in these questions. Conversely, if you have any information on recent work or useful articles, please let us know so that we can keep this page current.)

## 1. (Vakil, speaking for Looijenga)

Define:
- $a(\mathcal{M}_g) = g - 2$,
- $a(\mathcal{M}_{g,n}) = g - 1$ (for $n > 0$),
- $a(\mathcal{M}^c_{g,n}) = 2g - 3 - n$,
- $a(\mathcal{M}_{g,n}^\text{rational tails}) = g + n - 2$, and
- $a(\mathcal{M}_{g,n}^{\leq k \text{ rational components}}) = g - 1 + k$.

(See [[Partial compactifications]] for definitions referred to in the final three entries above.)

Question: Is it true that $\mathcal{M}_{g,n}^*$ has the homotopy type of a complex of (real) dimension $a(\mathcal{M}_{g,n}^\bullet) + \dim_\mathbb{C} \mathcal{M}_{g,n}^\bullet$? If not, is the cohomological dimension $\leq a(\mathcal{M}_{g,n}^\bullet)$ + $\dim_\mathbb{C} \mathcal{M}_{g,n}^\bullet$? What about quasicoherent cohomological dimension $C \leq a(\mathcal{M}_{g,n}^*)$? Or with cohomology of $\ell$-adic sheaves, is the cohomological dimension $a(\mathcal{M}_{g,n}^*) + \dim_\mathbb{C} \mathcal{M}_{g,n}^*$? (Note that some of these have already been answered by Looijenga.)

## 2. (Sullivan)

Find an explicit cell decomposition of $\mathcal{M}_g$ (no marked points). Sullivan points out that there is no known cell decomposition of $\mathcal{M}_{g,0}$. It was suggested at the problem session that there may exist a Morse function which would provide such a decomposition. Looijenga adds the following remark via email: My 'suspicion' about the existence of a good Morse function on $\mathcal{M}_g$ is a bit more specific and does not involve lengths of geodesics a priori. Rather, it is related to the set of conjectures mentioned in Problem (1): it is my hope that there is a naturally defined real-analytic function $f:\mathcal{M}_g\to \mathbf{R}$ (resp. $f:\mathcal{M}_{g,1}\to \mathbf{R}$) which is (a) bounded from below, (b) proper and (c) is such that its Leviform $\sqrt{-1}\partial\overline{\partial} f$ has everywhere at most $g - 2$ (resp. $g-1$) eigenvalues $\leq 0$. This would not only imply Harer's result cited above, but would also imply that the cohomological dimension for coherent complex-analytic sheaves is at most $g-2$ (resp. $g-1$) and for constructible sheaves is at most $(3g - 3) + g - 2$ (resp. $(3g-2)+g-1$).

In addition, Sarnak has conjectured that $\mathrm{det} \Delta$ gives a Morse function on $\mathcal{M}_g$. (Is there a reason for Sarnak to believe this conjecture true?)

## 3. (Bodigheimer)

A question related to both of the previous problems: What is the Lusternik-Schnirelman category of $\mathcal{M}_g$? This is a number, bounded above by the dimension, and bounded below by the cup-length of the cohomology ring (the largest number of elements in positive degree which have a non-zero cup product. Can anyone compute the cup-length of the moduli space?

## 4. (Getzler et al.)

Consider the Hochschild cohomology of the Fukaya category of a compact Kahler manifold $X$. (Roughly speaking, the Fukaya category has Lagrangian subspaces as objects and intersections as morphisms.)

1. Is this (naturally) isomorphic to quantum cohomology? The problem here is to make the known map mathematically rigorous. What does this have to do with what we know about $\overline{\mathcal{M}}_{0,3}$?
2. Is the cyclic homology of the Fukaya category of $X$ isomorphic to the Gromow-Witten theory of $X$?

Costello's theorems imply that these conjectures are plausible. Costello comments that the existence of the map should be a purely analytic question.

## 5. (Bertram)

Are there any stable torsion classes in $AH^*(\mathcal{M}_{g,n})$? (Here $AH$ denotes the image of Chow in cohomology.)

## 5. (Mondello)

Is there a stable torsion class represented by some algebraic cycle which geometers "can see"? e.g. $\lambda_g
\delta_0$ on $\overline{\mathcal{M}}_g$ satisfies $2\lambda_g \delta_0=0$. Is it zero? Faber says yes, over a field of characteristic 2. Teleman suggests that there are lots of natural torsion classes in $K$-theory (arising from the Grotherdieck-Riemann-Roch theorem); how do they look in cohomology? (Compare to 13. below.)

## 5. (Looijenga)

As a related question, it is known that the $\kappa_i$'s live on $\overline{\mathcal{M}}_g$. It is true that all of the stable classes (so including torsion) live on the orbifold $\overline{\mathcal{M}}_g$?

## 6. (Madsen)

Consider the Torelli group $I_{g,n} = \mathrm{ker}\{
\mathcal{M}_{g,n} \to \mathrm{Aut}(H_1(F_{g,n}),\omega\} \cong
Sp_{2g}(\mathbb{Z})$. It is known that the odd classes $\kappa_{2i+1}$ on $\mathcal{M}_{g,n}$ can be pulled back from classes in $H^*(Sp_{2g}(\mathbb{Z}))$, but the even classes $\kappa_{2i}$ do not come from the symplectic group. One might thus expect that the even classes pull back to nontrivial classes on the Torelli group, but surprisingly the answer is not known. Do the $\kappa_{2i}$ restrict to zero on $H^*(I_{g,n})$? Is this true stably as $g \to \infty$? Igusa thinks that the answer is "yes."

## 7. (Madsen)

## 8. (Looijenga)

## 9. (Vakil)

## 10. (Mondello)

## 11. (Igusa)

## 12. (Baldwin)

## 13. (Faber)

## 14. (Bertram)

## 15. (Ellenberg)

Consider Hurwitz space (genus $g$, degree $d$). Could the cohomology stabilize as $g \to \infty$ with $d$ fixed? The reason behind this question is that point counting over finite fields gives exactly the behavior we would expect if we had Harer stability in degree 2.

So, could some sort of Harer stability hold for some sort of Hurwitz schemes? Motivation for this question comes from work on number fields/function fields done in the '80s by Darskovksy and Wright.

The general philosophy is this: suppose we have a nice sequence of varieties $\{X_n\}_{n\in \mathbb{N}}$, and
$$
\displaystyle \mathrm{lim}_{n\to\infty} \frac{\text{\#  points on $X_n(\mathbb{F}_q)$}}
{q^{\mathrm{dim} X_n}}
$$

exists for all $q$. Is this because of some version of Harer stability at play here?

## 16. (Tseng)

## 17. (Sullivan)

Fix a curve $C$ and look at all unbranched covers of it. This gives points in $\mathcal{M}_g$. Do these become uniformly dense for any $C$ (with respect to the Teichmuller metric) in universally defined regions $U_{g}$ of $\mathcal{M}_g$ for $g$ large? More precisely, given $\epsilon > 0$, can we find $g_{0}$ such that, for $g > g_{0}$ every point of $U_{g}$ is within distance $\epsilon$ of an unbranched cover of $C$ of genus $g$? This would imply that, given curves $C_1,C_2$, one could find covers $\tilde{C}_1,\tilde{C}_2$ which are arbitrarily close in the moduli space, the Siegel-Ehrenpreis problem.

## 18. (Morita)

## 19. (Sullivan)

