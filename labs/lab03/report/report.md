---
## Front matter
title: "Отчёт по лабораторной работе"
subtitle: "Язык разметки Markdown"
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
Целью работы является освоение процедуры оформления отчётов с помощью легковесного языка разметки Markdown.

# Задание
1. В соответствующем каталоге сделайте отчёт по лабораторной работе № 2 в формате
Markdown. В качестве отчёта необходимо предоставить отчёты в 3 форматах: pdf, docx
и md.
2. Загрузите файлы на github

# Выполнение лабораторной работы

1.Откроем терминал.Перейдем в каталог курса сформированный при выполнении лабораторной работы №2.(рис. @fig:001)

![Перемещение по файловой системе](image/1.png){#fig:001 width=70%}

2.Обновим локальный репозиторий, скачав изменения из удалённого репозитория с помощью команды.(рис. @fig:002)

![Обновление данных репозитория](image/2.png){#fig:002 width=70%}

3.Переходим в каталог с шаблоном отчёта по лабораторной работе №3.(рис. @fig:003)

![Перемещение по файловой системе](image/3.png){#fig:003 width=70%}

4.Проведём компиляцию отчёта с использованием Makefile.(рис. @fig:004)

![Процесс компиляции](image/4.png){#fig:004 width=70%}

5.Проверим успешность компиляции.(рис. @fig:005)

![Просмотр файлов](image/5.png){#fig:005 width=70%}

6.Удалим полученные файлы с использованием Makefile.(рис. @fig:006)

![Удаление файлов](image/6.png){#fig:006 width=70%}

7.Проверим правильность удаления файлов.(рис. @fig:007)

![Просмотр файлов](image/7.png){#fig:007 width=70%}

8.Откроем файл report.md с помощью любого текстового редактора, например gedit.(рис. @fig:008)

![Запуск текстового редактора](image/8.png){#fig:008 width=70%}

9.Далее заполним и скомпилируем отчёт с использованием Makefile. (рис. @fig:009)

![Название рисунка](image/9.png){#fig:009 width=70%}

10.Загрузим файлы на Github.


![](image/10.png){#fig:010 width=70%} 

![](image/11.png){#fig:011 width=70%}

![](image/12.png){#fig:012 width=70%}

![](image/13.png){#fig:013 width=70%}

# Выводы

В процессе выполнения лабораторной работы я освоил процедуры оформления отчётов с помощью легковесного языка разметки Markdown.

