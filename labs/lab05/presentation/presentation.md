---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №5
subtitle: Настройка рабочей среды
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

Настроить рабочую среду



# Выполнение лабораторной работы

## 

Устанавливаю менеджер паролей pass

![Установка](image/1.png)

## 

Устанавливаю gopass

![Установка](image/2.png)

## 

Просматриваю список ключей

![Список ключей](image/3.png)

##

Инициализирую хранилище 

![Инициализация](image/4.png)

##

Создаю структуру git 

![Создание структуры](image/5.png)

##

Создаю репозиторий, задаю адрес на хостинге, синхранизирую и создаю изменения в файловой системе 

![Действия с репозиторием](image/6.png)

## 

Устанавливаю программу, обеспечивающую интерфейс native messaging

![Установка программы](image/7.png)

##

Устанавливаю дополнительное программное обеспечение

![Установка](image/8.png)

##

Устанавливаю шрифты

![Установка](image/9.png)

##

Устанавливаю бинарный файл и создаю репозиторий на основе шаблона 

![Установка файла и создание репозитория](image/10.png)

##

Инициализирую chezmoi с репозиторием dotfiles 

![Инициализация chezmoi](image/11.png)

##

Проверяю изменение,которые внесет chezmoi

![Проверка](image/12.png)

##

Меня устраивают изменения,поэтому запускаю chezmoi apply

![Запуск](image/13.png)

##

Извлекаю изменения и применяю их, смотрю,что изменится,не примененяя изменения

![Операции с chezmoi](image/14.png)

##

Включаю функцию,которая может автоматически отправлять изменения в исходный каталог в репозиторий 

![Редактирование файла конфигурации](image/15.png)



## Выводы

Я настроил рабочую среду

