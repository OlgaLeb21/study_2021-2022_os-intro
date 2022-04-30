---
## Front matter
title: "Индивидуальный проект"
subtitle: "Индивидуальный проект. Часть 1"
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
Размещение на Github pages заготовки для персонального сайта.

- Установить необходимое программное обеспечение.
- Скачать шаблон темы сайта.
- Разместить его на хостинге git.
- Установить параметр для URLs сайта.
- Разместить заготовку сайта на Github pages.

# Ход работы

Скачали исполняемй файл Hugo, чтобы генерировать страницы сайта. (рис. [-@fig:001]) (рис. [-@fig:002])

![Скачиваем Hugo](1.png){ #fig:001 width=70% }

![Скачиваем Hugo](2.png){ #fig:002 width=70% }

Разархивируем файл, создадим папку bin и скопируем файл higo туда. (рис. [-@fig:004])

![Hugo, папка bin](4.png){ #fig:004 width=70% }

Далее необходимо создать репозиторий. Находим его на сайте ТУИС.(рис. [-@fig:006])

![Шаблон сайта](6.png){ #fig:006 width=70% }

Создаем репозиторий с именем blog. (рис. [-@fig:007])

![Создание репозитория](7.png){ #fig:006 width=70% }

Клонируем репозиторий через консоль.(рис. [-@fig:003]) (рис. [-@fig:008])

![Создание репозитория. Клонирование](3.png){ #fig:003 width=70% }

![Создание репозитория. Клонирование](8.png){ #fig:007 width=70% }

Заходим в blog, сморим файлы. (рис. [-@fig:009])

![Создание репозитория. Клонирование](9.png){ #fig:009 width=70% }

Выполняем коману ~/bin/hugo. (рис. [-@fig:010])

![Создание репозитория. Клонирование](10.png){ #fig:010 width=70% }

Появился каталог public, его пока удалим. (рис. [-@fig:011]) (рис. [-@fig:012]) (рис. [-@fig:013])

![Простмотр файлов](11.png){ #fig:011 width=70% }

!Удаление public](12.png){ #fig:012 width=70% }

![Проверка](13.png){ #fig:013 width=70% }

Выполняем команду ~/bin/hugo server. У нас появится ссылка, переходим по ней. (рис. [-@fig:014])

![Ссылка](14.png){ #fig:014 width=70% }

В браузере появился сайт. Необходимо убрать зеленый фон. Для этого на сайте есть инструкция. Сделаем необходимые действия, после которых цвет изменится на белый.

![Сайт](15.png){ #fig:015 width=70% }

Перейдём в Гитхаб и создадим новый репозиторий. Зададим специальное название как имя пользователя. (рис. [-@fig:016])

![Создание нового репозитория](16.png){ #fig:016 width=70% }

Клонируем его через консоль. (рис. [-@fig:017])

![Клонирование нового репозитория](17.png){ #fig:017 width=70% }

Создадим новую ветку main. (рис. [-@fig:018])

![Создание ветки main](18.png){ #fig:018 width=70% }

Создадим новый файл README.md и отправляем его в репозиторий. (рис. [-@fig:019])

![Файл README.md](19.png){ #fig:019 width=70% }

Проверяем наличие файла. (рис. [-@fig:020])

![Проверка](20.png){ #fig:020 width=70% }

Создаём каталог public. Мы увидим, что существует игнорируемые каталоги. (рис. [-@fig:021])

![Создание каталога public](21.png){ #fig:021 width=70% }

Исправим это, добавив #. (рис. [-@fig:022])

![Исправляем игнорируемые каталоги](22.png){ #fig:022 width=70% }

После комментария каталоги игнорироваться не будут. (рис. [-@fig:023])

![Проверка](23.png){ #fig:023 width=70% }

Повторяем ранее введенную команду, public добавляется в index.  (рис. [-@fig:024])

![Проверка](24.png){ #fig:024 width=70% }

Еще проверим, что каталог подключен к репозиторию. (рис. [-@fig:025])

![Проверка](25.png){ #fig:025 width=70% }

Далее проделываем стандартные действия, чтобы отправить файлы в репозиторий. (рис. [-@fig:026]) (рис. [-@fig:026])

![Отправка файлов](26.png){ #fig:026 width=70% }

![Отправка фалов](27.png){ #fig:027 width=70% }

В репозитории появились новые файлы. (рис. [-@fig:028])

![Файлы в репозитории](28.png){ #fig:028 width=70% }

Сайт создан. (рис. [-@fig:029])

![Сайт](29.png){ #fig:029 width=70% }

# Вывод
- Установили необходимое программное обеспечение.
- Скачали шаблон темы сайта.
- Разместили его на хостинге git.
- Установили параметр для URLs сайта.
- Разместили заготовку сайта на Github pages.


