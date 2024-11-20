# labs_assembler
## Лабораторные работы по assembler

### Лабораторная работа №4:
Разработать программу используя команды ветвления по условию и команды организации цикла.

Вариант задания:
![image](https://github.com/user-attachments/assets/cf54b936-cce9-4d51-9311-dde604a831ff)

### Лабораторная работа №5:
Составить программу, которая удовлетворяет следующим условиям:

•	выполняет действия согласно варианту задания

•	двоичные числа вводятся с клавиатуры пользователем (валидация на ввод не более 8 разрядов числа, формирование двоичного числа из введенной строки, дополнение старших разрядов нулями при вводе меньше 8 бит информации)

•	при реализации программы на Ассемблере использовать только логические операции

•	результат вывести на экран в двоичной системе счисления

Вариант задания: 
Дано двоичное число. В старшей части числа все четные биты заменить
на противоположные. В младшей части числа все нечетные биты обнулить. Результат разделить на 16.

### Лабораторная работа №6:
На диске имеется файл in.txt, в котором записано несколько строк,
содержащих не более 9 слов каждая (в качестве символов можно использовать только английские
буквы). Подготовить программу, которая выполняет чтение строк из файла
in.txt и обрабатывает в соответствии с алгоритмом, заданным вариантом
задания. После обработки массива строк программа должна записать
результат в созданный файл out.txt. При этом результат обработки каждой
строки должен находиться в отдельной строке, а вначале строки должен быть
указан номер строки.

Вариант задания:
Удалить в каждом слове каждой строки повторяющиеся в нем буквы. 

### Лабораторная работа №7:
Используя математическое выражение разработать программу, обеспечивающую:

• ввод переменных математического выражения с клавиатуры

• расчет математического выражения

• вывод результата на экран пользователя.
При вводе учесть, что вводиться должны только числа. 

При вводе программа должна запрещать вводить любые символы, кроме символов от 0 до 9. Поэтому должна использоваться функция ReadConsoleInput.
Количество цифр в каждом из вводимых чисел может быть от 1-го до 4-х. Пользователь сам определяет при вводе сколько цифр ввести (1 или более). Ввод оканчивается Enter.
При выводе результата на экран в данной работе нельзя использовать функции типа crt_printf и подобные. Вывод необходимо организовать посимвольно, с помощью команд вывода кодов символов (цифр) на экран.

Вариант задания:
(ab + c + de + f/g)+(h + k/m), a = 3, b = 5
