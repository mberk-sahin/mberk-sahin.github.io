---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


[PDF Version](http://mberk-sahin.github.io/files/cv.pdf)

Education
======
* **Doctor of Philosophy** - Electrical and Computer Engineering **(4.00/4.00)**, Aug 2022 - July 2027 (Expected)  
Purdue University - The Elmore Family School of Electrical and Computer Engineering - Indiana, US.  
**Advisor**: [Prof. Abolfazl Hashemi](https://abolfazlh.github.io) and [Prof. Behzad Sharif](https://medicine.iu.edu/research-centers/cardiovascular/research/microcirculation)

* **Master of Science** - Electrical and Computer Engineering **(4.00/4.00)**, Aug 2022 - May 2026          
Purdue University - The Elmore Family School of Electrical and Computer Engineering - Indiana, US.       
**Advisor**: [Prof. Abolfazl Hashemi](https://abolfazlh.github.io) and [Prof. Behzad Sharif](https://medicine.iu.edu/research-centers/cardiovascular/research/microcirculation)

* **Bachelor of Science** - Electrical and Electronics Engineering **(3.67/4.00)**, Aug 2018 - July 2022 
Bilkent University - Faculty of Engineering - Ankara, Turkey.

Research Background & Interests
======
* Diffusion Models and Applications to Inverse Problems
* Vision Foundation Models for Cardiac MRI (2D+Time Data)
* Multimodal Learning for 3D Medical Imaging
* Optimization and Langevin Monte Carlo Sampling Theory

Professional Experiences
======

### Purdue University, Research Assistant  

**Diffusion Models** _(Advisor: Prof. Abolfazl Hashemi)_, _Aug 2022 -- Present_  
- Developed the first theoretically grounded algorithm for solving inverse problems with diffusion model priors without requiring forward-model derivatives or pseudo-inverses. Demonstrated applications to brain MRI reconstruction, black-hole imaging, and fluid dynamics (Navier–Stokes equations), and established the first convergence guarantees among derivative-free methods to an $$\varepsilon$$-accurate solution for general inverse problems. Accepted to **[ICML'26](https://openreview.net/forum?id=UlFOINq6SY&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICML.cc%2F2026%2FConference%2FAuthors%23your-submissions))**.

- Developed a principled posterior sampling algorithm for general inverse problems by integrating variance reduction with Langevin Monte Carlo and diffusion model priors, enabling lower-variance and more accurate reconstructions. Established convergence guarantees to an $$\varepsilon$$-accurate solution and demonstrated effectiveness on MRI and CT reconstruction. Accepted to **[UAI'26](https://arxiv.org/pdf/2606.16257)**.

**Vision Foundation Models for Cardiac MRI** _(Advisor: Prof. Behzad Sharif)_, _Aug 2022 -- Present_  
- Built the largest-scale foundation model for cardiac perfusion MRI using a Masked Autoencoder. Pretrained on $$>600,000$$ unlabeled stress/rest images, the model achieved state-of-the-art myocardium segmentation and landmark localization performance using 10$$\times$$ fewer manual labels than supervised baselines, with performance further validated by blood flow quantification analysis. Accepted to **[ISMRM'26 (Oral).](https://drive.google.com/file/d/1TNASuo5zYftx9WPfDACiZvt20Zn6p86D/view?usp=sharing)**           

- Adapted a pretrained cardiac cine foundation model for cardiac perfusion MRI, reducing the need for manually labeled training data by 12$$\times$$ for automatic myocardium segmentation. In a separate study, developed a cardiac perfusion MRI–based ischemia detection method that achieved high diagnostic accuracy with limited labeled data. Both works were accepted to **[SCMR'26 (Oral).](https://www.journalofcmr.com/article/S1097-6647(25)00807-5/fulltext)**

### Siemens Healthineers, Research Internship, _Malvern, Pennsylvania_

**3D Multimodal Abnormality Classifier**, _May 2024 - Aug 2024_  
- Large-scale annotation for 3D brain MRI abnormality classification is highly labor-intensive. To mitigate this, proposed a multimodal classifier that uses the Phi-3 Large Language Model to align radiology reports with brain atlas-defined abnormality regions of interest, which are converted into Gaussian attention maps to guide model training.

- Employed an efficient 3D state-space Mamba architecture with anatomy-guided connections, achieving improved benchmark performance without requiring any manual annotations. This work was conducted under mentorship of Yoshihisa Shinagawa. Under review for \textbf{patent application}, and accepted to a **[CVPR'26 workshop (Oral).](https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/html/Sahin_Multimodal_Abnormality_Classifier_Using_Anatomy-Guided_Connection_for_3D_Medical_Images_CVPRW_2026_paper.html)**

### BAYKAR Technology, Artificial Intelligence Internship, _Istanbul, Turkey_

**Anomaly Detection**, _May 2021 - Aug 2021_
- Designed various anomaly detection models using machine learning for time series data for unmanned aerial vehicles. As the programming language, Python was used; Pandas, Scikit-learn, Keras, and TensorFlow libraries were used for data visualization and building a model.

### HAVELSAN, Computer Vision and Deep Learning Internship, _Ankara, Turkey_

**Object Detection and Classification**, _May 2020 - Aug 2020_
- Due to the outbreak of COVID-19, an application was designed to identify unmasked individuals that present a serious health risk to the general public. This application utilized famous YOLO algorithm written in Python with TensorFlow library.


Publications and Preprints
======

* denotes equal contribution

### Publications
1. **M. B. Sahin**, B. Sharif, A. Hashemi, _“Zeroth-Order Non-Log-Concave Sampling with Variance Reduction and Applications to Inverse Problems"_, International Conference on Machine Learning (ICML), 2026.       
    Available: [https://arxiv.org/abs/2605.30573](https://arxiv.org/abs/2605.30573)          
    Code: [https://github.com/mberk-sahin/zo-posterior-sampling](https://github.com/mberk-sahin/zo-posterior-sampling)

2. **M. B. Sahin**, A. E. Tanriverdi, B. Sharif, A. Hashemi, _“Variance Reduction for Non-Log-Concave Sampling with Applications to Inverse Problems"_, Uncertainty in Artificial Intelligence (UAI), 2026.          
    Available: [https://arxiv.org/abs/2606.16257](https://arxiv.org/abs/2606.16257)          
    Code: [https://github.com/mberk-sahin/variance-reduced-sampling](https://github.com/mberk-sahin/variance-reduced-sampling)

3. **M. B. Sahin\***, D. Yalcinkaya\*, B. Sharif, A. Hashemi, _“Phase-map synthesis from magnitude-only MR images using conditional score-based diffusion models with application in training of accelerated MRI reconstruction models"_, Computer Vision and Pattern Recognition (CVPR) Workshop, 2026.          
    Available: [https://arxiv.org/abs/2605.01185](https://arxiv.org/abs/2605.01185)          
    Code: [https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM](https://github.com/mberk-sahin/phase-map-synthesis-with-SBDM)

4. **M. B. Sahin**, Y. Shinagawa, H. Z. Yerebakan, A. Hashemi, et al., _“Multimodal Abnormality Classifier Using Anatomy-Guided Connection for 3D Medical Images"_, Computer Vision and Pattern Recognition (CVPR) Workshop, 2026. **(Oral)**               
    Available: [https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/papers/Sahin_Multimodal_Abnormality_Classifier_Using_Anatomy-Guided_Connection_for_3D_Medical_Images_CVPRW_2026_paper.pdf](https://openaccess.thecvf.com/content/CVPR2026W/PHAROS-AIF-MIH/papers/Sahin_Multimodal_Abnormality_Classifier_Using_Anatomy-Guided_Connection_for_3D_Medical_Images_CVPRW_2026_paper.pdf)

5. P. Duan, X. Guo, S. Farhand, **M. B. Sahin**, et al. _“AGA3DNet: Anatomy-Guided Gaussian Priors with Multi-view xLSTM for 3D Brain MRI Subtype Classification"_, Computer Vision and Pattern Recognition (CVPR) Workshop, 2026.       
    Available: [https://arxiv.org/abs/2605.07142](https://arxiv.org/abs/2605.07142)

6. **M. B. Sahin**, Z. Li, K. Youssef, A. M. Sohi, et al., _“Foundation model for cardiac perfusion MRI enables 10-fold reduction in labeled dataset size for deep-learning analysis"_, International Conference on Magnetic Resonance Imaging (ISMRM), 2026. **(Oral)**

7. Z. Li, **M. B. Sahin**, A. M. Sohi, D. Yalcinkaya, et al., _“Leveraging a CMR Foundation Model for Automated Classification of Stress Perfusion CMR Datasets: Initial Results Using the SCMR Registry"_, Journal of Cardiovascular Magnetic Resonance, 2026. **(Oral)**      
    Available: [https://www.journalofcmr.com/article/S1097-6647(25)00399-0/fulltext](https://www.journalofcmr.com/article/S1097-6647(25)00399-0/fulltext)

8. **M. B. Sahin**, Z. Li, K. Youssef, A. M. Sohi, et al., _“Adapting a CMR foundation model for A.I.-powered analysis of perfusion CMR: Enabling 12-fold reduction in manually labeled training dataset for automatic segmentation"_, Journal of Cardiovascular Magnetic Resonance, 2026. **(Rapid-Fire)**           
    Available: [https://www.journalofcmr.com/article/S1097-6647(25)00807-5/fulltext](https://www.journalofcmr.com/article/S1097-6647(25)00807-5/fulltext)

9. **M. B. Sahin\***, D. M. Yalcinkaya\*, R. Dharmakumar, A. Hashemi, B. Sharif, _“Retrospective Phase-map Synthesis for CMR Datasets FBom Magnitude-only DICOM Images Enabled by A.I. Generative Models to Create Large Training Datasets for Deep Learning-based Image Reconstruction"_, Journal of Cardiovascular Magnetic Resonance, 2024. **(Rapid-Fire)**                            
    Available: [https://www.journalofcmr.com/article/S1097-6647(24)00978-5/fulltext](https://www.journalofcmr.com/article/S1097-6647(24)00978-5/fulltext)

10. E. C. Kaya*, **M. B. Sahin\***, A. Hashemi, _“Communication-constrained exchange of zeroth-order information with application to collaborative target tracking"_, International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2023.        
    Available: [https://ieeexplore.ieee.org/abstract/document/10096148](https://ieeexplore.ieee.org/abstract/document/10096148)      
    Code: [https://github.com/mberk-sahin/EF_ZO_SGD](https://github.com/mberk-sahin/EF\_ZO\_SGD)

11. E. C. Kaya*, **M. B. Sahin\***, A. Hashemi, _“Communication-Efficient Zeroth-Order Distributed Online Optimization: Algorithm, Theory, and Applications"_, IEEE Access, 2023.         
    Available: [https://ieeexplore.ieee.org/abstract/document/10147304](https://ieeexplore.ieee.org/abstract/document/10147304)          
    Code: [https://github.com/mberk-sahin/FED-EF-ZO-SGD](https://github.com/mberk-sahin/FED-EF-ZO-SGD)

### Preprints
1. Z. Luo\*, **M. B. Sahin\***, A. Upadhyay\*, B. Sharif, A. Hashemi, _“RAMPAGE: RAndomized Mid-Point for debiAsed Gradient Extrapolation"_, Under Review at NeurIPS 2026.          
    Available: [https://arxiv.org/abs/2603.22155](https://arxiv.org/abs/2603.22155)

2. Z. Luo\*, A. Upadhyay\*, **M. B. Sahin**, S. B. Moon, A. Makur, A. Hashemi, _“Unified High-Probability Analysis of Stochastic Variance-Reduced Estimation"_, Under Review at NeurIPS 2026.         
    Available: [https://arxiv.org/abs/2605.15388](https://arxiv.org/abs/2605.15388)

Academic Duties
======
**Reviewer Duties**
* **Conferences**: UAI'26 (_Top Reviewer_; selected among 35 of 1,149 reviewers, top 3%), AAAI'24-'25, ICASSP'24

**Data Science Instructor** at Berkeley Coding Academy, _Jul 2021 - Jun 2022_
* Gave data science and machine learning classes, and prepared course materials, assignments, and code notebooks for 
students. Also, mentored students in Kaggle machine learning competitions.

**Teaching Assistantship** at Bilkent University, Computer Science Department, _Sep 2020 - May 2021_
* CS115 Introduction to Programming in Python



Software Skills
======
* **Python:** Professional research and industrial experience based on machine learning. Strong knowledge and experience in libraries such as _PyTorch_, _Tensorflow_, _JAX_, _Pandas_, _Numpy_ and _Scikit-Learn_. I have experience with Docker and Git via industrial projects.
* **SLURM:** Proficient in using SLURM to manage multi-GPU computing resources for large-scale machine learning research.
* **MATLAB:** Professional research experience in signal processing and computer vision. Used for projects during courses, research and internships.
* **C/C++/Java:** Intermediate experience in various course projects.

Languages
======
_English:_ Fluent                  
_Turkish:_ Native  
