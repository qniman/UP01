# Практическая работа №6

## Тема: удаление элементов массива  
## Цель: приобрести навыки составления программ  с использованием одномерных массивов 


### Задачи:

* повторить структуру операторов ввода-вывода и использование циклов, вложенных циклов 
* повторить синтаксис оператора инициализации и ввода-вывода массивов;
* повторить основные библиотечные файлы, подключаемые при выполнении программ;
* усовершенствовать  навыки составления  программ с одномерными массивами.

---

### Задание 1

> Выполните 2 задания – номера первого задания – это ваш номер по журналу, номер второго задания – ваш вариант +10. Количество элементов N – произвольное и вводится с клавиатуры, значение элементов массива генерируются случайным образом, кроме контрольных примеров, когда значения массива инициализируются присваиванием. 
 
1. Из массива удалить первый из четных элементов.
    > Пример: из массива A[5]: 1 3 4 5 6 должен получиться
    > массив A[4]: 1 3 5 6
2. Из массива удалить последний из четных элементов.
    > Пример: из массива A[5]: 1 3 4 5 6 должен получиться
    > массив A[4]: 1 3 4 5
3. Из массива удалить последний из нечетных элементов.
    > Пример: из массива A[5]: 1 3 4 5 6 должен получиться
    > массив A[4]: 1 3 4 6
4. Из массива удалить первый из нечетных элементов.
    > Пример: из массива A[5]: 1 3 4 5 6 должен получиться
    > массив A[4]: 3 4 5 6
5. После максимального из четных элементов вставить 0.
    > Пример: из массива A[5]: 1 9 8 3 5 должен получиться
    > массив A[6]: 1 9 8 0 3 5
6. После первого четного элемента вставить 0.
    > Пример: из массива A[5]: 1 6 8 3 4 должен получиться
    > массив A[6]: 1 6 0 8 3 4
7. После последнего нечетного элемента вставить 0.
    > Пример: из массива A[5]: 1 3 8 3 5 должен получиться
    > массив A[6]: 1 3 8 3 5 0
8. Удалить максимальный из четных элементов.
    > Пример: из массива A[5]: 2 3 4 7 5 должен получиться
    > массив A[4]: 2 3 7 5
9. Удалить максимальный из кратных трем элементов.
    > Пример: из массива A[5]: 2 3 4 7 5 должен получиться
    > массив A[4]: 2 4 7 5
10. После последнего кратного четырем элемента вставить 0.
    > Пример: из массива A[5]: 1 3 8 3 4 должен получиться
    > массив A[6]: 1 3 8 3 4 0
11. Из массива удалить четные элементы, стоящие после максимального.
    > Пример: из массива A[5]: 2 7 4 6 5 должен получиться массив A[3]: 2 7 5
12. Из массива удалить четные элементы, имеющие значение больше среднего арифметического всех элементов массива.
    > Пример: из массива A[5]: 8 7 2 6 5 должен получиться массив A[3]: 7 2 5 (среднее арифметическое всех элементов =(8+7+2+6+5)/5=5.6)
13. Из массива удалить элементы, имеющие значение меньше среднего арифметического четных элементов массива.
    > Пример: из массива A[5]: 8 7 2 6 5 должен получиться массив A[3]: 8 7 6 (среднее арифметическое четных элементов =(8+2+6)/3=5.33)
14. Из массива удалить элементы, стоящие после максимального и имеющие значение меньше среднего арифметического всех элементов массива.
    > Пример: из массива A[5]: 8 6 9 4 5 должен получиться массив A[3]: 8 6 9 (среднее арифметическое четных элементов =(8+6+9+4+5)/5=6.4)
15. Из массива удалить четные элементы, стоящие между максимальным и минимальным элементами.
    > Пример: из массива A[7]: 1 8 8 4 7 0 5 должен получиться массив A[5]: 1 8 7 0 5
16. Из массива удалить элементы, кратные трем, стоящие между максимальным и минимальным элементами.
    > Пример: из массива A[7]: 1 9 3 4 9 0 0 должен получиться массив A[5]: 1 9 4 0 0
17. Из массива удалить элементы, имеющие четный индекс и стоящие между максимальным и минимальным элементами.
    > Пример: из массива A[7]: 9 3 4 9 1 0 0 должен получиться массив A[5]: 9 4 1 0 0
18. Из массива удалить элементы, встречающиеся в массиве более одного раза.
    > Пример: из массива A[7]: 9 3 4 9 1 0 0 должен получиться массив A[3]: 3 4 1
19. Из массива удалить элементы, встречающиеся в массиве только один раз.
    > Пример: из массива A[7]: 9 1 4 9 1 9 0 должен
    > получиться массив A[5]: 9 1 9 1 9
20. Из массива удалить нечетные элементы, встречающиеся в массиве только один раз.
    > Пример: из массива A[7]: 4 1 4 3 1 9 0 должен
    > получиться массив A[5]: 4 1 4 1 0



### Задание 2

В массиве А[m,n] каждый элемент, кроме граничных заменить произведением непосредственно примыкающих к нему элементов по вертикали и горизонтали. (Лучше использовать другой массив B[m][n]). 
 
