---
## Front matter
title: "Отчёт по первому этапу итогового проекта"
subtitle: "Специальность: архитерктура компьютеров"
author: "Комаров Владимир Артемович"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

# Задание

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

1. Переходим в режим суперпользователя и устанавливаем go hugo. (рис. [-@fig:001]).

![Установка go hugo](image/1.png){#fig:001 width=70%}

2. Создаем репозиторий на github. (рис. [-@fig:002]).

![Создание репозитория](image/2.png){#fig:002 width=70%}

3. Скачиваем пакеты данных. (рис. [-@fig:003]).

![Загрузка пакетов данных](image/3.png){#fig:003 width=70%}

4. Создаем новый репозиторий, (рис. [-@fig:004]). клонируем его и проверяем, на какой ветке мы сейчас находимся. (рис. [-@fig:005]).

![Создание нового репозитория](image/4.png){#fig:004 width=70%}

![Клонирование репозитория, проверка ветки](image/5.png){#fig:005 width=70%}

5. Делаем коммит в этот репозиторий. (рис. [-@fig:006]).

![Первый коммит](image/6.png){#fig:006 width=70%}

6. Добавляем подраздел в ветку main. (рис. [-@fig:007]).

![Добавление подраздела](image/7.png){#fig:007 width=70%}

7. Делаем коммит подраздела на репозиторий. (рис. [-@fig:008]).

![Коммит подраздела](image/8.png){#fig:008 width=70%}

8. Проверяем наличие выложенных файлов на репозитории. (рис. [-@fig:009]).

![Выгруженные файлы на github](image/9.png){#fig:009 width=70%}

# Выводы

Разместил на Github pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

