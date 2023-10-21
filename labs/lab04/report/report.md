---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "Создание и процесс обработки на языке ассемблера NASM"
author: "Попутников Егор Сергеевич"

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
lot: true # List of tables
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
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM

# Задание

1. В каталоге ~/work/arch-pc/lab04 с помощью команды cp создайте копию файла
hello.asm с именем lab4.asm
2. С помощью любого текстового редактора внесите изменения в текст программы в
файле lab4.asm так, чтобы вместо Hello world! на экран выводилась строка с вашими
фамилией и именем.
3. Оттранслируйте полученный текст программы lab4.asm в объектный файл. Выполните
компоновку объектного файла и запустите получившийся исполняемый файл.
4. Скопируйте файлы hello.asm и lab4.asm в Ваш локальный репозиторий в ката-
лог ~/work/study/2023-2024/"Архитектура компьютера"/arch-pc/labs/lab04/.
Загрузите файлы на Github.



# Выполнение лабораторной работы

Создадим каталог для работы с программами на языке ассемблера NASM.(рис. @fig:001)


![](image/q.png){#fig:001 width=120% height=100% "Создание каталога"}


Создадим текстовый файл с именем hello.asm и откроем его с помощью текстового редактора.(рис. @fig:002)

![](image/w.png){#fig:002 width=120% height=100% "Создание файла hello.asm"}

Введём в него следующий текст:(рис. @fig:003)

![](image/e.png){#fig:003 width=120% height=100% "Редактирование файла"}

Проведем компиляцию для приведённого выше файла:(рис. @fig:004)

![](image/r.png){#fig:004 width=120% height=100% "Компиляция файла"}

Скомпилируем исходный файл в obj.o, обЪектный файл передадим на обработку компоновщику и запустим исполняемый файл:(рис. @fig:005)

![](image/t.png){#fig:005 width=120% height=100% "Запуск исполняемого файла"}

# Выполнение самостоятельной работы

В каталоге ~/work/arch-pc/lab04 с помощью команды cp создадим копию файла hello.asm с именем lab4.asm:(рис. @fig:006)

![](image/y.png){#fig:006 width=120% height=100% "Копирование файла"}

С помощью команды gedit внесём изменения в текст программы в
файле lab4.asm так, чтобы вместо Hello world! на экран выводилась строка с моей
фамилией и моим именем:(рис. @fig:007)

![](image/u.png){#fig:007 width=120% height=100% "Редактирование файла"}

Скопируем файлы hello.asm и lab4.asm в мой локальный репозиторий в ката-
лог ~/work/study/2023-2024/"Архитектура компьютера"/arch-pc/labs/lab04/:(рис. @fig:008)

![](image/i.png){#fig:008 width=120% height=100% "Копирование файлов в локальный репозиторий"}

Далее загрузим файлы на github:(рис. @fig:009)(рис. @fig:010)(рис. @fig:011)

![](image/o.png){#fig:009 width=120% height=100%}

![](image/p.png){#fig:010 width=120% height=200%}

![](image/a.png){#fig:011 width=120% height=200% "Загрузка файлов на github"}








# Выводы

Я освоил процедуры компиляции и сборки программ, написанных на ассемблере NASM.


