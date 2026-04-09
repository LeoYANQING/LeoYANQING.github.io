---
permalink: /
title: "Leo Sin"
layout: splash
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<div class="home-progress" aria-hidden="true">
  <span class="home-progress__bar"></span>
</div>

<section class="home-hero">
  <div class="home-shell home-hero__grid">
    <div class="home-hero__copy" data-reveal>
      <p class="home-hero__eyebrow">Leo Sin · 施延庆</p>
      <h1>Spatial medicine, 3D intelligence, and multimodal AI.</h1>
      <p class="home-hero__subtitle">Spatial Medicine × 3D Intelligence × Multimodal AI</p>
      <p class="home-hero__identity">
        <span>Visiting Student @ Westlake University</span>
        <span>M.S. in HKU</span>
      </p>
      <p class="home-hero__lede">
        Building 3D reconstruction pipelines for spatial omics and medical AI systems, with research interests
        spanning biomedical perception, multimodal agents, and embodied intelligence.
      </p>
      <div class="home-hero__actions">
        <a class="home-button home-button--primary" href="{{ '/publications/' | relative_url }}">View Research</a>
        <a class="home-button home-button--secondary" href="{{ '/cv/' | relative_url }}">Download Resume</a>
        <a class="home-button home-button--secondary" href="mailto:shiyanqing8@gmail.com">Contact Me</a>
      </div>
    </div>

    <div class="home-hero__visual" data-reveal>
      <div class="home-portrait">
        <img src="{{ '/images/profile.png' | relative_url }}" alt="Portrait of Leo Sin">
      </div>
      <div class="home-hero__note">
        <span class="home-hero__note-label">Current Focus</span>
        <p>
          Virtual slice interpolation for spatial transcriptomics, multimodal medical workflows, and 3D scene
          understanding for biomedical intelligence.
        </p>
      </div>
    </div>
  </div>

  <div class="home-shell home-hero__stats">
    <article class="hero-stat" data-reveal>
      <span class="hero-stat__label">Research Themes</span>
      <strong>Spatial Omics, 3D Reconstruction, Medical AI</strong>
    </article>
    <article class="hero-stat" data-reveal>
      <span class="hero-stat__label">Academic Path</span>
      <strong>Westlake University, HKU, Soochow University</strong>
    </article>
    <article class="hero-stat" data-reveal>
      <span class="hero-stat__label">Public Writing</span>
      <strong>130+ followers and 18,000+ reads across platforms</strong>
    </article>
  </div>
</section>

<nav class="home-section-nav" aria-label="Homepage sections" data-reveal>
  <a href="#about">About</a>
  <a href="#research">Research</a>
  <a href="#work">Projects</a>
  <a href="#writing">Writing</a>
  <a href="#news">Updates</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about" class="landing-section">
  <div class="landing-section__header" data-reveal>
    <p class="landing-section__eyebrow">About Me</p>
    <h2>From robotics to spatial medicine.</h2>
    <p>
      My work sits at the intersection of scientific modeling and systems engineering. I care about turning noisy,
      multimodal biomedical data into models, tools, and interfaces that remain useful outside the demo stage.
    </p>
  </div>

  <div class="about-grid">
    <article class="surface-card feature-card feature-card--blue" data-reveal>
      <span class="feature-card__icon"><i class="fa-solid fa-microscope" aria-hidden="true"></i></span>
      <h3>Current Research</h3>
      <ul class="feature-list">
        <li>Virtual slice interpolation for spatial transcriptomics</li>
        <li>Multimodal medical AI agents and workflow systems</li>
        <li>3D reconstruction for surgical and biomedical scenes</li>
      </ul>
    </article>

    <article class="surface-card feature-card feature-card--green" data-reveal>
      <span class="feature-card__icon"><i class="fa-solid fa-graduation-cap" aria-hidden="true"></i></span>
      <h3>Academic Journey</h3>
      <ul class="feature-list">
        <li>Westlake University, Intelligent Spatial Medicine Lab</li>
        <li>The University of Hong Kong, M.S. in Computer Engineering</li>
        <li>Soochow University, B.S. in EE and Automation</li>
      </ul>
    </article>

    <article class="surface-card feature-card feature-card--purple" data-reveal>
      <span class="feature-card__icon"><i class="fa-solid fa-pen-nib" aria-hidden="true"></i></span>
      <h3>Public Writing</h3>
      <ul class="feature-list">
        <li>130+ followers across Zhihu and Xiaohongshu</li>
        <li>18,000+ total reads on AI systems and workflows</li>
        <li>Topics include agents, tooling, and research engineering</li>
      </ul>
    </article>
  </div>
