# Llm App Gallery

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

De vraies applis LLM à cloner — RAG, agents, workflows, démos

C'est quoi ?

Une galerie d'applications LLM **complètes et exploitables** — pas d'extraits, des repos complets avec l'architecture que vous pouvez étudier, cloner et adapter. La meilleure façon d'apprendre l'ingénierie LLM est de lire de vraies applications.

Clavardage et applications RAG

Appl.
|---|---|---|
Local ChatGPT clone.Js + OpenAI.
Clavardage, recherche, citations
Recherche hybride, reclassification
* Chat SQL * OpenAI + DuckDB * Text-to-SQL, mise à la terre du schéma *
Support bot-up FastAPI + Claude

Les applications Agent

Appl.
|---|---|---|
L'agent de recherche LangGraph + recherche
Agent d'analyse des données OpenAI + pandas
L'agent du navigateur L'auteur de jeux + la vision L'utilisation de l'ordinateur, des captures d'écran
Claude + git tools Numéro → Automation PR
Agent de triage par e-mail

Des applications originales

Appl.
|---|---|---|
Studio d'images Flux + API ComfyUI
TTS + script LLM
Génération structurée
Diffuseur + sous-titrage

Les modèles d'architecture méritent d'être volés

1. **Streaming SSE** — chaque chat moderne UI le fait de la même manière
2. **Loop** — `while tool_calls: execute → append → recall` — le squelette universel de l'agent
3. ** Sortie structurée** — mode schéma JSON > lecture rapide, toujours
4. **Eval harnais** — applications qui expédient ont un dossier `evals/`; copiez cette habitude
5. **Cost garde-corps** - jeton budgétisant intergiciel avant tout lancement prod

Kits de démarrage

Kit pour
|---|---|
`vercel/ai-chatbot`=Échafaudage de chat de qualité de production
40+ Variantes RAG
Modèles officiels
`anthropic-cookbook`

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
