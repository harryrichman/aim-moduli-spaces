---
title: Nerve of a category
---

Given a category $C$, its *nerve* $N(C)$ is the simplicial set constructed as follows. The set $N(C)_{k}$ of $k$-simplices is the set of diagrams
$$
\displaystyle A_{0} \rightarrow A_{1} \rightarrow \dots \rightarrow A_{k}
$$
of objects and morphisms from $C$. The face maps $\partial_i:N(C)_{k}
\rightarrow N(C)_{k-1}$ are given by composition of morphisms at the $i$-th node in the diagram (or dropping the first or last arrow if $i=0$ or $k$ respectively), and the degeneracy maps are given by inserting identity morphisms. The intuition here is that a $k$-simplex in $N(C)$ is precisely a commutative diagram in $C$ with the shape of a $k$-simplex. If $C$ is a topological category, we can enrich $N(C)$ to be a simplicial space.
