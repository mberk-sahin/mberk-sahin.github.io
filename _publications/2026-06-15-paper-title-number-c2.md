---
title: "Variance Reduction for Non-Log-Concave Sampling with Applications to Inverse Problems"
collection: publications
category: conferences
permalink: /publication/2026-06-15-paper-title-number-c2
excerpt: 'Developed the first variance-reduced Langevin sampling algorithms with non-asymptotic convergence guarantees for non-log-concave distributions. Applied the framework to diffusion model–based Bayesian inference, achieving higher-quality posterior sampling and improved MRI and CT reconstruction under the same computational budget.'
date: 2026-06-15
venue: 'Proceedings of the Forty-third Conference on Uncertainty in Artificial Intelligence'
presentation: 'Poster Presentation'
#slidesurl: 'https://drive.google.com/file/d/1whwTwWkJf2FcBn4iWku7baWxDBevQf86/view?usp=sharing'
paperurl: 'https://arxiv.org/pdf/2606.16257'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
codeurl: 'https://github.com/mberk-sahin/variance-reduced-sampling'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Sampling from high-dimensional, non-log-concave distributions with unnormalized densities is a fundamental challenge in machine learning, particularly when the exact gradient of the potential is unavailable and must be approximated via stochastic gradients that exhibit high variance under a fixed budget of gradient computations per iteration. Although variance reduction techniques such as SGD with momentum, STORM, and PAGE have demonstrated improved convergence properties in non-convex optimization, their implications for sampling from non-log-concave distributions remain largely unexplored. In this work, we develop the first unified analysis of these estimators for sampling from non-log-concave distributions. We establish improved non-asymptotic convergence rates in ε-relative Fisher information and, under a Poincaré inequality assumption, in squared total variation distance, and further prove weak convergence to the target distribution. We extend our analysis to solving inverse problems with score-based generative priors. We empirically validate our theory and demonstrate that, under a fixed gradient computations per iteration, variance-reduction techniques consistently improve sample quality in two standard imaging applications.