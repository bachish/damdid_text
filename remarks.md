❓1. Context Free Path Queries are a very advanced querying method for graph databases, and in my opinion it deserves a much more extended motivation section with some detailed real-world examples, not just a list of areas/problems where its applicable.

✅2.1. There are some mistypes: Cyper instead of Cypher (p. 3), constrains instead of constraints (p. 3).

❓2.2.It would be very interesting if the authors explain HOW the proposed GLL CPFQ algorithm outperforms some linear algebra-based algorithm (even though the proposed algorithm does not use parallel computations yet, but linear-algebra based algoritms do).
Isn't it right that linear-algebra based algorithms process many paths in one matrix operation but state machine algorithms process only one path at each moment?

Ревьюер 3
✅3.1. Полужирные выделения в тексте следует заменить на курсив.

[в каких-то источниках правда так пишут, но не знаю насколько они официальные (Bold type and underlining should be avoided, https://texdoc.org/serve/llncs/0)]

❓3.2. Во введении следует дать читателю более подробную интуицию о GLL.

✅3.3. Название раздела 5. Dataset Description не вполне соответствует содержанию: кроме набора данных, там описаны модельные запросы, сценарии применения и среда для экспериментов.
[заменено на Experiment design]

❓3.4. Для экспериментов используется специализированный набор RDF-графов для Context-Free Path Querying (CFPQ). Запросы выглядят модельными. Но похоже, что лучшего бенчмарка на задачу CFPQ в настоящее время нет.
⚠️3.5. Эксперименты в разделе 6 направлены на выбор решения для реализации в Neo4j. Но детали этой экспериментальной реализации не приведены. Можно дать ссылку на код.
✅3.6. Рисунки 6, 7, 8 – шрифт и детали мелкие, нечитаемо (поправила, но мб есть исходники?)

✅ найти все ?? (незарезолвенные ссылки)