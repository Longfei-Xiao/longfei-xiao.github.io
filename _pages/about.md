---
permalink: /
title: "Homepage"
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-section {
  margin: 34px 0 44px 0;
}

.home-title {
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 1.55rem;
  font-weight: 850;
  margin-bottom: 20px;
  color: #111827;
  letter-spacing: -0.02em;
}

.home-title::before {
  content: attr(data-icon);
  width: 36px;
  height: 36px;
  border-radius: 12px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #eef2ff 0%, #e0f2fe 100%);
  border: 1px solid #dbeafe;
  box-shadow: 0 4px 12px rgba(15, 23, 42, 0.06);
  font-size: 1.05rem;
  flex: 0 0 auto;
}

.home-title::after {
  content: "";
  height: 1px;
  flex: 1;
  background: linear-gradient(90deg, #e5e7eb 0%, rgba(229, 231, 235, 0) 100%);
  margin-left: 4px;
}

.bio-card {
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  padding: 26px 30px;
  background: linear-gradient(135deg, #ffffff 0%, #f8fafc 100%);
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.05);
  margin-bottom: 30px;
}

.bio-main {
  font-size: 1.08rem;
  line-height: 1.9;
  color: #374151;
}

.tag-row {
  margin-top: 18px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.tag {
  display: inline-block;
  padding: 7px 13px;
  border-radius: 999px;
  background: #eef2ff;
  color: #3730a3;
  font-size: 0.88rem;
  font-weight: 650;
  border: 1px solid #e0e7ff;
}

.action-row {
  margin-top: 22px;
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

.action-btn {
  display: inline-block;
  padding: 9px 15px;
  border-radius: 10px;
  text-decoration: none !important;
  font-weight: 700;
  font-size: 0.92rem;
  border: 1px solid #d1d5db;
  background: #ffffff;
  color: #374151 !important;
  box-shadow: 0 2px 6px rgba(15, 23, 42, 0.04);
}

.action-btn.primary {
  background: #2563eb;
  color: #ffffff !important;
  border-color: #2563eb;
}

.info-card {
  border: 1px solid #e5e7eb;
  border-radius: 16px;
  padding: 22px 26px;
  background: #ffffff;
  box-shadow: 0 6px 18px rgba(15, 23, 42, 0.04);
}

.info-card.soft {
  background: #fafafa;
}

.edu-head {
  display: flex;
  align-items: center;
  gap: 18px;
  flex-wrap: wrap;
}

.edu-logo {
  width: 76px;
  height: 76px;
  object-fit: contain;
  border-radius: 14px;
  background: #ffffff;
  padding: 8px;
  border: 1px solid #e5e7eb;
  box-shadow: 0 3px 10px rgba(15, 23, 42, 0.06);
}

.edu-name {
  font-size: 1.18rem;
  font-weight: 800;
  color: #111827;
  margin-bottom: 6px;
}

.edu-meta {
  color: #4b5563;
  margin-bottom: 14px;
  font-size: 0.98rem;
}

.edu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
  gap: 12px;
  margin-top: 18px;
}

.edu-item {
  padding: 12px 14px;
  border-radius: 12px;
  background: #f8fafc;
  border: 1px solid #eef2f7;
}

.pub-card {
  border-radius: 18px;
  padding: 24px 28px;
  margin: 22px 0;
  background: #f8fafc;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.055);
  border: 1px solid #e5e7eb;
  position: relative;
  overflow: hidden;
}

.pub-card::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  width: 6px;
  height: 100%;
}

.pub-card.seg::before {
  background: #4f46e5;
}

.pub-card.rs::before {
  background: #0ea5e9;
}

.pub-label {
  display: inline-block;
  padding: 5px 10px;
  border-radius: 999px;
  font-size: 0.78rem;
  font-weight: 800;
  margin-bottom: 12px;
}

.pub-label.seg {
  background: #eef2ff;
  color: #3730a3;
}

.pub-label.rs {
  background: #e0f2fe;
  color: #0369a1;
}

.pub-title {
  font-size: 1.18rem;
  font-weight: 850;
  color: #111827;
  line-height: 1.45;
  margin-bottom: 10px;
}

.pub-authors {
  line-height: 1.75;
  color: #374151;
  margin-bottom: 6px;
}

.pub-venue {
  font-style: italic;
  color: #4b5563;
  margin-bottom: 14px;
}

.pub-short {
  line-height: 1.85;
  color: #374151;
}

.pub-figure-wrap {
  margin: 18px 0 8px 0;
  text-align: center;
}

.pub-figure {
  display: block;
  max-width: 100%;
  max-height: 520px;
  margin: 0 auto;
  border-radius: 14px;
  border: 1px solid #e5e7eb;
  box-shadow: 0 6px 18px rgba(15, 23, 42, 0.06);
  background: #ffffff;
}

.pub-figcap {
  margin-top: 8px;
  font-size: 0.9rem;
  color: #6b7280;
}

.metric-row {
  margin-top: 14px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.metric {
  display: inline-block;
  padding: 6px 11px;
  border-radius: 10px;
  font-size: 0.86rem;
  font-weight: 800;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  color: #374151;
}

details {
  margin-top: 14px;
}

summary {
  cursor: pointer;
  font-weight: 800;
  color: #2563eb;
  margin-top: 10px;
}

.detail-box {
  margin-top: 12px;
  padding: 15px 18px;
  border-radius: 12px;
  background: #ffffff;
  border: 1px solid #e5e7eb;
  line-height: 1.85;
  color: #374151;
}

.project-card {
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  padding: 24px 28px;
  background: #ffffff;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.045);
}

.project-title {
  font-size: 1.16rem;
  font-weight: 850;
  margin-bottom: 8px;
  color: #111827;
}

.project-meta {
  color: #4b5563;
  font-style: italic;
  margin-bottom: 14px;
}

.award-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(285px, 1fr));
  gap: 14px;
  margin-top: 18px;
}

