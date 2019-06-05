##     
Комментарии преподавателя **в cpp файле** - для Вашего лучшего понимания проблем и ошибок!

# Прежде чем "демонстрировать" свои "крутейшие знания" с++ читать https://habrahabr.ru/post/347166/

|Прозвішча               |  экз|ДЗ1  | ДЗ2 | ДЗ3 | ДЗ4 | ДЗ5 | ДЗ6  | ДЗ7|Диктант| КР| iтог |комментарии |
|:-----------------------|:---:|----:|:---:|----:|----:|----:|:----:|----:|---:|---:|-----:|-----------:|
|Агейчик Анатолий        |  8  | +++ |  +  |   + |  +  |  +  |  +   |  •  |    |    |   8  |            |
|Волчик  Влад            |  8  | ++? |  +  |  +  |  +  |  +  |   +  |  •  |    |    |   8  |            |
|Гапанович Женя          |  7  | +++ |  +  |  +  |  +- |  +  |  -+  |     |    |    |   7  |bmp (Тухолко)   |
|Жилко Рома              |  8  | +++ |  +  |  +  |  -  | -   |  +   |     |    |    |   6  |bmp (Шпаковский)|
|Збойчик Константин      |  7  | +?? |  -+ | -   | -+  | +-  |  --  |     |    |    |   5  |            |
|Ильин Александр         |  9  | +++ |  +  | +   |  +- |  +- |  +-  |  •  |    |    |   7  |            |
|Ковалевский Глеб        |  7  | +++ |   + |  +  |  -  |  ++-|  +   |     |    |    |   7  |            |
|Кисляков Владислав      |  8  | +++ |  +  |  +  |  +  |  -  |   +  |     |    |    |   7  | после 2пинков |
|Куделич Дмитрий         |  8  | +++ |  -+ |  +- |  +  |  +  |   +  |     |    |    |   7  |   1-2 у кого-то я этот код уже видел....  |
|Мальчикова Ксения       |  8  | -+- |  +  |  -  |  -+ | -   |   +  |     |    |    |   4  |            |
|Мартиневский Денис      |  10 |  +  |  +  |  +  |  -  |  -  |   +- |     |    |    |   5  |            |
|Марченко Иван           |  6  |  -+ | +-  |  -+ |  -  |  --+|    --|     |    |    |   4  |            |
|Петращенко Артем        |  5  |     | -+  |     |     |   - |    --|     |    |    |   2  |            |
|Рапинчук Лиза           |  8  |  +++|  +  |  +  |  -  |  +- |   +  |     |    |    |   7  |            |
|Сорока Диана            |  6  |  ?  |  ?  |  ?  |  ?  |  ?  |      |     |    |    |      |            |
|Тухолко Алексей         |  7  | +++ |  +  |  +  |  +- |  +- | +    |  •  |    |    |   7  |bmp(Гапанович) |
|Хомцов Антон            |  7  | --+ | -   |  +? |  -  |  +  |  +-  |     |    |    |   5  |            |
|Шпаковский Андрей       |  7  | --- | +-  |  +  |  -  |  +? |   -- |     |    |    |   3  |bmp(Жилко)  |


# Обязательные требования ко всем лабам:

• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий       
также стоит реализовать вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.      
• имена переменных и функций должны соответствовать общепринятым нормам.

## Задание на 14.02 (указатели, одномерные массивы в heap )
Прочитать, скачать себе и распечатать хорошее краткое объяснение указателей с адреса http://www.math.spbu.ru/user/dlebedin/ncpp4.pdf

## Задание на 21.02 (указатели, одномерные массивы в heap )
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  3 файла с именами 0-1.cpp (тут решение 1-й задачи), 0-2.cpp (тут решение второй задачи), 0-3.cpp, 0-4.cpp)`

•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти прямо в  main;      
•	в зависимости от задания создать одну или несколько функций для обработки массивов, которые передавать туда через указатели;     
•	организация циклов **с использованием указателей**, а не с помощью A[i];     

1. В массиве размера N, заполненного случ.числами от 0 до 10, подсчитать количество элементов, встречающихся более одного раза.     
2. В массиве размера N, заполненного случ.числами от 0 до 10, определить максимальную длину последовательности равных элементов.     
3. Массив чисел размера N проинициализировать случайными числами из промежутка от -N до N. Написать функцию циклического сдвига элементов массива вправо на k элементов.
4. Расположить в порядке возрастания элементы массива А(N), начиная с k-го элемента.

## Задание на 28.02 (функции для работы с одномерными массивами в heap )     
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  4 файла с именами 1-1.cpp (тут решение 1-й задачи), 1-2.cpp (тут решение второй задачи), 1-3.cpp)`

