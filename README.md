# 🔧 JARVIS MCP Toolkit

> Toolkit complet pour orchestrer des agents IA autonomes via MCP

## 🎯 88+ Handlers MCP

- **Trading IA** : MEXC, multi-timeframe, consensus
- **LM Studio** : 7 modèles locaux (Qwen3, DeepSeek, Nemotron)
- **Monitoring** : Dashboard temps réel, alertes Telegram
- **GitHub** : Gestion repos, automatisation CI/CD
- **Browser** : Orchestration multi-onglets, scraping IA
- **SQL3** : Base distribuée 3 machines
- **n8n** : 20+ workflows

## 🏗️ Architecture

```
Machine1 (Master)  ↔  Machine2 (Worker)  ↔  Machine3 (Orchestrator)
   2x GPU              2x GPU             2x GPU
                88+ MCP Handlers
```

## 📊 Consensus Multi-IA

| Worker | Poids | Rôle |
|--------|-------|------|
| IA1 (Qwen3) | 1.3 | Analyse approfondie |
| IA2 (DeepSeek) | 1.0 | Réponse rapide |
| IA3 (Nemotron) | 0.8 | Validation croisée |
| IA4 (GLM4) | 0.6 | Documentation |
| IA5 (GPT-OSS) | 0.5 | Contrôle qualité |

## 👤 Auteur

**Franck Delmas** — Architecte IA & Automatisation
- 🌐 [franckdelmas.dev](https://franckdelmas.dev)
- 💼 [LinkedIn](https://linkedin.com/in/franck-hlb-80bb231b1)
- 🛠 Freelance IA pour TPE/PME — 55€/h

## 📄 License

MIT