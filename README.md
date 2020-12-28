# Bi-Objective Heuristic Search

Работа выполнена в рамках курсового проекта по учебному курсу "Эвристические методы планирования"

## Запуск

Программный код находится в jupyter тетрадке [`main.ipynb`](main.ipynb). Для ее открытия необходимо создать `conda` окружение, запустить `jupyter`, после чего открыть в нем файл.

```bash
conda env create -f environment.yml
juputer notebook
```

## Краткое описание работы

В данной работе реализованы методы эвристического поиска для двухкомпонентной функции веса ребра взвешенного ориентированного графа. Реализованные методы:
1. Best-First Bi-Objective Search (BDijkstra)
2. Best-First Bi-Objective Heuristic Search (BA*)
3. Fast Bi-Objective Search (BOA*)

Произведено сравнение данных методов на предмет быстродействия. Результаты могут быть найдены в [презентации](https://docs.google.com/presentation/d/1w9gtWc8_oPojmWx03Yq6f4qokSlrVqkP_1DEoPBsdJU/edit?usp=sharing), или востроизведены с помощью `jupyter` [тетрадки](main.ipynb).

Реализованные методы могут быть запущены на графах формата [DIMACS](http://users.diag.uniroma1.it/challenge9/format.shtml), либо на графах, представленных в виде `DiGraph` библиотеки обработки графов [NetworkX](https://networkx.org/).