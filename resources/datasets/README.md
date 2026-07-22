# Датасеты

Небольшие открытые корпуса для демонстрационного RAG-контура и проверки инференса. Для учебных целей достаточно урезанных выборок; полные дампы качать не обязательно. Ссылки — на официальные источники датасетов.

| Название | Аннотация | Связанные КИМ | Доступ | Лицензия / условия | Дата проверки |
|---|---|---|---|---|---|
| SQuAD 2.0 | Вопросно-ответный корпус на основе статей Wikipedia; удобен как демо-корпус для ingestion и retrieval в RAG. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [rajpurkar.github.io/SQuAD-explorer](https://rajpurkar.github.io/SQuAD-explorer/) | CC BY-SA 4.0 | 2026-07-22 |
| MS MARCO | Крупный набор реальных поисковых запросов и пассажей; стандарт для оценки passage retrieval и ранжирования. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [microsoft.github.io/msmarco](https://microsoft.github.io/msmarco/) | Некоммерческая исследовательская лицензия MS MARCO | 2026-07-22 |
| Natural Questions | Реальные запросы к Google с ответами из Wikipedia; используется для end-to-end RAG-сценариев. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [ai.google.com/research/NaturalQuestions](https://ai.google.com/research/NaturalQuestions) | CC BY-SA 3.0 | 2026-07-22 |
| Wikipedia (дампы Wikimedia / зеркало на Hugging Face) | Источник текстового корпуса произвольного объёма для наполнения векторной БД; для учёбы берут срез. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [dumps.wikimedia.org](https://dumps.wikimedia.org/), [huggingface.co/datasets/wikimedia/wikipedia](https://huggingface.co/datasets/wikimedia/wikipedia) | CC BY-SA (тексты Wikipedia) | 2026-07-22 |
| Hugging Face Datasets Hub | Каталог тысяч открытых датасетов с единым API загрузки (`datasets`); точка входа для подбора корпусов под задачу. | [Модуль 4](<../../M4-Data infrastructure/README.md>) | [huggingface.co/datasets](https://huggingface.co/datasets) | По лицензии каждого датасета | 2026-07-22 |

## Требования к добавлению

Укажите источник, лицензию, состав признаков, целевую переменную, объем, ограничения, возможные смещения и рекомендуемое разбиение.
