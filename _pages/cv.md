---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science**, The University of Hong Kong, 2026 - present
* **M.Sc. in Computer Science**, The University of Hong Kong, 2024 - 2025
  * Supervisor: Prof. Grantham Pang
* **B.S. in Electrical Engineering and Automation**, Soochow University, 2020 - 2024
  * Supervisor: Prof. Lu Bo
  * GPA: 3.7/4.0

Work & Research Experience
======
* **Research Assistant**, Tongji CDI, 2025.12 - 2026.01
* **Software Engineer (Intern)**, Tab Next Limited, Hong Kong, 2025.05 - 2025.09
  * Developed medical AI chatbot system for imaging centers
  * Designed triangular LLM supervision architecture (~99% accuracy)
* **Research Assistant**, HKU EEE, 2025.01 - 2025.06
  * Multimodal blood pressure estimation from PPG and ECG signals (UAT-NET)

Research Interests
======
* 3D surgical scene reconstruction (NeRF, 3DGS)
* Multimodal medical AI
* LLM agent systems and RAG
* Spatial transcriptomics / computational biology
* Embodied intelligence

Skills
======
* **Languages**: Python, C++
* **Deep Learning**: PyTorch, TensorFlow/Keras
* **3D Vision**: NeRF, 3DGS, SLAM
* **LLM/Agent**: RAG, LangChain, Agent frameworks, MCP
* **Hardware**: STM32, Keil
* **Tools**: Docker, Git, Linux

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
