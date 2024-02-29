---
## Front matter
title: "Лабораторная работа № 3."
subtitle: "Markdown"
author: "Сорокин Кирилл Васильевич"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Извучить markdown

# Задание

Сделать отчёт к 2й лабораторной работе

# Теоретическое введение

3.2.1. Базовые сведения о Markdown
Чтобы создать заголовок, используйте знак ( # ), например:
1 # This is heading 1
2 ## This is heading 2
3 ### This is heading 3
4 #### This is heading 4

# Выполнение лабораторной работы

Изменим название и заголовки лабораторной работы(рис. [-@fig:001]).

![Заголовки](image/01.png){#fig:001 width=70%}


Изменим текст в необходимых пунктах (рис. [-@fig:002]).

![Изменённый текст](image/02.png){#fig:002 width=70%}

Изменим путь к картинкам (рис. [-@fig:003]).

![Путь к изображениям](image/03.png){#fig:003 width=70%}

Напишем make и скомпилируем отчёты (рис. [-@fig:004]).

![Название рисунка](image/04.png){#fig:004 width=70%}

Убедимся что файлы созданы(рис. [-@fig:005]).

![Файлы](image/05.png){#fig:005 width=70%}

# Выводы

Мы научились работать с markdown