.award-card {
  border: 1px solid #e5e7eb;
  border-radius: 16px;
  padding: 17px 18px;
  background: #fafafa;
  box-shadow: 0 5px 14px rgba(15, 23, 42, 0.035);
}

.award-name {
  font-weight: 850;
  color: #111827;
  margin-bottom: 6px;
}

.award-meta {
  color: #4b5563;
  line-height: 1.7;
}

.cert-details {
  margin-top: 12px;
}

.cert-details summary {
  cursor: pointer;
  font-weight: 800;
  color: #2563eb;
  font-size: 0.9rem;
}

.cert-img {
  width: 100%;
  margin-top: 12px;
  border-radius: 12px;
  border: 1px solid #e5e7eb;
  box-shadow: 0 4px 14px rgba(15, 23, 42, 0.08);
  background: #ffffff;
}

@media (max-width: 768px) {
  .bio-card,
  .info-card,
  .pub-card,
  .project-card {
    padding: 20px 18px;
  }

  .pub-figure {
    max-height: 360px;
  }
}
</style>

<div class="bio-card" id="about">
  <div class="bio-main">
    I am <strong>Longfei Xiao</strong>, an undergraduate student majoring in <strong>Computer Science and Technology</strong> at <strong>Henan Polytechnic University</strong>. My academic interests mainly focus on <strong>computer vision</strong>, with a particular interest in semantic segmentation, image enhancement, visual representation learning, and robust deep learning.
    <br><br>
    Beyond research, I am deeply passionate about badminton and tennis, and I would say I am reasonably good at both. Basketball, however, has never been especially kind to my height, so I usually meet friends on the badminton or tennis court instead. I also enjoy history, thinking about how people and society change over time, and singing — though, to be fair, my enthusiasm for singing may be stronger than my actual voice.
  </div>

  <div class="tag-row">
    <span class="tag">Computer Vision</span>
    <span class="tag">Semantic Segmentation</span>
    <span class="tag">Image Enhancement</span>
    <span class="tag">Visual Representation Learning</span>
    <span class="tag">Robust Deep Learning</span>
  </div>
  
  <div class="action-row">
    <a class="action-btn primary" href="/files/Resume1.pdf" target="_blank" rel="noopener">Resume</a>
    <a class="action-btn" href="https://orcid.org/0009-0004-7405-1131" target="_blank" rel="noopener">ORCID</a>
    <a class="action-btn" href="https://github.com/Longfei-Xiao" target="_blank" rel="noopener">GitHub</a>
  </div>
</div>

