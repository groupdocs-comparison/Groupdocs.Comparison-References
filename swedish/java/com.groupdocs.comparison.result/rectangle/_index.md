---
title: "Rectangle"
second_title: "GroupDocs.Comparison för Java API-referens"
description: "Klassen Rectangle representerar det ändrade området i ett dokument."
type: docs
weight: 12
url: /sv/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Klassen Rectangle representerar det ändrade området i ett dokument.


Exempel på användning:

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


## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Initierar en ny instans av klassen Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Skapar ett nytt Rectangle‑objekt som är en kopia av den angivna rectangle. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Skapar en ny instans av klassen Rectangle med de angivna x, y, bredd och höjd. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getHeight()](#getHeight--) | Hämtar höjden på rectangle. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ställer in höjden på rectangle. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på rectangle. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ställer in bredden på rectangle. |
|
|  | [getX()](#getX--) | Hämtar x‑koordinaten för rectangle:s övre vänstra hörn. |
|
|  | [setX(double value)](#setX-double-) | Ställer in x‑koordinaten för rectangle:s övre vänstra hörn. |
|
|  | [getY()](#getY--) | Hämtar y‑koordinaten för rectangle:s övre vänstra hörn. |
|
|  | [setY(double value)](#setY-double-) | Ställer in y‑koordinaten för rectangle:s övre vänstra hörn. |
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


Initierar en ny instans av klassen Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Skapar ett nytt Rectangle‑objekt som är en kopia av den angivna rectangle.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Den rectangle som ska kopieras |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Skapar en ny instans av klassen Rectangle med de angivna x, y, bredd och höjd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | x | double | x-koordinaten för rektangelns övre vänstra hörn |
|
|  | y | double | y-koordinaten för rektangelns övre vänstra hörn |
|
|  | width | double | Rektangelns bredd |
|
|  | height | double | Rektangelns höjd |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar höjden på rectangle.


**Returns:**
double - höjden på rektangeln

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Ställer in höjden på rectangle.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Rektangelns höjd |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Hämtar bredden på rectangle.


**Returns:**
double - bredden på rektangeln

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Ställer in bredden på rectangle.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | Rektangelns bredd |
|

### getX() {#getX--}
```
public double getX()
```


Hämtar x‑koordinaten för rectangle:s övre vänstra hörn.


**Returns:**
double - x-koordinaten för rektangelns övre vänstra hörn

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Ställer in x‑koordinaten för rectangle:s övre vänstra hörn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | x-koordinaten för rektangelns övre vänstra hörn |
|

### getY() {#getY--}
```
public double getY()
```


Hämtar y‑koordinaten för rectangle:s övre vänstra hörn.


**Returns:**
double - y-koordinaten för rektangelns övre vänstra hörn

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Ställer in y‑koordinaten för rectangle:s övre vänstra hörn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | double | y-koordinaten för rektangelns övre vänstra hörn |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
