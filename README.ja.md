# Ai For Developers

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

開発者のための AI 活用法

_詳細なコンテンツ（リスト・リンク・説明）は保守のため英語です。以下のセクションがガイドになります。_

## 🧰 Where AI actually helps devs
| Task | How |
|---|---|
| Boilerplate & tests | Generate, review, commit — biggest daily win |
| Legacy code comprehension | Paste a file, ask for a walkthrough |
| Refactoring | "Extract this, simplify that" — review the diff |
| Debugging | Paste the trace + code, get hypotheses ranked |
| Docs & comments | First drafts — polish yourself |
| Prototypes | Hours → minutes on throwaway code |

## 🔄 Workflows that work
- **Plan → agent → review** — you write the spec, the agent writes the code, you read every line
- **Diff review** — never accept blind; ask the model to explain its own diff
- **Multi-model check** — second opinion on risky changes
- **Tests-first prompting** — ask for tests before implementation

## 🧱 Integration patterns
| Pattern | Use |
|---|---|
| Chat completion | Q&A, generation |
| Function calling | Let the model call your APIs |
| RAG | Answer from *your* docs/data |
| Agents | Multi-step tasks with tools |
| Evals | Prompt/version regression testing |

## ⚠️ Anti-patterns
- Blind-pasting generated code to prod
- Leaking secrets/PII into prompts — see where your data goes ([Snitch](https://github.com/aixisstudio/Snitch) shows every outbound connection 😉)
- Prompting whole codebases instead of narrow context
- Skipping tests because "the AI wrote it"

## 🚀 Ship faster with AI

| Task | Stack |
|---|---|
| API integration | `litellm` → any provider |
| Structured output | `instructor` (Pydantic) |
| Caching | `diskcache` + prompt hash |
| RAG | `chromadb` + embeddings |
| Evals | `promptfoo` / Braintrust |
| Agents | `pydantic-ai` / LangGraph |

## ⚡ The 80/20

Most "AI apps" = streaming + structured output + a RAG index. Master those three before touching agents.

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
