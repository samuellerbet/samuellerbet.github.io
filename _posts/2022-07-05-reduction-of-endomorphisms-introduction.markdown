---
layout: post
title:  "Reduction of endomorphisms, 0: Introduction"
date:   2022-07-05 10:41:13 +0200
categories: reduction-of-endomorphisms
usemathjax: true
---
<p style="text-align:justify;">This is the first of a series of blog posts about reduction of endomorphisms.</p>

<p style="text-align:justify;">Reduction is the part of (somewhat) linear algebra that studies vector spaces $\mathrm{V}$ over a field $k$ endowed with a specified endomorphism $u$ with the goal to find a basis of $\mathrm{V}$ in which the matrix of $u$ has a “nice form”. This may mean diagonal (the ideal case), upper triangular or diagonal by blocks, be they Jordan or Frobenius blocks, etc.</p>

<p style="text-align:justify;">Because of change-of-basis formulae, this mission statement has a more concrete interpretation solely in terms of matrices (since we will mostly consider reduction in a finite-dimensional setting). Let then $\mathrm{M}$ be a square matrix of size $n$ with coefficients in $k$. Then reducing $\mathrm{M}$ means finding an inversible matrix $\mathrm{P}$ such that $\mathrm{P}^{-1}\mathrm{M}\mathrm{P}$ has a nice form in the sense above.</p>

<p style="text-align:justify;">As alluded to in the beginning of this paragraph, the connection between these two points of view is given by change-of-basis formulae: if $u$ is an endomorphism of a (finite-dimensional) vector space $\mathrm{V}$ and if $\mathrm{M}$ denotes its matrix in a given basis of $\mathrm{V}$, then by change-of-basis formulae, reducing $u$ amounts to reducing $\mathrm{M}$; reciprocally, if $\mathrm{M}$ is a square matrix with coefficients in $k$, then recuding $\mathrm{M}$ is equivalent to reducing the endomorphism of $k^n$ naturally associated with $\mathrm{M}$ (which sends the $i$-th basis vector to the $i$-th column of $\mathrm{M}$). However, it is more flexible to think in the language of endomorphisms of vector bundles, in a coordinate-free manner; thus I will write mostly in this language. There is one significant exception. One often wishes to study reduction “up to extension of fields”: for instance, even if one is solely interested in matrices with real coefficients, it is useful to know when those are, <em>e.g.</em> diagonalisable <em>as complex matrices</em> which, because the field of complex numbers is algebraically closed, is more frequent. This is more convenient to state and investigate in terms of matrices, though by no means impossible to study with endomorphisms: it requires the introduction of tensor products which is slightly more advanced than I would like but I may return to it at a later date.</p>
