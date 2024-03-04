
---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №4
subtitle: Продвинутое использование git
author:
  - Софич А.С
institute:
  - Российский университет дружбы народов, Москва, Россия
  - НКАбд-05-23
date: 04 марта 2024

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

![](./image/18.jpg)

:::
::::::::::::::


## Цели и задачи

Получение навыков правильной работы с репозиториями git



# Выполнение лабораторной работы

## 

Устанавливаю gitflow 

![Установка](image/1.png)

## 

Для работы с NODE.JS добавим каталог с исполняемыми файлами. Запускаю, используя команду pnpm setup 

![Запуск](image/2.png)

## 

Создаю пустой файл в новый репозиторий, делаю первый коммит и выкладываю на github 

![Добавление на github](image/3.png)

##

Выполняю конфигурацию для пакетов NODE.js 

![Конфигурация](image/4.png)

##

Добавляю новый файлы,выполняю коммит и отправляю изменения на github 

![Добавление изменений на github](image/5.png)

##

Инициализирую gitflow, префикс для ярлыков устанавливаю в v 

![Инициализация gitflow](image/6.png)

## 

Проверяю,что нахожусь на ветке develop и отправляю весь репозиторий в хранилище 

![Загрузка в хранилище](image/7.png)

##

Уставливаю внешнюю ветку как вышестоящую для этой ветке 

![Установка внешней ветки](image/8.png)

##

Cоздаю релиз с версией 1.0.0 

![Создание релиза](image/9.png)

##

Cоздаю журнал изменений и добавляю его в индекс 

![Создание журнала](image/10.png)

##

Заливаю релизную ветку в основную ветку 

![Вложение ветки](image/11.png)

##

Отправляю данные на github 

![Отправление данных](image/12.png)

##

Создаю релиз на GitHub 

![Cоздание релиза](image/13.png)

##

Создаю ветку для новой функциональности 

![Cоздание ветки](image/14.png)

##

Обновляю файл package.json и создаю журнал изменений, добавляю журнал в индекс и заливаю ветку в основную 

![Действия с веткой](image/15.png)

##

Отправляю данные на github 

![Отправление данных](image/16.png)

##

Cоздаю релиз на GitHub с комментарием из журнала изменений 

![Создание релиза](image/17.png)

## Выводы

В ходе работы я получение навыков правильной работы с репозиториями git

