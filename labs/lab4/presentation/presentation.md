---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Системы линейных уравнений
author:
  - Беличева Д. М.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 05 декабря 2003

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Беличева Дарья Михайловна
  * студент
  * Российский университет дружбы народов
  * [1032216453@pfur.ru](mailto:1032216453@pfur.ru)
  * <https://dmbelicheva.github.io/ru/>

:::
::: {.column width="25%"}

![](./image/belicheva.jpeg)

:::
::::::::::::::

# Вводная часть

## Цель работы

Научиться решать СЛАУ в Octave.

## Задание

- применить метод Гаусса вручную;

- попробовать встроенные операции привода к треугольной форме;

- применить LU/LUP-разложение;

## Основные понятия

GNU Octave — свободная программная система для математических вычислений, использующая совместимый с MATLAB язык высокого уровня.

## Выполнение лабораторной работы

Задала матрицу, посмотрела ее поэлементно. Выполнила простейшие преобразования с матрицей по методу Гаусса.

![Метод Гаусса](image/1.png){#fig:001 width=50%}

## Выполнение лабораторной работы

Применила встроенную команду для непосредственного поиска треугольной формы матрицы.

![Треугольная форма](image/2.png){#fig:002 width=50%}

## Выполнение лабораторной работы

Применила операцию левого деления и LUP-разложение.

![LUP-разложение](image/3.png){#fig:003 width=50%}

## Выводы

В процессе выполнения этой лабораторной работы я научилась решать СЛАУ с использованием Octave.

## Список литературы

1. GNU Octave [Электронный ресурс]. 2023. URL: https://ru.wikipedia.org/wiki/GNU_Octave.


