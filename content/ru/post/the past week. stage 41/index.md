---
title: Программирование в командном процессоре ОС UNIX. Расширенное программирование
date: 2023-05-29
math: true
image:
  placement: 2
  caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
---

## Цель работы

Изучите основы программирования в оболочке операционной системы UNIX. Узнайте, как писать более сложные командные файлы, используя логические управляющие конструкции и циклы.

## Последовательность выполнения работ

1. Напишите пакетный файл, реализующий упрощенный механизм семафора. Командный файл должен подождать некоторое время t1
, пока ресурс будет освобожден, выдавая сообщение об этом, и, дождавшись его освобождения, использовать
его в течение некоторого времени t2<>t1, также выдавая информацию о том, что
ресурс используется соответствующим командным файлом (процессом). Бежать
пакетный файл в одном виртуальном терминале в фоновом режиме, перенаправляющий
его вывод на другой (> /dev/tty#, где # - номер терминала, на который перенаправляется
вывод), в котором этот файл также запущен, но не в фоновом режиме, а в привилегированном
режиме. Измените программу таким образом, чтобы была возможность взаимодействия трех
или более процессов.
2. Реализуйте команду man с помощью командного файла. Изучите содержимое журнала kata /usr/share/man/man1. Он содержит архивы текстовых файлов, содержащих
справку по большинству программ и команд, установленных в системе. Каждый архив
может быть открыт с помощью команды less сразу после просмотра содержимого справки. Командный
файл должен получить имя команды в качестве аргумента командной строки и в
результате выдать справку об этой команде или сообщение об отсутствии справки
, если соответствующего файла нет в каталоге man1.
3. Используя встроенную переменную $RANDOM, напишите командный файл, который генерирует случайную последовательность букв латинского алфавита. Обратите внимание, что $RANDOM
выводит псевдослучайные числа в диапазоне от 0 до 32767.