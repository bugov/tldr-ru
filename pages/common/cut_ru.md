# cut

> Вырезать поля из стандартного потока ввода(STDIN) или файла.

- Вырезать первые шестнадцать символов каждой строки STDIN:

`cut -c {{1-16}}`

- Вырезать первые шестнадцать символов каждой строки из казанного файла:

`cut -c {{1-16}} {{file}}`

- Вырезать все от 3-го символа до конца каждой строки:

`cut -c{{3-}}`

- Вырезать пятое поле каждой строки, используя двоеточие в качестве разделителя (разделитель по умолчанию - табуляция):

`cut -d'{{:}}' -f{{5}}`

- Вырезать 2-е и 10-е поля каждой строки, используя точку с запятой в качестве разделителя:

`cut -d'{{;}}' -f{{2,10}}`

- Вырезать поля с 3 по 7 каждой строки, используя пробел в качестве разделителя:

`cut -d'{{ }}' -f{{3-7}}`