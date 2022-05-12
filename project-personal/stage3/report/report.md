---
## Front matter
title: "Индивидуальный проект. Часть 3"
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

- Добавить информацию о навыках (Skills).

- Добавить информацию об опыте (Experience).

- Добавить информацию о достижениях (Accomplishments).

- Сделать пост по прошедшей неделе.

- Добавить пост на тему по выбору:
Легковесные языки разметки.

# Ход работы

1. Добавили информацию о навыках (Skills). (рис. [-@fig:001]) (рис. [-@fig:008])

![Изменяем данные](8.png){ #fig:008 width=70% }

![Навыки](1.png){ #fig:001 width=70% }

2. Добавили информацию об опыте (Experience). (рис. [-@fig:002]) 

![Опыт](2.png){ #fig:002 width=70% }

3. Добавили информацию о достижениях (Accomplishments). (рис. [-@fig:003]) (рис. [-@fig:010]) 

![Навыки](3.png){ #fig:003 width=70% }

![Навыки](10.png){ #fig:010 width=70% }

4. Добавили пост на тему по выбору:

Легковесные языки разметки. (рис. [-@fig:004])(рис. [-@fig:005]) (рис. [-@fig:012])

![Пост по выбору](4.png){ #fig:004 width=70% }

![Пост](5.png){ #fig:005 width=70% }

![Изменение данных](12.png){ #fig:012 width=70% }

5. Сделали пост по прошедшей неделе. (рис. [-@fig:006]) (рис. [-@fig:007])

![Пост по неделе](6.png){ #fig:006 width=70% }

![Пост](7.png){ #fig:007 width=70% }

# Вывод

- Добавили информацию о навыках (Skills).

- Добавили информацию об опыте (Experience).

- Добавили информацию о достижениях (Accomplishments).

- Сделали пост по прошедшей неделе.

- Добавили пост на тему по выбору:
Легковесные языки разметки.