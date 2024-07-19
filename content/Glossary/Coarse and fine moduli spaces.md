---
title: Course and fine moduli spaces
tags: []
---

Suppose we have some kind of algebraic object that we want to parametrize (say, curves or vector spaces). A moduli functor is a contravariant functor $F :
\mathrm{Schemes} \rightarrow \mathrm{Sets}$ which sends a scheme $X$ to the set of isomorphism classes of families of these objects parametrized by $X$ (e.g. families of curves over $X$). A morphism $f$ of schemes is sent to the set map induced by pulling back families via $f$.

A fine moduli space is a scheme $M$ representing this functor. That is to say, there is a universal family over $M$ and, for every family of objects over a scheme $X$, there is a unique map $X \rightarrow M$ which induces it by pulling back the universal family. This is usually impossible (for example, when there are extra automorphisms for some objects). If we are willing to enlarge the category in which we work, we can sometimes obtain a fine moduli space by working with stacks instead of schemes. Otherwise, the coarse moduli space is the scheme which best approximates the fine moduli space. By this, we mean that given a family of objects over a parameter space $X$, there will be a unique map from $X$ to the coarse space $M$, and $M$ is "universal" with respect to this property, which is to say that if there is also $M'$ with this property, then the map $X\to M'$ factors uniquely as $X\to M \to M'$. Note that not every map to the coarse moduli space $M$ gives rise to a family. In particular there may not be a universal family of objects over $M$ itself.

Another requirement for a coarse moduli space is that its points should be in bijection with the objects being parametrized. I.e. algebraically-closed-field-valued points should be in bijection with the objects defined over that algebraically closed field.