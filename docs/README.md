
# Принцип устройства

## Table of Contents
1) [[#File structure]]
2) [[#Math formulas]]
3) [[#Использование проекта]]
4) [[#Описание Функций]]
5) [[#История изменений]]

## File structure

./geometric_lib
├── circle.py
├── square.py
└── docs
    └── README.md

2 directories, 3 files

## Math formulas

### Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a² = a * a

### Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b = a + b + a +b
- Square: P = 4a
## Использование проекта

Проект содержит в себе 4 основных файла в формате .py, в каждом из которых имеется по две функции: первая считает площадь фигуры, а вторая — её периметр.

Для расчета периметра используются вышеприведенные [[#Math formulas|формулы]].


## Описание Функций

### Circle.py

**Пример использования функции площади круга и ее описание:**

>>> def area(r):
...     # Принимает радиус круга r, возвращает его площадь. В качестве Пи используется math.pi
...     return math.pi * r * r

>>> area(4)
50.26548245743669

**Пример использования функции периметра окружности и ее описание:**

>>> def perimeter(r):
...     # Принимает радиус окружности r, возвращает ее периметр. В качестве Пи используется math.pi
...     return 2 * math.pi * r 

>>> perimeter(3)
18.84955592153876

### Rectangle.py

**Пример использования функции площади прямоугольника и ее описание:**

>>> def area(a, b):
...     # Функция принимает стороны прямоугольника a и b, возвращает его площадь
...     return a * b

>>> area(5, 4)
20

**Пример использования функции периметра прямоугольника и ее описание:**

>>> def perimeter(a, b):
...     # Функция принимает стороны прямоугольника a и b, возвращает его периметр
...     return a + b + a + b

>>> perimeter(6, 9)
30

### Square.py

**Пример использования функции площади квадарата и ее описание:**

>>> def area(a):
...     # Принимает сторону квадрата a, возвращает его площадь
...     return a * a

>>> area(7)
49

**Пример использования функции периметра квадарата и ее описание:**

>>> def perimeter(a):
...     # Принимает сторону квадрата a, возвращает его периметр
...     return 4 * a

>>> perimeter(420)
1680

### Triangle.py

**Пример использования функции площади треугольника и ее описание:**

>>> def area(a, h):
...     # Принимает сторону треугольника a и высоту проведенную к ней, возвращает его площадь
...     return a * h / 2

>>> area(18, 1)
9.0

**Пример использования функции периметра треугольника и ее описание:**

>>> def perimeter(a, b, c):
...     # Принимает стороны треугольника a, b, c, возвращает его площадь
...     return a + b + c

>>> perimeter(11, 22, 33)
66

## История изменений

##### commit 26f9de8403520fe2a3ffdc2d3e5cccf231d74127 (new_features_465941_test)
| Author: Fire_Blitz <fireblitzwin@gmail.com>
| Date:   Fri Sep 20 10:42:28 2024 +0300
| 
|     `added some advanced optimized geometry formulas`
| 
##### commit b5f75be70ae951f1c7e47eaaad001552b28d0aa2
| Author: Fire_Blitz <fireblitzwin@gmail.com>
| Date:   Fri Sep 20 10:39:52 2024 +0300
| 
|     `forgor to save the rectangle, added triangle.py`
| 
##### commit 09f5bc60c0b58c012283d59b18fb342afbe98837
| Author: Fire_Blitz <fireblitzwin@gmail.com>
| Date:   Fri Sep 20 10:35:09 2024 +0300
| 
|     `added rectangle ong`
| 
##### commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 (HEAD -> main, origin/main, origin/HEAD)
| Author: smartiqa <info@smartiqa.ru>
| Date:   Thu Mar 4 14:55:29 2021 +0300
| 
|    `L-03: Docs added`
| 
##### commit 8ba9aeb3cea847b63a91ac378a2a6db758682460
  Author: smartiqa <info@smartiqa.ru>
  Date:   Thu Mar 4 14:54:08 2021 +0300
  
      L-03: Circle and square added