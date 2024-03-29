MergeSort

Запуск сортировки возможен через командную строку - необходимо перейти в директорию MergeSort и запускать обработку в соответствии с условиями задачи.
Файлы с входными данными для сортировки необходимо поместить в папку MergeSort. Файл с результатом появится тамже. 

По реализации:
 - Предусмотрены варианты восходящей и нисходящей сортировок (для строк и для чисел) согласно условию задания. 
 - Предусмотрена частичная сортировка файлов. При нарушении указанного порядка сортировки во входящих файлах некорректное значение пропускается и сортировка продолжается.
 - Предусмотрена обратка строк содержащих пробелы - программа их пропускает.
 - Алгоритм устойчив к большим файлам, не помещающимся целиком в оперативную память.
 
Параметры программы задаются при запуске через аргументы командной строки, по порядку:
1. режим сортировки (-a или -d), необязательный, по умолчанию сортируем по возрастанию;
2. тип данных (-s или -i), обязательный;
3. имя выходного файла, обязательное;
4. остальные параметры – имена входных файлов, не менее одного.
   Примеры запуска из командной строки для Windows:
   java -jar MergeSort -i -a out.txt in.txt (для целых чисел по возрастанию)
   java -jar MergeSort -s out.txt in1.txt in2.txt in3.txt (для строк по возрастанию)
   java -jar MergeSort -d -s out.txt in1.txt in2.txt (для строк по убыванию)
