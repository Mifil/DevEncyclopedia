Навигационный шаблон: “Алгоритмы и структуры данных”
(Стратегия → Тактика → Операция → Применение)

📌 1. Введение и мотивация
Что такое алгоритм в контексте программирования?
Что такое структура данных и зачем она нужна?
В чём разница между алгоритмом и структурой данных?
Почему это считается базовой темой в Computer Science?
Что будет, если игнорировать знания в этой области?
Как это связано с моей повседневной разработкой (C++, STM32, Linux)?
🔹 Блок в главе: Краткое объяснение понятий + мотивация через реальные инженерные проблемы.

🎯 2. Цели и задачи
Какова основная цель выбора подходящего алгоритма?
Почему важно оценивать время и память исполнения?
Когда важна скорость? Когда важна компактность?
Что считать "хорошим" или "оптимальным" алгоритмом?
Какие ограничения существуют в embedded-среде (например, ограничение стека/ОЗУ)?
🔹 Блок в главе: Пояснение trade-off'ов + инженерные сценарии выбора.

🧱 3. Классификация и базовые концепции
Какие бывают типы алгоритмов?
Сортировка, поиск, жадные, динамическое программирование, графовые, криптографические?
Какие бывают типы структур данных?
Линейные (массивы, списки), древовидные, хеш-структуры, графы?
Чем отличаются динамические и статические структуры данных?
Что значит «подходящая структура под задачу»?
🔹 Блок в главе: Таблица + иерархия алгоритмов и структур, их применимость.

⚙️ 4. Анализ производительности (асимптотика)
Что такое Big O, и как он оценивает производительность?
Как читается O(n), O(n log n), O(n²) и т.д.?
Как сравнить два алгоритма по производительности?
Что такое лучший, средний и худший случай?
Почему не всегда важна только "сложность по времени"? (а ещё по памяти)
Какие алгоритмы наиболее эффективны для малых и для больших объёмов данных?
🔹 Блок в главе: Формулы, графики, реальные примеры (в т.ч. из embedded).

🛠️ 5. Примеры ключевых алгоритмов
Как работают:
Сортировки: пузырьковая, быстрая, слиянием
Поиски: линейный, бинарный
Поиск путей: BFS/DFS
Что проще всего реализовать в embedded?
Какие алгоритмы лучше избегать из-за нестабильной производительности?
Какие из них легко реализуются без рекурсии?
🔹 Блок в главе: Таблица + краткие коды, визуализации, ссылки на репозитории.

🧩 6. Обзор структур данных
В чём разница между:
Массивом и связным списком?
Стеком и очередью?
Хеш-таблицей и деревом поиска?
Какой тип структуры быстрее при поиске? А при вставке?
Какие структуры часто используются в embedded?
Как хранятся структуры в памяти, и как это влияет на кэш?
🔹 Блок в главе: Иллюстрации памяти, конкретные примеры на C++.

🔍 7. Как выбирать алгоритм/структуру под задачу?
Как понять, какой алгоритм нужен для задачи сортировки?
Как выбрать структуру данных для хранения телеметрии с датчиков?
Какие вопросы я должен задать себе при проектировании?
Когда использовать массив, а когда список?
Как не “перепроектировать” алгоритм и не потратить зря время?
🔹 Блок в главе: Пошаговая методика принятия решений.

💥 8. Типовые ошибки
Почему пузырьковая сортировка — плохой выбор в большинстве случаев?
Что случится, если использовать рекурсию в системе с 2KB стека?
Почему важно использовать const и inline в embedded-алгоритмах?
Какие структуры нельзя использовать без выделения памяти из кучи?
Какие бывают ошибки при неправильной оценке сложности?
🔹 Блок в главе: Реальные баги, утечки, аварийные ситуации на практике.

🧪 9. Мини-проекты и практические задачи
✅ Примеры практик:
Реализовать бинарный поиск без рекурсии
Сравнить производительность QuickSort и MergeSort
Организовать буфер FIFO с кольцевым массивом
Реализовать стек вызовов для интерпретатора
🔹 Блок в главе: Лабораторные, задания с критериями.

📚 10. Что почитать и куда копать дальше
Какие книги стоит читать (например, Cormen)?
Какие видеолекции рекомендуешь (MIT, YouTube)?
Есть ли открытые симуляторы алгоритмов?
Какие задачи решать на Leetcode/Codeforces?
Что стоит знать из C++ STL и какие контейнеры избегать в embedded?
🔹 Блок в главе: Ссылки, рейтинги, советы по обучению.

✅ 11. Чек-лист самопроверки
 Знаю ключевые сложности алгоритмов и могу объяснить O(n log n)
 Умею реализовать хотя бы 3 алгоритма сортировки
 Понимаю, в чём плюсы и минусы хеш-таблиц
 Умею оптимизировать структуру данных под микроконтроллер
 Понимаю, почему структуры влияют на производительность

