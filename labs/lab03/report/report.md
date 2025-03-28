---
## Front matter
title: "отчёт по лабораторной работе №3"
subtitle: "Дисциплина: Операционные системы"
author: "Дмитрий Сергеевич Кулябов"

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

Научиться работать с языком разметки markdown

# Задание

Создать отчёт по лабораторной работе №2.

# Теоретическое введение

Лабораторная работа является небольшой научно-исследовательской работой, которую
и оформлять следует по всем утверждённым требованиям. При подготовке отчета по лабораторной работе вы освоите ряд важных элементов, которые в дальнейшем пригодятся
вам при написании курсовой и дипломной работы.
3.2.3.1. Структура отчёта
Согласно ГОСТ 7.32-2001, любая научно-исследовательская работа должна обязательно
содержать следующие элементы:
– титульный лист;
– реферат;
– введение;
– основную часть;
– заключение.
Также ГОСТ рекомендует включить в работу и такие элементы:
– список исполнителей;
– содержание;
– нормативные ссылки;
– определения;
– обозначения и сокращения;
– список использованных источников;
– приложения.
Если вы проводите сложную работу, выполняемую в несколько этапов, то вам может
понадобиться включить в работу часть или все элементы второго списка.
3.2.3.2. Содержание основных элементов отчета
– Титульный лист. Первый лист работы оформляется строго по образцу, который обычно
приводится в методических пособиях по вашему предмету. В нем не просто требуется
указать такие элементы, как название образовательного учреждения, вид работы
и сведения об исполнителе, но и расположить их в строгом соответствии со стандартами.
– Реферат. Реферат фактически является кратким представлением всего вашего отчета
и содержит ряд статистических сведений. В нем нужно указать количество частей,
страниц работы, иллюстраций, приложений, таблиц, использованных литературных
источников и приложений. Здесь же приводится перечень ключевых слов работы
и собственно текст реферата. Последний подразумевает основные элементы работы
от поставленных целей до результатов и рекомендаций по их внедрению. В практике
вузов в отчеты по лабораторным работам реферат обычно не включают.
– Введение. Во введении типовой лабораторной работы обычно прописывают цели
проводимого исследования и задачи, выполнение которых поможет достичь поставленных целей. В то же время существуют работы, в которых студенты становятся
настоящими первооткрывателями. Приходилось ли вам хотя бы однажды испытывать
чувство крайнего любопытства и нетерпения при проведении лабораторной работы?
Ощущать, что буквально через пару минут вы найдете ответ на вопрос, на который
еще никто и никогда не находил ответа? Именно для таких исследований пишется развернутое введение с доказательством актуальности и новизны изучаемой темы. Чтобы
действительно провести исследование в той области, в которой, как говорится, еще не
ступала нога человека, во введении вам понадобится привести оценку современного
состояния рассматриваемой проблемы и обосновать необходимость ее решения.
Кулябов Д. С. и др. Операционные системы 37
– Основная часть. Так как в разных вузах и в разных дисциплинах существуют свои
тонкости проведения лабораторных работ, содержание основной части подробно
описывают в соответствующих методичках. Важно, чтобы в этом разделе работы была
отражена ее суть, описана методика и результаты проделанной работы.
В основной части прописывают следующие элементы:
– цели проводимого исследования;
– задачи, выполнение которых поможет достичь поставленных целей;
– ход работы, в котором описываются выполненные действия;
– прочие разделы, предусмотренные методическими материалами по изучаемой
дисциплине.
– Заключение. В этой части работы вам потребуется сделать выводы по полученным в ходе лабораторной работы результатам. Для этого оцените, насколько полно выполнены
поставленные задачи. В сложных работах могут присутствовать и другие элементы,
например, рекомендации для дальнейшего применения результатов проведённой
работы.

# Выполнение работы

### Создание отчёта

С помощью шаблона из лабораторной работы настраиваю файл report.md и начинаю писать, с помощью специальных команд пишу сам отчёт. (рис. [-@fig:001])

![Создание отчёта](image/1.png){#fig:001 width=70%}

После написания отчёта нужно из файла, в котором находится отчёт сделать команду make, для создания pdf и docx

![Выполнение make](image/2.png){#fig:002 width=70%}

### Пуш изменений на гитхаб

Отправляем все изменения файлов на гитхаб (рис. [-@fig:003])

![Пуш изменений](image/3.png){#fig:003 width=70%}

# Выводы

Я научился работать с языком разметки Markdown и создал отчёд для лабораторной работы

# Список литературы{.unnumbered}