<div class="home-section" id="education">
  <div class="home-title" data-icon="🎓">Education</div>

  <div class="info-card soft">
    <div class="edu-head">
      <img class="edu-logo" src="/images/hpu-logo.png" alt="Henan Polytechnic University Logo">

      <div>
        <div class="edu-name">Henan Polytechnic University</div>
        <div class="edu-meta">B.Eng. in Computer Science and Technology &nbsp; | &nbsp; Sep. 2023 - Present</div>
      </div>
    </div>

    <div class="edu-grid">
      <div class="edu-item">
        <strong>GPA</strong><br>
        4.19 / 5.00
      </div>

      <div class="edu-item">
        <strong>Ranking</strong><br>
        2 / 161, top 1.5%
      </div>

      <div class="edu-item">
        <strong>English</strong><br>
        CET-4, CET-6 (452)
      </div>
    </div>
  </div>
</div>

<div class="home-section" id="publications">
  <div class="home-title" data-icon="📚">Publications</div>

  <div class="pub-card seg">
    <div class="pub-label seg">Semantic Segmentation · Visual State Space Models</div>

    <div class="pub-title">
      StructMamba-Seg: Boundary-Context Guided Deformable Scan for Semantic Segmentation
    </div>

    <div class="pub-authors">
      <strong>Longfei Xiao</strong>, Linlin Zhang, Kang Yang, Changqiu Xu, Shuyu Liu, Jianfang Wang
    </div>

    <div class="pub-venue">
      Under Review · ICONIP 2026 · CCF-C · First Author
    </div>

    <div class="pub-short">
      This work proposes <strong>StructMamba-Seg</strong> for challenging semantic segmentation regions such as object boundaries, small objects, fine structures, and semantically ambiguous areas. It introduces <strong>BCG-DefScan</strong> into Mamba-based visual state space models, using local features, boundary prompts, and multi-scale context to predict spatial offsets, local scan-order offsets, and gating signals for structure-adaptive scanning.
    </div>

    <div class="pub-figure-wrap">
      <img class="pub-figure" src="/images/structmamba-mech.png" alt="StructMamba-Seg mechanism figure">
      <div class="pub-figcap">Mechanism overview of StructMamba-Seg and BCG-DefScan.</div>
    </div>

    <div class="metric-row">
      <span class="metric">ICONIP 2026</span>
      <span class="metric">CCF-C</span>
      <span class="metric">First Author</span>
    </div>

    <details>
      <summary>Show details</summary>
      <div class="detail-box">
        I served as the first author and independently completed the literature review, idea design, model implementation, experimental training, ablation validation, figure preparation, and paper writing. The model achieves <strong>82.12% mIoU</strong> on Cityscapes and <strong>50.20% mIoU</strong> on ADE20K, with stable improvements on structure-sensitive metrics including Boundary IoU, Boundary F1, and Hard-class mIoU.
      </div>
    </details>
  </div>

  <div class="pub-card rs">
    <div class="pub-label rs">Remote Sensing · Low-light Image Enhancement</div>

    <div class="pub-title">
      Towards High-quality Low-Light Remote Sensing Image Enhancement via Geometric and Semantic Prior Guidance
    </div>

    <div class="pub-authors">
      Kang Yang, Jiaqi Zhang, Changqiu Xu, <strong>Longfei Xiao</strong>, Tong Liang, Zesheng Zhang
    </div>

    <div class="pub-venue">
      ICONIP 2026 · CCF-C · Student First Author
    </div>

    <div class="pub-short">
      This work constructs <strong>GSPNet</strong> for low-light remote sensing image enhancement, targeting brightness degradation, color distortion, dark-region noise propagation, and blurred land-cover boundaries. It decouples illumination and chromatic restoration with an HVI dual-branch representation, introduces semantic and geometric priors for structural modulation, and designs adaptive sparse refinement to suppress dark-region noise while preserving land-cover consistency.
    </div>

    <div class="pub-figure-wrap">
      <img class="pub-figure" src="/images/gspnet-mech.jpg" alt="GSPNet mechanism figure">
      <div class="pub-figcap">Mechanism overview of GSPNet for low-light remote sensing image enhancement.</div>
    </div>

    <div class="metric-row">
      <span class="metric">ICONIP 2026</span>
      <span class="metric">CCF-C</span>
      <span class="metric">Student First Author</span>
    </div>

    <details>
      <summary>Show details</summary>
      <div class="detail-box">
        I participated in method framework design, literature organization, experimental discussion, paper refinement, technical-route summarization, comparison analysis, and figure/table preparation. The method achieves overall leading performance on LOL and low-light remote sensing benchmarks. On iSAID-Dark, it reaches <strong>26.03 dB PSNR</strong>, <strong>0.796 SSIM</strong>, and <strong>0.166 LPIPS</strong>.
      </div>
    </details>
  </div>
