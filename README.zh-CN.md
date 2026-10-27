# Ai For Developers

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | **中文** | [日本語](README.ja.md) | [Русский](README.ru.md)

开发者如何用 AI — 工作流、工具、集成模式

_详细内容（列表、链接、描述）以英文维护 — 以下章节为你指引。_

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
## 贡献

欢迎提交 Pull Request，我们会审查并合并。由 [aixisstudio](https://github.com/aixisstudio) 维护，他也是开源应用防火墙 [Snitch](https://github.com/aixisstudio/Snitch) 的作者。

## 许可证: MIT
