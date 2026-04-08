---
title: "LogicVerse"
excerpt: "A modular LLM agent framework with dependency injection, Meta-Agent routing, and hot-pluggable skill ecosystem.<br/>"
collection: portfolio
---

[GitHub Repository](https://github.com/LeoYANQING/LogicVerse)

LogicVerse is a lightweight, highly decoupled LLM agent framework featuring:
- **Multi-Source Config**: `.env`, YAML, and Python dict chain injection
- **Dynamic Factory**: `LLMFactory` dynamically produces OpenAI-compatible model drivers (DeepSeek, Qwen, Ollama, vLLM)
- **Meta-Agent Routing**: Auto-dispatches tasks to Direct, Plan, or ReAct paradigms based on complexity
- **DLC-style Skill Ecosystem**: Hot-loadable skill packages via `SKILL.md` declarations and independent scripts
