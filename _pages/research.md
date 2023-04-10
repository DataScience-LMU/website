---
title: "Data Science @ LMU Munich - Research"
layout: textlay
excerpt: "Data Science @ LMU Munich -- Research"
sitemap: false
permalink: /research/
---

# Research

Our overarching goal is to combine ideas from statistics and machine learning to further develop methods in statistical modeling, probabilistic machine learning and uncertainty quantification in deep learning. Often these advances are motivated by real-world challenges and we work closely with domain experts from other fields to solve the world's most challenging tasks.

Here are some themes that we currently work on:

**Semi-structured Neural Networks** Semi-structured neural networks (SSNs) jointly learn interpretable structured effects of tabular data and additional unstructured effects modeled through a (deep) neural network. These two parts are embedded and trained together in one unifying network architecture. The structured part allows for an interpretation as in common statistical regression models whereas the remaining variation in the data can be explained by the more powerful (unstructured) neural network part. SSNs also open up new ways of modeling multi-modal data, e.g., datasets with both tabular and image information, while preserving statistical model characteristics typically relied on in various fields such as medical research or psychology. SSNs are implemented in a generic software framework called deepregression that leverages the full modularity of current deep learning platforms while also enabling many different statistical model specifications. Next to semi-structured applications, classic statistical models themselves can also benefit from being embedded and trained in a neural network, making them more flexible and scalable. More [here](https://www.tandfonline.com/doi/abs/10.1080/00031305.2022.2164054).

**Neural Structured Additive Learning** Neural structured learning describes the learning of structured models in neural networks. This field thus comprises semi-structured networks, but does not necessarily incorporate unstructured model parts. One example are highly scalable additive models that are embedded in neural networks. By training these models in batches and using other computational tricks such as array computations and factorizations, the framing as and training in a neural network allows models to be scaled to many observations, features and model effects. Our software framework [deepregression](https://github.com/neural-structured-additive-learning/deepregression) implements this idea and allows fast prototyping and many extensions. 
![]({{ site.url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}

**Uncertainty Quantification in Bayesian Neural Networks** The lack of infinitely many observations makes uncertainty quantification an important problem deep learning. However, the parameter posterior for Bayesian neural networks (BNNs) is typically highly multi-modal and rarely available in closed form. The classical Markov chain Monte Carlo (MCMC) approach asymptotically recovers the true posterior but is considered prohibitively expensive for BNNs, as the large number of posterior modes prevents a reasonable mixing of chains. Popular approximation techniques, such as Laplace approximation focus on local regions of the posterior landscape. While these methods are faster than traditional MCMC and perform well in many applications, they systematically omit regions of the parameter space that might be decisive for meaningful uncertainty quantification. We propose a [solution in this paper](https://arxiv.org/abs/2304.02902).

**Generative Models in Medical Imaging** Generative models allow for the creation of highly realistic artificial samples, opening up promising applications in medical imaging. In our work, we propose various generative models for high resolution medical images. We further aim to make generative models more accessible to researchers so that these can be applied to actual patient images. More [here](https://arxiv.org/pdf/2303.11224.pdf) and [here](https://link.springer.com/chapter/10.1007/978-3-031-25046-0_3).

#### ... and more.
