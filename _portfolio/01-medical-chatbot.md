---
title: "Medical RAG Chatbot"
excerpt: "Intelligent medical Q&A system for imaging centers with triangular LLM supervision achieving ~99% accuracy.<br/>"
collection: portfolio
---

Developed during internship at Tab Next Limited (2025.05 - 2025.09).

Built an intelligent medical chatbot for imaging centers using Qwen 2, FastAPI, and Docker. The system features:
- RAG-based retrieval for medical knowledge
- Multi-turn dialogue management
- A novel **triangular LLM supervision architecture**: since the end-to-end workflow required every step to be correct (90%^5 = 59% accuracy), we introduced a secondary LLM as a supervisory "bottom line" function, ultimately achieving ~99% accuracy.
