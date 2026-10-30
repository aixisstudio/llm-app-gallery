# Llm App Gallery

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

クローンして動かせる LLM アプリ集

## ️️ これは何ですか?

*complete, runnable LLM アプリケーションのギャラリー** — スニペットではなく、勉強し、クローン化し、適応できるアーキテクチャで完全なリポジトリ。 LLMエンジニアリングを学ぶ最速の方法は、実際のアプリを読み込みます。

## チャット&RAGアプリ

| アプリ | スタック | ティーチ |
|---|---|---|
| ローカルチャットGPTクローン | Next.js + OpenAI | ストリーミングUI、チャット状態 |
| チャット-with-PDF | LangChain + Chroma | チャンク、検索、引用 |
| マルチドキュメント RAG | LlamaIndex + Qdrant | ハイブリッドリトリーバール | リランク |
| SQL チャット | OpenAI + DuckDB | テキストからSQL、スキーマの接地 |
| サポートボット | FastAPI + Claude | ツール利用・エスカレーションフロー |

## ✔ エージェントアプリ

| アプリ | スタック | ティーチ |
|---|---|---|
| 研究代理店 | LangGraph+検索 | 計画的効果ループ |
| データアナリスト | OpenAI +パンダ | コード通訳パターン |
| ブラウザエージェント | プレイライト + ビジョン | コンピュータ使用・スクリーンショット |
| SWEエージェント | クロード + git ツール | 課題 → PR 自動化 |
| メールトリエーター | MCP + ルール | 受信トレイ自動化 |

## インポート生成アプリ

| アプリ | スタック | ティーチ |
|---|---|---|
| 映像工房 | フラックス + コンフィイ API | パイプライン |
| Podcast gen | TTS + スクリプト LLM | マルチモデルチェーン |
| スライドジェネレータ | PPTX + LLM | 構造生成 |
| ミームボット | 拡散+キャプション | ファン+エンゲージメントループ |

## ️️ 建築パターンを盗む価値のある

1。 **SSE**をStreaming — すべての近代的なチャットUIは同じようにします
2.**ツールループ** — `while tool_calls: execute → append → recall` — ユニバーサルエージェントスケルトン
3。**Structured output** — JSON スキーマモード > プロンプトペアリング、常に
4.**Eval ハーネス** — `evals/` フォルダーを出荷するアプリ; 習慣をコピーする
5。**Costガードレール** - 任意の起動前にトークン予算のミドルウェア

##スターターキット

| キット | 用 |
|---|---|
| `vercel/ai-chatbot` | 制作グレードのチャットサフォールド |
| `langchain templates` | 40+ ラグバリエーション |
| `openai-cookbook` | 公式パターン |
| `anthropic-cookbook` | クラウデ特異パターン |

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
