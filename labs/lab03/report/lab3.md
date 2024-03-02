---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Операционные системы"
author: "Калашникова Ольга Сергеевна"

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

После выполнения данной работы мы должны научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

- Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
– В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве, поскольку он должен содержать скриншоты, Makefile и т.д.)

# Выполнение лабораторной работы

Начинаем оформление с заголовка. Вписываем какая лабораторная работа, дисциплину и Имя. Это будет наш титульник.(рис. [-@fig:001]).

![Оформление титульника](image/1.png){#fig:001 width=70%}

Заполняем цель работы и задание. Для обозначения абзацев выделяем пустую строку. Для создания пронумерованного списка, ставим номер, точку и пробел перед текстом (рис. [-@fig:002]).

![Оформление цели и задачи](image/2.png){#fig:002 width=70%}

Переходим к оформлению основной части. Для подзаголовка использвуем два символа октоторп. Картинки вставляем при помощи способа, указанного в примере (изображения которые мы вставляем должны находиться в указанной папке). (рис. [-@fig:003]).

![Оформление основной части](image/3.png){#fig:003 width=70%}

Далее оформляем контрольные вопросы, я использую пронумерованный список и обычный, он задаётся при помощи "- " (рис. [-@fig:004]).

![Оформление контрольных вопросов](image/4.png){#fig:004 width=70%}

В завершении работы пишем вывод и источники. Ссылки на источники можно вставить в файл bib (рис. [-@fig:005]).

![Оформление вывода и списка литературы](image/5.png){#fig:005 width=70%}

# Выводы

Я научилась оформлять отчёты с помощью легковесного языка разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
