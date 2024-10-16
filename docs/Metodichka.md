# Методичка
Каждая программа содержит 2 функции, которые позволяют определить площадь и периметр определенной фигуры:
**area**
**perimetr**
Всего есть 4 программы:
## [**tringle.py**](https://github.com/egorzolotarev/geometric_lib/blob/main/triangle.py)
**tringle.py** вычисляет площадь и периметр треугольника

**area** принимает a - сторону треугольника и h - высоту, проведенную к a, и возвращает S, вычисленное по формуле _S = a*h/2_ 
### Пример работы:
area(2,2) = 2

**perimetr** принимает a, b, c - 3 стороны треугольника и возвращает P, вычисленное по формуле _P = a+b+c_ 
### Пример работы:
area(2,2,2) = 6

## [**circle.py**](https://github.com/egorzolotarev/geometric_lib/blob/main/circle.py)
**circle.py** вычисляет площадь и периметр окружности

**area** принимает r - радиус окружности и возвращает S, вычисленное по формуле _S = pi*r*r_ 
### Пример работы:
area(2) = 4*pi

**perimetr** принимает r - радиус окружности и возвращает P, вычисленное по формуле _P = 2*pi*r_ 
### Пример работы:
area(2) = 4*pi

## [**square.py**](https://github.com/egorzolotarev/geometric_lib/blob/main/square.py)
**square.py** вычисляет площадь и периметр квадрата

**area** принимает a - сторону квадрата и возвращает S, вычисленное по формуле _S = a*a_ 
### Пример работы:
area(2) = 4

**perimetr** принимает a - сторону квадрата и возвращает P, вычисленное по формуле _P = 4*a_ 
### Пример работы:
area(2) = 8

## [**rectangle.py**](https://github.com/egorzolotarev/geometric_lib/blob/main/rectangle.py)
**rectangle.py** вычисляет площадь и периметр прямоугольника

**area** принимает a, b - стороны прямоугольника и возвращает S, вычисленное по формуле _S = a*b_ 
### Пример работы:
area(2) = 4

**perimetr** принимает a, b - стороны прямоугольника и возвращает P, вычисленное по формуле _P = (a+b)*2_ 
### Пример работы:
area(2) = 8

# Коммиты

commit [bbcfb0db0c6c92a5df78a8bb46dc96fed06369d9](https://github.com/KulEDmitr/geometric_lib/commit/bbcfb0db0c6c92a5df78a8bb46dc96fed06369d9)
Date:   Tue Oct 15 00:33:04 2024 +0300

    создан triangle.py, rectangle.py изменен

commit [d0d4fa4cc5beff9df1f981543a2d58e4a85db9a1](https://github.com/KulEDmitr/geometric_lib/commit/d0d4fa4cc5beff9df1f981543a2d58e4a85db9a1)
Date:   Tue Oct 15 00:30:36 2024 +0300

    создан rectangle.py

commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 (origin/main, origin/HEAD)
Date:   Thu Mar 4 14:55:29 2021 +0300

    L-03: Docs added

commit 8ba9aeb3cea847b63a91ac378a2a6db758682460
Date:   Thu Mar 4 14:54:08 2021 +0300

    L-03: Circle and square added