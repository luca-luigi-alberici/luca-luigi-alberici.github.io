---
title: "Disciplined Learning: A GenAI Framework for Arbitrage-Free Term Structures"
collection: publications
category: manuscripts
permalink: /publication/2026-disciplined-learning
excerpt: 'A hybrid framework coupling a no-arbitrage term structure model with a generative model in latent factor space.'
date: 2026-01-01
citation: 'L.L. Alberici, L. Ballotta, G. Fusai (2026). <i>Disciplined Learning: A GenAI Framework for Arbitrage-Free Term Structures</i>.'
---

**Abstract.** Generative artificial intelligence (GenAI) methods are increasingly used to produce synthetic financial market data, but purely statistical generators offer no guarantee that simulated price systems are free of arbitrage. This article proposes a hybrid framework that couples a no-arbitrage term structure model with a generative model in latent factor space. We provide an analytically tractable, invertible, and arbitrage-free mapping between a low-dimensional latent state and the term structure of discount bond prices. Historical market curves are inverted through this mapping to recover a time series of latent states, to which a Bayesian Machine Learning algorithm is fitted via the EM algorithm. The resulting pipeline decouples the statistical realism of the generated data from its no-arbitrage properties, combining the flexibility of GenAI with the structural guarantees of a no-arbitrage pricing model.

*Joint work with L. Ballotta and G. Fusai.*
