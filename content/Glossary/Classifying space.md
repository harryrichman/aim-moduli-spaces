---
title: Classifying space
tags: []
---

The classifying space $BC$ of a category $C$ is the geometric realization of the [[Nerve of a category|nerve]] $N(C)$. That is,

$$
BC = (\amalg \bigtriangleup_{k} \times N(C)_{k})/\sim
$$

where the equivalence relation $\sim$ glues the $k$-simplices together as specified by the face and degeneracy maps of $N(C)$. For a group $G$, we can consider the category with a single object and morphisms given by elements of $G$; in this case, this construction recovers the Borel construction $BG$. More generally, given a group $G$ acting on a space $X$, we can construct a (topological) category whose objects are given by points in $X$ and whose morphisms are given by elements of $G$. The classifying space of this category is the homotopy quotient $X//G = EG \times_{G} X$. If $C$ is a strict symmetric monoidal category then $BC$ will be an [[Infinite loop space|infinite loop space]].

Note that in algebraic geometry, "$BG$" often refers to the stack-theoretic quotient $[\mathrm{point} / G]$.