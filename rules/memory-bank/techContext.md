# Technical Context

## Технологический стек
- **Язык**: Python 3.13+
- **Менеджер пакетов**: `uv`
- **Векторная БД**: Qdrant (запуск в Docker)
- **Эмбеддинги**: Ollama (модель: `qwen3-embedding` или аналогичная)
- **Интерфейсы**: MCP (Model Context Protocol), CLI, Web UI

## Среда разработки
- **IDE**: VS Code / Kilo Code
- **AI Модели**: Gemini 3 Pro (для архитектуры/планирования), Gemini 3 Flash (для реализации/отладки)

## Внешние зависимости
- Docker (для Qdrant)
- Ollama (локальный сервер эмбеддингов)