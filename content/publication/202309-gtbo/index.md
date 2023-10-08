---
title: "High-Dimensional Bayesian Optimization with Group Testing"
date: 2023-09-30
publishDate: 2023-09-30
authors: ["Erik Hellsten*", "**Carl Hvarfner***", "Leonard Papenmeier*", "Luigi Nardi"]
publication_types: ["1"]
abstract:  "Bayesian optimization is an effective method for optimizing expensive-to-evaluate black-box functions. High-dimensional problems are particularly challenging as the surrogate model of the objective suffers from the curse of dimensionality, which makes accurate modeling difficult. We propose a group testing approach to identify active variables to facilitate efficient optimization in these domains. The proposed algorithm, Group Testing Bayesian Optimization (GTBO), first runs a testing phase where groups of variables are systematically selected and tested on whether they influence the objective. To that end, we extend the well-established theory of group testing to functions of continuous ranges. In the second phase, GTBO guides optimization by placing more importance on the active dimensions. By exploiting the axis-aligned subspace assumption, GTBO is competitive against state-of-the-art methods on several synthetic and real-world high-dimensional optimization tasks. Furthermore, GTBO aids in the discovery of active parameters in applications, thereby enhancing practitioners' understanding of the problem at hand."
featured: true
publication: "Preprint, 2023 (under review)."
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://arxiv.org/abs/2310.03515v1'
---