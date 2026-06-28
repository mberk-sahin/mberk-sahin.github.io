---
title: "Retrospective Phase-map Synthesis for CMR Datasets FBom Magnitude-only DICOM Images Enabled by A.I. Generative Models to Create Large Training Datasets for Deep Learning-based Image Reconstruction"
collection: publications
category: abstracts
permalink: /publication/2024-01-01-paper-title-number-a1
excerpt: 'We propose a score-based diffusion model that synthesizes realistic cardiac MRI phase maps from magnitude-only images, enabling reconstruction of raw k-space data from routinely archived clinical scans. The generated phase maps are further validated by training a deep learning reconstruction model.'
date: 2024-01-01
venue: 'Journal of Cardiovascular Magnetic Resonance'
presentation: 'Rapid-Fire Presentation' # 🔥 Rapid-Fire Presentation
slidesurl: 'https://drive.google.com/file/d/1whwTwWkJf2FcBn4iWku7baWxDBevQf86/view?usp=sharing'
paperurl: 'https://drive.google.com/file/d/1Bz-AC3YPPqNh3eDSyrtHwWr02E6V1DZD/view?usp=sharing'
#bibtexurl: 'https://api.crossref.org/works/10.1016%2Fj.jocmr.2024.100987/transform/application/x-bibtex'
codeurl: 'https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Developing deep learning (DL)-based image reconstruction techniques requires large and diverse raw k-space datasets. In the majority of clinical CMR protocols, magnitude-only DICOMs are the only component that is saved and archived to enable retrospective access, e.g., for training generalizable DL-based models to enable improved image reconstruction. At the same time, large multi-vendor multi-center DICOM datasets are being built, e.g., the SCMR Registry has surpassed 150,000 patient studies with over 300 Million images. Recent work has shown the feasibility of using generative A.I. approaches such as generative adversarial networks (GANs) for synthesis of brain MRI phase maps to create raw k-space data. Emerging diffusion models also hold promise in generative tasks with their impressive performance and superior training stability vs. GANs. Here we propose a novel score-based diffusion model (SBDM) approach for generating realistic CMR phase maps from magnitude-only images. We further evaluate the quality of the synthesized phases by using them to train a DL-based reconstruction algorithm.