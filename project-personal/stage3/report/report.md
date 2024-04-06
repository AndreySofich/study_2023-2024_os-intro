---
## Front matter
title: "Индивидуальный проект №3"
subtitle: "Опереционные системы"
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

Нучиться добавлять данные на сайт


# Задание

Добавить к сайту данные о навыках и опыте и сделать посты

# Выполнение проекта


Прописываем hugo server и попадаем на сайт через локальную ссылку (рис. [-@fig:001]).

![Команда hugo server](image/1.png){#fig:001 width=70%}

Заходим в папку authors и редактируем файл index.md, добавляя информацию о навыках (рис. [-@fig:002]). 

![Редактирование файла](image/2.png){#fig:002 width=70%}
 
В папке content редактируем файл, добавляя информацию об опыте работы (рис. [-@fig:003]).

![Добавление информации](image/3.png){#fig:003 width=70%}

Добавляем и бновляем посты  (рис. [-@fig:004]).

![Редактирование постов](image/4.png){#fig:004 width=70%}

Обновляем все изменения и открываем сайт через публичную ссылку (рис. [-@fig:005]).

![Сайт](image/5.png){#fig:005 width=70%}




# Выводы

Я научился добавлять данные на сайт

