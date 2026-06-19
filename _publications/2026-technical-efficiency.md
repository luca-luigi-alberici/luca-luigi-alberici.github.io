---
title: "Technical Efficiency: A Regularization-Based Framework"
collection: publications
category: manuscripts
permalink: /publication/2026-technical-efficiency
excerpt: 'A portfolio optimization framework incorporating Data Envelopment Analysis efficiency scores via weighted Lasso regularization.'
date: 2026-01-03
citation: 'L.L. Alberici, F. Centrone, A. Goia (2026). <i>Technical Efficiency: A Regularization-Based Framework</i>.'
---

**Abstract.** This paper proposes a portfolio optimization framework that incorporates Data Envelopment Analysis efficiency scores into asset allocation through a weighted Lasso regularization scheme. The approach combines traditional mean-variance considerations with an efficiency-based selection mechanism, allowing DEA information to influence portfolio composition without modifying expected returns or risk estimates directly. Assets with lower efficiency scores face higher regularization costs, encouraging the optimization procedure to favor relatively efficient investments and potentially generate sparse portfolios. The resulting optimization problem remains convex and can be reformulated as a quadratic programming problem through a standard epigraph transformation, making it readily solvable with existing optimization software. Theoretical properties of the model are derived using subgradient optimality conditions, highlighting the role of DEA scores in asset selection. Analytical toy examples and MATLAB implementations are provided to illustrate the methodology and demonstrate how efficiency scores affect portfolio allocations under different constraint structures.

*Joint work with F. Centrone and A. Goia.*
