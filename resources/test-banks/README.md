# Банки тестов

Основной банк тестовых заданий курса — экспресс-тесты по материалам лекций, которые проводятся в начале занятия по пройденному модулю и дают до 15% итоговой оценки (см. [«Итоговая оценка»](../../README.md#4-итоговая-оценка)). Каждый экспресс-тест хранится в README соответствующего модуля рядом с КИМ лабораторной работы: там задаются темы, вопросы, ключи и правила выборки. Ниже — навигация по модульным банкам и внешние платформы, которые можно использовать для проведения и автопроверки тестов.

## Модульные экспресс-тесты (M1–M8)

| Название | Аннотация | Связанные КИМ | Доступ | Лицензия / условия | Дата проверки |
|---|---|---|---|---|---|
| Экспресс-тест «Архитектура и эксплуатационные требования» | Проверяет понимание SLA/SLO/SLI и метрик эксплуатации (p50/p95/p99, TTFT, TPS, availability), состава production-ИИ-сервиса. | [Модуль 1](<../../M1-Hardware architecture of AI/README.md>) | [M1-Hardware architecture of AI](<../../M1-Hardware architecture of AI/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |
| Экспресс-тест «Контейнеризация и серверы инференса» | Docker/containerd/Podman, NVIDIA Container Toolkit, сравнение vLLM/Triton/TGI/TorchServe, batching и квантование. | [Модуль 2](<../../M2-Containerd and inference/README.md>) | [M2-Containerd and inference](<../../M2-Containerd and inference/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |
| Экспресс-тест «Оркестрация и масштабирование» | Deployment/Service/Ingress, requests/limits, GPU-ноды, taints/tolerations, HPA/VPA, rolling update, probes. | [Модуль 3](<../../M3-Orchestration and scaling/README.md>) | [M3-Orchestration and scaling](<../../M3-Orchestration and scaling/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |
| Экспресс-тест «Инфраструктура данных и RAG» | MinIO/S3, DVC, векторные БД (Qdrant/Milvus), Redis, репликация PostgreSQL, RBAC, устройство RAG-контура. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [M4-Data infrastructure](<../../M4-Data infrastructure/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |
| Экспресс-тест «CI/CD и GitOps» | GitLab CI/GitHub Actions/ArgoCD/Tekton, model registry, GitOps-деплой, пайплайн поставки модели. | [Модуль 5](<../../M5-CICD-gitOps/README.md>) | [M5-CICD-gitOps](<../../M5-CICD-gitOps/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |
| Экспресс-тест «Мониторинг и наблюдаемость» | Prometheus/Grafana/ELK, метрики инференса (TTFT, inter-token latency, TPS, GPU util, queue depth), дашборды и алерты. | [Модуль 6](<../../M6-Monitoring/README.md>) | [M6-Monitoring](<../../M6-Monitoring/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |
| Экспресс-тест «Нагрузочное тестирование и качество» | soak/spike/stress, k6/Locust/ab, метрики эффективности (cost/1K req, W/req), A/B, chaos engineering. | [Модуль 7](<../../M7-Load testing and quality assessment/README.md>) | [M7-Load testing and quality assessment](<../../M7-Load testing and quality assessment/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |
| Экспресс-тест «Планирование мощности и разнородная инфраструктура» | Capacity planning (GPU на 30/1000 пользователей), CPU/GPU/TPU, облако/edge (ONNX, TF Lite), обоснование SLA. | [Модуль 8](<../../M8-Infrastructure planning/README.md>) | [M8-Infrastructure planning](<../../M8-Infrastructure planning/README.md>) | CC BY 4.0 (материалы курса) | 2026-07-22 |

## Внешние платформы для проведения тестов

| Название | Аннотация | Связанные КИМ | Доступ | Лицензия / условия | Дата проверки |
|---|---|---|---|---|---|
| Moodle (банк вопросов LMS) | Открытая LMS с встроенным банком вопросов и модулем «Тест»: категории, случайная выборка, автопроверка, импорт/экспорт (GIFT, Aiken, Moodle XML). Подходит для хранения и запуска экспресс-тестов. | [Все модули](../../README.md#3-контрольно-измерительные-материалы) | [moodle.org](https://moodle.org/) | GPLv3 (ПО) | 2026-07-22 |
| GitHub Classroom (autograding) | Раздача заданий на базе GitHub со стартовым кодом и автоматическим прогоном тестов при каждом push; удобно для «тестов-как-кода» по практическим модулям. | [Все модули](../../README.md#3-контрольно-измерительные-материалы) | [classroom.github.com](https://classroom.github.com/) | Бесплатно для образования; условия GitHub | 2026-07-22 |

## Требования к добавлению

Для каждого банка укажите темы, количество заданий, уровни сложности, правила выборки, ключи и порядок обновления. Экспресс-тесты храните внутри README соответствующего модуля; при выносе на внешнюю платформу указывайте формат экспорта (GIFT/Moodle XML) для воспроизводимости.
