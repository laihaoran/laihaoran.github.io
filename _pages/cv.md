---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D. in Biomedical Engineering**, University of Science and Technology of China (USTC), 2022 – Present  
  Advisor: Prof. Shaohua Zhou (IEEE Fellow, Dean)

* **M.S. in Biomedical Engineering**, Southern Medical University, 2019 – 2022  
  Advisor: Prof. Meiyan Huang (Guangdong Young Pearl River Scholar)

* **B.S. in Biomedical Engineering**, Southern Medical University, 2015 – 2019

---

## Research Interests

Multimodal learning, medical image analysis, vision-language models, cross-modal alignment, 3D medical imaging, reinforcement learning for clinical reasoning.

---

## Internship Experience

**iFLYTEK Co., Ltd. — Smart Healthcare Institute**  
*Research Algorithm Engineer (Intern)*, Apr 2023 – Apr 2025

- **XiaoYi Medical QA System**: Developed and optimized the medical dialogue generation module for a multimodal medical QA system. Introduced knowledge graphs and RAG techniques to significantly improve professional accuracy and consistency in clinical dialogue, supporting applications in medical record QA, imaging-assisted diagnosis, and health consultation.
- **iFLYTEK Spark Medical LLM**: Led research on image-text alignment algorithms and multimodal pre-training strategies. Proposed a cross-modal alignment optimization module for dynamic fusion of medical image and report features, achieving notable performance gains on multimodal diagnosis, report generation, and clinical QA tasks.

---

## Research Experience

**3D Medical Vision-Language Models**, Jul 2024 – Present  
- Explored construction of 3D medical VLMs for automated understanding and interpretable reasoning over complex 3D medical scenes.
- Built a VQA dataset from 3D CT scans and paired reports; proposed an efficient image-text alignment strategy; designed a **loss correction strategy** to address output bias in autoregressive models caused by report spatial bias.
- In the RL stage, proposed a **consistency reward function** to optimize reasoning chains, significantly enhancing diagnostic accuracy and logical coherence.
- The resulting 3D CT LLM surpasses existing open-source general and medical models on diagnostic and reasoning benchmarks.
- *Paper submitted to CVPR 2026 (CCF A).*

**3D Vision-Language Alignment and Cross-Modal Reasoning**, Dec 2023 – Jun 2024  
- Designed cross-modal alignment algorithms for semantic mapping between 3D vision and language, supporting zero-shot classification and image-text retrieval on 3D medical images.
- Proposed a combined explicit and implicit alignment strategy to address limited 3D CT-report data and suboptimal alignment; achieved state-of-the-art (SOTA) performance on three open-source 3D CT benchmarks.
- *Published in IEEE Journal of Biomedical and Health Informatics (CAS Q1, JCR Q1 Top, IF: 6.8).*

**2D Vision-Language Alignment and Cross-Modal Reasoning**, Sep 2022 – Nov 2023  
- Built a zero-shot image classification and recognition framework based on self-supervised contrastive learning and deep feature modeling.
- Proposed a learnable cross-attention based image-text alignment strategy to replace manually defined metrics (e.g., cosine similarity); achieved SOTA performance on chest X-ray zero-shot diagnosis and object detection tasks.
- *Published at CVPR 2024 (CCF A).*

**Early Macrovascular Invasion Prediction via Deep Learning**, May 2020 – Apr 2022  
- Developed multimodal diagnostic models for predicting early macrovascular invasion in hepatocellular carcinoma patients, assisting clinical treatment decisions.
- Built a multimodal model from liver CT and clinical indicators; introduced **word vector encoding** for clinical feature representation; further proposed a CT-only prediction framework incorporating **graph convolutional networks** for tumor boundary and global liver structure features.
- *Published in IEEE Transactions on Medical Imaging (CAS Q1, IF: 10.048) and EClinicalMedicine (CAS Q1, IF: 17.033).*

