---
title: "Rectangle"
second_title: "GroupDocs.Comparison voor Java API-referentie"
description: "De Rectangle-klasse vertegenwoordigt het gewijzigde gebied op een document."
type: docs
weight: 12
url: /nl/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

De Rectangle-klasse vertegenwoordigt het gewijzigde gebied op een document.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Initialiseert een nieuw exemplaar van de Rectangle-klasse. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Maakt een nieuw Rectangle-object dat een kopie is van de opgegeven rechthoek. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Maakt een nieuw exemplaar van de Rectangle-klasse met de opgegeven x, y, breedte en hoogte. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getHeight()](#getHeight--) | Haalt de hoogte van de rechthoek op. |
|
|  | [setHeight(double value)](#setHeight-double-) | Stelt de hoogte van de rechthoek in. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van de rechthoek op. |
|
|  | [setWidth(double value)](#setWidth-double-) | Stelt de breedte van de rechthoek in. |
|
|  | [getX()](#getX--) | Haalt de x-coördinaat van de linkerbovenhoek van de rechthoek op. |
|
|  | [setX(double value)](#setX-double-) | Stelt de x-coördinaat van de linkerbovenhoek van de rechthoek in. |
|
|  | [getY()](#getY--) | Haalt de y-coördinaat van de linkerbovenhoek van de rechthoek op. |
|
|  | [setY(double value)](#setY-double-) | Stelt de y-coördinaat van de linkerbovenhoek van de rechthoek in. |
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


Initialiseert een nieuw exemplaar van de Rectangle-klasse.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Maakt een nieuw Rectangle-object dat een kopie is van de opgegeven rechthoek.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | De te kopiëren rechthoek |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Maakt een nieuw exemplaar van de Rectangle-klasse met de opgegeven x, y, breedte en hoogte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | x | double | De x-coördinaat van de linkerbovenhoek van de rechthoek |
|
|  | y | double | De y-coördinaat van de linkerbovenhoek van de rechthoek |
|
|  | width | double | De breedte van de rechthoek |
|
|  | height | double | De hoogte van de rechthoek |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van de rechthoek op.


**Returns:**
double - de hoogte van de rechthoek

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Stelt de hoogte van de rechthoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De hoogte van de rechthoek |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt de breedte van de rechthoek op.


**Returns:**
double - de breedte van de rechthoek

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Stelt de breedte van de rechthoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De breedte van de rechthoek |
|

### getX() {#getX--}
```
public double getX()
```


Haalt de x-coördinaat van de linkerbovenhoek van de rechthoek op.


**Returns:**
double - de x-coördinaat van de linkerbovenhoek van de rechthoek

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Stelt de x-coördinaat van de linkerbovenhoek van de rechthoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De x-coördinaat van de linkerbovenhoek van de rechthoek |
|

### getY() {#getY--}
```
public double getY()
```


Haalt de y-coördinaat van de linkerbovenhoek van de rechthoek op.


**Returns:**
double - de y-coördinaat van de linkerbovenhoek van de rechthoek

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Stelt de y-coördinaat van de linkerbovenhoek van de rechthoek in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De y-coördinaat van de linkerbovenhoek van de rechthoek |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
