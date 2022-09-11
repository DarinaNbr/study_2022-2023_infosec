---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
subtitle: Основы информационной безопасности
author:
  - Набережных Дарина Денисовна, НПМбд-01-19
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 4 октября 2022 года

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
---


# Дискреционное разграничение прав. Изучение дополнительных атрибутов

## Цель работы 

- Изучить механизмы изменения индентификатора.
- Изучить особенности работы с дополнительными атрибутами

## Задачи лабораторной работы

- Создать программу, выводящую SetUID, SetGID, Sticky
- Создать программу для чтения файлов и проверить ее вывод 

# Ход выполнения лабораторной работы 

## Создание файла simpleid

Создадим файл simpleid и запишем в него программу:

![Текст программы в simpleid](image/1.jpg) 

## Компиляция программы

Скомпилируем программу и посмотрим ее вывод:

![Компиляция программы simpleid](image/2.jpg) 

## Создание файла simpleid2

Создадим файл simpleid2 на основе simpleid и запишем в него следующую программу:

![Текст программы в simpleid2](image/3.jpg) 

## Компиляция программы simpleid2

Скомпилируем программу simpleid2

![Компиляция simpleid2](image/4.jpg) 

## Запуск программы

Посмотрим, что выводит программа simpleid2

![Вывод программы simpleid2.с](image/5.jpg) 

## Установка SetUID-бита 

Установим бит

![Установка SetUID бита](image/6.jpg) 

## Запуск программы

Посмотрим, что выводит программа simpleid2

![Вывод программы simpleid2.с](image/7.jpg) 

## Установка SetGID-бита 

Установим бит

![Установка SetGID бита](image/8.jpg) 

## Создание программы

Создадим программу и запишем в нее следующий текст:

![Создание программы readfile](image/9.jpg) 

## Компиляция программы readfile

Скомпилируем программу readfile

![Компиляция readfile](image/10.jpg) 

## Выводы

- Узнала механизмы изменения идентификатора



