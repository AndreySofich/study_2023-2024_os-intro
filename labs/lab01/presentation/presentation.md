---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №2
subtitle: Операционные системы
author:
  - Софич А.С
institute:
  - Российский университет дружбы народов, Москва, Россия
  - НКАбд-05-23
date: 29 февраля 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'

## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---


## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Софич Андрей Геннадьевич
  * Студент
  * НКАбд-05-23
  * Российский университет дружбы народов
  * [1132237371@pfur.ru](mailto:1132237371@rudn.ru)

:::
::: {.column width="30%"}

![](./image/20.jpg)

:::
::::::::::::::


## Цели и задачи

Целью работы является приобретение практических навыков установки операционной системы на виртуальную машину и настройки необходимых компонентов.



# Выполнение лабораторной работы

## 

Устанавливаю систему sway и подбираю необходимые для работы настройки

![Запуск](image/1.png)

## 

После запуска системы начинаем загружать её 

![Загрузка](image/2.png)

## 

Изымаю оптический диск из привода

![Изъятие диска](image/3.png)

##

Обновляю пакеты 

![Обновление](image/4.png)

##

Устанавливаю программы для автоматического обновления 

![Установка](image/5.png)

##

Меняю значение Selinux

![Редактирование](image/6.png)

## 

Подключаю образ гостевого диска, монтирую его и ставлю на него драйвера

![Подключение образа](image/7.png)

##

Перезагружаю систему 

![Перезагрузка](image/8.png)

##

После создание конфигруционного файла редактирую раскладку клавиатуры

![Редактирование](image/9.png)

##

Устанавливаю pandoc

![Установка](image/10.png)

##

Устанавливаю Texlive

![Установка](image/11.png)

##

Ввожу в терминале команду dmesg, поиск определенных характеристик

![Поиски](image/12.png)

## Выводы

При выполнении работы я приобрел навыки установки операционной системы и базовых её настрек.