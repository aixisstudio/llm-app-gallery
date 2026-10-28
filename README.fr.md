# Llm App Gallery

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

De vraies applis LLM à cloner — RAG, agents, workflows, démos

_Le contenu détaillé (listes, liens, descriptions) est en anglais pour rester maintenable — les sections ci-dessous te guident._

## 🖼️ What this is

A gallery of **complete, runnable LLM applications** — not snippets, full repos with architecture you can study, clone and adapt. The fastest way to learn LLM engineering is reading real apps.

## 💬 Chat & RAG apps

| App | Stack | Teaches |
|---|---|---|
| Local ChatGPT clone | Next.js + OpenAI | Streaming UI, chat state |
| Chat-with-PDF | LangChain + Chroma | Chunking, retrieval, citations |
| Multi-doc RAG | LlamaIndex + Qdrant | Hybrid retrieval, reranking |
| SQL chat | OpenAI + DuckDB | Text-to-SQL, schema grounding |
| Support bot | FastAPI + Claude | Tool use, escalation flows |

## 🤖 Agent apps

| App | Stack | Teaches |
|---|---|---|
| Research agent | LangGraph + search | Plan-act-reflect loops |
| Data analyst agent | OpenAI + pandas | Code interpreter patterns |
| Browser agent | Playwright + vision | Computer-use, screenshots |
| SWE agent | Claude + git tools | Issue → PR automation |
| Email triage agent | MCP + rules | Inbox automation |

## 🎨 Generative apps

| App | Stack | Teaches |
|---|---|---|
| Image studio | Flux + ComfyUI API | Prompt pipelines |
| Podcast gen | TTS + script LLM | Multi-model chaining |
| Slide generator | PPTX + LLM | Structured generation |
| Meme bot | Diffusion + captioning | Fun + engagement loops |

## 🏗️ Architecture patterns worth stealing

1. **Streaming SSE** — every modern chat UI does it the same way
2. **Tool loop** — `while tool_calls: execute → append → recall` — the universal agent skeleton
3. **Structured output** — JSON schema mode > prompt-parsing, always
4. **Eval harness** — apps that ship have a `evals/` folder; copy that habit
5. **Cost guardrails** — token budgeting middleware before any prod launch

## 🧰 Starter kits

| Kit | For |
|---|---|
| `vercel/ai-chatbot` | Production-grade chat scaffold |
| `langchain templates` | 40+ RAG variants |
| `openai-cookbook` | Official patterns |
| `anthropic-cookbook` | Claude-specific patterns |

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
