# Python-библиотеки и программные средства

Программные средства для лабораторных работ. Версии в таблице не фиксируем — ставьте актуальные; для воспроизводимости пиновать версии в `requirements.txt`/`pyproject.toml` проекта. Инструменты не на Python (k6, ArgoCD) отмечены отдельно.

| Название | Аннотация | Связанные КИМ | Доступ | Лицензия / условия | Дата проверки |
|---|---|---|---|---|---|
| vllm | Сервер инференса БЯМ (continuous batching, paged attention), OpenAI-совместимый API. `pip install vllm` | [Модуль 2](<../../../M2-Containerd and inference/README.md>) | [pypi.org/project/vllm](https://pypi.org/project/vllm/) | Apache-2.0 | 2026-07-22 |
| transformers (Hugging Face) | Загрузка и запуск моделей, токенизаторы. `pip install transformers` | [Модуль 2](<../../../M2-Containerd and inference/README.md>) | [pypi.org/project/transformers](https://pypi.org/project/transformers/) | Apache-2.0 | 2026-07-22 |
| sentence-transformers | Эмбеддинг-модели для RAG (напр. `all-MiniLM-L6-v2`). `pip install sentence-transformers` | [Модуль 4](<../../../M4-Data infrastructure/README.md>) | [pypi.org/project/sentence-transformers](https://pypi.org/project/sentence-transformers/) | Apache-2.0 | 2026-07-22 |
| qdrant-client | Python-клиент векторной БД Qdrant. `pip install qdrant-client` | [Модуль 4](<../../../M4-Data infrastructure/README.md>) | [pypi.org/project/qdrant-client](https://pypi.org/project/qdrant-client/) | Apache-2.0 | 2026-07-22 |
| tritonclient | Клиент для NVIDIA Triton Inference Server (HTTP/gRPC). `pip install tritonclient[all]` | [Модуль 2](<../../../M2-Containerd and inference/README.md>) | [pypi.org/project/tritonclient](https://pypi.org/project/tritonclient/) | BSD-3-Clause | 2026-07-22 |
| dvc | Версионирование данных и моделей поверх S3/MinIO. `pip install dvc[s3]` | [Модуль 4](<../../../M4-Data infrastructure/README.md>), [Модуль 5](<../../../M5-CICD-gitOps/README.md>) | [pypi.org/project/dvc](https://pypi.org/project/dvc/) | Apache-2.0 | 2026-07-22 |
| mlflow | Трекинг экспериментов и реестр моделей (model registry). `pip install mlflow` | [Модуль 5](<../../../M5-CICD-gitOps/README.md>) | [pypi.org/project/mlflow](https://pypi.org/project/mlflow/) | Apache-2.0 | 2026-07-22 |
| prometheus-client | Экспорт кастомных метрик приложения в Prometheus. `pip install prometheus-client` | [Модуль 6](<../../../M6-Monitoring/README.md>) | [pypi.org/project/prometheus-client](https://pypi.org/project/prometheus-client/) | Apache-2.0 | 2026-07-22 |
| locust | Нагрузочное тестирование на Python (сценарии как код). `pip install locust` | [Модуль 7](<../../../M7-Load testing and quality assessment/README.md>) | [pypi.org/project/locust](https://pypi.org/project/locust/) | MIT | 2026-07-22 |
| k6 (не Python) | Инструмент нагрузочного тестирования на Go, сценарии на JavaScript. Ставится как CLI, не через pip. | [Модуль 7](<../../../M7-Load testing and quality assessment/README.md>) | [grafana.com/docs/k6/latest](https://grafana.com/docs/k6/latest/) | AGPL-3.0 | 2026-07-22 |

## Требования к добавлению

Фиксируйте версию, команду установки, назначение, совместимость, лицензию и пример минимального использования.
