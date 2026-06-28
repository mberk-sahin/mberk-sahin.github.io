---
title: "Leveraging a CMR Foundation Model for Automated Classification of Stress Perfusion CMR Datasets: Initial Results Using the SCMR Registry"
collection: publications
category: abstracts
permalink: /publication/2026-03-01-paper-title-number-a3
excerpt: 'We develop a foundation model-based approach for automated classification of stress first-pass perfusion cardiac MRI. By fine-tuning a cine CMR foundation model on multi-center stress perfusion data, our method enables accurate classification of normal and abnormal cases while improving robustness across heterogeneous imaging centers.'
date: 2026-03-01
venue: 'Journal of Cardiovascular Magnetic Resonance'
presentation: 'Oral Presentation'
authors: 'Z. Li, <strong>M. B. Sahin</strong>, D. Yalcinkaya, A. M. Sohi, et al.'
#slidesurl: 'https://drive.google.com/file/d/1yWo2pFYGmrDkglH_8H5yfX2XTBliwtke/view?usp=sharing'
paperurl: 'https://www.journalofcmr.com/action/showPdf?pii=S1097-6647%2825%2900399-0'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
#codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Stress first-pass perfusion (FPP) CMR is an established tool for assessing myocardial ischemia and ischemic burden, with strong prognostic value in patients with suspected coronary artery disease. An automated approach for classification of stress FPP data using artificial intelligence techniques is lacking. Automated classification is especially challenging in heterogeneous multi-center datasets, where established convolutional neural network (CNN) or ResNet architectures may have limited performance. Recent work has shown that Foundation models (FMs) pre-trained on large unlabeled cine CMR datasets can effectively encode/capture cardiac structure and motion, thereby enhancing the performance of downstream tasks including classification. We hypothesize that adopting a FM trained using cine CMR data and fine-tuning it with stress FPP data enables accurate binary classification of normal vs. abnormal stress FPP cases, supporting rapid automated analysis. We report preliminary results for such a method by leveraging a multi-center dataset derived from the SCMR Registry.