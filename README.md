# Лабораторные работы по предмету "Распознавание образов"

- [Лабораторные работы по предмету "Распознавание образов"](#лабораторные-работы-по-предмету-распознавание-образов)
  - [Лабораторная работа №1 "Построение эллипса Петунина"](#лабораторная-работа-1-построение-эллипса-петунина)
  - [Лабораторная работа №2 "Поиск диаметра множества"](#лабораторная-работа-2-поиск-диаметра-множества)
    - [Второй алгоритм](#второй-алгоритм)
  - [Лабораторная работа №3 "Расстояние Махаланобиса"](#лабораторная-работа-3-расстояние-махаланобиса)
  - [Лабораторная работа №4 "Многомерная классификация"](#лабораторная-работа-4-многомерная-классификация)
  - [Лабораторная работа №5 "Метод k-средних"](#лабораторная-работа-5-метод-k-средних)
  - [Лабораторная работа №6 "Проверка гипотезы про однородность выборок при помощи статистики Петунина"](#лабораторная-работа-6-проверка-гипотезы-про-однородность-выборок-при-помощи-статистики-петунина)


## Лабораторная работа №1 "Построение эллипса Петунина"

Лабораторная сделана в jupyter notebook. Вот [ссылка](Lab1/main.ipynb)


## Лабораторная работа №2 "Поиск диаметра множества"

- код лабы ([ссылка](Lab2/main.py))
- отчет pdf ([ссылка](Lab2/report/report.pdf))
- отчет tex ([ссылка](Lab2/report/report.tex))

В лабораторной был реализованы три алгоритма поиска диаметра множества

- Жадный алгоритм. Перебор всех пар точек.
- Алгоритм построения выпуклой оболочки совмещенный с алгоритмом вращающихся калиперов (Rotating calipers).
- Алгоритм, который строит прямоугольники, что разделяют множество точек. Вот ссылка на [статью](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.77.1699&rep=rep1&type=pdf).
  
### Второй алгоритм

Алгоритм можно разделить на 2 части
- **Построение выпуклой оболочки**. Я использовал алгоритм Грэхема, [статья](https://habr.com/ru/post/144921/). Но можно ускорить реализацию алгоритма если использовать модуль `scipy`, `scipy.spatial.ConvexHull`. [ссылка](https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.ConvexHull.html).
- **алгоритм Rotating calipers**. Алгоритм описан в [википедии](https://en.wikipedia.org/wiki/Rotating_calipers).



## Лабораторная работа №3 "Расстояние Махаланобиса"

Лабораторную делал в jupyter notebook. Генерация последнего рисунка может быть долгой.

- [Лаба notebook](Lab3/Mahalanobis%20distance.ipynb)
- [отчет pdf](Lab3/report/report.pdf)
- [отчет tex](Lab3/report/report.tex)
## Лабораторная работа №4 "Многомерная классификация"

Лабораторную делал в jupyter notebook.

- [Лаба notebook](Lab4/Labwork%204.ipynb)
- [отчет pdf](Lab4/report/report.pdf)
- [отчет tex](Lab4/report/report.tex)

## Лабораторная работа №5 "Метод k-средних"

Лабораторную делал в jupyter notebook.

- [Лаба notebook](Lab5/k-means%20clustering.ipynb)
- [отчет pdf](Lab5/report/report.pdf)
- [отчет tex](Lab5/report/report.tex)

## Лабораторная работа №6 "Проверка гипотезы про однородность выборок при помощи статистики Петунина"

Лабораторную делал в jupyter notebook.

- [Лаба notebook](/Lab6/Labwork6_p-stat.ipynb)
- [отчет pdf](/Lab6/report/Kravets_report_lab6.pdf)
- [отчет tex](/Lab6/report/Kravets_report_lab6.tex)