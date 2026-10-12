---
title: "Rectangle"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "La classe Rectangle représente la zone modifiée d'un document."
type: docs
weight: 12
url: /fr/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

La classe Rectangle représente la zone modifiée d'un document.


Exemple d'utilisation :

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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Initialise une nouvelle instance de la classe Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Crée un nouvel objet Rectangle qui est une copie du rectangle spécifié. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Crée une nouvelle instance de la classe Rectangle avec les x, y, largeur et hauteur spécifiés. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getHeight()](#getHeight--) | Obtient la hauteur du rectangle. |
|
|  | [setHeight(double value)](#setHeight-double-) | Définit la hauteur du rectangle. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur du rectangle. |
|
|  | [setWidth(double value)](#setWidth-double-) | Définit la largeur du rectangle. |
|
|  | [getX()](#getX--) | Obtient la coordonnée x du coin supérieur gauche du rectangle. |
|
|  | [setX(double value)](#setX-double-) | Définit la coordonnée x du coin supérieur gauche du rectangle. |
|
|  | [getY()](#getY--) | Obtient la coordonnée y du coin supérieur gauche du rectangle. |
|
|  | [setY(double value)](#setY-double-) | Définit la coordonnée y du coin supérieur gauche du rectangle. |
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


Initialise une nouvelle instance de la classe Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Crée un nouvel objet Rectangle qui est une copie du rectangle spécifié.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Le rectangle à copier |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Crée une nouvelle instance de la classe Rectangle avec les x, y, largeur et hauteur spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | x | double | La coordonnée x du coin supérieur gauche du rectangle |
|
|  | y | double | La coordonnée y du coin supérieur gauche du rectangle |
|
|  | largeur | double | La largeur du rectangle |
|
|  | hauteur | double | La hauteur du rectangle |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur du rectangle.


**Returns:**
double - la hauteur du rectangle

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Définit la hauteur du rectangle.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La hauteur du rectangle |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur du rectangle.


**Returns:**
double - la largeur du rectangle

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Définit la largeur du rectangle.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La largeur du rectangle |
|

### getX() {#getX--}
```
public double getX()
```


Obtient la coordonnée x du coin supérieur gauche du rectangle.


**Returns:**
double - la coordonnée x du coin supérieur gauche du rectangle

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Définit la coordonnée x du coin supérieur gauche du rectangle.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La coordonnée x du coin supérieur gauche du rectangle |
|

### getY() {#getY--}
```
public double getY()
```


Obtient la coordonnée y du coin supérieur gauche du rectangle.


**Returns:**
double - la coordonnée y du coin supérieur gauche du rectangle

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Définit la coordonnée y du coin supérieur gauche du rectangle.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La coordonnée y du coin supérieur gauche du rectangle |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Paramètre | Type | Description |
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
