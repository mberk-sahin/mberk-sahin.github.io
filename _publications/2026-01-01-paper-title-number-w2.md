---
title: "Multimodal Abnormality Classifier Using Anatomy-Guided Connection for 3D Medical Images"
collection: publications
category: workshops
permalink: /publication/2026-01-01-paper-title-number-w2
excerpt: 'This paper introduces an anatomy-guided framework for weakly supervised abnormality classification in 3D medical images using radiology reports. By combining anatomical attention maps generated from segmentation and language models with a Mamba-based 3D classifier, the proposed method significantly improves classification accuracy and F1 score over existing approaches.'
date: 2026-01-01
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops'
presentation: 'Oral Presentation' #

authors: '<strong>M. B. Sahin</strong>, Y. Shinagawa, H. Z. Yerebakan, A. Hashemi, et al.'
slidesurl: 'https://drive.google.com/file/d/1Ze9yWSQH6BU9uC7GJYFrO8pG9gAArsFi/view?usp=sharing'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/papers/Sahin_Multimodal_Abnormality_Classifier_Using_Anatomy-Guided_Connection_for_3D_Medical_Images_CVPRW_2026_paper.pdf'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
#codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Creating large-scale annotated datasets for abnormality classification in medical images is a labor-intensive and costly endeavor. To alleviate the scarcity of annotated data, weak supervision from readily available resources, such as radiology reports, can provide an effective alternative for training abnormality classification models. However, most existing methods either rely on inference of feature alignment across data modalities or focus on 2D medical images, overlooking the complex spatial relationships in anatomies such as the brain, which limits performance. To address such challenges, we introduce Anatomy-Guided Abnormality Classifier (AGAC), which integrates precise anatomical guidance for 3D medical image analysis. Our framework has two key components. First, we present a novel method for generating attention maps using anatomical descriptions of abnormalities, processed through the SynthSeg segmentation network and SBERT language model. Second, we introduce an efficient Mamba-based 3D medical image classifier, enhanced with anatomy-guided connections that leverage the generated attention maps. Together, these advancements significantly improve benchmark performance in both accuracy and F1 score.
