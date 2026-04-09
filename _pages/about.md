---
permalink: /
title: "Leo Sin"
layout: splash
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero">
  <div class="home-hero__content">
    <p class="home-hero__eyebrow">Leo Sin · 施延庆</p>
    <h1>Building 3D and multimodal systems for biomedical scenes.</h1>
    <p class="home-hero__lede">
      I am a visiting student in the Intelligent Spatial Medicine Lab at Westlake University. My work spans
      spatial omics, 3D perception, and multimodal medical AI, with a strong bias toward systems that can move
      from research prototypes into real workflows.
    </p>
    <div class="home-hero__actions">
      <a class="home-button home-button--primary" href="{{ '/publications/' | relative_url }}">View Research</a>
      <a class="home-button home-button--secondary" href="{{ '/cv/' | relative_url }}">Open Resume</a>
      <a class="home-button home-button--secondary" href="mailto:shiyanqing8@gmail.com">Email Me</a>
    </div>
    <div class="home-hero__meta">
      <span>Westlake University</span>
      <span>HKU M.Sc.</span>
      <span>Hangzhou, China</span>
    </div>
  </div>

  <div class="home-hero__figure">
    <div class="home-portrait-frame">
      <img src="{{ '/images/avatar_web.jpg' | relative_url }}" alt="Portrait of Leo Sin">
    </div>
    <div class="home-aside-card">
      <p class="home-aside-card__label">Current focus</p>
      <p>
        Virtual slice interpolation for spatial transcriptomics, multimodal agents for medical workflows,
        and 3D reconstruction pipelines for spatial intelligence.
      </p>
    </div>
  </div>
</section>

<nav class="home-section-nav" aria-label="Homepage sections">
  <a href="#about">About</a>
  <a href="#research">Research</a>
  <a href="#work">Selected Work</a>
  <a href="#writing">Writing</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about" class="landing-section">
  <div class="landing-section__header">
    <p class="landing-section__eyebrow">About</p>
    <h2>From robotics and physiological signals to spatial medicine.</h2>
    <p>
      I like research problems that sit between scientific depth and systems building. The common thread in my
      work is turning messy, multimodal data into models, tools, and interfaces that are actually useful.
    </p>
  </div>

  <div class="story-grid">
    <article class="surface-card prose-card">
      <p>
        At <strong>Westlake University</strong>, I work on <strong>3D cell atlas reconstruction for spatial omics</strong>,
        especially virtual slice interpolation between real tissue sections. Before that, at <strong>HKU</strong>
        I studied <strong>multimodal physiological modeling</strong> for blood pressure estimation, and during
        industry internships I built <strong>medical AI agents</strong> for real workflow settings.
      </p>
      <p>
        Earlier projects in continuum robotics, SLAM, and simulation still shape the way I think. Strong systems
        need to be grounded in sensing, geometry, data quality, and deployment constraints, not only benchmark
        numbers.
      </p>
      <p>
        I also enjoy technical writing and public communication. Across
        <a href="https://www.zhihu.com/people/--80-25-63-93">Zhihu</a> and
        <a href="https://www.xiaohongshu.com/user/profile/5f266c0b000000000100159b">Xiaohongshu</a>, I currently
        have around <strong>130 followers</strong> and more than <strong>18,000 total reads</strong>, mostly around
        AI systems, agent engineering, and research workflows.
      </p>
    </article>

    <aside class="surface-card facts-card">
      <h3>Quick Facts</h3>
      <ul class="facts-list">
        <li>
          <span class="facts-list__label">Current role</span>
          <span>Visiting Student, Intelligent Spatial Medicine Lab, Westlake University</span>
        </li>
        <li>
          <span class="facts-list__label">Education</span>
          <span>M.Sc. in Computer Engineering, The University of Hong Kong</span>
        </li>
        <li>
          <span class="facts-list__label">Background</span>
          <span>B.S. in Electrical Engineering and Automation, Soochow University</span>
        </li>
        <li>
          <span class="facts-list__label">Research areas</span>
          <span>Spatial Omics, 3D Reconstruction, Medical AI, Embodied Systems</span>
        </li>
        <li>
          <span class="facts-list__label">Online writing</span>
          <span>AI workflow notes, technical blogs, and applied systems summaries</span>
        </li>
      </ul>
    </aside>
  </div>
</section>

