# Llm App Gallery

[English](README.md) | [Français](README.fr.md) | **Español** | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Apps LLM reales para clonar

Lo que es

Una galería de **completos y ejecutables aplicaciones LLM** — no snippets, repos completo con arquitectura que puede estudiar, clonar y adaptar. La manera más rápida de aprender la ingeniería LLM es leer aplicaciones reales.

## 💬 Chat &gt; Aplicaciones RAG

← App ← Stack tención Teaches
|---|---|---|
Silencio Local ChatGPT clone ← Next.js + OpenAI Silencio Streaming UI, chat state ←
Silencio Chat-with-PDF Silencio LangChain + Chroma ¦ Chunking, retrieval, citas ¦
← Multi-doc RAG Silencio LlamaIndex + Qdrant ANTE Retrieval híbrido, reranking ¦
Silencio SQL chat ← OpenAI + DuckDB Silencio Text-to-SQL, schema grounding ←
← Soporte bot ← FastAPI + Claude fort Uso de la herramienta, flujos de escalada

## 🤖 Aplicaciones de agente

← App ← Stack tención Teaches
|---|---|---|
Silencio Agente de investigación Silencio LangGraph + búsqueda Silencioso Plan-act-reflect loops
Silencio Agente analista de datos Silencio OpenAI + pandas Silencio Código patrones de intérprete
Silencio Agente navegador Silencio Playwright + visión Silencio uso de ordenador, capturas de pantalla Silencio
Silencio agente SWE Silencio Claude + herramientas de git
← Agencia de triaje de correo electrónico

## Las aplicaciones generativas

← App ← Stack tención Teaches
|---|---|---|
← Estudio de imagen Ø Flux + ComfyUI API ← Prompt pipelines
Silencio Podcast gen Silencio TTS + script LLM Silencio Encadenamiento multimodelo
generador de diapositivas Silencio PPTX + LLM Silencio Generación estructurada
← Meme bot ¦ Diffusion + captioning

## ## 🏗中文 patrones de arquitectura vale la pena robar

1. **Streaming SSE** — cada chat moderno UI lo hace de la misma manera
2. **Tool loop** — `while tool_calls: execute → append → recall` — the universal agent skeleton
3. ** Salida estructural** — Modo de esquema JSON
4. **Arnés Eval** — aplicaciones que envían tienen una carpeta `evals/`; copiar ese hábito
5. **Guardias del polvo** — token budgeting middleware before any prod launch

## 🧰 Kits de arranque

Silencio para la vida
|---|---|
Silencio `vercel/ai-chatbot` Silencio Chat de grado de producción
Silencio `langchain templates` Silencio 40+ RAG variantes tención
Silencio `openai-cookbook`
Silencio `anthropic-cookbook`

---
## Contribuir

Los pull requests son bienvenidos: abre una PR y será revisada y fusionada. Mantenido por [aixisstudio](https://github.com/aixisstudio), autor de [Snitch](https://github.com/aixisstudio/Snitch), firewall de aplicaciones open source.

## Licencia: MIT
