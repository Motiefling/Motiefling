# Portia Hamid

Aspiring ML engineer with a focus on interpretability and AI safety.  
B.S. Computer Science, UT Dallas (2026)  
Incoming M.S. in Artificial Intelligence, UT Austin (Fall 2026)  

I'm interested in understanding *why* models behave the way they do, not just whether they perform well.  

## Projects

### [Docrot Detector](https://github.com/Motiefling/Docrot-Detector)
[See it in action.](https://docrot-detector.web.app/)  
[See the frontend repo.](https://github.com/marieliske/CS4485_Capstone_Frontend)  
  
Senior capstone project. An AST-based documentation rot detector that flags when code changes have likely made existing documentation stale. Parses Python source into semantic fingerprints per function, scores changes by impact (control flow, side effects, API signature, exceptions), maps changes to affected docs, and automates the whole flow as a GitHub Action with optional LLM-generated fix suggestions.

- AST parsing and semantic fingerprinting (`ast_parser.py`, `fingerprint.py`)
- Change scoring and doc-mapping pipeline (`comparator.py`, `alerts.py`)
- CI integration via GitHub Actions, with results persisted to Firebase/Firestore
- Optional AI-assisted documentation suggestions (Groq/Anthropic/OpenAI)

### [Read Aloud](https://github.com/Motiefling/read-aloud)
A local-first audiobook pipeline.  
Scrapes source text, translates with a local LLM, and generates narrated audio, all served through a self-hosted API and PWA.  

- Translation via Qwen-2.5 7B Instruct (HuggingFace Transformers) with a rule-based fallback for missed text.
- TTS via Kokoro, with configurable voices and a user-managed find/replace system for pronounciation fixes.
- Full asynchronous pipeline orchestration with FastAPI + Celery + Redis, including real-time progress over WebSockets.
- PWA frontend with offline support via Service Worker.

## Background

13+ years of professional experience prior to this transition, including data review/QA and instructional work, shaping how I approach correctness, edge cases, and clear documentation in technical work now.

## Currently

Looking for full-time, part-time, or internship roles in ML/AI engineering or research-adjacent work.

<!--
**Motiefling/Motiefling** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
