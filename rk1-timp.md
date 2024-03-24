Конов Михаил Алексеевич, ИУ8-24, вариант 10

1. Название проекта - SimpleAmqpClient

```shell 
computer@MLK:~/Desktop/SimpleAmqpClient-master$ cat README.md
```

2. Краткое описание проекта: враппер на языке C++ для библиотеки rabbitmq-c (AMQP - Advanced Message Queuing Protocol - открытый протокол для передачи сообщений между компонентами системы.)

```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ cat README.md
```

3. Количество файлов: 60

```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ tree -a | grep files```
9 directories, 60 files
```

4. Общий размер всех файлов - 532K.

```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ du -sh .
532K	.
```
5. Объем исходного кода:
.cpp - 184029

```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ find . -type f -name "*.cpp" -ls | awk '{sum+=$7} END {print sum}'```
184029
```

.h - 130947
computer@MLK:~/Desktop/SimpleAmqpClient-master$ find . -type f -name "*.h" -ls | awk '{sum+=$7} END {print sum}'
130947
6. файл формата .clang в репозитории присутствует в корневой папке.
```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ find . -name ".clang-format"
./.clang-format
```
7. Общее количество файлов в каталоге src - 19 объектов формата .h, 10 объектов формата .cpp. Итого - 29 объектов.
8. Количество файлов, содержащих слово "socket": 
```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ grep -irl "socket" . | wc -l
6
```
9. Количество файлов, содержащих слово "select":
```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ grep -irl "select" . | wc -l
1
```
10. Слова Microsoft, Google либо Intel встречаются 11 раз вне зависимости от написания:
```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ grep -ir -e "intel" -e "google" -e "microsoft" . | wc -l 
```
11. Файл "LICENSE-MIT" находится в корне репозитория.
12. Выведенные строки:
```shell
computer@MLK:~/Desktop/SimpleAmqpClient-master$ cat LICENSE-MIT | grep -e "BSD" -e "GNU" -e "MIT" -e "APSL" -e "Apache" -e "GPL" -e "AGPL" -e "LGPL"
The MIT License (MIT)
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
```

