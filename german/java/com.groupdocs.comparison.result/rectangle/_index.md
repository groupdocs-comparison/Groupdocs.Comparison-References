---
title: "Rectangle"
second_title: "GroupDocs.Comparison für Java API-Referenz"
description: "Die Klasse Rectangle stellt den geänderten Bereich in einem Dokument dar."
type: docs
weight: 12
url: /de/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

Die Klasse Rectangle stellt den geänderten Bereich in einem Dokument dar.


Beispielverwendung:

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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Initialisiert eine neue Instanz der Klasse Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Erstellt ein neues Rectangle-Objekt, das eine Kopie des angegebenen Rechtecks ist. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Erstellt eine neue Instanz der Klasse Rectangle mit den angegebenen x-, y-, Breiten- und Höhenwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getHeight()](#getHeight--) | Gibt die Höhe des Rechtecks zurück. |
|
|  | [setHeight(double value)](#setHeight-double-) | Setzt die Höhe des Rechtecks. |
|
|  | [getWidth()](#getWidth--) | Gibt die Breite des Rechtecks zurück. |
|
|  | [setWidth(double value)](#setWidth-double-) | Setzt die Breite des Rechtecks. |
|
|  | [getX()](#getX--) | Gibt die x-Koordinate der oberen linken Ecke des Rechtecks zurück. |
|
|  | [setX(double value)](#setX-double-) | Setzt die x-Koordinate der oberen linken Ecke des Rechtecks. |
|
|  | [getY()](#getY--) | Gibt die y-Koordinate der oberen linken Ecke des Rechtecks zurück. |
|
|  | [setY(double value)](#setY-double-) | Setzt die y-Koordinate der oberen linken Ecke des Rechtecks. |
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


Initialisiert eine neue Instanz der Klasse Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Erstellt ein neues Rectangle-Objekt, das eine Kopie des angegebenen Rechtecks ist.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Das zu kopierende Rechteck |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Erstellt eine neue Instanz der Klasse Rectangle mit den angegebenen x-, y-, Breiten- und Höhenwerten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | x | double | Die x-Koordinate der oberen linken Ecke des Rechtecks |
|
|  | y | double | Die y-Koordinate der oberen linken Ecke des Rechtecks |
|
|  | width | double | Die Breite des Rechtecks |
|
|  | height | double | Die Höhe des Rechtecks |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gibt die Höhe des Rechtecks zurück.


**Returns:**
double - die Höhe des Rechtecks

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Setzt die Höhe des Rechtecks.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Höhe des Rechtecks |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gibt die Breite des Rechtecks zurück.


**Returns:**
double - die Breite des Rechtecks

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Setzt die Breite des Rechtecks.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Breite des Rechtecks |
|

### getX() {#getX--}
```
public double getX()
```


Gibt die x-Koordinate der oberen linken Ecke des Rechtecks zurück.


**Returns:**
double - die x-Koordinate der oberen linken Ecke des Rechtecks

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Setzt die x-Koordinate der oberen linken Ecke des Rechtecks.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die x-Koordinate der oberen linken Ecke des Rechtecks |
|

### getY() {#getY--}
```
public double getY()
```


Gibt die y-Koordinate der oberen linken Ecke des Rechtecks zurück.


**Returns:**
double - die y-Koordinate der oberen linken Ecke des Rechtecks

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Setzt die y-Koordinate der oberen linken Ecke des Rechtecks.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die y-Koordinate der oberen linken Ecke des Rechtecks |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
