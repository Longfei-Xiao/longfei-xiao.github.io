---
permalink: /
title: "About Me"
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div style="font-size: 18px; line-height: 1.85; margin-bottom: 28px;">

I am <strong>Longfei Xiao</strong>, an undergraduate student majoring in <strong>Computer Science and Technology</strong> at <strong>Henan Polytechnic University</strong>. My research interests include <strong>computer vision</strong>, <strong>semantic segmentation</strong>, <strong>visual state space models</strong>, <strong>multimodal learning</strong>, and <strong>deep learning</strong>.

</div>

---

## Education

<div style="border: 1px solid #e5e7eb; border-radius: 14px; padding: 20px 24px; margin: 20px 0 34px 0; background: #fafafa; box-shadow: 0 2px 8px rgba(0,0,0,0.03);">

<div style="font-size: 20px; font-weight: 700; margin-bottom: 6px;">
Henan Polytechnic University
</div>

<div style="font-size: 16px; color: #555; margin-bottom: 14px;">
B.Eng. in Computer Science and Technology &nbsp; | &nbsp; Sep. 2023 - Present
</div>

<div style="line-height: 1.9;">
<strong>GPA:</strong> 4.19 / 5.00 &nbsp;&nbsp; <strong>Rank:</strong> 2 / 160, top 2%<br>
<strong>English:</strong> CET-4, CET-6<br>
<strong>Core Courses:</strong> Advanced Mathematics, Linear Algebra, Probability and Mathematical Statistics, Discrete Mathematics, Data Structures, Computer Organization
</div>

</div>

---

## Publications

<div style="border-left: 5px solid #4f46e5; padding: 20px 24px; margin: 24px 0; background: #f8fafc; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.03);">

<div style="font-size: 20px; font-weight: 700; margin-bottom: 10px;">
StructMamba-Seg: Boundary-Context Guided Deformable Scan for Semantic Segmentation
</div>

<div style="line-height: 1.8; margin-bottom: 8px;">
<strong>Longfei Xiao</strong>, Linlin Zhang, Kang Yang, Changqiu Xu, Shuyu Liu, Jianfang Wang
</div>

<div style="font-style: italic; color: #555; margin-bottom: 16px;">
Submitted to International Conference on Neural Information Processing (ICONIP), 2026
</div>

<div style="line-height: 1.9;">
This work proposes <strong>StructMamba-Seg</strong>, a structure-sensitive Mamba-based framework for semantic segmentation. It addresses the mismatch between scan decisions and segmentation-specific structural requirements by introducing <strong>Boundary-Context Guided Deformable Scan (BCG-DefScan)</strong> into the visual state space backbone.
<br><br>
BCG-DefScan incorporates local geometry, boundary prompts, and multi-scale contextual cues to jointly predict spatial offsets, local ordering offsets, and gating signals. This design enables sampling positions, local scan order, and offset modulation strength to adapt to object boundaries, small objects, thin structures, and semantically ambiguous regions. The framework further introduces an IoU-boundary joint optimization objective to provide complementary supervision for regional consistency and boundary details during training.
<br><br>
The method achieves <strong>82.12% mIoU on Cityscapes</strong> and <strong>50.20% mIoU on ADE20K</strong>, with consistent improvements on structure-sensitive metrics such as Boundary IoU, Boundary F1, hard-class mIoU, and small-class mIoU.
</div>

</div>

<div style="border-left: 5px solid #0ea5e9; padding: 20px 24px; margin: 24px 0; background: #f8fafc; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.03);">

<div style="font-size: 20px; font-weight: 700; margin-bottom: 10px;">
Towards High-quality Low-Light Remote Sensing Image Enhancement via Geometric and Semantic Prior Guidance
</div>

<div style="line-height: 1.8; margin-bottom: 8px;">
Kang Yang, Jiaqi Zhang, Changqiu Xu, <strong>Longfei Xiao</strong>, Tong Liang, Zesheng Zhang
</div>

<div style="font-style: italic; color: #555; margin-bottom: 16px;">
Submitted to International Conference on Neural Information Processing (ICONIP), 2026
</div>

<div style="line-height: 1.9;">
This work presents <strong>GSPNet</strong>, a geometric and semantic prior-guided framework for low-light remote sensing image enhancement. Unlike natural low-light enhancement, remote sensing scenes involve wide-area structures, dense land-cover patterns, and severe noise in under-exposed regions, making both visibility restoration and structural preservation challenging.
<br><br>
GSPNet adopts an <strong>HVI-based dual-branch architecture</strong> to decouple illumination restoration from chromatic recovery. It further injects semantic and geometric priors extracted from frozen vision foundation models through a prior-guided modulation module, providing reliable structural guidance for severely under-exposed regions. An adaptive sparse refinement block is introduced to suppress unreliable token correlations caused by dark-region noise while preserving land-cover boundaries and local details.
<br><br>
Experiments on low-light remote sensing benchmarks and the LOL dataset demonstrate that GSPNet improves reconstruction fidelity, structural preservation, and perceptual quality, especially in noise suppression and boundary restoration.
</div>

