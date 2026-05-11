---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am **Longfei Xiao**, an undergraduate student majoring in **Computer Science and Technology** at **Henan Polytechnic University**. My research interests include **computer vision**, **semantic segmentation**, **visual state space models**, **multi-modal learning**, and **deep learning**.

Currently, I am working on structure-aware visual representation learning for dense prediction tasks, with a focus on improving segmentation performance in challenging regions such as object boundaries, small objects, thin structures, and semantically ambiguous areas.

# News

- *2026.05*: Personal academic homepage launched.
- *2026.05*: Submitted **StructMamba-Seg** to ICONIP 2026.
- *2025.12*: Completed a robustness analysis and improvement project based on ConvNeXt and Tiny-ImageNet-200.

# Publications

## Under Review / Manuscripts

**StructMamba-Seg: Boundary-Context Guided Deformable Scan for Semantic Segmentation**  
**Longfei Xiao**, Linlin Zhang, Kang Yang, Changqiu Xu, Shuyu Liu, Jianfang Wang  
*Submitted to International Conference on Neural Information Processing (ICONIP), 2026*  
[PDF](/files/structmamba-seg.pdf)

- We propose **StructMamba-Seg**, a structure-sensitive Mamba-based semantic segmentation framework.
- The proposed **Boundary-Context Guided Deformable Scan (BCG-DefScan)** uses local features, boundary prompts, and multi-scale context to predict spatial offsets, local ordering offsets, and gating signals.
- The method achieves **82.12% mIoU on Cityscapes** and **50.20% mIoU on ADE20K**, while maintaining a favorable performance-efficiency trade-off.

---

**Towards High-quality Low-Light Remote Sensing Image Enhancement via Geometric and Semantic Prior Guidance**  
Kang Yang, Jiaqi Zhang, Changqiu Xu, **Longfei Xiao**, Tong Liang, Zesheng Zhang  
*Manuscript, 2026*  
[PDF](/files/gspnet.pdf)

- This work proposes **GSPNet**, a geometric and semantic prior-guided framework for low-light remote sensing image enhancement.
- It introduces an HVI-based dual-branch design, semantic and geometric prior modulation, and adaptive sparse refinement for structure-preserving enhancement.

---

**PDAO-Net: A Physics-Constrained Dual-Domain Alternating Optimization Network for Sparse-View 3D-DSA Reconstruction**  
Changqiu Xu, Xi Wang, Yujia Li, Tong Liang, Kang Yang, **Longfei Xiao**, Yikun Zhang, Yang Chen  
*Manuscript, 2026*  
[PDF](/files/pdao-net.pdf)

- This work proposes **PDAO-Net**, a physics-constrained dual-domain alternating optimization network for sparse-view 3D-DSA reconstruction.
- It alternates between projection-domain correction and image-domain refinement, while preserving measured-view consistency.

# Research Projects

## StructMamba-Seg: Boundary-Context Guided Deformable Scan for Semantic Segmentation

I served as the **first author** of this work. I independently completed the literature review, method design, model implementation, experimental training, ablation studies, paper writing, figure preparation, result organization, and submission formatting.

The project focuses on semantic segmentation in challenging regions, including boundaries, small objects, thin structures, and semantically ambiguous areas. It introduces BCG-DefScan into Mamba-based visual state space models, enabling scanning paths and offset controls to adapt to segmentation-specific structural cues.

## Robustness Analysis and Improvement of ConvNeXt under Real-world Degradation

I led this project and built a robustness evaluation and improvement framework based on ConvNeXt and Tiny-ImageNet-200. The project designed a hierarchical evaluation protocol covering clean validation, fixed degradation validation, and degradation-grid testing. It further introduced degradation augmentation, consistency constraints, sample mixing, and EMA to improve robustness under noise, blur, and JPEG compression.

# Honors and Awards

- *2024*: National Second Prize, China Undergraduate Mathematical Contest in Modeling, Team Leader
- *2025*: National Third Prize, International Mathematical Contest in Modeling, Team Leader
- *2025*: National Third Prize, Belt and Road & BRICS Skills Development and Technology Innovation Competition
- *2025*: Provincial First Prize, China Undergraduate Mathematical Contest in Modeling, Team Leader
- *2024*: Second Prize, Henan Provincial College Student Mathematics Competition

# Education

- *2023.09 - Present*, B.Eng. in Computer Science and Technology, Henan Polytechnic University  
  GPA: **4.19/5**, Ranking: **2/160**  
  Core courses: Advanced Mathematics, Linear Algebra, Probability and Mathematical Statistics, Discrete Mathematics, Data Structures, Computer Organization.
