# Тесты для лабораторной работы №8

## Входные данные

Текстовые файлы, содержащие записи о матрице в координатном формате

## Выходные данные

Текстовые файлы, результат операции, содержание записи о матрице в координатном формате

## Позитивные тесты

- 01 - сложение двух матриц порядка 3 на 3, где все элементы не нулевые;
- 02 - умножение матрицы порядка 3 на 3 с одним нулевым элементов на матрицу порядка 3 на 2 без нулевых элементов;
- 03 - вычисление обратной матрицы порядка 3 на 3 без ненулевых элементов.

## Негативные тесты

- 01 - неправильное количество аргументов командной строки;
- 02 - пустой файл с первой матрицей при сложении;
- 03 - нулевой размер матрицы при поиске обратной;
- 04 - матрицы, которые невозможно перемножить;
- 05 - неверный индекс очередного элемента матрицы;
- 06 - количество ненулевых элементов меньше нуля;
- 07 - не квадратная матрица для поиска обратной;
- 08 - пустой файл с первой матрицей при умножении;
- 09 - пустой файл с первой матрицей при поиске обратной матрицы;
- 10 - вырожденная матрица при поиске обратной;
- 11 - отрицательная размерность матрицы при поиске обратной матрицы;
- 12 - ошибка, если уже под считанными позициями был ненулевой элемент;
- 13 - нулевой индекс при записи матрицы в координатном формате;
- 14 - передача несуществующего файла;
- 15 - пустой файл со второй матрицей при сложении;
- 16 - количество ненулевых элементов превышает количество элементов в самой матрице;
- 17 - нулевой размер матрицы при сложении;
- 18 - нулевая матрица при поиске обратной.
