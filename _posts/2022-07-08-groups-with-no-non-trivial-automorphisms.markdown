---
layout: post
title:  "Groups with no non-trivial automorphisms"
date:   2022-07-08 10:42:00 +0200
categories: miscellaneous-mathematics
usemathjax: true
---
<p style="text-align:justify;">Today, I would like to write about a fun exercise which appeared in the oral part of the entrance “concours” of the École normale supérieure some years before I entered the École. Contrary to my natural tendencies, perhaps, it is in group theory and not in commutative or linear algebra.</p>

<p style="text-align:justify;">The exercise is the following:</p>

<p style="text-align:justify;"><b>Exercise.</b> What can be said about a group with no non-trivial automorphisms?</p>

<p style="text-align:justify;">I recall the exercise being posed precisely in this way, so as to give as little information about what answer is expected as possible to the candidate.</p>

<p style="text-align:justify;">The moral of the story in this exercise is that in a general group, we do not know many examples of automorphisms. The most well-known (and, to an extent, the most important) are the <em>inner automorphisms</em>: given an element $g$ of a group $\mathrm{G}$, it is given by $x\mapsto gxg^{-1}$. An easy but clever computation shows that it is indeed a group homomorphism; the inverse of the inner automorphism given by $g$ is then the inner automorphism given by $g^{-1}$.</p>

<p style="text-align:justify;">Assume now that $\mathrm{G}$ is a group with no non-trivial automorphism. In particular, the inner automorphism associated with $g\in\mathrm{G}$ is trivial. It is easy to see that its kernel is the <em>commutator</em> of $g$, that is, the set $\{x\in\mathrm{G},xg=gx\}$. Thus we see that $\mathrm{G}$ is commutative.</p>

<p style="text-align:justify;">Now in a commutative group, there is another important automorphism: the inverse $x\mapsto x^{-1}$. By assumption, the inverse is trivial: this means that any element of $\mathrm{G}$ has order at most $2$.</p>

<p style="text-align:justify;">Observe then that $\mathrm{G}$ may be turned into a $\mathbb{Z}/2\mathbb{Z}$-vector space: simply define $\overline{k}\cdot x=x^k$ for all $x\in\mathrm{G}$ and all $k\in\mathbb{Z}$ with class $\overline{k}\in\mathbb{Z}/2\mathbb{Z}$.</p>

<p style="text-align:justify;">We already know of two $\mathbb{Z}/2\mathbb{Z}$-vector spaces with no non-trivial group automorphisms: the trivial group and $\mathbb{Z}/2\mathbb{Z}$. We are going to show that they are the only two.</p>

<p style="text-align:justify;">We are going to prove this fact by contrapositive (very awkward terminology but I could not find the accurate English translation of “contraposée”). What we have to show is that given a $\mathbb{Z}/2\mathbb{Z}$-vector space $\mathrm{G}$ with a basis of cardinality at least two, $\mathrm{G}$ admits a non trivial automorphism.</p>

<p style="text-align:justify;">Let $\mathrm{H}$ be a $2$-dimensional $\mathbb{Z}/2\mathbb{Z}$-vector space of $\mathrm{G}$ with basis $(e_1,e_2)$ and let $\mathrm{K}$ be a subspace of $\mathrm{G}$ such that $\mathrm{G}=\mathrm{H}\oplus\mathrm{K}$. Define an automorphism $f$ of $\mathrm{G}$ by the following assignments: $f$ induces the identity on $\mathrm{H}$, $f(e_1)=e_2$ and $f(e_2)=e_1$. Then $f$ is non-trivial. This establishes the claim.</p>
