Добрый день! 
До 15 марта (на 4 недели) даётся две лабораторные работы. Защищать их (продемонстрировать код и запустить программу) необходимо в аудитории в Часы занятий: вт, 6,7 пара. К каждой работе необходимо подготовить отчёт.


Лабораторная работа №1
Целочисленная арифметика произвольной точности и RSA-шифрование
1. Написать класс, который содержит целое число со знаком в виде массива однобайтовых элементов. Реализовать конструкторы, деструктор, перегрузить операции: аддитивные (+, -), мультипликативные (*, /, %), сравнения (==, !=, <, >).
2. Написать функцию шифрования строки с помощью простого числа (алгоритм типа RSA)
3. Зашифровать/расшифровать текстовый файл с помощью открытого RSA-ключа


Лабораторная работа №2
Алгоритмы сортировки строк
    Реализовать алгоритмы сортировки. Выбрать наиболее трудоемкую операцию алгоритма. Создать план эксперимента с алгоритмом и получить статистические данные о работе алгоритма. Определить сложность алгоритма для этой операции: найти порядок сложности и коэффициент пропорциональности
    1. Bubble
    2. QSort
    3. SortTree
    4. Сортировка вставками
    5. Сортировка слиянием
    6. Сортировка с помощью красно-черного дерева


Требования к отчету по лабораторной работе
1. Титульный лист:
– шапка с названием организации;
– название работы;
– отчет по лабораторной работе дисциплины «Алгоритмы и анализ сложности»
– Студент: ФИО, группа
– Преподаватель: ФИО, должность, степень
– Год
2. Оглавление
3. Задание
4. Теоретическая часть. Найти, перечислить и сравнить различные методы решения данной задачи.
5. Инструкция пользователя.
6. Инструкция программиста
7. Тестирование
8. Выводы
9. Литература
10. Приложение


✓ Задача должна быть решена в виде отдельной функции или метода класса
✓ Функция должна иметь тестирующие функции
✓ Исходные данные для задачи должны передаваться в функцию в виде структуры или отдельных параметров.
✓ Исходные данные для работы и анализа алгоритма желательно задавать в формате xml-файлов [Котеров, Костарев]. Извлечение данных реализовать с помощью библиотеки xml-классов и XPath-запросов
Могут быть использованы библиотеки для работы с большим числами и во 2 л/р готовые библиотеки.
Писать необходимо на компилируемых языках, не на python. С, С++, Pascal, Также можно писать на С Шарп, Java




Лабораторная работа №1.9
Геометрические алгоритмы
1. Найти выпуклую оболочку множества точек на плоскости.
2. Алгоритм вычисления площади многоугольника.
3. Принадлежность точки многоугольнику.
4. Реализовать иерархию геометрических примитивов для визуализации движения составных фигур.
5. Реализовать алгоритм освещения трехмерной фигуры.




Лабораторная работа №2.6
Раскраска графа
Раскраска графа — теоретико-графовая конструкция, частный случай разметки графа. При раскраске элементам графа ставятся в соответствие метки с учётом определённых ограничений; эти метки традиционно называются «цветами». В простейшем случае такой способ окраски вершин графа, при котором любым двум смежным вершинам соответствуют разные цвета, называется раскраской вершин. Аналогично раскраска рёбер присваивает цвет каждому ребру так, чтобы любые два смежных ребра имели разные цвета[1]. Наконец, раскраска областей планарного графа назначает цвет каждой области, так, что каждые две области, имеющие общую границу, не могут иметь одинаковый цвет.
Раскраска вершин — главная задача раскраски графов, все остальные задачи в этой области могут быть сведены к ней. Например, раскраска рёбер графа — это раскраска вершин его рёберного графа, а раскраска областей планарного графа — это раскраска вершин его двойственного графа[1]. Тем не менее, другие проблемы раскраски графов часто ставятся и решаются в изначальной постановке. Причина этого частично заключается в том, что это даёт лучшее представление о происходящем и более показательно, а частично из-за того, что некоторые задачи таким образом решать удобнее (например, раскраска рёбер).
Раскраска графов находит применение и во многих практических областях, а не только в теоретических задачах. Помимо классических типов проблем, различные ограничения могут также быть наложены на граф, на способ присвоения цветов или на сами цвета. Этот метод, например, используется в популярной головоломке Судоку. В этой области всё ещё ведутся активные исследования.




Лабораторная работа №16
Кластерный анализ
Реализовать метод M-средних для разбиения множества точек на плоскости на кластеры.