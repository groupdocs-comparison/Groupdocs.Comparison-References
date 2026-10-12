---
title: "Rectangle"
second_title: "GroupDocs.Comparison for Java API Reference"
description: "Класс Rectangle представляет изменённую область в документе."
type: docs
weight: 12
url: /ru/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Класс Rectangle представляет изменённую область в документе.


Пример использования:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final Rectangle box = change.getBox();
         // Print the changed area on page
         System.out.println("Changed area on a page: "
                 + box.getX() + ", " + box.getY() + ", " + box.getWidth() + ", " + box.getHeight());
     }
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Инициализирует новый экземпляр класса Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Создаёт новый объект Rectangle, который является копией указанного прямоугольника. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Создаёт новый экземпляр класса Rectangle с указанными x, y, шириной и высотой. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getHeight()](#getHeight--) | Возвращает высоту прямоугольника. |
|
|  | [setHeight(double value)](#setHeight-double-) | Устанавливает высоту прямоугольника. |
|
|  | [getWidth()](#getWidth--) | Возвращает ширину прямоугольника. |
|
|  | [setWidth(double value)](#setWidth-double-) | Устанавливает ширину прямоугольника. |
|
|  | [getX()](#getX--) | Возвращает координату x левого верхнего угла прямоугольника. |
|
|  | [setX(double value)](#setX-double-) | Устанавливает координату x левого верхнего угла прямоугольника. |
|
|  | [getY()](#getY--) | Возвращает координату y левого верхнего угла прямоугольника. |
|
|  | [setY(double value)](#setY-double-) | Устанавливает координату y левого верхнего угла прямоугольника. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


Инициализирует новый экземпляр класса Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Создаёт новый объект Rectangle, который является копией указанного прямоугольника.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Прямоугольник, который будет скопирован |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Создаёт новый экземпляр класса Rectangle с указанными x, y, шириной и высотой.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | x | double | X‑координата верхнего левого угла прямоугольника |
|
|  | y | double | Y‑координата верхнего левого угла прямоугольника |
|
|  | ширина | double | Ширина прямоугольника |
|
|  | высота | double | Высота прямоугольника |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Возвращает высоту прямоугольника.


**Returns:**
double - высота прямоугольника

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Устанавливает высоту прямоугольника.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | double | Высота прямоугольника |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Возвращает ширину прямоугольника.


**Returns:**
double - ширина прямоугольника

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает ширину прямоугольника.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | double | Ширина прямоугольника |
|

### getX() {#getX--}
```
public double getX()
```


Возвращает координату x левого верхнего угла прямоугольника.


**Returns:**
double - X‑координата верхнего левого угла прямоугольника

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Устанавливает координату x левого верхнего угла прямоугольника.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | double | X‑координата верхнего левого угла прямоугольника |
|

### getY() {#getY--}
```
public double getY()
```


Возвращает координату y левого верхнего угла прямоугольника.


**Returns:**
double - Y‑координата верхнего левого угла прямоугольника

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Устанавливает координату y левого верхнего угла прямоугольника.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | double | Y‑координата верхнего левого угла прямоугольника |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
