# Python Laboratory Work №1
## Содержание
- Расчет траекторий точек по данным функциям при заданных наборах параметров и построение двумерных и трехмерных карт этих траекторий с помощью библиотеки [matplotlib](https://matplotlib.org/)
- Построение бифуркационного дерева


### Двумерное отображение
```next_point_2d``` - функция, возвращающая следующую точку двумерного отображения (параметры любые)  
  
  ![2d system](https://github.com/mariaamay/Python_HSE/blob/main/2d_system.png)   

Параметры: ```(a,b): (0.8, 0.3); (1.25, 0.04); (1.42, 0.26)``` - рассчитываем для них траекторию, выделяем закономерность  
  
### Трёхмерное отображение
```next_point_3d``` - функция возвращающую следующую точку трёхмерного отображения (параметры любые)  
  
  ![3d_system](https://github.com/mariaamay/Python_HSE/blob/main/3d_system.png)  

  Параметры: ```B=-0.5 (C, A): (0.13, 0.61); (-0.89, -0.12); (-1.38, -0.42))``` - поступаем аналогично двухмерному отображению 
  
### Построение бифуркационного дерева
- одномерного логистического отображения ```x = r*x*(1 - x)```
-  r меняется от 2.4 до 4.0

> Бифуркационное дерево - карта, по оси Ox отложен параметр (r), по оси Oy переменная (x); точками отмечается последняя тысяча точек из траектории длинной в 10000 при каждом значении параметра
