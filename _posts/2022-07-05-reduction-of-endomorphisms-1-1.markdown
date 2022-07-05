---
layout: post
title:  "Reduction of endomorphisms, 1.1: Invariant spaces, generalities"
date:   2022-07-05 11:48:59 +0200
categories: reduction-of-endomorphism
usemathjax: true
---
<p style="text-align:justify;">We let $k$ be a field; we make no assumptions on $k$. We let $\mathrm{V}$ be a $k$-vector space; the letter $u$ denotes a $k$-linear map from $\mathrm{V}$ to $\mathrm{V}$. The fundamental definition in reduction is the following.</p>

<p style="text-align:justify;"><b>Definition.</b> Let $\mathrm{W}$ be a sub-vector space of $\mathrm{V}$. Then $\mathrm{W}$ is <em>invariant under $u$</em> or $u$-invariant when $u(w)\in\mathrm{W}$ for all $w\in\mathrm{W}$.</p>

<p style="text-align:justify;"><em>Remark.</em> I prefer the French terminology of <em>stable</em> spaces, in part because to me, intuitively, an invariant space $\mathrm{W}$ should satisfy $u(\mathrm{W})=\mathrm{W}$ and not $u(\mathrm{W})\subseteq\mathrm{W}$ as is required by the definition above. If you come across the word “stable” in a sentence where “invariant” should clearly be used, or even if there is a possible confusion because of the context, do let me know by e-mail and I will correct it.</p>

<p style="text-align:justify;"><b>Trivial example.</b> The subspaces $\{0\}$ and $\mathrm{V}$ of $\mathrm{V}$ are $u$-invariant.</p>

<p style="text-align:justify;">The proof of the following lemma is very easy; we let the reader prove it themself.</p>

<p style="text-align:justify;"><b>Lemma.</b> Let $\mathrm{W}$ be a subspace of $u$. Then the set of $k$-linear endomorphisms of $\mathrm{V}$ under which $\mathrm{W}$ is invariant is a sub-$k$-algebra of the $k$-algebra $\mathrm{L}_k(\mathrm{V})$ of $k$-linar endomorphisms of $\mathrm{V}$.</p>

<p style="text-align:justify;">Recall the following definition.</p>

<p style="text-align:justify;"><b>Definition.</b> Let $u$ and $v$ be $k$-linear endomorphisms of $\mathrm{V}$. We say that $u$ and $v$ <em>commute</em> when $u\circ v=v\circ u$.</p>

<p style="text-align:justify;">The following class of invariant spaces yields a great number of examples in practice.</p>

<p style="text-align:justify;"><b>Lemma.</b> Let $u$ and $v$ be commuting $k$-linear endomorphisms of $\mathrm{V}$. Then the kernel $\mathrm{Ker}(v)=\{x\in\mathrm{V},v(x)=0\}$ and the image $\mathrm{Im}(v)=\{v(x),x\in\mathrm{V}\}$ of $\mathrm{V}$ are $u$-invariant.</p>

<p style="text-align:justify;"><em>Proof.</em> We only prove the assertion relative to the kernel; the proof for the assertion on the image is similar and left to the reader. Let then $x$ be an element of the kernel of $v$; we have to show that $u(x)$ belongs to the kernel of $v$, that is, that $v(u(x))=0$. But since $u$ and $v$ commute, $$v(u(x))=v\circ u(x)=u\circ v(x)=u(v(x))=u(0)=0.$$ This establishes the claim.$\square$</p>

<p style="text-align:justify;">In the next post, we will study invariant spaces for particular classes of endomorphisms.</p>
