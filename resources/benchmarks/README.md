# Бенчмарки и бейзлайны

Инструменты и наборы для измерения производительности инференса и качества поиска (retrieval). Используются в модулях нагрузочного тестирования, серверов инференса и RAG. Ссылки — на официальные репозитории и страницы бенчмарков.

| Название | Аннотация | Связанные КИМ | Доступ | Лицензия / условия | Дата проверки |
|---|---|---|---|---|---|
| MLPerf Inference: Datacenter (MLCommons) | Отраслевой бенчмарк скорости инференса: сценарии Offline/Server/SingleStream, метрики throughput и latency, целевые пороги качества. Референс для формулировки метрик эксплуатации и capacity planning. | [Модуль 7](<../../M7-Load testing and quality assessment/README.md>), [Модуль 8](<../../M8-Infrastructure planning/README.md>) | [Страница бенчмарка](https://mlcommons.org/benchmarks/inference-datacenter/), [reference implementation](https://github.com/mlcommons/inference) | Apache-2.0 (reference impl.) | 2026-07-22 |
| vLLM `benchmark_serving` | Штатный скрипт нагрузки vLLM: измеряет TTFT, inter-token latency, throughput при заданном профиле запросов. Используется как бейзлайн замеров сервинга. | [Модуль 2](<../../M2-Containerd and inference/README.md>), [Модуль 7](<../../M7-Load testing and quality assessment/README.md>) | [benchmarks/ в репозитории vLLM](https://github.com/vllm-project/vllm/tree/main/benchmarks) | Apache-2.0 | 2026-07-22 |
| LLMPerf | Инструмент нагрузочного тестирования LLM-API: inter-token latency и throughput при конкурентных запросах. Примечание: репозиторий переведён в архив (read-only) в декабре 2025, использовать как справочный образец методики. | [Модуль 7](<../../M7-Load testing and quality assessment/README.md>) | [github.com/ray-project/llmperf](https://github.com/ray-project/llmperf) | Apache-2.0 | 2026-07-22 |
| BEIR | Набор из 15+ разнородных датасетов для оценки моделей поиска (dense/sparse/rerank) — база для оценки качества retrieval-компонента RAG. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [github.com/beir-cellar/beir](https://github.com/beir-cellar/beir) | Apache-2.0 | 2026-07-22 |
| MTEB (Massive Text Embedding Benchmark) | Бенчмарк эмбеддинг-моделей по множеству задач (в т.ч. retrieval); помогает обоснованно выбрать модель эмбеддингов для RAG-контура. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [github.com/embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | Apache-2.0 | 2026-07-22 |

## Требования к добавлению

Опишите задачу, метрики, протокол эксперимента, базовые решения, требования к воспроизводимости и правила сравнения.
