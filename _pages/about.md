---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi! I'm **Leo Sin (施延庆)**.

I am a visiting student at [Westlake University](https://www.westlake.edu.cn/), Intelligent Spatial Medicine Lab, supervised by [Prof. Haoyang Li](https://www.westlake.edu.cn/). I received my M.Sc. in Computer Engineering from [The University of Hong Kong](https://www.hku.hk/) (supervised by [Prof. Grantham Pang](https://www.eee.hku.hk/~gpang/)) and my B.S. in Electrical Engineering from [Soochow University](http://www.suda.edu.cn/) (supervised by Prof. Lu Bo).

My research focuses on **3D perception for surgical and biomedical scenes**, **spatial omics**, and **multimodal AI**. I am particularly interested in applying generative AI and 3D reconstruction (NeRF/3DGS) to medical imaging and spatial transcriptomics.

**Research Interests**: Spatial Omics, 3D Reconstruction (NeRF/3DGS), Surgical Scene Analysis, Multimodal Medical AI, Embodied Intelligence, LLM Agent Systems

<h2 class="section-title">News</h2>

<ul class="news-list">
  <li><strong>2026.02</strong> Joined Westlake University as visiting student.</li>
  <li><strong>2026.01</strong> Built <em>Maze Mask</em> at Global Game Jam 2026 — <a href="https://mask.colanns.me">mask.colanns.me</a></li>
  <li><strong>2025.12</strong> Started research internship at Tongji University CDI on robot questioning strategies.</li>
  <li><strong>2025.10</strong> Working on autonomous driving digital twin with 3DGS + CARLA/Autoware.</li>
  <li><strong>2025.06</strong> Joined Tab Next (HK) as algorithm engineer intern, developing medical AI chatbot.</li>
</ul>

<h2 class="section-title">Selected Projects</h2>

<div class="project-row">
  <div class="project-img">
    <img src="/images/projects/spatial_omics_3d.png" alt="Spatial Omics 3D Atlas">
  </div>
  <div class="project-text">
    <h3>Spatial Omics — 3D Cell Atlas Reconstruction</h3>
    <div class="project-meta">Westlake University · 2025.02 - present · Visiting Student</div>
    <p>Core research on 3D virtual slice interpolation for spatial transcriptomics. Synthesize virtual intermediate tissue slices between real 2D spatial transcriptomics sections to reconstruct 3D cell atlases. Working with Xenium sequencing data, H&E staining image to spatial omics mapping.</p>
    <div class="project-tags">
      <span>Spatial Omics</span>
      <span>3D Reconstruction</span>
      <span>Optimal Transport</span>
      <span>AnnData</span>
    </div>
  </div>
</div>

<div class="project-row">
  <div class="project-img">
    <img src="/images/projects/s20_2_tabnext_arch.png" alt="Medical Chatbot Architecture">
  </div>
  <div class="project-text">
    <h3>Medical RAG Chatbot — AI Agent for Imaging Center</h3>
    <div class="project-meta">Tab Next (HK) · 2025.06 - 2025.09 · Algorithm Engineer Intern</div>
    <p>Built ReAct agent-based medical chatbot for TST Imaging Center. Designed 7-tool architecture (business query, appointment, form analysis), CoT + FAISS retrieval, LoRA fine-tuning (SFT+DPO), vLLM acceleration (+70% performance), and Qwen2.5VL multimodal WhatsApp processing. CSAT on par with human agents, saving 20% labor.</p>
    <div class="project-tags">
      <span>LLM Agent</span>
      <span>RAG</span>
      <span>LoRA</span>
      <span>vLLM</span>
      <span>Qwen</span>
      <span>WhatsApp</span>
    </div>
  </div>
</div>

<div class="project-row">
  <div class="project-img">
    <img src="/images/projects/s9_0_surgical_defibrillator.png" alt="NeRF Surgical Scene">
  </div>
  <div class="project-text">
    <h3>AskThenRearrange — Robot Questioning Strategy via KCQ Encoding</h3>
    <div class="project-meta">Tongji University CDI · 2025.12 - 2026.03 · Research Intern · Supervisor: Prof. Guo Weiwei</div>
    <p>Designed robot questioning strategy planning based on KCQ encoding from real human dialogues. Conducted 24-group 1v1 user experiments comparing result-oriented vs. process-oriented tasks. Found process-oriented tasks better suit user-preference strategies. Deployed on Unitree humanoid robot.</p>
    <p><em>Paper: Task Matters: Investigating Human Questioning Behavior in Different Household Service for Learning by Asking Robots</em> (in progress)</p>
    <a href="https://github.com/LeoYANQING/AskThenRearrange" class="project-link">GitHub →</a>
    <a href="https://www.figma.com/slides/dSrHneAbChTG23glur6gLr/" class="project-link" style="margin-left:12px;">Figma Slides →</a>
    <div class="project-tags">
      <span>Embodied AI</span>
      <span>LLM</span>
      <span>HRI</span>
      <span>Unitree</span>
    </div>
  </div>
</div>

<div class="project-row">
  <div class="project-img">
    <img src="/images/projects/s8_1_surgical_3d.jpg" alt="3DGS Digital Twin">
  </div>
  <div class="project-text">
    <h3>Autonomous Driving Digital Twin — 3DGS + CARLA/Autoware</h3>
    <div class="project-meta">2025.10 - present</div>
    <p>Built Image → COLMAP → 3D Gaussian Splatting reconstruction pipeline with multi-view preprocessing and camera pose recovery. gsplat-based training with PSNR/SSIM/LPIPS evaluation. CARLA simulation with vehicle, pedestrian, camera, LiDAR, GNSS, IMU deployment. Exploring digital twin for Autoware co-simulation.</p>
    <div class="project-tags">
      <span>3DGS</span>
      <span>COLMAP</span>
      <span>CARLA</span>
      <span>Autoware</span>
      <span>Digital Twin</span>
    </div>
  </div>
</div>

<div class="project-row">
  <div class="project-img">
    <img src="/images/projects/s7_2_continuum_slam.png" alt="Continuum Robot Platform">
  </div>
  <div class="project-text">
    <h3>Continuum Robot for Intestinal Surgery + SLAM Navigation</h3>
    <div class="project-meta">Soochow University · 2021.09 - 2022.06 · Supervisor: Prof. Lu Bo</div>
    <p>Built 6-stepper-motor continuum robot for intestinal tract with FTL precision testing via Raspberry Pi + STM32. A* path planning algorithm burned into STM32. Extended with LiDAR SLAM + ROS for autonomous scene reconstruction and obstacle avoidance. CAD-designed chassis platform.</p>
    <div class="project-tags">
      <span>Surgical Robot</span>
      <span>STM32</span>
      <span>ROS</span>
      <span>SLAM</span>
      <span>Raspberry Pi</span>
    </div>
  </div>
</div>

<div class="project-row">
  <div class="project-img">
    <iframe src="//player.bilibili.com/player.html?bvid=BV1va6tBiEui&page=1&high_quality=1&danmaku=0" scrolling="no" frameborder="no" allowfullscreen="true"></iframe>
  </div>
  <div class="project-text">
    <h3>Maze Mask — Global Game Jam 2026</h3>
    <div class="project-meta">GGJ2026 · 2026.01.29 - 2026.01.31</div>
    <p>Multiplayer online pixel-art game: multiple thieves navigate pathways, collect coins, find exits and escape the maze. Masks grant different abilities with roguelike power-up elements. Responsible for map design, planning, and mask feature implementation.</p>
    <a href="https://mask.colanns.me" class="project-link">Play Online →</a>
    <a href="https://www.bilibili.com/video/BV1va6tBiEui/" class="project-link" style="margin-left:12px;">Bilibili →</a>
    <div class="project-tags">
      <span>React</span>
      <span>TypeScript</span>
      <span>Node.js</span>
      <span>Game Dev</span>
    </div>
  </div>
</div>

<div class="project-row">
  <div class="project-img">
    <img src="/images/projects/s12_0_bp_model.png" alt="UAT-NET Blood Pressure Model">
  </div>
  <div class="project-text">
    <h3>UAT-NET — Multimodal Blood Pressure Estimation</h3>
    <div class="project-meta">HKU · 2024.08 - 2025.06 · Supervisor: Prof. Grantham Pang</div>
    <p>Attention-based mechanism for blood pressure estimation from multimodal PPG and ECG signals. Reproduced and improved upon existing methods for reconstructing BP signals from physiological waveforms. Evaluated with MAE/RMSE on PulseDB dataset using 3× NVIDIA RTX 4090.</p>
    <div class="project-tags">
      <span>Deep Learning</span>
      <span>PPG</span>
      <span>ECG</span>
      <span>TensorFlow</span>
    </div>
  </div>
</div>