<section id="research" class="landing-section">
  <div class="landing-section__header">
    <p class="landing-section__eyebrow">Research</p>
    <h2>Directions I am actively building toward.</h2>
    <p>
      The current portfolio sits around biomedical imaging, multimodal foundation models, and embodied system
      design. I care about methods that can survive noisy inputs, real operators, and long pipelines.
    </p>
  </div>

  <div class="focus-grid">
    <article class="surface-card focus-card">
      <h3>Spatial Omics and 3D Cell Atlas Reconstruction</h3>
      <p>
        Reconstructing 3D tissue structure from sparse 2D sections, with emphasis on virtual slice interpolation,
        Xenium-scale data integration, and image-to-omics alignment.
      </p>
    </article>

    <article class="surface-card focus-card">
      <h3>3D Perception for Surgical and Biomedical Scenes</h3>
      <p>
        NeRF and 3DGS style reconstruction for challenging scenes with reflections, occlusions, dynamic tissue,
        and complex lighting conditions.
      </p>
    </article>

    <article class="surface-card focus-card">
      <h3>Multimodal Medical AI Systems</h3>
      <p>
        Agent workflows, RAG pipelines, multimodal understanding, and physiological signal modeling for medical
        settings where reliability matters.
      </p>
    </article>

    <article class="surface-card focus-card">
      <h3>Interactive and Embodied Intelligence</h3>
      <p>
        Question-asking robots, digital twins, and simulation-ready environments that connect language, planning,
        sensing, and deployment.
      </p>
    </article>
  </div>
</section>

<section id="work" class="landing-section">
  <div class="landing-section__header">
    <p class="landing-section__eyebrow">Selected Work</p>
    <h2>Research and engineering projects with real constraints.</h2>
    <p>
      A few representative projects across spatial medicine, multimodal agents, human-robot interaction, and
      simulation systems. The full archive lives on the <a href="{{ '/portfolio/' | relative_url }}">projects page</a>.
    </p>
  </div>

  <div class="work-grid">
    <article class="surface-card work-card">
      <img src="{{ '/images/projects/spatial_omics_3d.png' | relative_url }}" alt="Spatial omics 3D reconstruction project">
      <div class="work-card__body">
        <p class="work-card__meta">Westlake University · 2025.02 - present</p>
        <h3>Spatial Omics - 3D Cell Atlas Reconstruction</h3>
        <p>
          Building virtual intermediate tissue slices between real sections to support 3D reconstruction for
          spatial transcriptomics.
        </p>
        <div class="tag-list">
          <span>Spatial Omics</span>
          <span>3D Reconstruction</span>
          <span>Xenium</span>
          <span>AnnData</span>
        </div>
        <a class="inline-link" href="{{ '/portfolio/01-spatial-omics/' | relative_url }}">Read more</a>
      </div>
    </article>

    <article class="surface-card work-card">
      <img src="{{ '/images/projects/s20_2_tabnext_arch.png' | relative_url }}" alt="Medical RAG chatbot architecture">
      <div class="work-card__body">
        <p class="work-card__meta">Tab Next (HK) · 2025.06 - 2025.09</p>
        <h3>Medical RAG Chatbot for an Imaging Center</h3>
        <p>
          Built a ReAct-style medical assistant with tool calling, FAISS retrieval, LoRA fine-tuning, and
          multimodal WhatsApp processing.
        </p>
        <div class="tag-list">
          <span>LLM Agent</span>
          <span>RAG</span>
          <span>LoRA</span>
          <span>vLLM</span>
        </div>
        <a class="inline-link" href="{{ '/portfolio/01-medical-chatbot/' | relative_url }}">Read more</a>
      </div>
    </article>

    <article class="surface-card work-card">
      <img src="{{ '/images/projects/s9_0_surgical_defibrillator.png' | relative_url }}" alt="AskThenRearrange robot project">
      <div class="work-card__body">
        <p class="work-card__meta">Tongji University CDI · 2025.12 - 2026.03</p>
        <h3>AskThenRearrange - Robot Questioning Strategy</h3>
        <p>
          Studied how robots should ask questions under different household task settings, then deployed the
          strategy on a Unitree humanoid platform.
        </p>
        <div class="tag-list">
          <span>Embodied AI</span>
          <span>HRI</span>
          <span>LLM</span>
          <span>Unitree</span>
        </div>
        <a class="inline-link" href="{{ '/portfolio/03-askthenrearrange/' | relative_url }}">Read more</a>
      </div>
    </article>

    <article class="surface-card work-card">
      <img src="{{ '/images/projects/s8_1_surgical_3d.jpg' | relative_url }}" alt="3DGS digital twin project">
      <div class="work-card__body">
        <p class="work-card__meta">Independent Project · 2025.10 - present</p>
        <h3>3DGS Digital Twin for Autonomous Driving</h3>
        <p>
          Built an image-to-COLMAP-to-3DGS pipeline and connected it with CARLA and Autoware oriented simulation
          for digital twin experiments.
        </p>
        <div class="tag-list">
          <span>3DGS</span>
          <span>COLMAP</span>
          <span>CARLA</span>
          <span>Autoware</span>
        </div>
        <a class="inline-link" href="{{ '/portfolio/04-3dgs-digital-twin/' | relative_url }}">Read more</a>
      </div>
    </article>
  </div>
