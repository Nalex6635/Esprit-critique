# Esprit-critique
Algo esprit critique
# Esprit-critique (Alternative-Mind)

A browser extension concept designed to break algorithmic filter bubbles and echo chambers using AI.

---

## 🌍 Project Overview (English)

### 🎯 The Problem
Recommendation algorithms (especially on YouTube and social media) tend to trap users in "filter bubbles". If a user starts watching videos about a specific bias or conspiracy theory (e.g., "Flat Earth"), the algorithm continuously feeds them similar content, leading to a loss of critical thinking and cognitive diversity.

### 💡 The Solution
A browser extension that acts as an "intellectual antidote". It analyzes what you are currently watching and suggests high-quality, opposing viewpoints or debunking content in real-time.

### 🛠️ Technical Scope (MVP)
- **Architecture:** Manifest V3 extension leveraging the native `sidePanel` API to avoid breaking when platforms update their DOM.
- **Workflow:**
  1. Detect the current YouTube video and extract its title/context.
  2. Use an **AI/LLM** (via Cloud API or a local LLM runner like Ollama) to identify the core bias or topic.
  3. Generate counter-arguments or opposing search queries.
  4. Fetch and display 3-4 alternative video/article links inside the side panel.

### 🚀 Looking for Contributors
I am looking for experienced developers to help build this open-source project. Specifically, we need expertise in:
- Modern Browser Extension development (JavaScript/TypeScript).
- AI/LLM integration (Prompt engineering, API handling, or Local LLM integration like WebGPU/Ollama).
- Privacy-first data fetching.

If you are interested in building a tool for digital sovereignty and critical thinking, please leave a comment in the Issues or reach out!

---

## 🇫🇷 Présentation du Projet (Français)

### 🎯 Objectif
Lutter contre l'enfermement intellectuel et les chambres d'écho générés par les algorithmes de recommandation. L'extension doit proposer du contenu en opposition sémantique ou factuelle avec ce que l'utilisateur est en train de regarder (ex: si l'utilisateur regarde une vidéo complotiste sur la Terre Plate, l'extension lui suggère des contenus scientifiques et de zététique sur la Terre Ronde dans un panneau latéral).

### 🛠️ Approche Technique
* **Format :** Extension Manifest V3 utilisant l'API `sidePanel` pour une stabilité maximale.
* **Logique IA :** Analyse sémantique du contexte (titre/tags) via LLM pour générer des requêtes de contradiction constructives. Souveraineté numérique et respect de la vie privée privilégiés (option locale recherchée).

---
