# bilinear_interpolation
Реализация билинейной интерполяции для компилятора cuda c ++.
В математике билинейная интерполяция является расширением линейной интерполяции 
для интерполяционных функций двух переменных (например, x и y) на прямолинейной двумерной сетке. 
Билинейная интерполяция выполняется с использованием линейной интерполяции сначала в одном направлении, 
а затем снова в другом направлении. 
Хотя каждый шаг является линейным по выборочным значениям и по положению, интерполяция в целом не является линейной, 
а скорее квадратичной по местоположению выборки.

Билинейная интерполяция является одним из основных методов передискретизации в компьютерном зрении и обработке изображений, 
где ее также называют билинейной фильтрацией или билинейным отображением текстуры.

Prerequisites
installed cuda c++ compiler
test picture test.jpg
Current PC Configuration
graphics processor - GeForce GTX 950
nvcc compiler version - release 10.1
