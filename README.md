# Final Task

## **Задача:**
 
 Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых *меньше, либо равна 3 символам*. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

 ## __Описание__

Объявляю 2 массива, в которых величина первого задается на старте выполнения, а величина второго равняется величине первого. Потом создается метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да элемент первого массива заносится в count элемент второго массива. Переменная count чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.

Блок-схема алгоритма решения задачи представлена в файле **Method.png**.

Программа реализована на языке программирования _С#_ и представлена в папке __Final_Task__ файл *Program.cs*.