</section>

<section id="research" class="landing-section">
  <div class="landing-section__header" data-reveal>
    <p class="landing-section__eyebrow">Research</p>
    <h2>Four directions shaping the work.</h2>
    <p>
      These themes define the research and engineering problems I keep returning to: geometry, sensing, multimodal
      understanding, and deployment-aware system design.
    </p>
  </div>

  <div class="research-grid">
    <article class="surface-card research-card" data-reveal>
      <img loading="lazy" src="{{ '/images/projects/spatial_omics_3d.png' | relative_url }}" alt="Spatial omics reconstruction visualization">
      <div class="research-card__body">
        <h3>Spatial Omics and 3D Cell Atlas</h3>
        <p>
          Reconstructing tissue structure from sparse slices with virtual interpolation, Xenium-scale alignment,
          and image-to-omics modeling.
        </p>
        <div class="tag-list">
          <span>Xenium</span>
          <span>AnnData</span>
          <span>3D Reconstruction</span>
        </div>
        <a class="inline-link" href="{{ '/portfolio/01-spatial-omics/' | relative_url }}">Read More</a>
      </div>
    </article>

    <article class="surface-card research-card" data-reveal>
      <img loading="lazy" src="{{ '/images/projects/s8_1_surgical_3d.jpg' | relative_url }}" alt="3D perception for medical scenes">
      <div class="research-card__body">
        <h3>3D Perception for Medical Scenes</h3>
        <p>
          NeRF and 3DGS style methods for dynamic tissue, occlusion, reflections, and other hard conditions found
          in surgical environments.
        </p>
        <div class="tag-list">
          <span>NeRF</span>
          <span>3DGS</span>
          <span>Surgical Vision</span>
        </div>
        <a class="inline-link" href="{{ '/publications/' | relative_url }}">Read More</a>
      </div>
    </article>

    <article class="surface-card research-card" data-reveal>
      <img loading="lazy" src="{{ '/images/projects/s20_2_tabnext_arch.png' | relative_url }}" alt="Multimodal medical AI workflow diagram">
      <div class="research-card__body">
        <h3>Multimodal Medical AI</h3>
        <p>
          Agentic workflows, multimodal understanding, and deployment-ready medical assistants that combine RAG,
          tool use, and practical interface design.
        </p>
        <div class="tag-list">
          <span>RAG</span>
          <span>LLM</span>
          <span>Multimodal Fusion</span>
        </div>
        <a class="inline-link" href="{{ '/portfolio/01-medical-chatbot/' | relative_url }}">Read More</a>
      </div>
    </article>

    <article class="surface-card research-card" data-reveal>
      <img loading="lazy" src="{{ '/images/projects/s7_2_continuum_slam.png' | relative_url }}" alt="Embodied intelligence and robot interaction project">
      <div class="research-card__body">
        <h3>Embodied Intelligence</h3>
        <p>
          Human-robot interaction, questioning strategies, simulation environments, and digital twin systems that
          connect planning, sensing, and learning.
        </p>
        <div class="tag-list">
          <span>HRI</span>
          <span>Digital Twin</span>
          <span>Simulation</span>
        </div>
        <a class="inline-link" href="{{ '/portfolio/03-askthenrearrange/' | relative_url }}">Read More</a>
      </div>
    </article>
  </div>
</section>

