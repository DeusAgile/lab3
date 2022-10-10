# lab3 | РАЗРАБОТКА СИСТЕМЫ МАШИННОГО ОБУЧЕНИЯ
Отчет по лабораторной работе #3 выполнил(а):
- Калюжный Сергей Александрович
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

## Цель работы
Разработать и понять как устроена данная система машинного обучения на MLAgent

## Задание 1
### Реализовать систему машинного обучения в связке Python - Google-Sheets – Unity. При выполнении задания можно использовать видео- материалы и исходные данные, предоставленные преподавателями курса.
Ход работы:
- Шаг 1. Создать новый пустой 3D проект на Unity. Скачать папку с ML агентом. В созданный проект добавить ML Agent, выбрав Window - Package Manager - Add Package from disk. Последовательно добавить .json – файлы. По итогу в компонентах должен появиться MlAgent:  
![Снимок экрана 2022-10-06 165508](https://user-images.githubusercontent.com/81421386/194924753-8ce4bbdf-2895-4b24-ba1b-5326706eeb6b.png)


- Шаг 2. Запускаю Anaconda Prompt и начинаю создавать виртуальную среду под MLAgent, вписывая в консоль последовательно необходимые команды:  
![image](https://user-images.githubusercontent.com/81421386/194925242-237a0e08-8d4b-4c74-b7cd-57ec2276f4fc.png)
![image](https://user-images.githubusercontent.com/81421386/194925314-f5f4310d-8786-46ca-ba0d-e27876b517f5.png)



- Шаг 3. Создаю в проекте юнити арену с плоскостью, сферов и кубом. Присваиваю сфере компоненты и параметры, указанные на скриншоте и rigidbody. Также привязываю скрипт к сфере:  
![Снимок экрана 2022-10-06 200848](https://user-images.githubusercontent.com/81421386/194925982-9448b46e-6900-4129-b628-76f2e9f38e16.png)


- Шаг 4. Запускаю MLAgent и начинаю обучать его на 1 арене, на 9 и 27 аренах:  
![image](https://user-images.githubusercontent.com/81421386/194925496-cc8f12ad-82c9-495d-aaac-fa3fe3dbc121.png)
![image](https://user-images.githubusercontent.com/81421386/194925536-f547a78a-7469-4765-89e5-36e78537e9ab.png)
![image](https://user-images.githubusercontent.com/81421386/194925561-b5d8ea65-630d-40fa-a3db-308005881019.png)
![image](https://user-images.githubusercontent.com/81421386/194926210-4844bc39-505a-4495-814c-9ff4605819b8.png)
Наблюдаю постоянное перемещение шарика в сторону куба. Куб респавнится на арене рандомно и процесс продолжается циклично.

## Задание 2
### Детально описать конфигурационный файл для машинного обучения  
![image](https://user-images.githubusercontent.com/81421386/194931216-6922a468-bcab-4087-82f1-726e396b7584.png)


## Задание 3
### Доработать сцену и обучить MLAgent так, чтобы шар проходил между двумя кубами. Кубы случайным образом меняют свои координаты на плоскости.

## Выводы
Баланс в играх - равновесие различных показателей игровых объектов (персонажей) при помощи каких-либо методик рассчета. Это может быть равенство сумм характеристик, например. Система машинного обучения позволяет симулировать значительно большее количество игр и при этом быстрее, чем обычные тестировщики. Обучаясь, млагент предоставляет данные о лучшем варианте использования игровых объектов. Проанализировав данные, можно увидеть дизбаланс на основе винрейта или других показателей.


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