Разработать программу для работы с одним или несколькими одномерными массивами в heap, предусмотрев в ней:     
•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти **в отдельной функции**, а не в main;      
•	разработать функции для инициализации, для ввода, для вывода массивов в heap;      
•	удаление динамической памяти после её использования **обязательно в отдельной функции**;      
•	организация циклов **обязательно с использованием указателей**;     
• одну или несколько функций для обработки массивов (для сортировки новый массив не создавать);нормальные алгоритмы сортировки **для N=100000**  прочитать на https://habr.com/ru/post/414653/   

1. Даны точки плоскости своими координатами в виде двух одномерных массивов (случайные числа). Точки плоскости рассортировать по возрастанию расстояния до прямой ax + by + c = 0.
2. Неотрицательные элементы  (случайные числа) массива А(N), **где N=100000** переставить в конец массива, сохраняя порядок следования. Отрицательные элементы расположить в порядке убывания. Дополнительный массив не использовать.
3. Элементы (случайные числа) массива А(N), **где N=100000** значения которых – простые числа, расположить в порядке возрастания, не изменяя позиций других элементов. Например: 4,11,2,6,8,3 --> 4, 2, 3, 6, 8, 11


Подготовить для работы в аудитории функции для выделения памяти для **двумерного массива**, функции для инициализации, ввода, печати...      
**Прототипы функций:**     

* void give_memory(int**&, int, int)//первый способ. Подумайте, почему обязательно надо тут &
* int** give_memory(int, int)//второй способ. Подумайте, можно ли и безопасно ли тут напісать int**& give_memory     
* void init_array(int **,int,int)
* void print_array(int **,int,int)
* void free_array(int **,int)

## Задание на 7.03 (двумерные массивы в heap)
1) Готовимся программировать динамические структуры данных (стек, дек, очередь). Читаем теорию http://learnc.info/adt/

