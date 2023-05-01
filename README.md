# Algorithms and data structures (seminars)

## Урок 2. Структуры данных. Массивы. Алгоритмы массивов.

Реализовать алгоритм пирамидальной сортировки (сортировка кучей).


## Урок 3. Структуры данных. Связный список.

Необходимо реализовать метод разворота связного списка (двухсвязного или односвязного на выбор).


## Урок 4. Структуры данных дерево и хэш-таблица

Необходимо превратить собранное на семинаре дерево поиска в полноценное левостороннее (по желанию можно обычное) красно-черное дерево. И реализовать в нем метод добавления новых элементов с балансировкой.

Красно-черное дерево имеет следующие критерии:
• Каждая нода имеет цвет (красный или черный)
• Корень дерева всегда черный
• Новая нода всегда красная
• Красные ноды могут быть только левым ребенком
• У краной ноды все дети черного цвета

Соответственно, чтобы данные условия выполнялись, после добавления элемента в дерево необходимо произвести балансировку, благодаря которой все критерии выше станут валидными. Для балансировки существует 3 операции – левый малый поворот, правый малый поворот и смена цвета.
