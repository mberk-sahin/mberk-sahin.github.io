---
title: "Communication-Constrained Exchange of Zeroth-Order Information with Application to Collaborative Target Tracking"
collection: publications
category: conferences
permalink: /publication/2023-06-04-paper-title-number-1
excerpt: 'We develop a communication-efficient federated learning algorithm for multi-agent zeroth-order online optimization, enabling collaborative target tracking with collision avoidance under limited communication. We establish theoretical convergence guarantees under weaker assumptions than prior work and validate the approach through numerical experiments.'
date: 2023-06-04
venue: 'ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
presentation: 'Poster Presentation'
#slidesurl: 'https://drive.google.com/file/d/1whwTwWkJf2FcBn4iWku7baWxDBevQf86/view?usp=sharing'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10096148'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
codeurl: 'https://github.com/mberk-sahin/EF_ZO_SGD'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

In this paper, we study a communication-constrained multi-agent zeroth-order online optimization problem within the federated learning (FL) setting with application to target tracking where multiple agents have access only to the knowledge of their current distances to their respective targets. The agents additionally aim to avoid collisions by maintaining a minimum safe distance from their peers. Leveraging FL, the coordination among the agents as well as the dissemination of the collision-prevention information to the agents is handled by a central server. To cope with the inherent communication limitations of the agents, we further leverage a feedback-based compression scheme in the agent-to-server communications where we compress/quantize a judiciously designed zeroth-order gradient estimator. We provide a theoretical analysis of the resulting algorithm. Our result features requiring less restrictive assumptions compared to the prior work and carefully characterizing the impact of such relaxations on the convergence error. Finally, we numerically analyze the performance of the proposed algorithmic solution with regard to the tracking errors and collisions between agents.