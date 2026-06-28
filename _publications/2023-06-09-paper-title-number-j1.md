---
title: "Communication-Efficient Zeroth-Order Distributed Online Optimization: Algorithm, Theory, and Applications"
collection: publications
category: journals
permalink: /publication/2023-06-09-paper-title-number-j1
excerpt: 'We develop a communication-efficient federated algorithm for distributed zeroth-order online optimization, motivated by multi-agent target tracking. Using error-feedback compression, the method achieves non-asymptotic convergence guarantees under significantly weaker assumptions than prior work, with convergence rates that are robust to compression.'
date: 2023-06-09
venue: 'IEEE Access'
#presentation: 'Poster Presentation'
#slidesurl: 'https://drive.google.com/file/d/1whwTwWkJf2FcBn4iWku7baWxDBevQf86/view?usp=sharing'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10147304'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
codeurl: 'https://github.com/mberk-sahin/FED-EF-ZO-SGD'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This paper focuses on a multi-agent zeroth-order online optimization problem in a federated learning setting for target tracking. The agents only sense their current distances to their targets and aim to maintain a minimum safe distance from each other to prevent collisions. The coordination among the agents and dissemination of collision-prevention information is managed by a central server using the federated learning paradigm. The proposed formulation leads to an instance of distributed online nonconvex optimization problem that is solved via a group of communication-constrained agents. To deal with the communication limitations of the agents, an error feedback-based compression scheme is utilized for agent-to-server communication. The proposed algorithm is analyzed theoretically for the general class of distributed online nonconvex optimization problems. We provide non-asymptotic convergence rates that show the dominant term is independent of the characteristics of the compression scheme. Our theoretical results feature a new approach that employs significantly more relaxed assumptions in comparison to standard literature. The performance of the proposed solution is further analyzed numerically in terms of tracking errors and collisions between agents in two relevant applications.