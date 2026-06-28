---
title: "Quantifying the Impact of Dataset Shifts in Deep Learning-based Dynamic MRI Reconstruction: Need for Spatially Localized Performance Metrics"
collection: publications
category: abstracts
permalink: /publication/2026-03-01-paper-title-number-a2
excerpt: 'We introduce a localized normalized root-mean-square error (NRMSE) metric for evaluating deep learning-based cardiac MRI reconstruction. Unlike conventional global metrics, the proposed metric focuses on the cardiac region, providing a more sensitive assessment of reconstruction quality and model generalization across variations in scanners, imaging sites, field strengths, and contrast dose protocols.'
date: 2026-03-01
venue: 'Journal of Cardiovascular Magnetic Resonance'
presentation: 'Oral Presentation'
slidesurl: 'https://drive.google.com/file/d/1yWo2pFYGmrDkglH_8H5yfX2XTBliwtke/view?usp=sharing'
paperurl: 'https://www.journalofcmr.com/action/showPdf?pii=S1097-6647%2825%2900455-7'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
#codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Deep learning (DL)-based methods have advanced dynamic cardiac MRI reconstruction, enabling higher acceleration while preserving spatiotemporal fidelity. Clinical translation, however, remains limited by dataset shifts arising from variations in scanner hardware, imaging site, magnetic field strength, and contrast dose protocols. Conventional error metrics compute error globally, spreading it across the entire field-of-view and thus failing to emphasize reconstruction errors in the region-of-interest (e.g., the heart). As a result, they provide an incomplete assessment of model generalization across variations in datasets. To address this, we proposed a localized normalized root-mean-square error (NRMSE) metric restricted to the cardiac region and demonstrated through rigorous experiments that it enables more accurate detection of performance degradations and a clearer assessment of model generalization across such variations compared with global NRMSE.