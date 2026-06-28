---
title: "RAMPAGE: RAndomized Mid-Point for debiAsed Gradient Extrapolation"
collection: publications
category: preprints
permalink: /publication/2026-03-23-paper-title-number-p1
excerpt: 'We develop RAMPAGE, an unbiased randomized extrapolation method for variational inequalities that eliminates the discretization bias of classical Extragradient methods. We further introduce a variance-reduced variant, RAMPAGE+, and establish convergence guarantees for root finding, constrained variational inequalities, and smooth convex-concave games, demonstrating improved theoretical and practical performance.'
date: 2026-03-23
venue: 'arXiv preprint arXiv:2603.22155'
paperurl: 'https://arxiv.org/pdf/2603.22155'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

A celebrated method for Variational Inequalities (VIs) is Extragradient (EG), which can be viewed as a standard discrete-time integration scheme. With this view in mind, in this paper we show that EG may suffer from discretization bias when applied to non-linear vector fields, conservative or otherwise. To resolve this discretization shortcoming, we introduce RAndomized Mid-Point for debiAsed Gradient Extrapolation (RAMPAGE) and its variance-reduced counterpart, RAMPAGE+, which leverages antithetic sampling. In contrast with EG, both methods are unbiased. Furthermore, leveraging negative correlation, RAMPAGE+ acts as an unbiased, geometric path-integrator that completely removes internal first-order terms from the variance, provably improving upon RAMPAGE. We further demonstrate that both methods enjoy provable $$\mathcal{O}(1/k)$$ convergence guarantees for a range of problems including root finding under co-coercive, co-hypomonotone, and generalized Lipschitzness regimes. Furthermore, we introduce symmetrically scaled variants to extend our results to constrained VIs. Finally, we provide convergence guarantees of both methods for stochastic and deterministic smooth convex-concave games. Somewhat interestingly, despite being a randomized method, RAMPAGE+ attains purely deterministic bounds for a number of the studied settings.
