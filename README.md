1.   Для создания репозитория, необходимо иметь учетную запись на сайте Github.com.После откыть вкладку **Репозитории** и выбрать *Создать репозиторий*. После нажать вкладку *Создать*.
2. **ЗАДАЧА:**

*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*

**Описание алгоритма решения:**

Сперва объявим два массива: первоначальный и второй  такой длины.Затем описываем метод, в котором создается цикл, равный длине массива. Внутри цикла выполняется проверка условия(длина символов менише либо равна трем). В случае выполнения данного условия(да) - элемент первого массива заносим в счетчик(переменная count) элемент второго мвссива. Переменная счетчика( count) предназначена, для поочередного записывания из первого массива во второй и чтобы  после не было пробелов.После этого счетчик(переменная count) увеличивается  на 1 и возвращается к циклу for, в котором значение i увеличивается на 1. И так проверяется до конца первоначального условия.

**Графическое представление метода в папке Schems**

**Реализация алгоритма по пути Задача/Program.cs**