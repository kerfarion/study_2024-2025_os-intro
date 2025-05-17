---
## Front matter
title: "Отчет по прохождению метакурса"
subtitle: "Предмет: архитектура компьютеров"
author: "Кудинец Максим Антонович"

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

Пройти метакурс по операционным системам и получить необходимые знания для работы с markdown и bash.

# Задание

Пройти все 3 модуля в метакурсе, получить сертификат.

# Выполнение лабораторной работы

## Прохождение первого раздела метакурса: 

![1 этап](image/1.jpg){#fig:001 width=70%}

##

![2 этап](image/2.jpg){#fig:002 width=70%}

##

![3 этап](image/3.jpg){#fig:003 width=70%}

##

![4 этап](image/4.jpg){#fig:004 width=70%}

##

![5 этап](image/5.jpg){#fig:005 width=70%}

##

![6 этап](image/6.jpg){#fig:006 width=70%}

##

![7 этап](image/7.jpg){#fig:007 width=70%}

##

![8 этап](image/8.jpg){#fig:008 width=70%}

##

![9 этап](image/9.jpg){#fig:009 width=70%}

## Прохождение второго раздела метакурса:

![1 этап](image/10.jpg){#fig:010 width=70%}

##

![2 этап](image/11.jpg){#fig:011 width=70%}

##

![3 этап](image/12.jpg){#fig:012 width=70%}

##

![4 этап](image/13.jpg){#fig:013 width=70%}

3#

![5 этап](image/14.jpg){#fig:014 width=70%}

##

![6 этап](image/15.jpg){#fig:015 width=70%}

##

![7 этап](image/16.jpg){#fig:016 width=70%}

## Прохождение третьего раздела метакурса:

![1 этап](image/17.jpg){#fig:017 width=70%}

##

![2 этап](image/18.jpg){#fig:018 width=70%}

##

![3 этап](image/19.jpg){#fig:019 width=70%}

##

![4 этап](image/20.jpg){#fig:020 width=70%}

##

![5 этап](image/21.jpg){#fig:021 width=70%}

##

![6 этап](image/22.jpg){#fig:022 width=70%}

##

![7 этап](image/23.jpg){#fig:023 width=70%}

## Сертификат:

![Сертификат](image/24.jpg){#fig:024 width=70%}

# Выводы

Прошел метакурс. Получил и закрепил необходимые знания для работы с языком bash и markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
