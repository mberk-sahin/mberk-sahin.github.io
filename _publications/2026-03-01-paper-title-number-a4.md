---
title: "Adapting a CMR foundation model for A.I.-powered analysis of perfusion CMR: Enabling 12-fold reduction in manually labeled training dataset for automatic segmentation"
collection: publications
category: abstracts
permalink: /publication/2026-03-01-paper-title-number-a4
excerpt: 'We develop a foundation model-based approach for stress perfusion cardiac MRI segmentation by fine-tuning a cine CMR foundation model with limited labeled perfusion data. The method leverages prior knowledge of cardiac anatomy to improve myocardial segmentation and generalization across multi-center datasets.'
date: 2026-03-01
venue: 'International Conference'
presentation: 'Rapid-Fire Presentation'
slidesurl: 'https://drive.google.com/file/d/17WXRCXw8to5ne6YBk_j2uF8eaxtbpAzp/view?usp=sharing'
paperurl: 'https://echo.ismrm.org/abstracts/view/9434c721-7cc4-40de-8c0e-9eadd0bc5634'
videourl: 'https://drive.google.com/drive/folders/1QmPkTn1AoHJjJur3IR2CT-K-4kCaLUTa?dmr=1&ec=wgc-drive-%5Bmodule%5D-goto'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
#codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Accurate segmentation of stress first-pass perfusion (FPP) CMR is critical for myocardial blood flow analysis and ischemia detection. Automated artificial intelligence (AI) methods are essential for overcoming the inefficiencies and inconsistencies inherent in manual contouring of stress/rest FPP studies, but their development is limited by the scarcity of manually contoured perfusion datasets, which require substantial expertise, time and cost to generate. A recent study showed that a foundation model (FM) trained on large unlabeled cine CMR dataset can improve cine segmentation performance with limited labeled data. Building on this, we propose to fine-tune a cine FM using a limited manually contoured FPP cases to leverage its prior knowledge of cardiac structure with the aim of achieving accurate FPP myocardial segmentation and assessing its generalization across multi-center data.
