# Counting-nuts-and-washers-in-the-picture
Сounting nuts and washers in the picture using OpenCV and python

To see full code open [colab code](https://github.com/SaladQueeny/Counting-nuts-and-washers-in-the-picture/blob/main/Kolpakov_Egor_Find_nuts.ipynb)

# Задание: Найти гайки и шайбы

### Исходное изображение:

![image](https://user-images.githubusercontent.com/70723969/177841856-98895853-d52e-4581-9103-ac560b9c8724.png)

## Метод 1. Использование контуров для нахождения и подсчёта гаек и шайб.

### Обработанное изображение для поиска гаек:

![image](https://user-images.githubusercontent.com/70723969/177841907-b664c306-b9cd-4234-8aba-e2c88d4ccd66.png)

### Обработанное изображение для поиска шайб:

![image](https://user-images.githubusercontent.com/70723969/177841966-3e6a75f9-6186-4dae-a845-7a17e69322e1.png)

### Вывод всех найденных и распознанных контуров:

![image](https://user-images.githubusercontent.com/70723969/177842031-007686bf-b466-4e63-9046-37f642985e7b.png)

### Полученный результат методом 1:

![image](https://user-images.githubusercontent.com/70723969/177842066-6e592dd2-72cf-4845-88d9-885881312698.png)

gaikaCount 7
shaibaCount 6

## Поиск методом каскада хаара с тренировкой гайках

![image](https://user-images.githubusercontent.com/70723969/177842110-4cf9222e-f5e1-44fa-8ec6-f7cb9c10e51a.png)

## HoughCircles

![image](https://user-images.githubusercontent.com/70723969/177842161-637f1d62-d9c3-40cb-b90c-134668a89747.png)

![image](https://user-images.githubusercontent.com/70723969/177842180-e71fce7e-44c2-4dd4-ab61-2bc99ea93b38.png)

Найдено гаек: 6 из 11 существующих
