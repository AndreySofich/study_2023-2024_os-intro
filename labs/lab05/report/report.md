---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Настройка рабочей среды"
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

Настроить рабочую среду.


# Задание

Настроить рабочую среду.


# Выполнение лабораторной работы

Устанавливаю менеджер паролей pass (рис. [-@fig:001]).

![Установка](image/1.png){#fig:001 width=70%}

Устанавливаю gopass(рис. [-@fig:002]).

![Установка](image/2.png){#fig:002 width=70%}

Просматриваю список ключей (рис. [-@fig:003]).

![Список ключей](image/3.png){#fig:003 width=70%}

Инициализирую хранилище  (рис. [-@fig:004]).

![Инициализация](image/4.png){#fig:004 width=70%}

Создаю структуру git (рис. [-@fig:005]).

![Создание структуры ](image/5.png){#fig:005 width=70%}

Создаю репозиторий, задаю адрес на хостинге, синхранизирую и создаю изменения в файловой системе (рис. [-@fig:006]).

![Действия с репозиторием](image/6.png){#fig:006 width=70%}

Устанавливаю программу, обеспечивающую интерфейс native messaging (рис. [-@fig:007]).

![Установка программы](image/7.png){#fig:007 width=70%}

Устанавливаю дополнительное программное обеспечение (рис. [-@fig:008]).

![Установка](image/8.png){#fig:008 width=70%}

Устанавливаю шрифты  (рис. [-@fig:009]).

![Установка](image/9.png){#fig:009 width=70%}

Устанавливаю бинарный файл и создаю репозиторий на основе шаблона (рис. [-@fig:010]).

![Установка файла и создание репозитория](image/10.png){#fig:010 width=70%}

Инициализирую chezmoi с репозиторием dotfiles (рис. [-@fig:011]).

![Инициализация chezmoi](image/11.png){#fig:011 width=70%}

Проверяю изменение,которые внесет chezmoi (рис. [-@fig:012]).

![Проверка изменений](image/12.png){#fig:012 width=70%}

Меня устраивают изменения,поэтому запускаю chezmoi apply (рис. [-@fig:013]).

![Запуск](image/13.png){#fig:013 width=70%}

Извлекаю изменения и применяю их, смотрю,что изменится,не примененяя изменения (рис. [-@fig:014]).

![Операции с chezmoi](image/14.png){#fig:014 width=70%}

Включаю функцию,которая может автоматически отправлять изменения в исходный каталог в репозиторий (рис. [-@fig:015]).

![Редактирование файла конфигурации](image/15.png){#fig:015 width=70%}


# Выводы

Я настроил рабочую среду

# Список литературы{.unnumbered}

 Лабораторная работа №5
