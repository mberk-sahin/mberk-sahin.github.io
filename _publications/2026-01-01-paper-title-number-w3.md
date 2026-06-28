---
title: "AGA3DNet: Anatomy-Guided Gaussian Priors with Multi-view xLSTM for 3D Brain MRI Subtype Classification"
collection: publications
category: workshops
permalink: /publication/2026-01-01-paper-title-number-w3
excerpt: 'We present AGA3DNet, a report-grounded framework for 3D brain MRI subtype classification that integrates anatomical phrases from radiology reports as soft spatial priors. By combining anatomy-guided attention with a lightweight 3D CNN and multi-view xLSTM aggregation, AGA3DNet improves classification performance over strong 3D baselines while providing interpretable, anatomy-aware localization without requiring voxel-level annotations.'
date: 2026-01-01
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops'
presentation: 'Poster Presentation'
authors: 'P. Duan, X. Guo, S. Farhand, <strong>M. B. Sahin</strong>, et al.'
#slidesurl: 'https://drive.google.com/file/d/1Ze9yWSQH6BU9uC7GJYFrO8pG9gAArsFi/view?usp=sharing'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2026W/CV4Clinic2026/papers/Duan_AGA3DNet_Anatomy-Guided_Gaussian_Priors_with_Multi-view_xLSTM_for_3D_Brain_CVPRW_2026_paper.pdf'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
#codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Creating large-scale annotated datasets for abnormality classification in medical images is a labor-intensive and costly endeavor. To alleviate the scarcity of annotated data, weak supervision from readily available resources, such as radiology reports, can provide an effective alternative for training abnormality classification models. However, most existing methods either rely on inference of feature alignment across data modalities or focus on 2D medical images, overlooking the complex spatial relationships in anatomies such as the brain, which limits performance. To address such challenges, we introduce Anatomy-Guided Abnormality Classifier (AGAC), which integrates precise anatomical guidance for 3D medical image analysis. Our framework has two key components. First, we present a novel method for generating attention maps using anatomical descriptions of abnormalities, processed through the SynthSeg segmentation network and SBERT language model. Second, we introduce an efficient Mamba-based 3D medical image classifier, enhanced with anatomy-guided connections that leverage the generated attention maps. Together, these advancements significantly improve benchmark performance in both accuracy and F1 score.
