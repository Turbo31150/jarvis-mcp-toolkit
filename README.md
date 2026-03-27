# 🔧 JARVIS MCP Toolkit

> Toolkit complet pour orchestrer des agents IA autonomes via Model Context Protocol (MCP)

## 🎯 Fonctionnalités

**88+ handlers MCP** couvrant l'ensemble de l'écosystème IA :

- **Trading IA** : MEXC, analyse multi-timeframe, consensus multi-modèles
- **LM Studio** : 7 modèles locaux (Qwen3, DeepSeek, Nemotron, GLM4, GPT-OSS...)
- **Monitoring** : Dashboard temps réel, alertes Telegram, métriques système
- **GitHub** : Gestion repos, automatisation commits, CI/CD
- **Browser** : Orchestration multi-onglets, scraping intelligent, dispatch IA
- **SQL3** : Base de données distribuée sur 3 machines
- **n8n** : 20+ workflows automatisés

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────┐
│              JARVIS MCP Hub                      │
│                                                  │
│  Machine1 (Master) ↔ Machine2 (Worker)          │
│     2x GPU              2x GPU                   │
│            ↕                ↕                     │
│        Machine3 (Orchestrator)                   │
│            2x GPU                                │
│                                                  │
│  ┌──────────────────────────────────────────┐   │
│  │         88+ MCP Handlers                  │   │
│  │  Trading | LM Studio | Browser | SQL3    │   │
│  │  GitHub  | Telegram  | n8n     | FS      │   │
│  └──────────────────────────────────────────┘   │
└─────────────────────────────────────────────────┘
```

## 📊 Consensus Multi-IA

Le toolkit intègre un système de **consensus pondéré** entre 5 IA :

| Worker | Poids | Rôle |
|--------|-------|------|
| IA1 (Qwen3) | 1.3 | Analyse approfondie |
| IA2 (DeepSeek) | 1.0 | Réponse rapide |
| IA3 (Nemotron) | 0.8 | Validation croisée |
| IA4 (GLM4) | 0.6 | Documentation |
| IA5 (GPT-OSS) | 0.5 | Contrôle qualité |

## 🚀 Quick Start

```bash
npm install jarvis-mcp-toolkit
cp .env.example .env
node server.js
```

## 👤 Auteur

**Franck Delmas** — Architecte IA & Automatisation
- 🌐 [franckdelmas.dev](https://franckdelmas.dev)
- 💼 [LinkedIn](https://linkedin.com/in/franck-hlb-80bb231b1)
- 🛠️ Freelance IA pour TPE/PME — 55€/h

## 📄 License

MIT
