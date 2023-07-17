# GameLife
Целью работы является реализация игры “Жизнь” , позволяющая
выводить поколение игры в монохромную картинку в формате BMP. Плоскость
“вселенной” игры ограничена положительными координатами.
Лабораторная работы должна быть выполнена в виде консольного приложения
принимающего в качестве аргументов следующие параметры:

1. --input input_file.bmp

Где input_file.bmp - монохромная картинка в формате bmp,
хранящая начальную ситуация (первое поколение) игры

2. --output dir_name

Название директории для хранения поколений игры в виде
монохромной картинки

3. --max_iter N

Максимальное число поколений которое может эмулировать

программа. Необязательный параметр, по-умолчанию бесконечность

4. --dump_freq N

Частота с которой программа должно сохранять поколения виде
картинки. Необязательный параметр, по-умолчанию равен 1

Программа должна предусматривать исключительные ситуации, которые могут
возникать во время ее работы и корректно их обрабатывать.
# Example
![Result](https://github.com/siriusbNS/GameLife/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202023-07-17%20%D0%B2%2016.59.58.png)