<section id="work" class="landing-section">
  <div class="landing-section__header" data-reveal>
    <p class="landing-section__eyebrow">Selected Projects</p>
    <h2>A timeline of research and engineering builds.</h2>
    <p>
      Representative projects across spatial omics, multimodal assistants, embodied interaction, and simulation.
      Each one reflects a different constraint: data quality, deployment speed, or system complexity.
    </p>
  </div>

  <div class="project-timeline">
    <article class="timeline-project" data-reveal>
      <div class="timeline-project__year">2025.02</div>
      <div class="timeline-project__marker"></div>
      <div class="timeline-project__card surface-card">
        <img loading="lazy" src="{{ '/images/projects/spatial_omics_3d.png' | relative_url }}" alt="Spatial Omics 3D Reconstruction project">
        <div class="timeline-project__content">
          <p class="timeline-project__meta">Westlake University · Visiting Student</p>
          <h3>Spatial Omics 3D Reconstruction</h3>
          <p>
            Building virtual intermediate tissue slices between real sections to support 3D cell atlas
            reconstruction for spatial transcriptomics.
          </p>
          <div class="tag-list">
            <span>Spatial Omics</span>
            <span>Interpolation</span>
            <span>Xenium</span>
          </div>
          <a class="inline-link" href="{{ '/portfolio/01-spatial-omics/' | relative_url }}">View Details</a>
        </div>
      </div>
    </article>

    <article class="timeline-project" data-reveal>
      <div class="timeline-project__year">2025.06</div>
      <div class="timeline-project__marker"></div>
      <div class="timeline-project__card surface-card">
        <img loading="lazy" src="{{ '/images/projects/s20_2_tabnext_arch.png' | relative_url }}" alt="Medical RAG chatbot project">
        <div class="timeline-project__content">
          <p class="timeline-project__meta">Tab Next (HK) · Algorithm Engineer Intern</p>
          <h3>Medical RAG Chatbot</h3>
          <p>
            A ReAct-style assistant for an imaging center with retrieval, multimodal WhatsApp processing, and
            production-minded workflow automation.
          </p>
          <div class="tag-list">
            <span>ReAct</span>
            <span>LoRA</span>
            <span>vLLM</span>
          </div>
          <a class="inline-link" href="{{ '/portfolio/01-medical-chatbot/' | relative_url }}">View Details</a>
        </div>
      </div>
    </article>

    <article class="timeline-project" data-reveal>
      <div class="timeline-project__year">2025.12</div>
      <div class="timeline-project__marker"></div>
      <div class="timeline-project__card surface-card">
        <img loading="lazy" src="{{ '/images/projects/s9_0_surgical_defibrillator.png' | relative_url }}" alt="AskThenRearrange robot questioning project">
        <div class="timeline-project__content">
          <p class="timeline-project__meta">Tongji University CDI · Research Intern</p>
          <h3>AskThenRearrange Robot</h3>
          <p>
            Designing robot questioning strategies from real dialogue behavior and deploying the resulting policy
            on a Unitree humanoid platform.
          </p>
          <div class="tag-list">
            <span>Embodied AI</span>
            <span>HRI</span>
            <span>Unitree</span>
          </div>
          <a class="inline-link" href="{{ '/portfolio/03-askthenrearrange/' | relative_url }}">View Details</a>
        </div>
      </div>
    </article>

    <article class="timeline-project" data-reveal>
      <div class="timeline-project__year">2025.10</div>
      <div class="timeline-project__marker"></div>
      <div class="timeline-project__card surface-card">
        <img loading="lazy" src="{{ '/images/projects/s8_1_surgical_3d.jpg' | relative_url }}" alt="3DGS Digital Twin project">
        <div class="timeline-project__content">
          <p class="timeline-project__meta">Independent Project · Ongoing</p>
          <h3>3DGS Digital Twin</h3>
          <p>
            An image-to-COLMAP-to-3DGS pipeline connected to CARLA and Autoware-style simulation for digital twin
            experiments in complex scenes.
          </p>
          <div class="tag-list">
            <span>3DGS</span>
            <span>COLMAP</span>
            <span>CARLA</span>
          </div>
          <a class="inline-link" href="{{ '/portfolio/04-3dgs-digital-twin/' | relative_url }}">View Details</a>
        </div>
      </div>
    </article>
  </div>
</section>

<section id="writing" class="landing-section">
  <div class="landing-section__header" data-reveal>
    <p class="landing-section__eyebrow">Writing and Publications</p>
    <h2>Public communication and academic work in parallel.</h2>
    <p>
      I treat writing as part of the research workflow: documenting systems, clarifying methods, and making
      practical lessons reusable for other builders.
    </p>
  </div>

  <div class="writing-grid">
    <article class="surface-card split-panel" data-reveal>
      <span class="split-panel__icon"><i class="fa-solid fa-feather-pointed" aria-hidden="true"></i></span>
      <h3>Public Writing</h3>
      <p>
        I share applied notes on AI systems, agent engineering, and workflow design. A representative article is
        <a href="https://zhuanlan.zhihu.com/p/2023172833434502245"><em>AI Workflow Pipeline</em></a>.
      </p>
      <div class="link-row">
        <a class="home-button home-button--secondary" href="https://www.zhihu.com/people/--80-25-63-93">Visit Zhihu</a>
        <a class="home-button home-button--secondary" href="https://www.xiaohongshu.com/user/profile/5f266c0b000000000100159b">Visit Xiaohongshu</a>
      </div>
    </article>

    <article class="surface-card split-panel" data-reveal>
      <span class="split-panel__icon"><i class="fa-solid fa-book-open-reader" aria-hidden="true"></i></span>
      <h3>Academic Work</h3>
      <p>
        Publications are being built as projects mature. The current focus is spatial omics, medical AI, and
        interactive robot learning with strong systems constraints.
      </p>
      <div class="link-row">
        <a class="home-button home-button--primary" href="{{ '/publications/' | relative_url }}">View Research Page</a>
      </div>
    </article>
  </div>
