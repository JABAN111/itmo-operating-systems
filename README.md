# Операционные системы
Курс операционных систем построен знакомит слушателей в детали различных операционных систем.
Курс охватывает операционные системы:
* Linux
* Unix 
* Solaris
* Windows
* Time-sharing machine и прочее наследие
А также
* Внутренее устройство процессора 
* Внутрее устройство памяти и виртуальной памяти
* Работу виртуальных машин
* Многозадачность в рамках операционных систем
* Стратегии работы с многозадачностью
* Процессы и потоки
* IO
* Работу дисков
* RAID
И многое другое, подробнее на se.ifmo.ru/os


Лектор:
Старший преподаватель факультета ПИиКТ [Клименков Сергей Викторович](https://edu.itmo.ru/ru/lecturers_and_professors/105395)

Практик:
[Смирнов Виктор Игоревич](https://isu.ifmo.ru/pls/apex/f?p=2143:3:116919570511236::NO:RP:PID:335158)

Подробное описание лабораторных работ, лекции и презентации к ним можно найти [тут](https://se.ifmo.ru/os)

Полезные материалы:
* [Задачи из книжки Столингса, которые попадаются на рубежной работе](resources/ЗадачиРубеж.pdf)
* [Разбор задач](resources/ЗадачиРубеж.pdf)
* [Расписанные билеты к экзамену](resources/ОС%20-%20Все%20билеты%20к%20экзамену.pdf)


## Лабораторная работа номер 1
Краткое описание
Необходимо реализовать две программы нагрузчик и свой "bash". Запуская нагрузчики необходимо проанализировать создаваемую ими нагрузку на операционную систему, используя инструменты time, perf, flamegraph. 

### Условия задания 
Платформа:\
**Linux**

ForkKind:\
**vfork**

Нагрузчики:
1. ema-sort-int - Сортировка массива чисел во внешней памяти
2. factorize - Разложение числа на простые множители

---

## Лабораторная работа номер 2
Краткое описание
Необходимо реализовать "библиотеку" для операционной системы, которая будет осуществлять кэш страниц с выданным вариантом стратегии. Также протестировать на бенчмарках из предыдущей лабораторной и проанализировать результат

### Условия задачи 

Платформа:\
**Linux**

Стратегия:\
**LIFO**
