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
- **Context Optimization**: Реорганизована структура `.kilocode` (Memory Bank, Skills, Mode Rules) для эффективной работы с Gemini 3.

### 2026-02-04
- **HSM Integration**: Полная интеграция проекта с HSM.
- **Components**: Реализован и зарегистрирован `rag4code-chunker`.
- **Core**: Реализован `RagEngine` с динамической загрузкой плагинов через Entry Points.
- **Orchestration**: Настроена автоматическая генерация `docker-compose.hsm.yml` и управление режимами `dev/prod` через HSM.
- **Memory Bank**: Реализована федеративная структура Memory Bank (Root + Sub-projects).