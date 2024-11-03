---
title: "Transforming Breast Cancer Diagnosis: Towards Real-Time Ultrasound to Mammogram Conversion for Cost-Effective Diagnosis"
collection: publications
permalink: /publication/transforming-breast-cancer-diagnosis
date: 2023-08-01
venue: 'Journal of Ultrasonics'
paperurl: 'https://arxiv.org/abs/2308.05449'

---

Ultrasound (US) imaging is better suited for intraoperative settings because it is real-time and more portable than other imaging techniques, such as mammography. However, US images are characterized by lower spatial resolution noise-like artifacts. This research aims to address these limitations by providing surgeons with mammogram-like image quality in real-time from noisy US images. Unlike previous approaches for improving US image quality that aim to reduce artifacts by treating them as (speckle noise), we recognize their value as informative wave interference pattern (WIP). To achieve this, we utilize the Stride software to numerically solve the forward model, generating ultrasound images from mammograms images by solving wave-equations. Additionally, we leverage the power of domain adaptation to enhance the realism of the simulated ultrasound images. Then, we utilize generative adversarial networks (GANs) to tackle the inverse problem of generating mammogram-quality images from ultrasound images. The resultant images have considerably more discernible details than the original US images.