---
## Front matter
title: "Индивидуальный проект. Часть 4"
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

- Добавить к сайту ссылки.
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:

1. Оформление отчёта.

2. Создание презентаций.

3. Работа с библиографией.

# Ход работы

1. Добавили к сайту ссылки на свои социальные сети, а также на Гитхаб. (рис. [-@fig:001]) (рис. [-@fig:002]) 

![Изменяем данные](image/1.png){ #fig:001 width=70% }

![Обновление иконок](image/2.png){ #fig:002 width=70% }

2. Написали пост по прошедшей неделе. (рис. [-@fig:003]) (рис. [-@fig:004]) 

![Пост по прошедшей неделе](image/3.png){ #fig:003 width=70% }

![Содержание поста](image/4.png){ #fig:004 width=70% }

3. Написали пост на тему по выбору : оформление отчета. (рис. [-@fig:005]) (рис. [-@fig:006]) (рис. [-@fig:007]) 

![Пишем текст поста](image/5.png){ #fig:005 width=70% }

![Содержание](image/6.png){ #fig:006 width=70% }

![Внешний вид](image/7.png){ #fig:007 width=70% }

# Вывод

- Добавили к сайту ссылки.
- Сделали пост по прошедшей неделе.
- Добавили пост на тему по выбору:

1. Оформление отчёта.


