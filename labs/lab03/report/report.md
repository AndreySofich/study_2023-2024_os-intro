---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Операционные системы"
author: "Софич Андрей Геннадьевич"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью работы является приобретение практических навыков по оформелению отчётов на языке разметки mousepad.


# Задание

1.Создание отчёта

# Выполнение лабораторной работы
##Создание отчёта

Открываю файл отчёта используя mousepad (рис. [-@fig:001]).

![Открытие отчёта](image/1.png){#fig:001 width=70%}

После полного создания отчета компилирую его, используя команду make (рис. [-@fig:002]).

![Компилирование отчёта](image/2.png){#fig:002 width=70%}

Отправляю созданные файлы в глобальный репозиторий и сохраняю изменения (рис. [-@fig:003]).

![Отправление файлов](image/3.png){#fig:003 width=70%}

Отправляю все файлы на GitHub

![Отправка файлов на гит](image/4.png){#fig:004 width=70%} 



# Выводы

Я научился создавать отчёты

# Список литературы{.unnumbered}

::: лабораторная работа №3
:::
