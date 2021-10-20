---
name: Баг-репорт java 1-1
about: bug details
title: "[BUG]"
labels: ''
assignees: ''

---

**Описание**
Сумма двух положительных чисел получается отрицательной.

**Шаги воспроизведения**
1) создать новый проект в IDEA
2) скопировать код по ссылке https://github.com/towerfalls/java1-1/blob/master/src/task01.java
3) открыть терминал
4) запустить выполнение кода (нажать Run или Shift+F10)

**Ожидаемый результат**
Значения переменных account и transfer суммируются

**Фактический результат**
Сумма двух положительных чисел получается отрицательной и равняется -1794967296

Логи приложения:
sampling ...
include patterns:
exclude patterns:
-1794967296
Class transformation time: 0.0441153s for 119 classes or 3.707168067226891E-4s per class

Process finished with exit code 0


Тестирование производилось в следующем окружении:
* Windows 10 Home 64 Bit
* Java 11.0.1
* IntelliJ IDEA 2021.2.
