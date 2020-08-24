---
layout: archive
title: "Test"
permalink: /test/
author_profile: true
---

Consider the following problem: we need to sample vectors $(x,y)$ from the unit disk $\mathcal{D} = \\{ (x,y) : x^2 + y^2 \leq 1\\}$ uniformly with respect to the 2-dimensional Lebesgue measure, that is, all the regions of the disk having the same area are equally likely to contain the points sampled. Normally we can use libraries that are able to generate random uniform/normal numbers, and if we are lucky, we can generate other distributions such as exponential, Poisson, binomial, etc. Although, we do not expect to be able to find more involved distributions such as the one of our problem, hence we need to figure how to use the available distributions to generate our random vectors. 

Test