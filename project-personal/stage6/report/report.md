---
## Front matter
title: "Индивидуальный проект. Этап 6"
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

- Сделать поддержку английского и русского языков.

- Разместить элементы сайта на обоих языках.

- Разместить контент на обоих языках.

- Сделать пост по прошедшей неделе.

- Добавить пост на тему по выбору (на двух языках).

# Ход работы

Сделали поддержку двух языков - русского и английского. Изменили шапку в файле languages. (рис. [-@fig:001])

![Изменения в файле](image/1.png){ #fig:001 width=70% }

Появился значок смены языка. (рис. [-@fig:002])

![Значок смены языка](image/2.png){ #fig:002 width=70% }

Все переведенные файлы поместили в отдельную папку ru. (рис. [-@fig:003])

![Папка Ru](image/3.png){ #fig:003 width=70% }

Получили переведенный сайт. (рис. [-@fig:004]) (рис. [-@fig:005]) (рис. [-@fig:006])

![Сайт1](image/4.png){ #fig:004 width=70% }

![Сайт2](image/5.png){ #fig:005 width=70% }

![Сайт3](image/6.png){ #fig:006 width=70% }

Также мы добавили пост по прошедшей неделе. (рис. [-@fig:007]) (рис. [-@fig:008])

![Пост по прошедшей неделе](image/7.png){ #fig:007 width=70% }

![Пост по прошедшей неделе1](image/8.png){ #fig:008 width=70% }

Загрузили пост на тему по выбору. Также с поддержкой двух языков. (рис. [-@fig:009]) (рис. [-@fig:010])

![Пост на тему по выбору](image/9.png){ #fig:009 width=70% }

![Пост на тему по выбору1](image/10.png){ #fig:010 width=70% }

# Вывод

- Сделали поддержку английского и русского языков.

- Разместили элементы сайта на обоих языках.

- Разместили контент на обоих языках.

- Сделали пост по прошедшей неделе.

- Добавили пост на тему по выбору (на двух языках).
