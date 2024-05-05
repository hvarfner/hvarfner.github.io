---
title: "πBO: Augmenting Acquisition Functions with User Beliefs for Bayesian Optimization"
date: 2022-04-11
publishDate: 2022-04-11
authors: ["**Carl Hvarfner**", "Danny Stoll", "Artur Souza", "Marius Lindauer", "Frank Hutter", "Luigi Nardi"]
publication_types: ["1"]
abstract: "Bayesian optimization (BO) has become an established framework and popular tool for hyperparameter optimization (HPO) of machine learning (ML) algorithms. While known for its sample-efficiency, vanilla BO can not utilize readily available prior beliefs the practitioner has on the potential location of the optimum. Thus, BO disregards a valuable source of information, reducing its appeal to ML practitioners. To address this issue, we propose πBO, an acquisition function generalization which incorporates prior beliefs about the location of the optimum in the form of a probability distribution, provided by the user. In contrast to previous approaches, πBO is conceptually simple and can easily be integrated with existing libraries and many acquisition functions. We provide regret bounds when πBO is applied to the common Expected Improvement acquisition function and prove convergence at regular rates independently of the prior. Further, our experiments show that πBO outperforms competing approaches across a wide suite of benchmarks and prior characteristics. We also demonstrate that πBO improves on the state-of-the- art performance for a popular deep learning task, with a 12.5× time-to-accuracy speedup over prominent BO approaches."
featured: true
publication: "International Conference on Learning Representations, 2022."
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://arxiv.org/abs/2204.11051'
---