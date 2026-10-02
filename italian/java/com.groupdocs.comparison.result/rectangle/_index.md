---
title: "Rectangle"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "La classe Rectangle rappresenta l'area modificata in un documento."
type: docs
weight: 12
url: /it/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

La classe Rectangle rappresenta l'area modificata in un documento.


Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Inizializza una nuova istanza della classe Rectangle. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Crea un nuovo oggetto Rectangle che è una copia del rettangolo specificato. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Crea una nuova istanza della classe Rectangle con i valori x, y, larghezza e altezza specificati. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getHeight()](#getHeight--) | Ottiene l'altezza del rettangolo. |
|
|  | [setHeight(double value)](#setHeight-double-) | Imposta l'altezza del rettangolo. |
|
|  | [getWidth()](#getWidth--) | Ottiene la larghezza del rettangolo. |
|
|  | [setWidth(double value)](#setWidth-double-) | Imposta la larghezza del rettangolo. |
|
|  | [getX()](#getX--) | Ottiene la coordinata x dell'angolo superiore sinistro del rettangolo. |
|
|  | [setX(double value)](#setX-double-) | Imposta la coordinata x dell'angolo superiore sinistro del rettangolo. |
|
|  | [getY()](#getY--) | Ottiene la coordinata y dell'angolo superiore sinistro del rettangolo. |
|
|  | [setY(double value)](#setY-double-) | Imposta la coordinata y dell'angolo superiore sinistro del rettangolo. |
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


Inizializza una nuova istanza della classe Rectangle.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Crea un nuovo oggetto Rectangle che è una copia del rettangolo specificato.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Il rettangolo da copiare |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Crea una nuova istanza della classe Rectangle con i valori x, y, larghezza e altezza specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | x | double | La coordinata x dell'angolo superiore sinistro del rettangolo |
|
|  | y | double | La coordinata y dell'angolo superiore sinistro del rettangolo |
|
|  | width | double | La larghezza del rettangolo |
|
|  | height | double | L'altezza del rettangolo |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene l'altezza del rettangolo.


**Returns:**
double - l'altezza del rettangolo

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Imposta l'altezza del rettangolo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | L'altezza del rettangolo |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ottiene la larghezza del rettangolo.


**Returns:**
double - la larghezza del rettangolo

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Imposta la larghezza del rettangolo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La larghezza del rettangolo |
|

### getX() {#getX--}
```
public double getX()
```


Ottiene la coordinata x dell'angolo superiore sinistro del rettangolo.


**Returns:**
double - la coordinata x dell'angolo superiore sinistro del rettangolo

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Imposta la coordinata x dell'angolo superiore sinistro del rettangolo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La coordinata x dell'angolo superiore sinistro del rettangolo |
|

### getY() {#getY--}
```
public double getY()
```


Ottiene la coordinata y dell'angolo superiore sinistro del rettangolo.


**Returns:**
double - la coordinata y dell'angolo superiore sinistro del rettangolo

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Imposta la coordinata y dell'angolo superiore sinistro del rettangolo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La coordinata y dell'angolo superiore sinistro del rettangolo |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
