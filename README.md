# DomashevskayaControl![Algorithm](https://user-images.githubusercontent.com/110190533/190850322-27b2d44c-17b5-47eb-a525-c4b3c83626e8.jpg)
Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
Алгоритм решения:
объявляю два массива: первоначальный и вторый (такой же длины). Далее описан метод, в котором срабатывает цикл (соразмерный длине массива), внутри цикла проверка условия ( <=3 ), если да -  элемент первого массива заносится в count элемент второго массива. Переменная count нужна для того, чтобы поочередно закидывать из первого массива во второй, и чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for, в котором i увеличивается на 1. И так проверяется до конца.
Графическое представление метода в README на гитхаб.
Реализация алгоритма по пути DomashevskayaControl/Program.cs