</div>

<div class="home-section" id="research-project">
  <div class="home-title" data-icon="🔬">Research Project</div>

  <div class="project-card">
    <div class="project-title">
      Robustness Analysis and Improvement of ConvNeXt under Real-world Degradation
    </div>

    <div class="project-meta">
      Independent Project · Project Leader
    </div>

    <div style="line-height: 1.9; color: #374151;">
      This project builds a degradation robustness analysis pipeline based on <strong>ConvNeXt-Tiny</strong> and <strong>Tiny-ImageNet-200</strong>. It designs a dual-validation protocol with <strong>Val(Clean)</strong> and <strong>Val(Degraded-Fixed)</strong>, together with a multi-strength <strong>Degradation Grid</strong> testing protocol to evaluate model performance under noise, blur, motion blur, and JPEG compression.
    </div>

    <details>
      <summary>Show details</summary>
      <div class="detail-box">
        I independently completed the degradation evaluation protocol design, fixed degraded validation set construction, M0-M3 robustness training modules, baseline comparison experiments, module-combination ablation studies, and error-sample/high-confidence misclassification analysis. The baseline achieves 0.7800 Clean Top-1 and 0.3910 Degraded Top-1, with a Top-1 Drop of 0.3890. After introducing degradation augmentation, AugMix, Mixup/CutMix, and EMA, Degraded Top-1 improves to 0.6910 and Top-1 Drop decreases to 0.0761.
      </div>
    </details>
  </div>
</div>

<div class="home-section" id="awards">
  <div class="home-title" data-icon="🏆">Awards</div>

  <div class="award-grid">
    <div class="award-card">
      <div class="award-name">National Second Prize</div>
      <div class="award-meta">
        China Undergraduate Mathematical Contest in Modeling<br>
        2024 | Team Leader, Programming & Modeling
      </div>

      <details class="cert-details">
        <summary>View Certificate</summary>
        <img class="cert-img" src="/images/awards/cumcm-2024-national-second.jpg" alt="CUMCM 2024 National Second Prize Certificate">
      </details>
    </div>

    <div class="award-card">
      <div class="award-name">National Third Prize</div>
      <div class="award-meta">
        International Mathematical Contest in Modeling<br>
        2025 | Team Leader, Programming & Modeling
      </div>

      <details class="cert-details">
        <summary>View Certificate</summary>
        <img class="cert-img" src="/images/awards/mcm-2025-national-third.jpg" alt="MCM 2025 National Third Prize Certificate">
      </details>
    </div>

    <div class="award-card">
      <div class="award-name">National Third Prize</div>
      <div class="award-meta">
        Belt and Road & BRICS Skills Development and Technology Innovation Competition<br>
        2025 | Programming Contributor
      </div>

      <details class="cert-details">
        <summary>View Certificate</summary>
        <img class="cert-img" src="/images/awards/brics-2025-national-third.jpg" alt="BRICS 2025 National Third Prize Certificate">
      </details>
    </div>

    <div class="award-card">
      <div class="award-name">Provincial First Prize</div>
      <div class="award-meta">
        China Undergraduate Mathematical Contest in Modeling<br>
        2025 | Team Leader, Programming & Modeling
      </div>

      <details class="cert-details">
        <summary>View Certificate</summary>
        <img class="cert-img" src="/images/awards/cumcm-2025-provincial-first.jpg" alt="CUMCM 2025 Provincial First Prize Certificate">
      </details>
    </div>

    <div class="award-card">
      <div class="award-name">Provincial Second Prize</div>
      <div class="award-meta">
        Henan Provincial College Student Mathematics Competition<br>
        2024
      </div>

      <details class="cert-details">
        <summary>View Certificate</summary>
        <img class="cert-img" src="/images/awards/henan-math-2024-second.jpg" alt="Henan Mathematics Competition 2024 Second Prize Certificate">
      </details>
    </div>
  </div>
</div>