</section>

<section id="writing" class="landing-section">
  <div class="landing-section__header">
    <p class="landing-section__eyebrow">Writing</p>
    <h2>Technical communication is part of the research workflow.</h2>
    <p>
      I use public writing to sharpen ideas, document reproducible workflows, and translate engineering details
      into something other people can actually reuse.
    </p>
  </div>

  <div class="dual-grid">
    <article class="surface-card">
      <h3>Tech Writing and Outreach</h3>
      <p>
        Recent posts focus on practical AI systems, agent engineering, research tooling, and workflow design.
        One representative article is
        <a href="https://zhuanlan.zhihu.com/p/2023172833434502245"><em>AI Workflow Pipeline</em></a>, where I summarize
        how to structure multi-stage AI workflows for real development settings.
      </p>
      <div class="link-row">
        <a class="home-button home-button--secondary" href="https://www.zhihu.com/people/--80-25-63-93">Zhihu</a>
        <a class="home-button home-button--secondary" href="https://www.xiaohongshu.com/user/profile/5f266c0b000000000100159b">Xiaohongshu</a>
      </div>
    </article>

    <article class="surface-card">
      <h3>Research and Publications</h3>
      <p>
        My publications page is being built out as projects mature into papers. Right now the emphasis is on
        ongoing work in spatial omics, multimodal medical AI, and interactive robot learning.
      </p>
      <p>
        I keep the research overview updated on the
        <a href="{{ '/publications/' | relative_url }}">research page</a>, and I use the homepage to surface the
        most active threads rather than an empty publication list.
      </p>
    </article>
  </div>
</section>

<section id="news" class="landing-section">
  <div class="landing-section__header">
    <p class="landing-section__eyebrow">News</p>
    <h2>A compact timeline of recent steps.</h2>
    <p>Short updates on research, internships, prototypes, and the systems I am building right now.</p>
  </div>

  <div class="surface-card">
    <ul class="timeline-list">
      <li><strong>2026.02</strong> Joined Westlake University as a visiting student.</li>
      <li><strong>2026.01</strong> Built <em>Maze Mask</em> at Global Game Jam 2026.</li>
      <li><strong>2025.12</strong> Started a research internship at Tongji University CDI on robot questioning strategies.</li>
      <li><strong>2025.10</strong> Began a 3DGS digital twin pipeline for CARLA and Autoware experiments.</li>
      <li><strong>2025.06</strong> Joined Tab Next (HK) as an algorithm engineer intern for a medical AI chatbot.</li>
    </ul>
  </div>
</section>

<section id="contact" class="landing-section landing-section--compact">
  <div class="contact-banner">
    <div>
      <p class="landing-section__eyebrow">Contact</p>
      <h2>Interested in spatial medicine, multimodal systems, or research engineering?</h2>
      <p>
        I am happy to talk about collaborations, research directions, and ambitious systems problems that need both
        engineering discipline and experimental curiosity.
      </p>
    </div>
    <div class="contact-links">
      <a class="home-button home-button--primary" href="mailto:shiyanqing8@gmail.com">shiyanqing8@gmail.com</a>
      <a class="home-button home-button--secondary" href="https://github.com/LeoYANQING">GitHub</a>
      <a class="home-button home-button--secondary" href="{{ '/cv/' | relative_url }}">Resume</a>
    </div>
  </div>
</section>
