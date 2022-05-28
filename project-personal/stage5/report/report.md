---
## Front matter
title: "Индивидуальный проект. Этап 5"
subtitle: "Создание сайта"
author: "Лебедева Ольга Андреевна"

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
lot: true # List of tables
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

- Сделать записи для персональных проектов.

- Сделать пост по прошедшей неделе.

- Добавить пост на тему по выбору: Языки научного программирования.

# Ход работы

1. Добавили пост по прошедшей неделе. (рис. [-@fig:001]) (рис. [-@fig:002]) 

![Пост по прошедшей неделе](1.png){ #fig:001 width=70% }

![Содержание](2.png){ #fig:002 width=70% }

2. Добавили пост на тему по выбору. (рис. [-@fig:003]) (рис. [-@fig:004]) 

![Содержание ](3.png){ #fig:003 width=70% }

![Пост на тему по выбору](4.png){ #fig:004 width=70% }

3. Добавили проект. (рис. [-@fig:005]) (рис. [-@fig:006]) 

![Содержание ](5.png){ #fig:005 width=70% }

![Пост на тему по выбору](6.png){ #fig:006 width=70% }

# Вывод

- Сделали записи для персональных проектов.

- Сделали пост по прошедшей неделе.

- Добавили пост на тему по выбору: Языки научного программирования.
