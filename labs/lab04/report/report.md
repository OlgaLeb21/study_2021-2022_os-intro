---
## Front matter
title: "Лабораторная работа №4"
subtitle: "Основы интерфейса взаимодействия
пользователя с системой Unix на уровне командной строки"
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
Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Теоретическое введение
В операционной системе типа Linux взаимодействие пользователя с системой обычно
осуществляется с помощью командной строки посредством построчного ввода команд. При этом обычно используется командные интерпретаторы языка shell: /bin/sh;
/bin/csh; /bin/ksh.

Командой в операционной системе называется записанный по
специальным правилам текст (возможно с аргументами), представляющий собой указание на выполнение какой-либо функций (или действий) в операционной системе.
Обычно первым словом идёт имя команды, остальной текст — аргументы или опции,
конкретизирующие действие.
Общий формат команд можно представить следующим образом:
<имя_команды><разделитель><аргументы>

# Ход работы
1. Определили полное имя нашего домашнего каталога: (рис. [-@fig:001])

![Домашний каталог](image/1.png){ #fig:001 width=70% }

2. Выполнили следующие действия:

Перешли в каталог /tmp и вывели его содержимое. (рис. [-@fig:002])

![Содержимое каталога](image/2.png){ #fig:002 width=70% }

Просмотрели различные опции команды ls. (рис. [-@fig:003]) (рис. [-@fig:004]) (рис. [-@fig:005]) (рис. [-@fig:006])

![Команда ls -a](image/3.png){ #fig:003 width=70% }

![Команда ls -alF](image/4.png){ #fig:004 width=70% } 

![Команда ls -l](image/5.png){ #fig:005 width=70% }

![Команда ls -F](image/6.png){ #fig:006 width=70% }

Перешли в каталог /var/spool и проверили наличие подкаталога с именем cron. Данный подкаталог существует. (рис. [-@fig:007])

![Проверка наличия подкаталога](image/7.png){ #fig:007 width=70% }

Перешли в свой домашний каталог и вывели на экран его содержимое. Определили, кто является владельцем файлов и подкаталогов. (рис. [-@fig:008]) (рис. [-@fig:009])

![Владелец каталогов](image/8.png){ #fig:008 width=70% }

![Владелец каталогов](image/9.png){ #fig:009 width=70% }

3. В домашнем каталоге создали новый каталог с именем newdir. (рис. [-@fig:010])

![Создание каталога newdir](image/10.png){ #fig:010 width=70% }

В каталоге ~/newdir создали новый каталог с именем morefun. (рис. [-@fig:011])

![Создание каталога morefun](image/11.png){ #fig:011 width=70% }

В домашнем каталоге создали одной командой три новых каталога с именами
letters, memos, misk (рис. [-@fig:012]). Затем удалили эти каталоги одной командой.(рис. [-@fig:012]) (рис. [-@fig:013])

![Создание трёх каталогов](image/12.png){ #fig:012 width=70% }

![Удаление трёх каталогов](image/13.png){ #fig:013 width=70% }

Попробовали удалить ранее созданный каталог ~/newdir командой rm. Проверили,
был ли каталог удалён.
Удалили каталог ~/newdir/morefun из домашнего каталога. Проверили, был ли
каталог удалён.(рис. [-@fig:014]) (рис. [-@fig:015]) 

![Удаление каталога morefun](image/14.png){ #fig:014 width = 70% }

![Удаление newdir](image/15.png){ #fig:015 width=70% }

4. С помощью команды man определили, какую опцию команды ls нужно использовать для просмотра содержимое не только указанного каталога, но и подкаталогов,
входящих в него. (рис. [-@fig:016]) (рис. [-@fig:017]) 

![Функции команды ls](image/16.png){ #fig:016 width=70% }

![Функции команды ls](image/17.png){ #fig:017 width=70%}

5. С помощью команды man определили набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов. (рис. [-@fig:018])

![Удаление трёх каталогов](image/18.png){ #fig:018 width=70% }

6. Использовали команду man для просмотра описания следующих команд: cd, pwd, mkdir,
rmdir, rm. Пояснили основные опции этих команд. (рис. [-@fig:023]) (рис. [-@fig:024]) (рис. [-@fig:025]) (рис. [-@fig:026]) (рис. [-@fig:027]) (рис. [-@fig:028]) (рис. [-@fig:029]) (рис. [-@fig:030]) (рис. [-@fig:031]) (рис. [-@fig:032]) (рис. [-@fig:033]) (рис. [-@fig:034]) 

![man <команда>](image/33.png){ #fig:033 width=70% }

![Функции команды cd](image/23.png){ #fig:023 width=70% }

![Функции команды cd](image/24.png){ #fig:024 width=70% }

![Функции команды cd](image/25.png){ #fig:025 width=70% }

![Функции команды cd](image/26.png){ #fig:026 width=70% } 

![Функции команды pwd](image/27.png){ #fig:027 width=70% }

![Функции команды pwd](image/28.png){ #fig:028 width=70% }

![Функции команды mkdir](image/29.png){ #fig:029 width=70% }

![Функции команды rmdir](image/30.png){ #fig:030 width=70% }

![Функции команды rmdir](image/31.png){ #fig:031 width=70% }

![Функции команды rm](image/32.png){ #fig:032 width=70% }

![Функции команды rm](image/34.png){ #fig:034 width=70% }

7. Используя информацию, полученную при помощи команды history, выполнили модификацию и исполнение нескольких команд из буфера команд. (рис. [-@fig:035]) (рис. [-@fig:036]) (рис. [-@fig:037]) 

![команда history](image/35.png){ #fig:035 width=70% }

![Модификация](image/36.png){ #fig:036 width=70% }

![Исполнение команды](image/37.png){ #fig:037 width=70% }

# Вывод
Приобрели практические навыки взаимодействия пользователя с системой посредством командной строки.

# Ответы на вопросы 

1. Что такое командная строка?

Командная строка (консоль или Терминал) – это специальная программа, которая позволяет управлять компьютером путем ввода текстовых команд с клавиатуры.

2. При помощи какой команды можно определить абсолютный путь текущего каталога?
Приведите пример.

pwd (Пример - рис.1)

3. При помощи какой команды и каких опций можно определить только тип файлов
и их имена в текущем каталоге? Приведите примеры.

При помощи команды ls -F (Пример есть в ходе лабораторной работы)

4. Каким образом отобразить информацию о скрытых файлах? Приведите примеры.

Файл считается скрытым, если его название начинается с символа точка «.». Обычно такие файлы используются приложениями для хранения настроек, конфигураций и другой информации, которую нужно скрыть от пользователя. Чтобы просмотреть скрытые файлы в каталоге необходимо ввести команду ls -a.

5. При помощи каких команд можно удалить файл и каталог? Можно ли это сделать одной и той же командой? Приведите примеры.

При помощи команд rm и rmdir можно удалить файл и каталог. Это нельзя сделать одной и той же командой, т.к. rmdir используется, чтобы удалить пустой каталог, а rm используется, чтобы удалить непустые файлы или целые деревья каталогов.

6. Каким образом можно вывести информацию о последних выполненных пользователем командах? работы?

Команда history

7. Как воспользоваться историей команд для их модифицированного выполнения? Приведите примеры.

С помощью следующей команды: !<номер_команды>:s/<что_меняем>/<на_что_меняем> Например: history 3 ls -a . !3:s/a/F ls -F

8. Приведите примеры запуска нескольких команд в одной строке.

В одной строке можно записать несколько команд. Если требуется выполнить последовательно несколько команд, записанный в одной строке, то для этого используется символ точка с запятой. Пример: cd; ls.

9. Дайте определение и приведите примера символов экранирования.

Экранирующий символ сообщает интерпретатору, что следующий за ним символ должен восприниматься как обычный символ. Пример: echo "Привет" # Привет echo "Он сказал: "Привет"." # Он сказал: "Привет".

10. Охарактеризуйте вывод информации на экран после выполнения команды ls с опцией l.

Если используется опция l в команде ls, то на экран выводится подробный список, в котором будет отображаться владелец, группа, дата создания, размер и другая информация о файлах и каталогах.

11. Что такое относительный путь к файлу? Приведите примеры использования относительного и абсолютного пути при выполнении какой-либо команды.

Относительный путь – это путь к файлу относительно текущей папки. Начинается со знака "/".

12. Как получить информацию об интересующей вас команде?

С помощью команды man.

13. Какая клавиша или комбинация клавиш служит для автоматического дополнения
вводимых команд?

Клавиша "Tab".