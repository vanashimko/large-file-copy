Написать программу копирования больших (<b> > 2 Гб </b>) файлов несколькими процессами одновременно. 

Пользователь задает N - количество одновременно работающих процессов и имена  входного и выходного файлов. Для копирования входной файл разбивается на N частей и каждая часть копируется в отдельном процессе. 

Для решения задачи взаимного исключения при одновремнной записи в выходной файл использовать семафор.

Количество процессов  в любой момент времени должно быть равно N.
