---
layout: page
title: Про предмет
description: Загальна інформація.
nav_order: 1
---

# Про предмет
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - Рівень володіння англійською мовою не нижче А2.
- Базовi знання з лiнiйної алгебри та теорiї ймовiрностей.
- Досвiд тренування глибинних мереж (iнiцiалiзацiя, оптимiзацiя, регуляризацiя).

Підручники
: 1. Goodfellow, I., Bengio, Y., & Courville, A. (2016).  [*Deep Learning.* ](https://www.deeplearningbook.org/) MIT press.
2. Sergios Karagiannakos (2021). [*Deep Learning in Production.*](https://www.amazon.com/Deep-Learning-Production-Sergios-Karagiannakos-ebook/dp/B09MJF24HZ/ref=cm_cr_arp_d_pl_foot_top?ie=UTF8#customerReviews) AI Summer.


## На випадок повітряної тривоги
{% assign specifics = site.slides | where: "title", "Повітряна тривога" | first %}
{{ specifics.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}