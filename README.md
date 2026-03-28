<div align="center">

# 🔧 JARVIS MCP Toolkit

[![MCP](https://img.shields.io/badge/MCP-88+_Handlers-blue)](https://modelcontextprotocol.io)
[![Python](https://img.shields.io/badge/Python-3.12-green?logo=python)](https://python.org)
[![GPUs](https://img.shields.io/badge/GPUs-6x_NVIDIA-76B900?logo=nvidia)](https://nvidia.com)

**88+ MCP handlers for autonomous AI agents on a 6-GPU cluster**

</div>

## Architecture

```mermaid
graph LR
    Agent[AI Agent] --> MCP{MCP Protocol}
    MCP --> DB[Database 15]
    MCP --> FS[Filesystem 12]
    MCP --> API[API Bridge 18]
    MCP --> GPU[GPU Mgmt 8]
    MCP --> Voice[Voice 10]
    MCP --> Trade[Trading 12]
    MCP --> Browser[Browser 8]
    MCP --> System[Monitor 5]
```

## Handler Categories

| Category | Count | Examples |
|----------|-------|---------|
| Database | 15 | SQLite CRUD, search, analytics |
| Filesystem | 12 | Read, write, watch, backup |
| API | 18 | REST, WebSocket, MCP bridge |
| GPU | 8 | VRAM, thermal, model loading |
| Voice | 10 | STT, TTS, Whisper commands |
| Trading | 12 | MEXC, signals, consensus |
| Browser | 8 | CDP, screenshots, scraping |
| System | 5 | Health, monitoring, alerts |

## Part of [JARVIS OS](https://github.com/Turbo31150/jarvis-linux)

[TradeOracle](https://github.com/Turbo31150/TradeOracle) · [WhisperFlow](https://github.com/Turbo31150/jarvis-whisper-flow) · [LUMEN](https://github.com/Turbo31150/lumen)