2) Выбираем одну задачу по работе с массивами **в heap** из списка и реализуем её.      
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  1 файл с именами 2-1.cpp `      
**Попроще**       
• ( ________) В массиве А(N,М) найти номер строки, среднее арифметическое положительных элементов которой является наименьшим и поменять её с первой строкой.    
• (Rapinchuk) В массиве А(N,N) найти первую строку, не содержащую отрицательных элементов, и поменять её с последней строкой.       
• (________) В массиве А(N,М) найти строку, для которой количество перемен знаков максимально и поменять её с первой строкой.        
• (________) В массиве А(N,N) найти максимальные элементы нижнего и верхнего треугольников относительно главной диагонали и поменять местами строки в которых они находятся.       
•	(Malchikova) В массиве А(N,М) поменять местами строки, содержащие максимальный и минимальный элементы.        
•	(Шпаковский) В массиве А(N,М) часть строк состоит из нулей. удалить нулевые строки.       
•	(Марченко) В массиве А(N,М) сменить знаки минимальных элементов и удалить строку с минимальным произведением элементов.       
•	(Гапанович) В массиве А(N,М) расположить строки в порядке возрастания их максимальных элементов.        
•	(________) В массиве А(N,М) расположить строки в порядке возрастания количества минимальных элементов в каждой строке.    
•	(Ковалевский) В массиве А(N,M) переставить строки в порядке возрастания элементов последнего столбца.     
•	(Сорока) В массиве А(N,M) переставить строки так, чтобы строка с максимальной суммой элементов стала первой строкой, а остальные строки расположить в порядке возрастания элементов первого столбца.     

**Посложнее немножко**       
• (Ильин) В массиве А(N,M) расположить строки, стоящие после строки с первым максимальным элементом матрицы, в порядке возрастания количества чётных элементов в строке.      
• (Жилко) В массиве А(N,M) переставить столбцы так, чтобы столбец с максимальной суммой элементов стал первым, а остальные столбцы расположить в порядке возрастания элементов первой строки.        
• (Куделич)	В массиве А(N,M) расположить столбцы по возрастанию количества чётных элементов в столбце.        
• (Тухолко)	В массиве А(N,M) расположить столбцы по возрастанию значений минимальных элементов столбцов. Если минимальные значения в двух столбцах - одинаковые, то первым должен быть тот у которого больше таких минимальных элементов.        
• (________) В массиве А(N,M) элементы столбцов, не содержащих нулевых элементов, расположить в порядке убывания, а сами столбцы расположить в порядке возрастания элементов первой строки.        
• (________)	В массиве А(N,M) расположить элементы каждого столбца в порядке возрастания модулей их отрицательных элементов, а сами столбцы расположить в порядке убывания  сумм их элементов.        
• (________)	В массиве А(N,M) расположить положительные элементы каждого столбца в порядке возрастания, а сами столбцы расположить в порядке убывания их первых максимальных элементов.        
• (Homtsov)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества нечётных элементов в столбце.        
• (Volchyk)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества перемен знаков в каждом столбце.        
• (Kisliakou)	В массиве А(N,M) расположить столбцы в порядке  возрастания количества нулевых элементов в каждом столбце.       
• (Збойчик)	В массиве А(N,М) "удалить" столбцы, все элементы которых являются простыми числами, сдвинув остальные.       
• (Ageichik)	В массиве А(N,М) столбец с минимальным количеством нечетных элементов поменять местами с столбцом c максимальным кол-вом таких элементов.       
• (Денис)	В каждом столбце массива А(N,М) после первого отрицательного элемента вставить максимальную цепочку из положительных элементов данного столбца. Расположить столбцы в порядке возрастания по количеству вставленных элементов. 

## Задание на 21.03 (работа с строкой)
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файл с именем 3-1.cpp)`

