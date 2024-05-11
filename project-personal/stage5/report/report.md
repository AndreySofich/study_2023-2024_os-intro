---
## Front matter
title: "Индивидуальный проект №5"
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

Создать проект на сайт


# Задание

Создать проект и сделать посты

# Выполнение проекта


Перхожу в дирректорию blog и перехожу по локальной ссылке (рис. [-@fig:001]).

![Локальная ссылка](image/1.jpg){#fig:001 width=70%}

Перехожу в папку с проектами и создаю новый проект (рис. [-@fig:002]). 

![Создание проекта](image/2.jpg){#fig:002 width=70%}
 
Добавляю посты о предыдущей неделе и пост, о языках программирования(рис. [-@fig:003]).

![Добавление постов](image/3.jpg){#fig:003 width=70%}

Отправляю все изменения  (рис. [-@fig:004]).

![Изменения](image/4.jpg){#fig:004 width=70%}

Отправляю все изменения  (рис. [-@fig:005]).

![Изменения](image/5.jpg){#fig:005 width=70%}


Проверяю выполнение, используя официальную ссылку (рис. [-@fig:006]).

![Проверка сайта](image/6.jpg){#fig:006 width=70%}



# Выводы

Я научился добавлять проекты на сайт
