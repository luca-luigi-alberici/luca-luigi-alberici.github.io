---
layout: single
permalink: /publications/
title: "Working Papers"
author_profile: true
---

<style>
.pub-entry {
  margin-bottom: 2.2em;
  padding-bottom: 1.8em;
  border-bottom: 1px solid rgba(128,128,128,0.25);
}
.pub-entry:last-child { border-bottom: none; }
.pub-title-row {
  display: flex;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 0.5em;
}
.pub-title {
  font-size: 1.1em;
  font-weight: bold;
}
.ssrn-btn {
  display: inline-block;
  border: 1px solid rgba(128,128,128,0.5);
  border-radius: 4px;
  padding: 1px 8px;
  font-size: 0.78em;
  color: rgba(128,128,128,0.8);
  background: transparent;
  cursor: default;
  font-weight: normal;
  white-space: nowrap;
}
.pub-authors {
  opacity: 0.65;
  font-size: 0.93em;
  margin-top: 0.25em;
}
details { margin-top: 0.6em; }
details summary {
  cursor: pointer;
  color: #1a73e8;
  font-weight: bold;
  font-size: 0.92em;
  list-style: none;
  user-select: none;
}
details summary::-webkit-details-marker { display: none; }
.abstract-box {
  margin-top: 0.6em;
  background: rgba(128,128,128,0.1);
  border-radius: 6px;
  padding: 0.9em 1.1em;
  font-size: 0.93em;
  line-height: 1.65;
}
</style>

<div class="pub-entry">
  <div class="pub-title-row">
    <span class="pub-title">Estimation of a Hierarchical Normal-Inverse Gaussian Factor Model via the EM Algorithm</span>
    <span class="ssrn-btn">SSRN</span>
  </div>
  <div class="pub-authors">with L. Ballotta and G. Fusai</div>
  <details>
    <summary>Abstract ▸</summary>
    <div class="abstract-box">
      We propose a hierarchical Normal-Inverse Gaussian (NIG) factor model in which a latent mixing variable drives both the conditional mean and variance of each observation. This mean-variance mixing generalises existing latent-factor specifications — restricted to the variance component only — producing marginal distributions that jointly capture heavy tails, excess kurtosis, and asymmetry. We derive closed-form EM updates for all parameter blocks. Exploiting the NIG structure, the characteristic function of any portfolio return admits a closed form, from which the first four cumulants follow analytically — without estimating high-dimensional co-skewness and co-kurtosis tensors.
    </div>
  </details>
</div>

<div class="pub-entry">
  <div class="pub-title-row">
    <span class="pub-title">Implied Impermanent Loss for Concentrated Liquidity</span>
    <span class="ssrn-btn">SSRN</span>
  </div>
  <div class="pub-authors">with A. Papanicolaou and L. Schoenleber</div>
  <details>
    <summary>Abstract ▸</summary>
    <div class="abstract-box">
      Providing liquidity on decentralized exchanges earns fees but exposes liquidity providers (LPs) to impermanent loss from price movements. With concentrated liquidity, LPs control this risk by choosing how narrowly to deploy capital around the price. Using option prices, we quantify the cost of liquidity provision by developing measures of implied impermanent loss for concentrated liquidity and define the associated impermanent loss risk premium. Empirically, higher expected impermanent loss widens liquidity ranges, while higher risk premia re-center liquidity around the spot price, highlighting opposing effects of risk and compensation.
    </div>
  </details>
</div>

<div class="pub-entry">
  <div class="pub-title-row">
    <span class="pub-title">Disciplined Learning: A GenAI Framework for Arbitrage-Free Term Structures</span>
    <span class="ssrn-btn">SSRN</span>
  </div>
  <div class="pub-authors">with L. Ballotta and G. Fusai</div>
  <details>
    <summary>Abstract ▸</summary>
    <div class="abstract-box">
      Generative artificial intelligence (GenAI) methods are increasingly used to produce synthetic financial market data, but purely statistical generators offer no guarantee that simulated price systems are free of arbitrage. This article proposes a hybrid framework that couples a no-arbitrage term structure model with a generative model in latent factor space. We provide an analytically tractable, invertible, and arbitrage-free mapping between a low-dimensional latent state and the term structure of discount bond prices. Historical market curves are inverted through this mapping to recover a time series of latent states, to which a Bayesian Machine Learning algorithm is fitted via the EM algorithm. The resulting pipeline decouples the statistical realism of the generated data from its no-arbitrage properties, combining the flexibility of GenAI with the structural guarantees of a no-arbitrage pricing model.
    </div>
  </details>
</div>

<div class="pub-entry">
  <div class="pub-title-row">
    <span class="pub-title">Technical Efficiency: A Regularization-Based Framework</span>
    <span class="ssrn-btn">SSRN</span>
  </div>
  <div class="pub-authors">with F. Centrone and A. Goia</div>
  <details>
    <summary>Abstract ▸</summary>
    <div class="abstract-box">
      This paper proposes a portfolio optimization framework that incorporates Data Envelopment Analysis efficiency scores into asset allocation through a weighted Lasso regularization scheme. The approach combines traditional mean-variance considerations with an efficiency-based selection mechanism, allowing DEA information to influence portfolio composition without modifying expected returns or risk estimates directly. Assets with lower efficiency scores face higher regularization costs, encouraging the optimization procedure to favor relatively efficient investments and potentially generate sparse portfolios. The resulting optimization problem remains convex and can be reformulated as a quadratic programming problem through a standard epigraph transformation, making it readily solvable with existing optimization software. Theoretical properties of the model are derived using subgradient optimality conditions, highlighting the role of DEA scores in asset selection. Analytical toy examples and MATLAB implementations are provided to illustrate the methodology and demonstrate how efficiency scores affect portfolio allocations under different constraint structures.
    </div>
  </details>
</div>
