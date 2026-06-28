---
title: "Adapting a CMR foundation model for A.I.-powered analysis of perfusion CMR: Enabling 12-fold reduction in manually labeled training dataset for automatic segmentation"
collection: publications
category: abstracts
permalink: /publication/2026-03-01-paper-title-number-a5
excerpt: 'We fine-tune a vision foundation model pretrained on cine cardiac MRI for myocardial segmentation in stress first-pass perfusion (FPP) CMR. By leveraging prior knowledge of cardiac anatomy, the proposed approach achieves accurate segmentation with limited labeled FPP data and demonstrates strong generalization across multi-center datasets.'
date: 2026-03-01
venue: 'Journal of Cardiovascular Magnetic Resonance'
authors: '<strong>M. B. Sahin</strong>, Z. Li, K. Youssef, A. M. Sohi, et al.'
presentation: 'Rapid-Fire Presentation'
slidesurl: 'https://drive.google.com/file/d/17WXRCXw8to5ne6YBk_j2uF8eaxtbpAzp/view?usp=sharing'
paperurl: 'https://www.journalofcmr.com/action/showPdf?pii=S1097-6647%2825%2900807-5'
#videourl: 'https://drive.google.com/file/d/1TNASuo5zYftx9WPfDACiZvt20Zn6p86D/view?usp=sharing'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
#codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Accurate segmentation of stress first-pass perfusion (FPP) CMR is critical for myocardial blood flow analysis and ischemia detection. Automated artificial intelligence (AI) methods are essential for overcoming the inefficiencies and inconsistencies inherent in manual contouring of stress/rest FPP studies [1], but their development is limited by the scarcity of manually contoured perfusion datasets, which require substantial expertise, time and cost to generate [2]. A recent study showed that a foundation model (FM) trained on large unlabeled cine CMR dataset can improve cine segmentation performance with limited labeled data [3]. Building on this, we propose to fine-tune a cine FM using a limited manually contoured FPP cases to leverage its prior knowledge of cardiac structure with the aim of achieving accurate FPP myocardial segmentation and assessing its generalization across multi-center data.
