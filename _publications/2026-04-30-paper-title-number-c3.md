---
title: "Zeroth-Order Non-Log-Concave Sampling with Variance Reduction and Applications to Inverse Problems"
collection: publications
category: conferences
permalink: /publication/2026-04-30-paper-title-number-c3
excerpt: 'Developed the first provably convergent zeroth-order Langevin sampling algorithm for non-log-concave distributions, enabling efficient Bayesian inference when gradients are unavailable. Extended the framework to diffusion model–based posterior sampling for black-box inverse problems, achieving strong performance on MRI reconstruction, black hole imaging, and other scientific inverse problems.'
date: 2026-04-30
venue: 'Proceedings of the Forty-third International Conference on Machine Learning'
presentation: 'Poster Presentation'
slidesurl: 'https://icml.cc/media/icml-2026/Slides/63673.pdf'
paperurl: 'https://openreview.net/pdf?id=UlFOINq6SY'
posterurl: 'https://icml.cc/media/PosterPDFs/ICML%202026/63673.png?t=1782359467.350254'
codeurl: 'https://github.com/mberk-sahin/zo-posterior-sampling'
videourl: 'https://icml.cc/virtual/2026/poster/63673'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

In this paper, we study a communication-constrained multi-agent zeroth-order online optimization problem within the federated learning (FL) setting with application to target tracking where multiple agents have access only to the knowledge of their current distances to their respective targets. The agents additionally aim to avoid collisions by maintaining a minimum safe distance from their peers. Leveraging FL, the coordination among the agents as well as the dissemination of the collision-prevention information to the agents is handled by a central server. To cope with the inherent communication limitations of the agents, we further leverage a feedback-based compression scheme in the agent-to-server communications where we compress/quantize a judiciously designed zeroth-order gradient estimator. We provide a theoretical analysis of the resulting algorithm. Our result features requiring less restrictive assumptions compared to the prior work and carefully characterizing the impact of such relaxations on the convergence error. Finally, we numerically analyze the performance of the proposed algorithmic solution with regard to the tracking errors and collisions between agents.