**Alzheimer's Disease Imaging-Genomics Cross-modal Modeling**, Sep 2019 – May 2020  
- Explored cross-modal association patterns between medical images and gene sequences; built a unified multimodal representation learning framework for Alzheimer's disease (AD).
- Proposed a feature alignment method for brain MRI and SNP sequences; identified key SNP loci linked to brain structural changes via gradient backpropagation to reveal potential AD-related pathogenic mechanisms.
- *Published in Medical Image Analysis (CAS Q1, JCR Q1 Top, IF: 10.7).*

---

## Publications

**Journal Papers**

1. **Bridged Semantic Alignment for Zero-shot 3D Medical Image Diagnosis**  
   **Haoran Lai**, et al. *IEEE Journal of Biomedical and Health Informatics*, 2025. **(1st author)** — CAS Q1, JCR Q1 Top, IF: 6.8

2. **Prior Knowledge-Aware Fusion Network for Prediction of Macrovascular Invasion in Hepatocellular Carcinoma**  
   **Haoran Lai**, et al. *IEEE Transactions on Medical Imaging*, 2022. **(1st author)** — CAS Q1, JCR Q1 Top, IF: 10.048

3. **Multi-task Deep Learning Network to Predict Future Macrovascular Invasion in Hepatocellular Carcinoma**  
   **Haoran Lai\***, et al. *EClinicalMedicine*, 2021. **(co-first author)** — CAS Q1, JCR Q1 Top, IF: 17.033

4. **Deep-Gated Recurrent Unit and Diet Network-Based Genome-Wide Association Analysis for Detecting the Biomarkers of Alzheimer's Disease**  
   *Medical Image Analysis*, 2021. **(2nd author)** — CAS Q1, JCR Q1 Top, IF: 10.7

5. **2D-3D Cascade Network for Glioma Segmentation in Multisequence MRI Images Using Multiscale Information**  
   **Haoran Lai\***, et al. *Computer Methods and Programs in Biomedicine*, 2022. **(co-first author)** — CAS Q2, JCR Q1 Top, IF: 6.1

6. **Semi-supervised hybrid spine network for segmentation of spine MR images**  
   *Computerized Medical Imaging and Graphics*, 2023. **(co-corresponding author)** — CAS Q2, JCR Q1 Top, IF: 5.4

**Conference Papers**

1. **CARZero: Cross-Attention Alignment for Radiology Zero-Shot Classification**  
   **Haoran Lai**, et al. *CVPR 2024*. **(1st author)** — CCF A, Top Venue in Computer Vision

2. **Long-Tailed Multi-Label Classification with Noisy Label of Thoracic Diseases from Chest X-Ray**  
   **Haoran Lai**, et al. *ISBI 2024*. **(1st author)** — IEEE Flagship Conference in Biomedical Imaging

**Under Review**

1. **E3D-GPT: Enhanced 3D Visual Foundation for Medical Vision-Language Model**  
   **Haoran Lai**, et al. **(1st author)**

2. **Med3D-R1: Incentivizing Clinical Reasoning in 3D Medical Vision-Language Models for Abnormality Diagnosis**  
   **Haoran Lai**, et al. *MICCAI 2026* (under review). **(1st author)** — CCF B

---

## Conference Presentations

- **CVPR 2024**, Seattle, WA, USA — Poster presentation on *CARZero*, Jun 2024

---

## Honors & Awards

- Outstanding Ph.D. Graduate, USTC, 2026
- National Scholarship for Ph.D. Students, USTC, 2024
- Suzhou Industrial Park Scholarship, USTC, 2022
- Outstanding Graduate Student, Southern Medical University, 2022
- National Scholarship for M.S. Students, Southern Medical University, 2021
- Exempt Admission Scholarship (推免生奖学金), Southern Medical University, 2019
- **Champion**, MICCAI Thyroid Nodule Classification & Segmentation (TN-SCUI2020) — Classification Track, 2020

---

## Skills

- **Programming**: Python (proficient), C++ (proficient)
- **Frameworks**: PyTorch, TensorFlow
- **Languages**: Chinese (native), English (CET-6: 488)
- **Certifications**: National Computer Rank Examination Level 2, C++ (98/100)
