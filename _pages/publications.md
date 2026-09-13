---
layout: single
permalink: /publications/
title: "Publications"
author_profile: true
---
<style>
/* Links / badges for papers */
.paper-links {
  margin-top: 0.45em;
  margin-bottom: 0.7em;
}

.paper-btn {
  display: inline-block;
  border: 1px solid rgba(82, 173, 200, 0.65);
  border-radius: 4px;
  padding: 2px 9px;
  margin-right: 5px;
  font-size: 0.78em;
  color: #52adc8 !important;
  background: transparent;
  font-weight: 600;
  text-decoration: none !important;
  white-space: nowrap;
  vertical-align: middle;
}

.paper-btn:hover {
  background: rgba(82, 173, 200, 0.10);
  text-decoration: none !important;
}

/* Disabled button, e.g. SSRN not available yet */
.paper-btn.disabled {
  border-color: rgba(128,128,128,0.4);
  color: rgba(128,128,128,0.7) !important;
  cursor: default;
}

details {
  margin-top: 0.6em;
  margin-bottom: 1.5em;
}

details summary {
  cursor: pointer;
  color: #52adc8;
  font-weight: bold;
  font-size: 0.92em;
  list-style: none;
  user-select: none;
}

details summary::-webkit-details-marker {
  display: none;
}

details summary::after {
  content: ' ▶';
}

details[open] summary::after {
  content: ' ▼';
}

.abstract-box {
  margin-top: 0.6em;
  background: rgba(128,128,128,0.08);
  border-radius: 6px;
  padding: 1em 1.15em;
  font-size: 0.93em;
  line-height: 1.65;
}

/* Metadata below abstract */
.paper-meta {
  margin-top: 1em;
  padding-top: 0.75em;
  border-top: 1px solid rgba(128,128,128,0.20);
  font-size: 0.90em;
}

.meta-row {
  margin-top: 0.35em;
}

.meta-label {
  font-weight: 600;
  color: inherit;
}

.keyword {
  display: inline-block;
  padding: 1px 7px;
  margin: 2px 3px 2px 0;
  border-radius: 10px;
  background: rgba(82, 173, 200, 0.10);
  color: #4a94aa;
  font-size: 0.90em;
}
</style>

## Working Papers

---

**Estimation of a Hierarchical Normal-Inverse Gaussian Factor Model via the EM Algorithm**

with [L. Ballotta](https://scholar.google.com/citations?user=rmmGBqMAAAAJ&hl=en) and [G. Fusai](https://scholar.google.com/citations?user=j92IMd0AAAAJ&hl=it)

<div class="paper-links">
  <span class="paper-btn disabled">SSRN</span>
</div>

<details>
<summary>Abstract</summary>

<div class="abstract-box">

We propose a hierarchical Normal-Inverse Gaussian (NIG) factor model in which a latent mixing variable drives both the conditional mean and variance of each observation. This mean-variance mixing generalises existing latent-factor specifications — restricted to the variance component only — producing marginal distributions that jointly capture heavy tails, excess kurtosis, and asymmetry. We derive closed-form EM updates for all parameter blocks. Exploiting the NIG structure, the characteristic function of any portfolio return admits a closed form, from which the first four cumulants follow analytically — without estimating high-dimensional co-skewness and co-kurtosis tensors.

<div class="paper-meta">
  <div class="meta-row">
    <span class="meta-label">Keywords:</span>
    <span class="keyword">Factor model</span>
    <span class="keyword">Normal-Inverse Gaussian distribution</span>
    <span class="keyword">EM algorithm</span>
    <span class="keyword">Latent variables</span>
    <span class="keyword">Downside risk</span>
  </div>
</div>

</div>
</details>

---

**Implied Impermanent Loss for Concentrated Liquidity**

with [A. Papanicolaou](https://math.sciences.ncsu.edu/people/apapani/) and [L. Schoenleber](https://sites.google.com/view/lorenzo-schoenleber/menu)

<div class="paper-links">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7380038"
     class="paper-btn"
     target="_blank"
     rel="noopener noreferrer">SSRN</a>

  <a href="https://iilx.io/"
     class="paper-btn"
     target="_blank"
     rel="noopener noreferrer">IILX</a>
</div>

<details>
<summary>Abstract</summary>

<div class="abstract-box">

Providing liquidity on decentralized exchanges earns fees but exposes liquidity providers (LPs) to impermanent loss from price movements. With concentrated liquidity, LPs control this risk by choosing how narrowly to deploy capital around the price. Using option prices, we quantify the cost of liquidity provision by developing measures of implied impermanent loss for concentrated liquidity and define the associated impermanent loss risk premium. Empirically, higher expected impermanent loss widens liquidity ranges, while higher risk premia re-center and tighten liquidity around the spot price, highlighting opposing effects of risk and compensation.

<div class="paper-meta">
  <div class="meta-row">
    <span class="meta-label">Keywords:</span>
    <span class="keyword">Decentralized Exchanges</span>
    <span class="keyword">Decentralized Finance</span>
    <span class="keyword">Risk-Neutral Pricing</span>
    <span class="keyword">Risk Premium</span>
    <span class="keyword">Staking</span>
    <span class="keyword">Impermanent Loss</span>
    <span class="keyword">Derivatives</span>
  </div>

  <div class="meta-row">
    <span class="meta-label">JEL:</span>
    <span class="keyword">G10</span>
    <span class="keyword">G11</span>
    <span class="keyword">G13</span>
    <span class="keyword">G20</span>
  </div>
</div>

</div>
</details>

---

## Work in Progress

**Disciplined Learning: A GenAI Framework for Arbitrage-Free Term Structures** <span class="ssrn-btn">SSRN</span>  
with [L. Ballotta](https://scholar.google.com/citations?user=rmmGBqMAAAAJ&hl=en) and [G. Fusai](https://scholar.google.com/citations?user=j92IMd0AAAAJ&hl=it)

<!--
<details>
<summary>Abstract</summary>
<div class="abstract-box">
Generative artificial intelligence (GenAI) methods are increasingly used to produce synthetic financial market data, but purely statistical generators offer no guarantee that simulated price systems are free of arbitrage. This article proposes a hybrid framework that couples a no-arbitrage term structure model with a generative model in latent factor space. We provide an analytically tractable, invertible, and arbitrage-free mapping between a low-dimensional latent state and the term structure of discount bond prices. Historical market curves are inverted through this mapping to recover a time series of latent states, to which a Bayesian Machine Learning algorithm is fitted via the EM algorithm. The resulting pipeline decouples the statistical realism of the generated data from its no-arbitrage properties, combining the flexibility of GenAI with the structural guarantees of a no-arbitrage pricing model.
</div>
</details>
-->

---

**Technical Efficiency: A Regularization-Based Framework** <span class="ssrn-btn">SSRN</span>  
with [F. Centrone](https://upobook.uniupo.it/francesca.centrone) and [A. Goia](https://scholar.google.com/citations?user=qP_hjCcAAAAJ&hl=it)

<!--
<details>
<summary>Abstract</summary>
<div class="abstract-box">
This paper proposes a portfolio optimization framework that incorporates Data Envelopment Analysis (DEA) efficiency scores through an efficiency-based penalization term. The approach provides a flexible mechanism for integrating efficiency information into portfolio construction without directly modifying the underlying asset characteristics. By assigning higher penalties to relatively inefficient assets, the model encourages allocations toward more efficient investments while potentially generating sparse portfolios. Theoretical properties of the framework are examined to characterize the influence of DEA scores on portfolio selection. Illustrative examples highlight the applicability of the proposed approach and its implications for asset allocation.
</div>
</details>
-->