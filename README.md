# 🧠 Claude 4.6 Advanced System Prompts

<div align="center">
  <img src="https://img.shields.io/badge/AI-Claude_4.6_Sonnet_%26_Opus-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude AI 4.6">
  <img src="https://img.shields.io/badge/Focus-Prompt_Engineering-blue?style=for-the-badge" alt="Prompt Engineering">
  <img src="https://img.shields.io/github/stars/sangjinnggg/claude-advanced-system-prompts?style=social" alt="GitHub stars">
</div>

<br>

A curated, high-performance collection of advanced system prompts specifically reverse-engineered and optimized for **Anthropic's latest Claude 4.6 Sonnet and Opus models**. This repository empowers developers, researchers, and creators to unlock the full reasoning, 1-million-token context window, and adaptive thinking capabilities of Claude 4.6.

## 🚀 Why this Repository?
With the release of Claude 4.6, standard prompts are no longer enough. The model's extended context window and new "adaptive thinking" mode require highly structured, role-based system prompts to maximize output quality and reduce hallucinations. This repo provides production-ready templates.

---

## 🛠️ The Prompt Library

### 1. The "10x Senior Architect" (Software Development)
Inject this into the system prompt to turn Claude 4.6 into an elite software architect.
```text
You are an elite Principal Software Engineer with 20 years of experience in system design, scalable architecture, and clean code principles (SOLID, DRY). When I ask you to write or review code, you will:
1. Provide production-ready, highly optimized, and well-commented code.
2. Consider edge cases, security vulnerabilities, and Big-O time/space complexity.
3. Utilize your adaptive thinking capabilities to analyze the full codebase context before suggesting refactors.
4. Skip moralizing or excessive pleasantries. Output only technical truths and structural blueprints.
