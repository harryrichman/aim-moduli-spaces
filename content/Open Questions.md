---
title: A list of open problems and questions on the moduli space of curves
short_title: Open questions
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

Find an explicit cell decomposition of $\mathcal{M}_g$ (no marked points). Sullivan points out that there is no known cell decomposition of $\mathcal{M}_{g,0}$. It was suggested at the problem session that there may exist a Morse function which would provide such a decomposition. Looijenga adds the following remark via email: 
> My 'suspicion' about the existence of a good Morse function on $\mathcal{M}_g$ is a bit more specific and does not involve lengths of geodesics a priori. 
> Rather, it is related to the set of conjectures mentioned in Problem (1): it is my hope that there is a naturally defined real-analytic function $f:\mathcal{M}_g\to \mathbf{R}$ (resp. $f:\mathcal{M}_{g,1}\to \mathbf{R}$) which is (a) bounded from below, (b) proper and (c) is such that its Leviform $\sqrt{-1}\partial\overline{\partial} f$ has everywhere at most $g - 2$ (resp. $g-1$) eigenvalues $\leq 0$. 
> This would not only imply Harer's result cited above, but would also imply that the cohomological dimension for coherent complex-analytic sheaves is at most $g-2$ (resp. $g-1$) and for constructible sheaves is at most $(3g - 3) + g - 2$ (resp. $(3g-2)+g-1$).

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

There is a potentially interesting connection between outer automorphisms and mapping class groups. Let $F_n$ denote the free group on $n$ generators and $\mathrm{Aut}(F_n)$ its automorphism group.

**Conjecture:** $\widetilde{H}^*(B\mathrm{Aut}(F_\infty);\mathbb{Q})=0$.  

Daniel Biss (of Chicago) has suggested that the diagram

