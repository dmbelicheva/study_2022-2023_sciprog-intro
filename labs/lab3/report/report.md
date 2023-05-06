---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Введение в работу с Octave"
author: "Беличева Дарья Михайловна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: false # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с Octave, изучить основные команды.

# Задание

- Выполнить простейшие операции

- Выполнить операции с векторами

- Вычислить проектор

- Выполнить операции с матрицами

- Построить графики

- Сравнить циклы и операции с векторами

# Теоретическое введение

GNU Octave — свободная программная система для математических вычислений, использующая совместимый с MATLAB язык высокого уровня.

Предоставляет интерактивный командный интерфейс для решения линейных и нелинейных математических задач, а также проведения других численных экспериментов. Кроме того, Octave можно использовать для пакетной обработки. Язык Octave оперирует арифметикой вещественных и комплексных скаляров, векторов и матриц, имеет расширения для решения линейных алгебраических задач, нахождения корней систем нелинейных алгебраических уравнений, работы с полиномами, решения различных дифференциальных уравнений, интегрирования систем дифференциальных и дифференциально-алгебраических уравнений первого порядка, интегрирования функций на конечных и бесконечных интервалах. Этот список можно легко расширить, используя язык Octave (или используя динамически загружаемые модули, созданные на Си, C++, Фортране и других). [@wiki:bash]

# Выполнение лабораторной работы

Для начала я установила Octave. Далее запустила его. После выполнила команду для журналирования сессии(рис. @fig:001).

![Запуск](image/1.jpeg){#fig:001 width=70%}

Изучила матрицы и векторы, провела операции над ними(рис. @fig:002).

![Простейшие операции](image/2.jpeg){#fig:002 width=70%}

Построила графики. Изучила команды для изменения цвета графика, подписи осей и создания легенды(рис. @fig:003).

![Графики](image/3.jpeg){#fig:003 width=70%}

Поработала с циклами и завершила журналирование сессии(рис. @fig:004).

![Завершение](image/4.jpeg){#fig:004 width=70%}


# Выводы

В процессе выполнения лабораторной работы я познакомилась с Octave и освоила основные команды для работы с ним.

# Список литературы{.unnumbered}

::: {#refs}
:::