</div>

<div style="border-left: 5px solid #10b981; padding: 20px 24px; margin: 24px 0 36px 0; background: #f8fafc; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.03);">

<div style="font-size: 20px; font-weight: 700; margin-bottom: 10px;">
PDAO-Net: A Physics-Constrained Dual-Domain Alternating Optimization Network for Sparse-View 3D-DSA Reconstruction
</div>

<div style="line-height: 1.8; margin-bottom: 8px;">
Changqiu Xu, Xi Wang, Yujia Li, Tong Liang, Kang Yang, <strong>Longfei Xiao</strong>, Yikun Zhang, Yang Chen
</div>

<div style="font-style: italic; color: #555; margin-bottom: 16px;">
Submitted to International Conference on Neural Information Processing (ICONIP), 2026
</div>

<div style="line-height: 1.9;">
This work proposes <strong>PDAO-Net</strong>, a physics-constrained dual-domain alternating optimization network for sparse-view 3D digital subtraction angiography reconstruction. Sparse-view acquisition can reduce radiation exposure and acquisition time, but incomplete angular sampling often leads to severe streak artifacts, blurred vessel boundaries, and missing small vascular branches.
<br><br>
PDAO-Net initializes reconstruction in both the image and projection domains using a pre-trained restoration network and forward projection. It then unfolds the reconstruction process into an <strong>N-stage alternating optimization framework</strong>, where projection-domain correction and image-domain refinement are performed alternately. A measured-view replacement mechanism explicitly preserves acquired sparse-view measurements during missing-view projection estimation, thereby enforcing data consistency.
<br><br>
Experiments on simulated and clinical 3D-DSA datasets show that PDAO-Net improves artifact suppression, vascular continuity preservation, and small-branch recovery compared with representative analytical and learning-based methods.
</div>

</div>

---

## Research Project

<div style="border: 1px solid #e5e7eb; border-radius: 14px; padding: 20px 24px; margin: 20px 0 34px 0; background: #ffffff; box-shadow: 0 2px 8px rgba(0,0,0,0.03);">

<div style="font-size: 20px; font-weight: 700; margin-bottom: 8px;">
Robustness Analysis and Improvement of ConvNeXt under Real-world Degradation
</div>

<div style="font-style: italic; color: #555; margin-bottom: 16px;">
Project Leader &nbsp; | &nbsp; Oct. 2025 - Dec. 2025
</div>

<div style="line-height: 1.9;">
This project investigates the performance degradation and high-confidence misclassification of ConvNeXt under real-world corrupted inputs. Based on <strong>ConvNeXt</strong> and <strong>Tiny-ImageNet-200</strong>, I built a robustness evaluation and improvement framework covering clean validation, fixed-degradation validation, and degradation-grid testing.
<br><br>
The project further introduces training-time degradation augmentation, consistency regularization, sample mixing, and exponential moving average to improve robustness under noise, blur, and JPEG compression.
</div>

</div>

---

## Awards

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(285px, 1fr)); gap: 14px; margin-top: 20px;">

<div style="border: 1px solid #e5e7eb; border-radius: 12px; padding: 16px 18px; background: #fafafa; box-shadow: 0 2px 6px rgba(0,0,0,0.025);">
<strong>National Second Prize</strong><br>
China Undergraduate Mathematical Contest in Modeling, 2024<br>
Team Leader
</div>

<div style="border: 1px solid #e5e7eb; border-radius: 12px; padding: 16px 18px; background: #fafafa; box-shadow: 0 2px 6px rgba(0,0,0,0.025);">
<strong>National Third Prize</strong><br>
International Mathematical Contest in Modeling, 2025<br>
Team Leader
</div>

<div style="border: 1px solid #e5e7eb; border-radius: 12px; padding: 16px 18px; background: #fafafa; box-shadow: 0 2px 6px rgba(0,0,0,0.025);">
<strong>National Third Prize</strong><br>
Belt and Road & BRICS Skills Development and Technology Innovation Competition, 2025<br>
Programming Contributor
</div>

<div style="border: 1px solid #e5e7eb; border-radius: 12px; padding: 16px 18px; background: #fafafa; box-shadow: 0 2px 6px rgba(0,0,0,0.025);">
<strong>Provincial First Prize</strong><br>
China Undergraduate Mathematical Contest in Modeling, 2025<br>
Team Leader
</div>

<div style="border: 1px solid #e5e7eb; border-radius: 12px; padding: 16px 18px; background: #fafafa; box-shadow: 0 2px 6px rgba(0,0,0,0.025);">
<strong>Second Prize</strong><br>
Henan Provincial College Student Mathematics Competition, 2024
</div>

</div>
