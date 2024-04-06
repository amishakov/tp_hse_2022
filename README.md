![year][0] ![status][1] ![progress][2]

**4 модуль, 2023/2024 учебный год, ВШЭ ВШБ ДБИ**

## [Канал курса в telegram](https://t.me/tp_hse_2024)

## [Рабочая ведомость по курсу / TODO]()

# Аннотация

*Курс про все, что связано с созданием ПО, кроме непосредственно написания программного кода*

Курс состоит из лекционного материала (в формате записей и тестов к ним) и очных "живых" семинарских занятий.

Лекционный материал включает краткий обзор важных с точки зрения процесса разработки понятий: методы отладки и этапы исправления дефектов ПО, критерии хорошей и неудачной архитектуры, этапы проектирования и разработки, методологии разработки.
Семинарский материал состоит из рассказа о важных инструментах программиста: системы контроля версий, системы сборки, gdb, valgrind, развертывание и настройка систем непрерывной интеграции.

Цель курса — дать слушателям, которые параллельно изучают языки программирования, алгоритмы и т.п., информацию и дополнительные знания, какими инструментами можно пользоваться и на что обращать внимание при создании рыночного программного продукта.

# Лекционный материал 

## Записи лекций и тесты 

[Плейлист с лекциями на YouTube](https://www.youtube.com/playlist?list=PLSFRPndr3MpzgdGyIiBA6WgUyUKg38RDC)

*Курсивом* выделены предварительные даты, **жирным** - фактические.

| № | Тема | Ссылка на запись | Ссылка на презентацию(и) | Контрольный тест | Дата публикации теста | Дата и время закрытия теста |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 0 | Организационное | [YouTube](https://youtu.be/3pTX38B6k5c) | *нет презентации* | *нет теста* |
| 1 | Этапы развития проекта | [YouTube](https://youtu.be/-QJpDnzwSwA) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec1.pdf) | Тест №1 | *7 апреля* | *14 апреля 18:00* |
| 2 | Базовые понятия о языках программирования | [YouTube](https://www.youtube.com/watch?v=uCq1cTMrzWs) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec2.pdf) | Тест №1 | *7 апреля* | *14 апреля 18:00* |
| 3 | Основные диаграммы UML | [YouTube(1/2)](https://www.youtube.com/watch?v=CTWDKuQBb84) [YouTube(2/2)](https://www.youtube.com/watch?v=zFTXtkBTmzk) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec3.pdf) | Тест №2 | *14 апреля* | *21 апреля в 18:00* |
| 4 | CI/CD/CD | [YouTube](https://www.youtube.com/watch?v=I6NVeuzzSyY) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec4.pdf) | Тест №2 | *14 апреля* | *21 апреля в 18:00* |
| 5 | Отладка ПО, ч.1: работа с ошибками ПО | [YouTube(1/2)](https://www.youtube.com/watch?v=6StbXboJJCg) [YouTube(2/2)](https://www.youtube.com/watch?v=HuYGaVWVJd0)| [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec5.pdf) | Тест №3 | *21 апреля* | *28 апреля в 18:00* |
| 6 | Отладка ПО, ч.2: техники отладки | [YouTube](https://www.youtube.com/watch?v=0RHzG8SBM9U) [YouTube(дополнение)](https://www.youtube.com/watch?v=xgDl2NX0mSI) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec6.pdf) | Тест №3 | *21 апреля* | *28 апреля в 18:00* |
| 7 | Управление качеством ПО, ч.1 | [YouTube](https://youtu.be/PAw5dwmfimg) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec7.pdf) | Тест №4 | *28 апреля* | *5 мая в 18:00* |
| 8 | Управление качеством ПО, ч.2 | [YouTube(предисловие)](https://youtu.be/t7rLxcOQXrM) [YouTube](https://youtu.be/uJUFQqtrPrI) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec8.pdf) | Тест №4 | *28 апреля* | *5 мая в 18:00* |
| 9 | Принципы проектирования ПО, ч.1 | [YouTube](https://www.youtube.com/watch?v=PMVgPAlZQGc) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec9.pdf) | Тест №5 | *12 мая* | *19 мая в 18:00* |
| 10 | Принципы проектирования ПО, ч.2 | [YouTube](https://www.youtube.com/watch?v=ZgDWK9PGxuU) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec10.pdf) | Тест №5 | *12 мая* | *19 мая в 18:00* |
| 11 | Архитектурные паттерны | [YouTube(1/2)](https://youtu.be/54JUwNgaa1Q) [YouTube(2/2)](https://youtu.be/yRi-HnTiLAk) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec11.pdf) | Тест №6 | *19 мая* | *26 мая в 18:00* |
| 12 | Методологии разработки ПО | [YouTube(1/2)](https://www.youtube.com/watch?v=i0CpJxwsov8) [YouTube(2/2)](https://www.youtube.com/watch?v=2uOZOqg9oaQ) | [pdf-файл](https://github.com/demist/tp_hse/blob/main/slides/lec12.pdf) | Тест №6 | *19 мая* | *26 мая в 18:00* |

## Содержание лекций

### Лекция 0 

**Организационное**

-  План курса
-  Правила оценивания
-  Информация о заданиях
-  Контрольные мероприятия

### Лекция 1

**Этапы развития проекта**

-  Основные этапы жизненного цикла проектирования, реализации и внедрения ПО
-  Формирование требований
-  Разработка концепции
-  Техническое задание
-  Эскизный проект
    - Понятие о MVP и примеры MVP
-  Технический проект
-  Рабочая документация
-  Поставка / ввод в действие
-  Сопровождение 
-  Вывод из эксплуатации

> Почитать подробнее про MVP можно [тут](https://www.productplan.com/glossary/minimum-viable-product/), [тут](https://vc.ru/marketing/139040-sekret-uspeshnyh-startapov-minimum-viable-product-chto-eto-i-kak-ego-sozdayut), [тут](https://habr.com/ru/company/productstar/blog/508892/) и [тут](https://trends.rbc.ru/trends/innovation/60dc23419a7947caa5598064)

> [Хороший пост про "Техническое задание на разработку ПО"](https://habr.com/ru/post/328822/)

### Лекция 2

**Базовые понятия о языках программирования**

-  Парадигмы программирования
	- Императивное программирование
		- Описание
		- Примеры
		- "Вложенные парадигмы"
			- Процедурное программирование
			- Структурное программирование
			- Аспектно-ориентированное программирование
			- Объектно-ориентированное программирование
			- Обобщенное программирование
	- Декларативное программирование
		- Пример-объяснение
		- "Вложенные парадигмы"
			- Логическое программирование 
			- Функциональное программирование
	- Общая схема парадигм
	- Метапрограммирование
	- Реализация парадигм в языках программирования
-  Компилируемые и интерпретируемые языка
	- Определения
	- Примеры
-  Типизация
	- Сильная / слабая типизация
	- Статическая / динамическая типизация
	- Явная / неявная типизация


### Лекция 3

**Основные диаграммы UML**

-  Что такое UML? 
	- Базовое понятие о нотации UML
-  Диаграмма вариантов использования
	- Понятие о вариантах использования
	- Понятие об акторах
	- Нотация диаграммы вариантов использования
-  Диаграмма классов
	- Понятие о классах
	- Нотация диаграммы классов
	- Выделение сущностей
		- Карточки CRC
		- Метод Аббота
-  Диаграмма последовательности
	- Нотация диаграммы последовательности
-  Диаграмма состояний
	- Нотация диаграммы состояний
-  Диаграмма деятельности
	- Нотация диаграммы деятельности

> [UML Cheat Sheet](https://www.guru99.com/uml-cheatsheet-reference-guide.html)

### Лекция 4

**CI/CD/CD**

-  CI/CD/CD
-  Понятие о Continuous Integration
-  Понятие о Continuous Delivery
-  Понятие о Continuous Deployment
-  Пример организации процесса разработка из индустрии
	- Этап проектирования
	- Этап реализации
	- Этап сдачи задачи
	- Подготовка к выпуску версии

> [TravisCI](https://www.travis-ci.com/), [TeamCity](https://www.jetbrains.com/teamcity/), [GitHub Actions](https://github.com/features/actions), [Jenkins](https://www.jenkins.io/)

### Лекция 5

**Отладка ПО, ч.1: работа с ошибками ПО**

-  Основные этапы отладки ПО
-  Воспроизведение дефекта
	- Необходимая информация для воспроизведения
-  Анализ дефекта
	- Понятие root-cause
	- Условия возникновения
	- Область повреждения
	- Необходимые выводы
-  Дизайн исправления 
	- Технический
	- Архитектурный
	- Технологический
-  Исправление дефекта
-  Валидация исправления
-  Интеграция исправления в код или целевую систему
-  Дополнительные валидации после интеграции

### Лекция 6

**Отладка ПО, ч.2: техники отладки**

-  Запуск программ в отладчике (трассировка)
	- Софтверный дебаггер
	- "Железный" дебаггер
	- Удаленный дебаггер
-  Логирование
	- Работы системы
	- Программного кода
-  Анализ программного кода без исполнения программы
	- "Метод пристального взгляда"
	- Статические анализаторы
-  Анализ поведения системы
	- Упрощение сценария
	- Ограничение объема данных
	- Упрощение данных / запроса
-  UNIT-тестирование
-  Прототипирование
-  Отладка с помощью дампов
-  Отладка с помощью перехватов
-  Профилирование кода
-  Выполнение кода в другой среде
-  Отладка методом RPC (*Remote procedure call*)
-  Отладка путем анализа документации
-  Отладка трансляцией кода 
	- Трансляция "вниз"
	- Трансляция "вверх"
-  Отладка разработкой интерпретатора
-  Метод индукции
-  Метод дедукции
-  Обратное движение по алгоритму

### Лекция 7

**Управление качеством ПО, ч.1**

-  Понятие о качестве ПО
-  Характеристики и атрибуты качества ПО
-  Основые аспекты качества ПО
-  Парадокс тестировщика
-  Соответствие ожиданиям stakeholder'ов
-  Качество и деньги
	- Десятичное правило качества
	- Важные аспекты

### Лекция 8

**Управление качеством ПО, ч.2**

-  Ручное тестирования
	- Класс эквивалентности
	- Граничные значения
-  7 ключевых инструментов качества
	- Причинно-следственная диаграмма Исикавы
	- Блок-схема
	- Контрольный листок
	- Контрольная карта (карта Шухарта)
		- Примеры
	- Гистограмма
	- Диаграмма Парето
	- Диаграмма разбрасывания
-  Ручное тестирование. Практические советы
-  Автоматизированное тестирование 
	- Основные аспекты
	- Жизненный цикл автотеста
	- Практические советы
	- Как на практике?

### Лекция 9

**Принципы проектирования ПО, часть 1**

-  Что такое программа, как она устроена, как она работает
-  Что такое архитектура ПО
-  Что такое "Проектирование ПО"?
-  По каким критериям можно оценить архитектуру? 
	- Критерии хорошей архитектуры
		- Эффективность
		- Гибкость
		- Расширяемость
		- Масштабируемость, тестируемость, возможность повторного использования, сопровождаемость
	- Критерии неудачной архитектуры
		- Жесткость
		- Хрупкость
		- Неподвижность
-  Принцип *High Cohesion / Low Coupling*

> [Отличный ресурс про паттерны проектирования](https://refactoring.guru/ru/design-patterns/catalog)

### Лекция 10

**Принципы проектирования ПО, часть 2**

-  Принципы SOLID
	- **S**ingle responsibility principle
	- **O**pen-closed principle
	- **L**iskov substitutional principle
	- **I**nterface segregation principle
	- **D**ependency inversion principle
-  Закон Деметры
-  YAGNI
-  DRY / DIE
-  KISS

> [Лекция Роберта *Uncle Bob* Мартина  про SOLID](https://www.youtube.com/watch?v=zHiWqnTWsn4)

### Лекция 11

**Архитектурные паттерны**

-  Классификация архитектуры ПО
	- Локальные
	- Распределенные
		- Файл-серверные
		- Клиент-серверные
			- Двухзвенные
			- Трехзвенные
			- Многозвенные
-  Локальные приложения 
	- MVC (*Model-View-Controller*)
-  Клиент-серверная архитектура 
	- Тонкий и толстый клиент
	- Трехзвенная архитектура
-  Оценка нагрузки на систему
-  Тим проекта и влияние на нагрузку
-  Ресурсы для обеспечения производительности 
-  Масштабирование
	- Горизонтальное
	- Вертикальное
	- Функциональное разбиение
	- Шардинг
-  Типичная архитектура веб-сервиса
-  Типичная архитектура нагруженной информационной системы

### Лекция 12

**Методологии разработки ПО**

-  Основные понятия
-  Факторы, оказывающие влияние на процесс разработки
	- Внешние факторы
	- Внутренние факторы
-  Каскадная модель
-  V-модель
-  Инкрементная модель
-  Итерационная модель
-  Спиральная модель
-  RAD-модель 
-  Семейство гибких методологий
	- Agile-манифест
	- Scrum
	- Kanban

> [Статья про методологии разработки](https://acodez.in/12-best-software-development-methodologies-pros-cons/)


# Семинары

## Объявления к семинарам

### Подготовка к Семинару №1

Для успешного выполнения практики на **Семинаре №1** вам понадобятся некоторые инструменты, для разных операционных систем на вашем ПК действия разные: 

- Если у вас *Windows*, варианты:
	- (`в.1`) Поставить себе **Linux** - наиболее удобный способ
		- Рекомендуем использовать дистрибутив *Ubuntu 22.04.1 LTS* (скачать можно [тут](https://ubuntu.com/download/desktop))
		- Вы можете либо поставить *Ubuntu* второй системой, либо же развернуть в виртуальной машине
			- [Одна из множества инструкций, как поставить второй системой](https://www.tecmint.com/install-ubuntu-alongside-with-windows-dual-boot/)
			- [Одна из множества инструкций, как развернуть в виртуальной машине](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview)
	- (`в.2`) Установить себе WSL (*Windows Subsystem for Linux*)
		- [Одна из инструкций, как это сделать](https://docs.microsoft.com/ru-ru/windows/wsl/install)
	- (`в.3`) Использовать online-консоль (*наименее приоритетный вариант, использовать только если другое не получилось*)
		- Например, [вот эту](https://www.onlinegdb.com/online_bash_shell)
		- Или [вот эту](https://replit.com/languages/bash)
		- Или [вот эту](https://rextester.com/l/bash_online_compiler)
	- Если вы остановились на `в.2` или `в.3`, то вам еще необходимо установить `Git`
		- Скачать его можно [тут](https://git-scm.com/download/win)
- Если у вас *MacOS* - у вас есть уже приложение [*Terminal*](https://ru.wikipedia.org/wiki/Terminal_(macOS))
	- *Очень желательно, кроме того*, установить `brew`
		- Инструкция [тут](https://brew.sh/)
			- Достаточно в *Terminal* вставить команду `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
	- После установки `brew` - установить `Git`
		- Инструкция [тут](https://git-scm.com/download/mac)
			- Достаточно в *Terminal* вставить команду `brew install git`
- Если у вас *Linux* (любой дистрибутив) - у вас уже есть приложение *Терминал* / *Эмулятор терминала* / "что-то подобное" - точно есть во всех дистрибутивах, просто поищите
	- Нужно установить `Git`
		- Достаточно в *Терминале* набрать команду `sudo apt-get install git` (если выпадает ошибка - стоит погуглить, какой менеджер пакетов используется в вашем дистрибутиве)


## План семинаров

###  Семинар 1 *(неделя 1)*

**Базовые инструменты разработки ПО, ч.1**

Bash и основные команды.

**План семинара:** 
- показываем bash
- базовые команды bash: touch, rm, cd, mkdir, rmdir, ls, cp, mv, cat, echo, ...
- пишем простой скрипт на bash (*Например, считаем количество файлов в директории*)
- пишем более сложный скрипт на bash (*Например, считаем количество файлов в директории в разрезе типов файлов*)
  
> [bash commands cheatsheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet)

> [bash script cheatsheet](https://devhints.io/bash)

###  Семинар 2 *(неделя 2)*

**Базовые инструменты разработки ПО, ч.2**

Системы контроля версий, git, *опционально* gitflow

**План семинаров**
- рассказываем про системы контроля версий в целом (зачем нужно, какие есть)
- рассказываем основы git: что такое репозиторий, что такое ветки, что такое коммиты, pull-request'ы
- показываем: создание репозитория на github, клонирование локально, создание файла, коммит, push origin
- показываем работу с ветками, переключение между ветками, поиск источника изменений (какой коммит привел к изменению конкретной строчки в файле)
- показываем процесс создаения pull-request'а на github: от клонирования репозитория до принятия pull-request'а (с resolving'ом конфликтов)

###  Семинар 3 *(неделя 3)*

**Инструменты отладки**

Профилировка, gdb и valgrind 

**План семинара:**
- запускаем любимую IDE 
- пишем простую программу (на Java), запускаем дебагер
- показываем профилировщик
- показываем gdb - как работать из консоли (опять же, на простом примере - на C++)
- показываем valgrind в простейших сценариях (память не освобождена, переменная не инициализирована, используется неинициализированная переменная в условном переходе)
- *опционально* показать статический анализатор кода (для Java)

###  Семинар 4 *(неделя 4)*

**Тестирование ПО**

Отработка на семинаре простейших примеров написания тестов на Java, демонстрация разных видов тестов

**План семинара:**
- пишем на Java пару простых функций (например, сложение и умножение чисел)
- показываем юнит-тесты (каждую функцию)
- показываем нагрузочное тестирование (запускаем много итераций теста, смотрим производительность)
- показываем сценарное тестирование (на уровне "посчитаем значения выражения")
- показываем, как настроить простейший CI в *GitHub Actions*

### Семинар 5 *(неделя 5)*

**Диаграммы UML**

*Отработка на семинаре навыков построения диаграмм, решение небольших задач. Диаграммы классов пока не рассматриваем.*

**План семинара:**
- решаем задачку на диаграмму вариантов использования (например, "варианты использования сайта аэропорта")
- решаем задачку на диаграмму последовательности (например, "снимаем деньги в банкомате")
- решаем задачку на диаграмму деятельности (например, "поступаем в университет")
- решаем задачку на диаграмму состояний ("рассматриваем сдачу курса: изучается-сдан-пересдача-не сдан")

###  Семинар 6 *(неделя 6)*

**Практика проектирования**

*Отрабатываем практические навыки проектирования (без погружения в программный код) понятных предметных задач: заказ такси через приложение, покупка в интернет-магазине...Рисуем диаграммы классов UML*

**План семинара:**
- решаем простую задачу на проектирование локального приложения (мобильного или десктопного), без взаимодействия с сервером. *Например, проектируем простейшее приложение для создания и хранения заметок. Жетально проектировать на уровне классов. Если идет сложно - сначала пытаемся выделить варианты использования и придумать, как их реализовать. Даже если получится по итогу криво, главное, чтобы получилось хоть что-то.*.
- решаем задачу посложнее на проектирование клиент-серверного приложения. *Например, приложение для заказа такси. Обязательно надо подстветить проблему, что запрос от клиента до сервера может не дойти (или от сервера до клиента), как это можно решать (спойлер - таймлимитом)*

# Контрольные мероприятия

## Тесты по лекциям (6 штук)

- Всего будет 6 тестов
- Каждый тест - по двум лекциям, распределение лекций по тестам - в таблице **Записи лекций и тесты**
- Каждый тест - 10 вопросов (5 по одной лекции, 5 - по другой). Каждый вопрос стоит 1 балл, всего за один тест можно набрать 10 баллов
- Тесты публикуются в определенные дни (по воскресеньям), согласно графику. На выполнение теста - 1 неделя (*дедлайн по тесту указан в таблице, также будет дублироваться объявлением*)
- Каждый студент проходит тест только 1 раз
- Результаты непосредственно после прохождения теста не публикуются, посмотреть правильные ответы нельзя
- **После закрытия теста** публикуются результаты и баллы за него, а также правильные ответы

## Техническое задание №1 (ТЗ1)

**Пишем скрипт на bash**

### Легенда задания 

Вам нужно написать скрипт на bash, который на вход принимает два параметра - две директории (`входная директория` и `выходная директория`).
Во `входной директории` могут находиться как файлы, так и вложенные директории (внутри которых тоже могут быть как файлы, так и папки) - уровень вложенности может быть любой.
Задача скрипта - "обойти" `входную директорию` и скопировать все файлы из нее (и из всех сложенных директорий) в `выходную директорию` - но уже без иерархии, а просто все файлы - внутри `выходной директории`.

Пример:

`Входная директория` = `/home/input_dir`; `Выходная директория` = `/home/output_dir`.

`/home/output_dir` изначально пустая.

Структура `/home/input_dir`: 
- input_dir
	- a.txt
	- dir2
		- b.txt
	 - dir3
   		- c.txt

Тогда после работы вашего скрипта структура `/home/output_dir` должна быть следующая: 
- output_dir
	- a.txt
 	- b.txt
  	- c.txt

**Обратите внимание**: в разных поддиректориях `входной директории` могут быть файлы с одинаковым названием. В момент копирования в `выходную аудиторию` необходимо такие ситуации каким-либо образом разрешить без потери файлов и содержания файлов (как именно - на ваше усмотрение).

### Требования и критерии оценки

За задание вы можете получить максимум **10 баллов**.

Семинарист при проверке может выставить за какой-либо пункт частичный балл, если требования пункта выполнены не полностью.

- `1 балл` Скрипт запускается и принимает два параметра
- `1 балл` Реализовано получение списка файлов, находящихся непосредственно во `входной директории` (не во вложенных в нее директориях)
- `1 балл` Реализовано получение списка директорий, находящихся во `входной директории`
- `3 балла` Реализовано получение списка всех файлов, вложенных во `входную директорию`
- `1 балла` Реализовано копирование  всех файлов, вложенных во `входную директорию` в `выходную директорию`
- `3 балла` Решена проблема с файлами, имеющими одинаковое название 

### Дедлайн

Есть два дедлайна - `мягкий` и `жесткий`. 

- Если вы присылаете ваше решение до `мягкого дедлайна` - то ваш семинарист проверяет работу, дает замечания, и далее у вас есть **3 дня** на то, чтобы внести исправления (и получить балл выше). *Обратите внимание, допускается именно исправление замечаний, а не доработка каких-то пунктов задания, которые вы изначально не сделали*.
Вы можете не вносить исправления и согласиться на тот балл, который получили по итогам первой проверки.
- Если вы присылаете ваше решение после `мягкого дедлайна`, но до `жесткого дедлайна` - семинарист проверяет вашу работу и выставляет балл. Исправления не допускаются.
- Если вы присылаете ваше решение после `жесткого дедлайна`, то задание не проверяется, и вы получаете **0 баллов**

#### Сроки 

//TODO

### Формат сдачи

Задание вы сдаете своему семинаристу. Результаты выполнения задания должны быть загружены в репозиторий на *GitHub*.
Канал отправки ссылки на репозиторий семинаристу - на усмотрение семинариста.


## Техническое задание №2 (ТЗ2)

**Добавляем тесты и разворачиваем простейший CI/CD**

Задание состоит из двух частей. Каждая часть оценивается максимум в 5 баллов. Общий максимальный балл за задание: 5 + 5 = **10 баллов**

### Часть №1 *Тестирование* (стоит 5 баллов из 10)

#### Задание 

Реализуйте на `Java` простейшую программу, которая будет считывать из файла числа, а далее отдельными функциями искать среди этих чисел минимальное число, максимальное число, считать их общую сумму и произведение. 

Функции должны называться, соответственно `_min` (минимальное число), `_max` (максимальное число), `_sum` (сумма всех чисел), `_mult` (произведение всех чисел). 

Числа в файле записаны в одной строке, друг от друга отделены пробелами. В файле есть минимум одно число. Максимально возможное количество чисел в файле - 1 млн.

Для этой программы подготовьте тесты:
- проверяющие корректность работы функций поиска минимума и максимума
- проверяющие корректность работы функций сложения и умножения
- проверяющие скорость работы программы при увеличении размера входного файла (*при увеличении количества чисел в файле*).

#### Пример работы

**В файле**: 1 4 2 3

**Минимальное**: 1

**Максимальное**: 4

**Сумма**: 10 *(1+2+3+4)*

**Произведение**: 24 *(1\*2\*3\*4)*

#### Критерии оценки

- `1 балл`: реализуйте функции чтения из файла, поиска минимального числа, поиска максимального числа, сложения и умножения *всех* чисел из файла
- `1 балл`: реализуйте тесты для проверки корректности функций поиска минимума, максимума, сложения и умножения
- `1 балл`: реализуйте тесты для проверки скорости работы программы при увеличении размера входного файла
- `1 балл`: реализуйте любой другой тест на ваше усмотрение
- `1 балл`: постройте график зависимости времени выполнения от кол-ва чисел в файле (*вы можете измерять время выполнения любой функции из реализованных на ваш выбор*)

### Часть №2 (стоит 5 баллов из 10)

> [Github Actions](https://github.com/features/actions)

> [Travis CI](https://www.travis-ci.com/)

> [Circle CI](https://circleci.com/)

#### Задание 

Теперь вам необходимо настроить CI-систему для своего мини-проекта. 

#### Критерии оценки

- `1 балл`: заведите репозиторий для своего проекта на [GitHub](https://github.com/). Оформите простейший *README.md* ([туториал по markdown (файлы формата .md)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)). Загрузите в репозиторий файлы своего мини-проекта (код, тесты, *README.md*).
- `1 балл`: подключите к вашему проекту любую CI-систему (**выше есть подсказки с вариантами систем, но мы крайне рекомендуем использовать GitHub Actions в рамках этого задания, только если Ваш семинарист не демонстрировал вам другую систему**). Обеспечьте возможность запуска тестов в ручном режиме (например, по щелчку кнопки в веб-интерфейсе CI-системы) 
- `1 балл`: настройте CI таким образом, чтобы прогон тестов запускался автоматически при любом новом коммите в репозиторий вашего проекта
- `1 балл`: сделайте интеграцию CI-системы и вашего репозитория на GitHub: сделайте бэйдж в *README.md*, который будет показывать текущий статус тестов. Для информации смотрите [тут](https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/adding-a-workflow-status-badge), [тут](https://www.codeblocq.com/2016/04/Add-a-build-passing-badge-to-your-github-repository/) или в аналогичном доке для выбранной вами CI-системы.  Как выглядят бэйджи в целом, можно посмотреть в любом проекте на GitHub, где они сделаны, например, в [репозитории Telegram](https://github.com/telegramdesktop/tdesktop)
- `1 балл`: сделайте любую интеграцию CI-системы и какого-либо мессенджера (например, `telegram`, `slack`, `msteams` и т.п.). Настройте систему так, чтобы при успешном прохождении теста посылалось сообщение "все ок", при неуспешном - посылалась информация, какие именно тесты не пройдены. **Обратите внимание**, тут не нужно *писать код*, тут нужно взять готовые аддоны / расширения и просто настроить

### Дедлайн

//TODO

## Техническое задание №3 (ТЗ3)

**Проектируем небольшое приложение по требованиям**

### Задание 

Вам необходимо спроектировать небольшое приложение. *Подчеркнем, что вам нужно именно спроектировать приложение, а не разработать его. Писать программный код не нужно*.
В рамках проектирования приложения вам необходимо подготовить несколько *UML*-диаграмм.

#### Какие инструменты можно использовать для построения диаграмм

Вы можете использовать любые удобные для вас инструменты.
Как вариант, предлагаем следующие бесплатные онлайн-сервисы:
- [draw.io](https://draw.io/)
- [Diagram Editor](https://www.diagrameditor.com/)
- [LucidChart](https://www.lucidchart.com/pages/examples/uml_diagram_tool)
- [Miro](https://miro.com/uml-diagram-tool/)

### Легенда

Наверное, каждый из вас хоть раз заказывал доставку еды через мобильное приложение. 
Если нет - можете посмотреть, как работают подобные сервисы, например, `Яндекс.Еда` или `Delivery Club`. 
Вам необходимо спроектировать подобное приложение. 
*Понятно, что вы не можете в деталях знать, как устроена работа подобных систем с ресторанами и курьерами - но от вас и не требуется описать то, как работает в данных системах.*
*Вы можете предложить любые процессы и сценарии на ваше усмотрение, главное, чтобы они были логичны и реализуемы*.

### Требования и критерии оценки

- `Обязательное требование` (*без выполнения этого пункта проверка невозможна*): подготовьте краткое (0.5-1 стр текста) описание системы, для которой вы будете далее строить диаграммы
- `2 балла` Постройте диаграмму вариантов использования. *На диаграмме укажите только основные сценарии (не более 5-7 штук)*. 
- `2 балла` Постройте диаграмму последовательности для процесса заказа еды через приложение 
- `2 балла` Постройте диаграмму состояний для заказа (*подумайте, какие статусы могут быть у заказа*)
- `2 балла` Постройте диаграмму деятельности для описания процесса обработки заказа системой 
- `2 балла` Постройте диаграмму классов для системы. *Обратите внимание, можно вместо классов указывать большие "модули системы" - например, "модуль оплаты" или "модуль расчета времени доставки"*

### Дедлайн

//TODO

## Письменный экзамен в онлайн-формате (ЭКЗ)

Итоговая оценка за экзамен ставится по 10-балльной шкале (без округления).

Письменный экзамен включает в себя вопросы **исключительно** по лекционной части курса.

//TODO


# Понедельный план

Обратите внимание - на каждой неделе курса рекомендуется изучать определенные лекции. 

Изучать лекции быстрее графика можно, но не рекомендуем - может быть слишком много информации в единицу времени, лучше не торопиться.

Изучать лекции медленнее графика - крайне не рекомендуем, могут быть сложности и на семинарах, и с ТЗ, и в конце курса будет завал (а там еще и сессия будет близко и будет не до этого).

| Неделя | № лекций для изучения | Семинары | Выдача заданий | Сдача заданий | 
| :---: | :---: | :---: | :---: | :---: |
| *До первого семинара* | 0 | | [*Установить необходимое ПО для курса на свои машины*](https://github.com/demist/tp_hse/blob/main/README.md#%D0%BF%D0%BE%D0%B4%D0%B3%D0%BE%D1%82%D0%BE%D0%B2%D0%BA%D0%B0-%D0%BA-%D1%81%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80%D1%83-1) | |
| 1 | 1, 2 | Базовые инструменты разработки ПО, ч.1 | | |
| 2 | 3, 4 | Базовые инструменты разработки ПО, ч.2 | **ТЗ1**: Пишем скрипт на bash | |
| 3 | 5, 6 | Инструменты отладки | | |
| 4 | 7, 8 | Тестирование ПО | **ТЗ2**: Добавляем тесты и разворачиваем простейший CI/CD | **ТЗ1**: Пишем скрипт на bash |
| 5 | 9, 10 | Диаграммы UML | **ТЗ3**: Проектируем небольшое приложение по требованиям | |
| 6 | 11, 12 | Практика проектирования | | **ТЗ2**: Добавляем тесты и разворачиваем простейший CI/CD |
| 7 | **ЭКЗ** | | | **ТЗ3**: Проектируем небольшое приложение по требованиям |

# Правила оценивания

**Оценка за тесты** = *Сумма баллов по всем тестам* / 6

Каждый тест оценивается по 10-балльной шкале. 
**Оценка за тесты** не округляется.

**Финальная оценка** = *Математическое округление* (0.1\*`Оценка за тесты` + 0.15\*`ТЗ1` + 0.15\*`ТЗ2` + 0.15\*`ТЗ3` + 0.45\*`ЭКЗ`)

[0]:https://img.shields.io/badge/year-2023%2F2024-yellow
[1]:https://img.shields.io/badge/status-pending-pink
[2]:https://progress-bar.dev/0/
