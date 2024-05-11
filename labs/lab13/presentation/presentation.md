---
## Front matter
lang: ru-RU
title: Доклад по архитектуре компьютера
subtitle: Система инициализации SystemV
author:
  - Софич А.С
institute:
  - Российский университет дружбы народов, Москва, Россия
  - НКАбд-05-23
date: 24 мая 2024

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

![](./image/50.jpg)

:::
::::::::::::::


# Доклад

## Что такое System V

System V init (или просто «SysV») — это система инициализации, которая существует со времен операционной системы System V, которая была выпущена в 1983 году.

![SystemV на компьютере хх в.](image/д1.jpg)

##  Как работает System V init

Классический System V init читает файл /etc/inittab и выполняет ряд предписаний, которые прописаны в этом файле.

id:3:initdefault:

si::sysinit:/etc/rc.d/rc.sysinit

l3:3:wait:/etc/rc.d/rc 3

1:2345:respawn:/sbin/mingetty tty1

ca::ctrlaltdel:/sbin/shutdown -t3 -r now

## Уровни загрузки 

Уровни загрузки — это некая условность, которая позволяет управлять загружаемыми службами. 
Ближайший аналог в windows – это загрузка в безопасном режиме, когда грузится только ограниченное число драйверов и стартует минимальное количество служб, загрузка с отладкой, когда каждое действие дополнительно протоколируются и обычная полноценная загрузка.
![Уровни загрузки](image/д2.jpg)

## Основные различия SystemVinit от SystemD

![Сравнение систем инициализации](image/д3.jpg)

##

![Различия управления процессами и сервисами](image/д4.jpg)


## Заключение 

SysV до недавнего времени была основной системой инициализации в большинстве дистрибутивов Linux, но из-за некоторых своих недостатков для нее было разработано несколько замен, в том числе Systemd.
