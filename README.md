# Проверка графа на двудольность

## Постановка задачи

Определить, является ли заданный граф двудольным.

## Описание используемых структур данных

**Двудольный граф**— это граф, множество вершин которого можно разбить на две части таким образом, что каждое ребро графа соединяет какую-то вершину из одной части с какой-то вершиной другой части, то есть не существует ребра, соединяющего две вершины из одной и той же части.

## Описание алгоритма

**Поиск в ширину** — алгоритм позволяет определять является ли граф двудольным. Суть алгоритма заключается в том, что помечать каждый следующий узел одним из 2 цветов, и если узел помечен уже противоположным цветом, то граф не является двудольным.(1 – черный цвет, -1 – красный цвет)

## Тестирование

Тестирование проведено на различных входных данных. Ошибок не найдено!

![alt tag](https://github.com/Basharov1210/Bipartite_graph/blob/main/img/Interface.png)https://github.com/Basharov1210/Bipartite_graph/blob/main/img/Interface.png "Интерфейс")
