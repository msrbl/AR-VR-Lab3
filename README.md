# Lab3
# Виртуальная и дополненная реальность
Отчет по лабораторной работе #3 выполнил(а):
- Сиверухин Никита Андреевич
- РИ-300021
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨
## Цель работы изучить принципы создания и настройки передвиженияпользователя в VR с помощью стиков на контроллерах и с помощью телепортации.
## Задание 1
### Пошагово выполнить каждый пункт по примеру предоставленных видеоматериалов:
– Откройте проект, созданный в предыдущей лабораторной работе;

– Создайте у XR Rig дочерний объект Locomotion System;
– Добавьте Объект XR Rig в Locomotion System;

– Удалите из Locomotion System все компоненты, кроме Locomotion System;

– Добавьте в Locomotion System компоненты плавного передвижения иповорота;

– Настройте добавленные компоненты для левого контроллера;

– Добавьте и настройте компонент Character Controller для XR Rig;

– Скопировать из скрипта CharacterControllerDriver.cs процедуру,связанную с обновление Character Controller;

– Создать на объекте XR Rig новый компонент скрипта;
–Добавить в скрипт скопированную процедуру, переименовав переменные и добавив их в функцию Start;

– Прописать вызов добавленной процедуры каждый кадр проекта;

– Запустите проект и проверьте, что передвижение работает;

– Удалите из Locomotion System все компоненты, кроме Locomotion System;

– Добавьте в Locomotion System компоненты для телепорта и резкого поворота;

– Добавить на Plane, компонент пространства для телепортации.

– На объекте, отвечающем за правый контроллер убрать все объекты кроме Transform и XR Controller;

– На объекте левого контроллера изменить толщину линии луча на 0.01;

– Изменить тип линии на Projectile Curve;

– Изменить в Input System Teleport Mode Active Direction на Everything

– Добавить на Locomotion System новый скрипт;

– Настроить в скрипте отображение луча, только при активации кнопки телепорта.

– Запустить проект и проверить его работу.

## Задание 2
### В чём разница между Continuous Turn Provider и Snap Turn Provider? Привести развернутый ответ с примерами.
Ответ:
Сontinuous turn provider - это провайдер перемещения, который позволяет пользователю плавно поворачивать свою установку непрерывно с течением времени, используя указанное действие ввода.

Snap Turn Provide - это провайдер перемещения, который позволяет пользователю поворачивать свою установку, используя ввод по оси 2D из действиЙ системы ввода.

## Выводы
В данной работе, я изучил принципы создания и настройки передвижения пользователя в VR с помощью стиков на контроллерах и с помощью телепортации.

