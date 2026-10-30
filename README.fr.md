# Ai For Developers

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Comment les devs utilisent l'IA — workflows, outils, patterns d'intégration

Où l'IA aide réellement les devs
Tâche
|---|---|
Générer, examiner, s'engager — plus grande victoire quotidienne
Compréhension du code legs
Refactoring (en anglais seulement) "Extrait ceci, simplifie ça" — revisite le diff (en anglais seulement)
Déboguage Collez la trace + code, obtenez des hypothèses classées
Docs et commentaires: Premières ébauches — polissez-vous
Prototypes Heures → minutes sur le code de lancement

Flux de travail qui fonctionnent
- **Plan → agent → avis** — vous écrivez la spécification, l'agent écrit le code, vous lisez chaque ligne
- **Diff review** — jamais accepter aveugle; demander au modèle d'expliquer sa propre diff
- **Vérification multimodèle** — deuxième avis sur les changements à risque
- **Tests-premier appel** — demander des tests avant la mise en œuvre

Modèles d'intégration
Utilisation
|---|---|
Achèvement du clavardage
Fonction appelant le modèle appelant votre API
Réponse de *votre* docs/données
Agents Tâches en plusieurs étapes avec des outils
Essai de régression rapide/version

Anti-patterns
- Code généré par le collage aveugle à prod
- Baisser les secrets/l'IPI dans les invites — voir où vos données vont ([Snitch](https://github.com/aixisstudio/Snitch) montre chaque connexion sortante
- Proposer des bases de code complètes au lieu d'un contexte étroit
- Sauter les tests parce que "l'IA l'a écrit"

Navire plus vite avec l'IA

Tâche
|---|---|
L'intégration de l'API
Sortie structurée: `instructor` (Pydantique)
Caching: `diskcache` + hash
CdPH0X + emboîtements
Evales `promptfoo` / Braintrust
Agents `pydantic-ai` / LangGraph

Les 80/20

La plupart des applications AI = streaming + sortie structurée + indice RAG. Maître ces trois avant de toucher des agents.

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