</section>

<section id="news" class="landing-section">
  <div class="landing-section__header" data-reveal>
    <p class="landing-section__eyebrow">Recent Updates</p>
    <h2>A compact timeline of recent work.</h2>
    <p>Selected milestones across research, internships, prototypes, and system building.</p>
  </div>

  <div class="surface-card updates-card" data-reveal>
    <ul class="updates-list">
      <li><span class="updates-list__date">2026.02</span><span class="updates-list__text">Joined Westlake University as a visiting student.</span></li>
      <li><span class="updates-list__date">2026.01</span><span class="updates-list__text">Built Maze Mask at Global Game Jam 2026.</span></li>
      <li><span class="updates-list__date">2025.12</span><span class="updates-list__text">Started a research internship at Tongji CDI.</span></li>
      <li><span class="updates-list__date">2025.10</span><span class="updates-list__text">Began a 3DGS digital twin pipeline for CARLA and Autoware experiments.</span></li>
      <li><span class="updates-list__date">2025.06</span><span class="updates-list__text">Joined Tab Next (HK) as an algorithm engineer intern.</span></li>
    </ul>
  </div>
</section>

<section id="contact" class="landing-section landing-section--compact">
  <div class="contact-panel surface-card" data-reveal>
    <div class="contact-panel__intro">
      <p class="landing-section__eyebrow">Let's Connect</p>
      <h2>Open to collaborations and ambitious problems.</h2>
      <p>
        Interested in spatial medicine, multimodal systems, or research engineering? I am always happy to discuss
        collaborations, system design, and difficult research problems with practical impact.
      </p>
    </div>

    <div class="contact-grid">
      <a class="contact-card" href="mailto:shiyanqing8@gmail.com">
        <i class="fa-solid fa-envelope" aria-hidden="true"></i>
        <span>Email</span>
      </a>
      <a class="contact-card" href="https://github.com/LeoYANQING">
        <i class="fa-brands fa-github" aria-hidden="true"></i>
        <span>GitHub</span>
      </a>
      <a class="contact-card" href="{{ '/cv/' | relative_url }}">
        <i class="fa-solid fa-file-lines" aria-hidden="true"></i>
        <span>Resume</span>
      </a>
      <a class="contact-card" href="{{ '/publications/' | relative_url }}">
        <i class="fa-solid fa-flask" aria-hidden="true"></i>
        <span>Research</span>
      </a>
    </div>
  </div>
</section>

<script>
(() => {
  const boot = () => {
    const revealItems = Array.from(document.querySelectorAll("[data-reveal]"));
    revealItems.forEach((item) => item.classList.add("reveal-ready"));

    if ("IntersectionObserver" in window) {
      const observer = new IntersectionObserver((entries) => {
        entries.forEach((entry) => {
          if (!entry.isIntersecting) {
            return;
          }
          entry.target.classList.add("is-visible");
          observer.unobserve(entry.target);
        });
      }, {
        threshold: 0.14,
        rootMargin: "0px 0px -48px 0px"
      });

      revealItems.forEach((item) => observer.observe(item));
    } else {
      revealItems.forEach((item) => item.classList.add("is-visible"));
    }

    const progressBar = document.querySelector(".home-progress__bar");
    if (!progressBar) {
      return;
    }

    const updateProgress = () => {
      const maxScroll = document.documentElement.scrollHeight - window.innerHeight;
      const ratio = maxScroll > 0 ? window.scrollY / maxScroll : 0;
      progressBar.style.transform = `scaleX(${Math.min(Math.max(ratio, 0), 1)})`;
    };

    updateProgress();
    window.addEventListener("scroll", updateProgress, { passive: true });
    window.addEventListener("resize", updateProgress);
  };

  if (document.readyState === "loading") {
    document.addEventListener("DOMContentLoaded", boot, { once: true });
  } else {
    boot();
  }
})();
</script>
