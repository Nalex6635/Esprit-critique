# Esprit-critique (Alternative-Mind)

A browser extension concept designed to encourage cognitive diversity by suggesting opposing viewpoints using AI.

---

## 🌍 Project Overview (English)

### 🎯 The Problem
Modern recommendation algorithms are designed to maximize engagement, which often leads to recommending content that aligns strictly with a user's current viewing habits. This can limit exposure to alternative perspectives and reduce the opportunity for critical thinking and balanced comparison.

### 💡 The Solution
A browser extension that acts as a neutrality companion. It analyzes the topic of the video you are currently watching and suggests high-quality content representing alternative viewpoints or counter-arguments in real-time.

### 🛠️ Technical Scope (MVP)
- **Architecture:** Manifest V3 extension leveraging the native `sidePanel` API to ensure stability regardless of platform DOM updates.
- **Workflow:**
  1. Detect the current YouTube video and extract its title/context.
  2. Use an **AI/LLM** (via Cloud API or a local LLM runner) to identify the core theme or stance of the video.
  3. Generate balanced, opposing search queries or alternative angles.
  4. Fetch and display 3-4 alternative video or article links inside the side panel.

### 🚀 Looking for Contributors
I am looking for experienced developers to help build this open-source project. Specifically, we need expertise in:
- Modern Browser Extension development (JavaScript/TypeScript).
- AI/LLM integration (Prompt engineering, API handling, or Local LLM integration like WebGPU/Ollama).
- Privacy-first data fetching.

If you are interested in building a tool dedicated to cognitive diversity and critical thinking, please leave a comment in the Issues or reach out!

---

## 🇫🇷 Présentation du Projet (Français)

### 🎯 Objectif
Favoriser la diversité cognitive en élargissant les perspectives de l'utilisateur face aux algorithmes de recommandation. L'extension analyse le thème général de la vidéo visionnée et propose, dans un panneau latéral, des contenus de qualité qui soutiennent un point de vue opposé ou une approche alternative, permettant ainsi une confrontation constructive des idées.

### 🛠️ Approche Technique
* **Format :** Extension Manifest V3 utilisant l'API officielle `sidePanel` pour une stabilité maximale.
* **Logique IA :** Analyse sémantique du contexte pour identifier la thèse principale et générer des requêtes de recherche alternatives. Une attention particulière sera portée à la protection de la vie privée (recherche d'une solution d'IA locale).

---