![diagram](https://www.aimath.org/WWN/modspacecurves/open-problems/img50.png)

becomes homotopy cartesian after localization at $\mathbb{Q}$. Borel's computation of $H^*(BSp_\infty(\mathbb{Z});\mathbb{Q})$ and $H^*(BGL_\infty(\mathbb{Z});\mathbb{Q})$ in conjunction with the Madsen-Weiss calculation of $H^*(B\Gamma_{\infty,1};\mathbb{Q})$ implies the conjecture. Perhaps it might be better to replace $BGL_\infty(\mathbb{Q})^+$ by Waldhausen's $A(*)$ and $BSp_\infty(\mathbb{Z})^+$ with a symplectic analogue $ASp(*)$. (Note: $A(pt)$ is rationally equivalent to $BGL(\mathbb{Z})^+$, and $ASp(pt)$ is rationally equivalent to $BSp(\mathbb{Z})^+$.) The resulting diagram might then be homotopy cartesian even before localizing at $\mathbb{Q}$. (We have seen cohomology classes in $BAut$, but they all vanish as rank goes to infinity.)

Some related thoughts: What is the relation with the restriction of $\kappa_{2i}$ to $H^*(\mathcal{M}_{g,n}^c)$? Is $\mathcal{M}^c_{g,n}$a $K(\pi,1)$? Is it true that $\pi_1\mathcal{M}_{g,n}^c$ is precisely the kernel of the Johnson homomorphism? Looijenga points out that the answer to these last two questions is definitely no for large genus. By work of Johnson, the $\mathbf{Q}$-cohomological dimension of the (orbifold) fundamental group of $\mathcal{M}_{g}^{c}$ grows like a cubic polynomial in $g$ which is certainly larger than the dimension of the space itself. Instead he proposes the following question.

## 8. (Looijenga)

It is well-known that the map $K(\Gamma_g,1)\to
K(Sp_g(\mathbb{Z}),1)$ is realized in algebraic geometry as the period map $\mathcal{M}_g\to\mathcal{A}_g$. This map extends to a proper map $\mathcal{M}^c_g\to \mathcal{A}_g$. The former is injective, but the latter is not (the image of a stable curve of compact type only allows us to recover its irreducible components of positive genus). Perhaps less known is the fact that the Eilenberg-MacLane functor applied to the Johnson truncation $\Gamma_g\to J_g = \pi_1(\mathcal{M}^c_g)$ has an algebro-geometric incarnation as well, namely a lift of the period map to a torus bundle $\mathcal{D}_g^\mathrm{pr}$ over $\mathcal{D}_g$, which was studied in depth by Hain. This map also extends to a proper map $\mathcal{M}^c_g\to \mathcal{D}_g^\mathrm{pr}$ (Theorem 8.6. of [ [HL97]](Bibliography#HL97)). That extension still fails to be injective in general, but it certainly remembers more that the period map: given a stable curve $C$ of compact type, then its image in $\mathcal{D}_g^\mathrm{pr}$ allows us to reconstruct the curve obtained from $C$ by contracting all of its rational components (so we not only know its irreducible components of positive genus, but also how they are connected with each other). Let $\mathcal{M}^{cc}_g$ be the corresponding quotient of $\mathcal{M}^c_g$ so that we now have a closed injection $\mathcal{M}^{cc}_g\to \mathcal{D}_g^\mathrm{pr}$ (in the orbifold sense).

**Question:** is this map highly connected in the sense is that orbifold universal cover of $\mathcal{M}^{cc}_g$ is $n_g$-connected with $n_g\to\infty$ as $g \to \infty$?

Remarks: 
- (a) It is known that the image of the stable cohomology of $J_g$ in the rational cohomology of $\Gamma_g$ is the subalgebra generated by the $\kappa_i$'s. Since we know a priori that all the $\mathbb{Q}$-stable classes on $\mathcal{M}_g$ extend to $\mathcal{M}^{cc}_g$, a yes answer would lead to a new proof of the Mumford conjecture. Perhaps that conversely the techniques of the Madsen-Weiss proof can help to settle this question.
- (b) The variety $\mathcal{M}^{cc}_g$ may of interest in its own right. For an algebraic geometer it is natural to ask whether it solves a moduli problem.

## 9. (Vakil)

Regarding Faber's conjecture, explain the intersection number part (values of products of $\kappa$ classes in $R^{g-2}\mathcal{M}_g$). This is known by Virasoro methods, but this should not be the "real reason." What is the real reason? This is related to Morita's conjecture announced at this conference [ [Mor05]](Bibliography#Mor05) (Conjecture 1, p. 4). For that matter, prove Morita's conjecture! Perhaps this is the "right" way to prove Faber's intersection number conjecture.

## 10. (Mondello)

For $\mathcal{M}_{g,n}^{\leq k \text{ rational components}}$, is $R^{g-1+k}\cong \mathbb{Q}$? What is $\mathcal{R}^{g-1+k}$ generated by? When should we expect a 1-dimensional socle, and what should we expect for $\mathcal{R}(\mathcal{M}_{g,n}^{\leq k})$?

## 11. (Igusa)

Are there operations which relate the stable classes on $B\Gamma_\infty$? We have $H_{spec}^*(\mathbb{CP})^\infty_{-1} \cong
\mathbb{Z}[c_1]\cdot u$, where $u$ is the Thom class in degree -2. How is this reflected at the level of infinite loop spaces? What are the stable maps $\mathbb{CP}^\infty_{-1} \to \mathbb{CP}^\infty_{-1}$?

## 12. (Baldwin)

 Has anyone computed the intersection cohomology of $\overline{\mathcal{M}}_{g,n}(\mathbb{P}^r,d)$? These can be arbitrarily singular, but this is what intersection cohomology is designed for. Is there a good notion of the tautological ring here? Perhaps the virtual fundamental class plays the usual role of the fundamental class.

## 13. (Faber)

 From Ekedahl and van der Geer, $\lambda_g$ is 0 on $\mathcal{A}_g$ rationally but not integrally. The order in integral cohomology has been computed up to a factor of two. What is it? (Compare to [[Open Questions#5. (Mondello)]] above.)

## 14. (Bertram)

When will Getzler's paper on $\overline{\mathcal{M}}_1$ appear (even just as a preprint)? **Conjecture:** $t\to \infty$. Getzler comments that he does not like how this question is phrased.

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

Same question for $C\to BG$, with $G$ a finite group. Tillmann says "yes" for $G=S^1$. More precisely, consider
$$
E \mathrm{Diff}(F_{g,1})\times_{\mathrm{Diff}(F_{g,1})}
\mathrm{Map}^\partial(F_{g,1},BG)
$$
for $G$ connected, such as $S^1$. This stabilizes by gluing in tori and the induced map on homology is an isomorphism in some range. Is this related?

## 17. (Sullivan)

Fix a curve $C$ and look at all unbranched covers of it. This gives points in $\mathcal{M}_g$. Do these become uniformly dense for any $C$ (with respect to the Teichmuller metric) in universally defined regions $U_{g}$ of $\mathcal{M}_g$ for $g$ large? More precisely, given $\epsilon > 0$, can we find $g_{0}$ such that, for $g > g_{0}$ every point of $U_{g}$ is within distance $\epsilon$ of an unbranched cover of $C$ of genus $g$? This would imply that, given curves $C_1,C_2$, one could find covers $\tilde{C}_1,\tilde{C}_2$ which are arbitrarily close in the moduli space, the Siegel-Ehrenpreis problem.

## 18. (Morita)

There are many numerical invariants that can be associated to the moduli space.

1. One may compute the signature of the cohomology ring of $\overline{\mathcal{M}}_{g,n}$.
2. Since $\overline{\mathcal{M}}_{g,n}$ is a rational cohomology manifold, there are Thom's rational Pontrjagin classes, and one may compute the rational $L$-genus with respect to these.
3. Lastly, $\overline{\mathcal{M}}_{g,n}$ is an orbifold of a complex manifold, so there are orbifold Chern classes, and hence orbifold Pontrjagin classes. Thus one may talk about the orbifold $L$-genus.

What are these numbers? Do they agree? Probably not, but their disagreement would tell us interesting information about the types of singularities in the moduli space. The difference between the signature and the rational $L$-genus detects geometric singularities. The difference between the rational $L$-genus and the orbifold $L$-genus detects complex analytic singularities.

One may similarly ask questions about the signature of the tautological ring, and many other variations on this theme.

## 19. (Sullivan)

This question regards the algebraic structure on the homology of the free loop space of a manifold. There are maps
$$\displaystyle H_*LM \stackrel{\Delta}{\longrightarrow} H_*LM \otimes H_*LM
$$
and
$$\displaystyle H_*LM \otimes H_*LM \stackrel{\mu}{\longrightarrow} H_*LM
$$
First the naive question: what is the algebraic structure here? The spectral sequence converging to $H_*LM$ has $E_2$ term a tensor product of a Hopf algebra (coming from the base $M$) and a Frobenius algebra (coming from the fibre). But the differential does not respect these structures.

A perhaps better question is: can we illuminate the situation be reformulating in terms of the category of spaces over $M$? We have

![$\displaystyle \begin{diagram}\node{LM} \arrow{s} \arrow{e} \node{LM \times_M LM...<br>...w{e,t}{\mathrm{id}} \node{M} \arrow{e,t}{\Delta} \node{M\times M} \end{diagram}$](https://www.aimath.org/WWN/modspacecurves/open-problems/img125.png)

The left square corresponds to the Frobenius algebra part, and the right square corresponds to the Hopf algebra part. So, what is the full algebraic structure here?
