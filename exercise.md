## Задача:
*Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*
### 1. Блок - схема
Блок - схема представлена на изображении ![picture](picture.png)
### 2. Решение задачи
Решение задачи на языке программирования С# расположенна в файле Program.cs.
### 3. Описания решения
* объявляется два массива;
* Затем  метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия <4, если условие выполнятся то,  элемент первого массива заносится в count элемент второго массива. 
* После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.
