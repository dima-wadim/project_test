# Библиотека для вычисления площади фигур

Эта библиотека позволяет вычислять площадь круга по радиусу и треугольника по трем сторонам. Также включает проверку, является ли треугольник прямоугольным.

## Требования

- Python 3.8 или выше
- `requests` библиотека
- `pillow` библиотека

## Установка

1. Клонируйте репозиторий:
    ```sh
    git clone https://github.com/your-username/geometry.git
    cd geometry
    ```

2. Установите зависимости:
    ```sh
    pip install -r requirements.txt
    ```

## Использование

```python
from shapes.circle import Circle
from shapes.triangle import Triangle

shapes = [Circle(5), Triangle(3, 4, 5)]

for shape in shapes:
    print(f"Area: {shape.area()}")