1.	(Шпаковский)Определить, сколько слов в строке содержат хотя бы одну заданную букву. Вывести такие слова на экран.
2.	(Ковалевский)Определить количество слов в строке, которые начинаются на заданную букву. Вывести их на экран.
3.	(Рапинчук) Определить, сколько слов в строке начинается с прописной буквы. Вывести их на экран.
4.	Определить, сколько раз стоящие рядом два слова в строке начинаются на одну и ту же букву. Вывести эти слова на экран.
5.	(Мальчикова)Определить длину первого и последнего слова в строке. Если длины совпадают, то заменить их заданной подстрокой, например  ”---”.
6.	(Волкова)Определить, каких слов больше в строке, с чётной длиной или нечётной. Удалить первое слово с чётной длиной.
7.	(Сорока)Определить, каких слов меньше в строке, четырёхсимвольных или пятисимвольных. Вставить после первого четырёхсимвольного слова заданную подстроку, например  ”---”.
8.	Вывести первое и последнее слова на экран. Определить, каких слов больше в строке, совпадающих с первым или последним. Вставить после первого слова заданную подстроку, например  ”---”.
9.	Найти и вывести на экран все слова строки, в которых первый и последний символы совпадают и длина которых чётная. Вывести такие слова на экран. Заменить первое такое слово заданной подстрокой, например  ”---”. (На выбор –удалить все такие слова).
10.	(Марченко)Определить, сколько в строке 4-символьных слов. Вывести такие слова на экран. Заменить последнее такое слово на заданную подстроку, например  ”---”..
11.	Определить, сколько слов в строке совпадает с заданным словом. Вывести такие слова на экран. Удалить первое такое слово.
12.	После каждого слова чётной длины в строке вставить заданную подстроку, например  ”---”.
14.	(6)В строке найти и удалить все слова, начинающиеся и заканчивающиеся гласной буквой.
15.	В строке найти и удалить все слова максимальной длины.
16.	(Петращенко) Найти и удалить все слова строки, состоящие только из цифр.
17.	В строке найти и вывести на экран слова, длина которых - простое число. Вставить после первого слова, длина которого простое число, заданную подстроку, например  ”---”..
18.	В строке удалить все слова заданной длины, начинающиеся с цифры.
19. (Гапанович) В строке после каждого слова с нечётной длиной, начинающегося с заданного символа, вставить заданную подстроку, например  (”---”..
20.	(7-8.Тухолко) В строке найти все слова чётной длины, заканчивающиеся на заданную букву. Вывести их на экран, и вставить после них заданную подстроку, например  ”---”..
21.	(8) В строке удалить слова, в которых буквы упорядочены в алфавитном порядке и которые начинаются на большую букву.
26.	(8) В строке найти и вывести на экран слова, в которых буквы упорядочены в алфавитном порядке. Удалить все такие слова.
40.	(7-8 ) В строке найти и вывести на экран все слова, в которых буквы упорядочены в порядке, обратном алфавитному (TOK, zona).
22.	(7 ) В строке удалить все слова, содержащие заданную букву ровно два раза.
23.	(Устинов 6) В строке найти, вывести на экран и, затем, удалить из исходной строки фрагменты, заключённые в круглые скобки. Скобки расставлены верно. Проверять не надо.
13.	(6) В строке удалить слова, заключённые в круглые скобки и длина которых чётная.  Скобки расставлены верно. Проверять не надо.24.	(6) После каждого трёхбуквенного слова в строке вставить заданную подстроку, например  ”---”..
25.	В строке найти и вывести на экран все слова ”палиндромы” (пишутся одинаково слева направо и справа налево).
27.	(Kisliakou)(8-9) После каждого слова строки, оканчивающегося заданной подстрокой, вставить указанный символ.
28.	(7)В строке поменять местами первое слово минимальной длины и первое слово максимальной длины.
29.	(Homtsov)(8-9 ) В строке в каждой паре слов поменять слова местами, если длины слов совпадают, иначе заменить их звёздочками.
30.	В каждом слове нечётной длины строки удалить буквы, стоящие на нечётных позициях.
31.	Преобразовать каждое слово в строке, удалив в нём заданную букву.
32.	Преобразовать каждое слово чётной длины в строке, удалив в нём стоящие рядом одинаковые символы, оставив по одному.
33.	Заменить все слова в строке  заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит хотя бы одну цифру.
34.	(8) Если в строке есть слово, которое встречается k раз, удалить все такие слова кроме последнего.
36. (Збойчик)(8-9) Назовём два слова, стоящие рядом, особой парой, если заданная буква встречается в них одинаковое число раз, и номера позиций, в которых она располагается и в том и в другом слове, одинаковы. Вывести на экран все особые пары и удалить их.
37.	(Волчик)(7) Найти и удалить все слова  в  тексте,  содержащие 1 слог. Вывести все такие слова на экран.
38.	(8)В строке найти и вывести на экран все слова максимальной длины,  и удалить за ними следующее слово.
39.	(7-8) В строке найти слова-палиндромы c нечётной длиной (radar, ANANA), и вставить после них заданную подстроку .
41.	(7-8) В строке найти слова, длина которых простое число, и заменить слово на  ---…- .  Количество  -  должно соответствовать длине слова.
42.	Поменять местами в строке первое слово и последнее (длины слов могут не совпадать), второе и предпоследнее и т.д. Заменить потом в последнем слове все вхождения заданного символа заданной подстрокой.
43.	(7) В строке удалить лишние пробелы и поменять местами слова минимальной и максимальной длины (если таких слов несколько, то брать первое;  длины слов могут не совпадать).
44.	В строке удалить лишние пробелы и слова максимальной длины, начинающиеся и заканчивающиеся заданными символами.
45.	Заданы две строки S1 и S2. Удалить из строки S1 первое и последнее вхождения подстроки S2.
46.	(Куделич 6)Определить, сколько слов в строке содержат хотя бы одну букву A. Вывести такие слова на экран.
47.	(7) Определить, сколько слов в строке имеют одинаковую длину. Вывести такие слова на экран.
48.	(6) В строке найти сумму цифр, содержащихся во всех словах и слово с максимальной суммой цифр.
49.	(7)В строке удалить лишние пробелы и найти слово, которое содержит максимальное количество заданной буквы.
50.	(6) Определить, сколько слов в строке имеют заданную длину. Вывести такие слова на экран. Вставить перед такими словами заданную подстроку.
51.	(5-6) В строке после каждого слова заданной длины, начинающегося с цифры, вставить заданную подстроку.
52.	(6-7) Определить, сколько слов в строке начинаются заданным символом. Вывести такие слова на экран. После первого такого слова удалить следующее слово.
53.	(Ilyin)(7-8) Заменить все слова в строке заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит хотя бы одну цифру.
54. (Жилко)(7) Определить, сколько слов в строке состоит только из цифр. Вывести такие слова на экран и удалить после них следующее слово.
55.	(Ageichik)(7) В строке найти слова, содержащие цифры, расположенные подряд, и заменить их  ---…-. Вставить перед такими словами заданную подстроку.
35.	(8)В строке найти слово (слова), содержащее максимальное количество цифр, расположенных подряд, и заменить их на ---…-. Вставить после таких слов заданную подстроку.
56.	(Денис) (8-9 ) Найти и вывести на экран все слова строки, в которых все буквы различны. Вставить перед такими словами заданную подстроку.


## Задание на 29.03 (работа с массивами строк)
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файл с именем 4-1.cpp)`

Выбрать ОДНО задание из списка ниже и разработать программу, предусмотрев в ней:     
•	последовательное чтение строк **из входного текстового файла** (ПОСТРОЧНОЕ, а не весь файл целиком или побайтово);    
### Программа тестируется на текстовом файле "Война и мир" (100500строк) ###     
•	использование указателей при работе со строками;     
•	использование библиотечных функций <cstring> для работы со строками (т.е. нельзя в программе обратиться к символам строки как str[1] или str[i]);     
•	создание нескольких собственных функций для обработки строк;     
•	вывод результатов **в новый текстовый файл (result.txt)**;     
•	поощряется использование меню на массиве указателей на функции.

**Попроще итоговая оценка меньше 8. Файл не большой <1000 строк**    
1.	Отсортировать строки по количеству слов, содержащих цифры.
2.	Отсортировать строки по количеству слов заданной длины.
3.	Отсортировать строки по количеству слов с двумя слогами.
4.	Отсортировать строки по количеству слов-палиндромов.
5.	Отсортировать строки по количеству слов, в которых все буквы различны.
6.	Отсортировать строки по количеству слов, в которых буквы упорядочены в алфавитном порядке.
7.	Отсортировать строки по возрастанию длин слов максимальной длины.
8.	Отсортировать строки по количеству слов, длины которых  простые числа.
9.	Отсортировать строки по количеству слов, состоящих только из цифр.
10.	Отсортировать строки по количеству предложений, заканчивающихся восклицательным знаком.
11.	Определить, каких слов больше в каждой строке, первого или последнего. Если больше первого, отсортировать строки в алфавитном порядке по первому слову, иначе – по последнему.
12.	Отсортировать строки по количеству слов, в которых первый и последний символы совпадают и длина которых чётная.
13. После каждого слова чётой длины в каждой строке вставить заданную подстроку, например  ”---”. Отсортировать строки по количеству вставленных подстрок.
14.	В каждой строке после слов, заканчивающихся заданной буквой, вставить подстроку, состоящую из  звёздочек, количество которых соответствует длине слова. Отсортировать строки по количеству вставленных подстрок.
15. (Ковалевский)	После каждого трёхбуквенного слова в строке вставить заданную подстроку. Отсортировать строки по количеству вставленных подстрок.
16.	(Шпаковский) В строке удалить все слова заданной длины, начинающиеся с цифры. Отсортировать строки по количеству удалённых слов.
17.	(Марченко)В строке удалить все слова нечётной длины, начинающиеся на заданную букву. Отсортировать строки по количеству удалённых слов.
18.	(Гапанович) В каждой строке удалить все слова чётной длины, заканчивающиеся на заданную букву. Отсортировать строки по количеству удалённых слов.
19. (Петращенко)	В каждой строке удалить слова, в которых буквы упорядочены в алфавитном порядке и которые начинаются на большую букву. Отсортировать строки по количеству удалённых слов.
20.	(Рапинчук) В строке удалить все слова, содержащие заданную букву два раза. Отсортировать строки по количеству удалённых слов.
21. (Тухолко)	В строке удалить слова (а не выражения), заключённые в круглые скобки. Скобки могут быть расставлены неправильно!!! Отсортировать строки по количеству удалённых слов.
22.(Куделич)    Преобразовать каждое слово в строках, удалив в них заданную букву. Отсортировать строки по количеству удалённых букв.
23.	Преобразовать каждое слово чётной длины в строках, удалив в них стоящие рядом одинаковые символы, оставив по одному. Отсортировать строки по количеству удалённых символов.
24. (ilyin)	Заменить все слова в строках заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит несколько цифр. Отсортировать строки по количеству замен.
25.	В каждой строке найти слова, содержащие максимальное количество цифр, расположенных подряд, и заменить их на ---…-. Отсортировать строки по количеству таких слов.
26.	Назовём два слова особой парой, если заданная буква встречается в них одинаковое число раз, и номера позиций, в которых она располагается и в том и в другом слове, одинаковы. Отсортировать строки по количеству таких слов.
27.	В каждой строке поменять местами соседние слова, если их длины совпадают, иначе удалить эти слова. Отсортировать строки по количеству удалённых пар слов.

**Посложнее. Файл большой >100000 строк**    
28. (Ageichik)	В тексте выбрать все слова, начинающиеся с заданной буквы, и расположить их в порядке убывания количества букв в слове.
29.	(Збойчик) В тексте выбрать все слова, начинающиеся с гласных букв, и расположить их в порядке возрастания количества букв в слове.
30.	(Мальчикова) В тексте выбрать все слова-палиндромы и расположить в порядке возрастания их длин.
31.	Для каждого слова из заданного списка определить, сколько раз оно встречается в тексте, и рассортировать их в порядке убывания найденных количеств.
32.	Найти и вывести без повторений все слова заданной длины, содержащиеся в восклицательных предложениях текста. Отсортировать все найденные слова в алфавитном порядке.
33. (Волчик)	В тексте найти предложение, содержащее наибольшее количество слов, начинающихся на заданную букву. Отсортировать все слова найденного предложения в алфавитном порядке.
34. (Жилко)	Найти все предложения текста, в которых есть одинаковые слова. Отсортировать их в алфавитном порядке по первому слову.
35.	Во всех вопросительных предложений текста выбрать слова заданной длины. Отсортировать их в алфавитном порядке.
36. (Денис)	Найти в каждой строке вопросительные предложения, содержащие чётное количество слов. Отсортировать строки по количеству таких слов в вопросительных предложениях.
37. (Homtsov).	В каждой строке удалить восклицательные предложения. Отсортировать строки по количеству удалённых предложений.
38.	В каждой строке выбрать самые длинные предложения. Отсортировать их по первому слову ( последнему) в алфавитном порядке.    
•	()В строках текста удалить фрагменты, заключённые в круглые скобки.    
•	() В тексте удалить фрагменты, заключённые в круглые скобки (скобка может начинаться в одной строке, а заканчиваться -  другой. Могут быть вложенные скобки, но они всегда верно расставлены. Т.е. нет ситуации "(...(...)..()" ).     
•	()Определить есть ли в тексте слово, которое встречается ровно k раз, удалить все такие слова кроме последнего.     
•	В тексте найти и вывести все слова максимальной длины, и удалить за ними следующее слово.В тексте поменять местами слова минимальной и максимальной длины (если таких слов несколько, то брать первое).  

```
// Прочитать файл "date1.txt".
// К концу каждой строки добавить "***"  и записать в новый файл "date2.txt".
#include<iostream>
#include<fstream> 		                 // подключение библиотеки файлового ввода/вывода через потоки
using namespace std;
int main(){
const int N=200;
 char *buff = new char[N];
 ifstream fffff("d:\\date1.txt"); // отсюда читаем (поток типа ifstream= input file stream)
 ofstream ggggg("d:\\date2.txt");//сюда пишем (поток типа ofstream= output file stream)
 if (!fffff){cout<<"No file d:\\date1.txt. Can't open\n"; exit(1);}
 if (!ggggg){cout<<"   file d:\\date2.txt. Can't create\n"; exit(1);}

int count=0;
while(1){
    fffff.getline(buff, N-1); //читаем ПОСТРОЧНО.
//Если будет в строке файла больше N-1 символов, то getline() поместит в буфер N-1 символов, в конец поместит '\0', установит флаг ошибки (failbit), поток станет нерабочим, не введённое останется в очереди ввода.
    if (fffff.fail()) fffff.clear(); //getline при переполнении выставляет бит состояния =1. Его проверяем fail'ом. А потом подчищаем буфер
    cout<<buff<<'\n'; //на экран
    ggggg<<buff<<"***";//в файл
    count++;

    if(fffff.eof()) break; //читаем пока не кончится исходный файл. Т.е. пока не прочитаем EOF.
    ggggg<<'\n';//переход на новую строку пишем в date2.txt только, если в строке 16 мы прочитали действительно СТРОКУ (до endl), а не последнюю строку афйла в которой EOF, а не endl
 }
cout<<"-----In file "<<count<<" lines";
delete [] buff;
fffff.close();//закрыли файл
ggggg.close();//закрыли файл
system("pause");
}
```    

## Задание на 29.03 (чтение информации из файла bmp)

0. Создать в корне диска D: средствами MSpaint произвольный bmp файл с размером изображения 256px на 128px      
1. Открыть файл в HEX редакторе     
2. Найти в сети информацию (запрос "Структура bmp") в каких байтах записаны высота и ширина. Найти их в вашем файле. Убедиться, что там записано 256px и 128px     
3. Написать свою программ, которая читает эти данные из bmp файла
4*(для желающих). Прочитать из произвольного файла bmp информацию про изображение. Построить "гистограмму" распределения на промежутке [0;255] цветов в нём. Т.е. вычислить кол-во точек с R=0,R=1,R=2,...R=255 и как-то визуализировать это кол-во. Аналогично для компонент G и B.      

```  
#include<iostream>
#include<fstream>  
using namespace std;
struct color{ unsigned char r; unsigned char g; unsigned char b; } c;

