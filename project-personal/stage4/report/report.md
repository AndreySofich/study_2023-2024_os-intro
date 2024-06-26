---
## Front matter
title: "Индивидуальный проект №4"
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

Добавить ссылки и сделать посты

# Выполнение проекта


Перхожу в дирректорию blog/content/authors/index.md и меняю ссылки на собственные (рис. [-@fig:001]).

![Смена ссылок](image/1.jpg){#fig:001 width=70%}

Проверяю прапвильность выполнения на сайте,перейдя по локальной ссылке (рис. [-@fig:002]). 

![Проверка ссылок](image/2.jpg){#fig:002 width=70%}
 
Добавляю посты о предыдущей неделе и пост, о создании презентаций (рис. [-@fig:003]).

![Добавление постов](image/3.jpg){#fig:003 width=70%}

Отправляю все изменения  (рис. [-@fig:004]).

![Изменения](image/4.jpg){#fig:004 width=70%}

Проверяю выполнение, используя официальную ссылку (рис. [-@fig:005]).

![Проверка сайта](image/5.jpg){#fig:005 width=70%}



# Выводы

Я научился добавлять ссылки на сайт
