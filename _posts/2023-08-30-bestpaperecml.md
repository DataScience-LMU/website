---
title: Lisa and Gregor won the best paper award at ECML-PKDD!!
layout: post
post-image: "https://ecmlpkdd.org/uploads/Main/torinologo.jpg"
description: Gregor and Lisa's paper *Towards Efficient MCMC Sampling in Bayesian Neural Networks by Exploiting Symmetry* won the best paper award at ECML-PKDD 2023!!
tags:
- lisa
- gregor
- ecml
- best
---

Among 196 accepted papers, Gregor and Lisa's paper *Towards Efficient MCMC Sampling in Bayesian Neural Networks by Exploiting Symmetry* was selected to be the best paper at ECML-PKDD 2023 in the Research Track!! They will present our work in the award session in Turin on Sept. 19.

### Abstract

Bayesian inference in deep neural networks is challenging due to the high-dimensional, strongly multi-modal parameter posterior density landscape. Markov chain Monte Carlo approaches asymptotically recover the true posterior but are considered prohibitively expensive for large modern architectures. Local methods, which have emerged as a popular alternative, focus on specific parameter regions that can be approximated by functions with tractable integrals. While these often yield satisfactory empirical results, they fail, by definition, to account for the multi-modality of the parameter posterior. In this work, we argue that the dilemma between exact-but-unaffordable and cheap-but-inexact approaches can be mitigated by exploiting symmetries in the posterior landscape. Such symmetries, induced by neuron interchangeability and certain activation functions, manifest in different parameter values leading to the same functional output value. We show theoretically that the posterior predictive density in Bayesian neural networks can be restricted to a symmetry-free parameter reference set. By further deriving an upper bound on the number of Monte Carlo chains required to capture the functional diversity, we propose a straightforward approach for feasible Bayesian inference. Our experiments suggest that efficient sampling is indeed possible, opening up a promising path to accurate uncertainty quantification in deep learning.

For more details, see our [ArXiv](https://arxiv.org/abs/2304.02902) preprint!
