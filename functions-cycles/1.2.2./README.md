## Задача 2. Суммирование времени.
### Описание

Вы планируете задачи своей команды на неделю. При составлении задач для программиста необходимо следить за тем, чтобы его нагрузка не вышла за определенные рамки.

Для этого вам нужна программа, которая может вычислить суммарное время выполнения задач, общее количество которых заранее неизвестно. Пользователь будет поочередно вводить длительность задач в минутах. После ввода длительности последней задачи он введет `end`. После этого программа должна вывести суммарную длительность задач в минутах.

### Процесс реализации
1. Создать переменную, в которой будет храниться суммарная длительность задач и переменную `int totalTime`, в которой будут храниться вводимые пользователем значения `String inputString`.
2. Получить ввод длительности первой задачи.
3. Используя цикл `while` получить ввод длительности оставшихся задач. Для проверки на ввод `end` нужно использовать `inputString.equals("end")`, оператор `==` со строками не работает.
4. В цикле нужно привести введенную строку к числовому типу, и прибавить ее значение к переменной, в которой хранится суммарная длительность задач. Получить ввод нового значения в `inputString`.
5. После того как пользователь введет `end` и программа выйдет из цикла нужно вывести на экран суммарную длительность задач.

Не забывайте выводит понятные пользователю приглашения на ввод и сообщения при выводе данных на экран.

### Примеры
Пользователь вводит: 60, 120, 360, end.

Вывод: 540