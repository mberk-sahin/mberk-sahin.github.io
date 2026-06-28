---
title: "Foundation model for cardiac perfusion MRI enables 10-fold reduction in labeled dataset size for deep-learning analysis"
collection: publications
category: abstracts
permalink: /publication/2026-05-11-paper-title-number-a4
excerpt: 'We propose the largest-scale cardiac perfusion MRI foundation model trained on > 600,000 unlabeled multi-center images, achieving state-of-the-art performance for automatic segmentation with over 10-fold fewer manual labels, reducing reliance on manual annotation, and providing a reusable model for other tasks.'
date: 2026-05-11
venue: 'Proceedings of International Society for Magnetic Resonance Imaging (ISMRM)'
authors: '<strong>M. B. Sahin</strong>, Z. Li, K. Youssef, A. M. Sohi, et al.'
presentation: 'Oral Presentation'
slidesurl: 'https://drive.google.com/file/d/1ezVbIlm_FVS6XRSyn-BX3uiYJ7V3kgsf/view?usp=sharing'
paperurl: 'https://echo.ismrm.org/abstracts/view/9434c721-7cc4-40de-8c0e-9eadd0bc5634'
videourl: 'https://drive.google.com/file/d/1TNASuo5zYftx9WPfDACiZvt20Zn6p86D/view?usp=sharing'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
#codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Accurate myocardial segmentation in stress/rest first-pass perfusion (FPP) cardiac MRI is essential for robust quantitative analysis of myocardial blood flow and perfusion reserve, which are key imaging markers for diagnosis of ischemic heart disease. However, manual contour annotation is time-consuming, requires expert knowledge, and suffers from inter-observer variability, limiting applicability in both clinical and research settings. Although deep learning (DL)–based automated segmentation methods offer a promising solution, their performance is limited by the scarcity of manually labeled FPP datasets due to the substantial cost of expert labels. Recent advances in medical imaging foundation models (FM) with self-supervised learning have shown that large-scale pretraining on unlabeled data can improve downstream segmentation performance significantly. Building on this premise, here we introduce the largest-scale cardiac FPP foundation model to date, pretrained on 609,930 unlabeled stress/rest FPP images originating from 4 medical centers as part of the SCMR Global Registry. We tested the hypothesis that the developed FM enables order-of-magnitude reduction in the labeled dataset size needed for DL-based analysis of stress FPP images. 