int main(){
	ifstream fff("d:\\1.bmp", ios::binary); //  ios::binary влияет ТОЛЬКО на endl.
	ofstream ggg("d:\\rez.bmp", ios::binary);//сюда пишем (поток типа ofstream= output file stream)
	if (!fff){ cout << "No file d:\\1.bmp. Can't open\n"; exit(1); }
	if (!ggg){ cout << "   file d:\\rez.bmp. Can't create\n"; exit(1); }

	char buf[30];// куда читать байты
	unsigned char r, g, b;//компоненты цвета
 color c;
	unsigned int w, h;//надеемся. что тут 4 байта

	fff.read((char *)&buf, 18);   //чтение 18 байт заголовка bmp
	ggg.write((char *)&buf, 18);    //запись 18 байт заголовка bmp
	fff.read((char *)&w, 4); cout << "w=" << w;   //чтение width из заголовка bmp
	fff.read((char *)&w, 4); cout << ", h=" << w; //чтение height из заголовка bmp
	w =32 ; ggg.write((char *)&w, 4);    //запись width в заголовок bmp ( w кратно 4, обязательно для нас, чтобы не делать выравнивание)
	h =128; ggg.write((char *)&h, 4);    //запись height в заголовок bmp
	fff.read((char *)&buf, 28);   //чтение 28 байт заголовка bmp
	ggg.write((char *)&buf, 28);    //запись 28 байт заголовка bmp

	//c.r=c.g=c.b=0;
	//for(int i=1;i<=h;++i){
	// /*    ++r;g=0;b=0;*/
	//for(int j=1;j<=w;++j){
	//    ggg.write((char *)&c, 3);     //запись сразу всего цвета
	//    ++c.g;
	// /*    ggg.write((char *)&b, 1);   //запись одной компоненты цвета
	//    ggg.write((char *)&g, 1);    //запись одной компоненты цвета
	//    ggg.write((char *)&r, 1);    //запись одной компоненты цвета
	//    ++g;
	//    */
	//}
	//++c.r;c.g=c.b=0;
	//}

	fff.close();//закрыли файл
	ggg.close();//закрыли файл
	return 1;
}
```  

## Задание на 4.04 (создание файла bmp)

0. Создать в корне диска D: средствами MSpaint 1.bmp файл с 24Bit изображением      
1. Создать собственный bmp файл взяв из 1.bmp заголовок (желающие могут сами генерировать заголовок bmp файла)     
• Ширина изображения должна быть кратна 4     
• Высота - какую пожелаете     
• Изображение должно показыать градиент от цвета1 до цвета2 с шагом step(кратным 4). Например, от 128,16,77 до 255,46,99 за 80 шагов. Эти переменные или вводятся пользователем или объявлены как константы и я их могу менять при трансляции.    
а) (простые) вертикальный-горизонтальный градиент     
б) (сложнее) диагональный градиент     
в) (интересные) радиальный градиент от центра/угла/произвольной точки, "прямоугольный" градиент от произвольной точки     

## Задание на 19.04 (класс-значение)

Cсылка на реализацию класса студент: http://blog.kislenko.net/show.php?id=1465     
Лекции с подробными объяснениями лабораторных http://ermak.cs.nstu.ru/cprog/HTML/index.htm     

Cделать свои проекты с реализацией конструкторов, деструкторов (в которых, просто выдается сообщение, что он сработал) и операций =, +,-,умножить, <<, >> и т.д. простейших классов.     
В main() надо не только объявить 2-3 объекта вашего класса и массив таких объектов, но и сделать пару-тройку указателей на объеты!!! Проинициализировать некоторые из них теми объетами, которые уже есть, а некоторые проинициализировать с помощью оператора, NEW. После этого, в main выполнить пару-тройку действий с объектами и с указателями (присвоение, сумма, удаление...) чтобы показать, что все методы работают!

(Мартиневский)Класс линейных уравнений с использованием динамической памяти(выбор количества неизвестных)
(Гапанович)Класс квадратные уравнения. Хранить коэффициенты и корни.
(Куделич)Объект: возвратное кубическое уравнение.  решение возвратного кубического уравнения (Ax^3+Bx^2+Bx+A=0)      

(Ковалевский)Класс парабола. Хранить коэффициенты и вершину.
(Збойчик)Класс система 2-х линейных ур-й. Хранить коэффициенты и решение(решения).

(Петращенко)Класс квадратных матриц 2x2     
(Сорока)Класс квадратных матриц 3x3

(Ильин)Класс дата. Операция - вывести какой день недели сейчас хранится в объекте     
(Агейчик)Класс время. Операция - вывести что сейчас хранится в объекте: сейчас утро, день,вечер или ночь.    
(Кисляков)Класс деньги(рубли,копейки).     

(Волчик)Класс арифметическая дробь.     
(Жилко)Класс смешанная дробь.     

(Тухолко)Класс точка в двумерном пространстве. Хранить декартовы прямоугольные и полярные координаты.     
(Хомцов)Класс вектор в трехмерном пространстве.     
(Рапинчук)Класс вектор в N-мерном пространстве. N задается как глобальная константа.     
(Мальчикова)Класс точка в N-мерном пространстве. N задается как глобальная константа.     
(Марченко)Класс прямоугольник в декартовой прямоугольной с/к     
(Шпаковский)Класс треугольник в декартовой прямоугольной с/к     

## Задание на 01.06 В репозитории лежит pdf с заданиями.
Список задач финального проекта 

1.  Збойчик К.
2.  Мартиневский Д.
3.  Кисляков В.
4.  Агейчик А.
5.  Ильин 
6.  Волчик 
7.  Тухолко
8.  Мальчикова 
9.  Куделич Д.
10. Гапанович Е.
11. Жилко 
12. Марченко 
13. Шпаковский
14. Рапинчук 
15. Ковалевский 
16. Хомцов 
17. Петращенко 
