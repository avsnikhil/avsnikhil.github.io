---
title: "Near-Optimal Algorithms for Stochastic Online Bin
Packing"
collection: publications
permalink: /publications/online-bin-packing-ICALP2022
excerpt: 
date: 2022-06-28
venue: 'ICALP'
paperurl: 'https://drops.dagstuhl.de/opus/volltexte/2022/16353/'
citation:
---
with Rajni Dabas, Arindam Khan, K. V. N. Sreenivas.

[Download paper here](https://drops.dagstuhl.de/opus/volltexte/2022/16353/)

## Abstarct
We study the online bin packing problem under two stochastic settings. In the bin packing problem, we are given $n$ items with sizes in $(0,1]$ and the goal is to pack them into the minimum number of unit-sized bins.
First, we study bin packing under the  i.i.d. model, where item sizes are sampled independently and identically from a distribution in $(0,1]$.
Both the distribution and the total number of items are unknown. 
The items arrive one by one and their sizes are revealed upon their arrival and they must be packed immediately and irrevocably
in bins of size $1$. 
We provide a simple meta-algorithm that takes an offline $\alpha$-asymptotic approximation algorithm and
provides a polynomial-time $(\alpha + \epsilon)$-competitive algorithm for online bin packing under the  i.i.d. model, where $\epsilon>0$ is a small constant.
Using the AFPTAS for offline bin packing, we thus provide a linear time $(1+\epsilon)$-competitive algorithm for online bin packing under i.i.d. model, thus settling the problem.

We then study the random-order model, where an adversary specifies the items, but the order of arrival of items is drawn uniformly
at random from the set of all permutations of the items. Kenyon's seminal result [SODA'96] showed that the Best-Fit algorithm has a competitive ratio of at most $3/2$ in the random-order model, and conjectured the ratio to be $\approx 1.15$. 
However, it has been a long-standing open problem to break the barrier of
$3/2$ even for special cases. Recently, Albers et al. [Algorithmica'21] showed an improvement to $5/4$ competitive ratio in the special case when
all the item sizes are greater than $1/3$.
For this special case,
we settle the analysis by showing that Best-Fit has a competitive ratio of $1$.
We also make further progress by breaking the barrier of $3/2$ for
the *3-Partition* problem, a notoriously hard special case of bin packing, where all item sizes lie in $(1/4,1/2]$.
