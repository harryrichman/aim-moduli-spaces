---
title: Pontrjagin-Thom construction
---

This is the construction which identifies cobordism groups of manifolds with the homotopy groups of certain [[Spectrum|spectra]] (written $MO$, $MU$, etc). The result is the following, along with many variations obtained by considering some additional structure on the stable normal bundle.

**Theorem 1** (Pontrjagin-Thom)    _$\pi_n MSO $ is canonically isomorphic to the oriented cobordism group of $n$-manifolds._

Given a manifold $M^{d}$ smoothly embedded in Euclidean space $\mathbb{R}^{n+d}$, there exists a tubular neighborhood $U \supset M$ homeomorphic to the total space of the normal bundle $\nu^{n}$ of $M$. If we collapse everything outside of $U$ to a point, we obtain a map from $S^{n+d}$ to the one-point compactification of $U$, which is just $\mathrm{Th}(\nu^{n})$, the Thom space of $\nu^{n}$. If we compose this map with the map from $\mathrm{Th}(\nu)$ to the universal Thom space $\mathrm{Th}(U^{d})$ over the Grassmannian (these fit together to form a [[Spectrum|spectrum]] $MSO$, $MU$, etc), this rephrases the data of an embedded manifold in terms of a map $f:S^{n+d} \to \mathrm{Th}(U^d)$. A cobordism of $M$ can be embedded into $\mathbb{R}^{n+d}\times I$ and similarly gives rise to a homotopy between the maps constructed at either end of the cobordism.

Going in the other direction, a map $f:S^{n+d} \to \mathrm{Th}(U^d)$ can be modified by a homotopy to be transversal to the zero-section. The inverse image of the zero-section is an embedded manifold $M^d$, whose cobordism class depends only on the homotopy class of $f$.

Thom was able to use this homotopy theoretic reformulation of the cobordism groups, together with algebraic properties of the Steenrod algebra, to completely compute the structure of the oriented cobordism ring.

In the proof of Mumford's conjecture, the Pontrjagin-Thom construction is used to construct a map $B\Gamma_{g} \rightarrow \lim_{n\rightarrow
\infty}\Omega^{n+2}\mathrm{Th}(U_{2,n}^{\perp})$.
