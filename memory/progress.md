# Progress

## История изменений

### 2026-02-01
- **Architecture**: Спроектирована модульная архитектура на основе Python (uv).
- **Documentation**: Создан `docs/architecture.md` с C4-диаграммой и описанием "LEGO-кирпичиков".
- **Decisions**: 
    - Разделение Core Logic и MCP Layer (Domain-Driven Design).
    - Выбор Qdrant как основной векторной БД.
    - Выбор Ollama + Qwen3-Embedding для локальной работы.
    - Выделение Chunking в отдельный Python-пакет.
- **Memory Bank**: Инициализированы и обновлены `projectBrief.md` и `activeContext.md`.