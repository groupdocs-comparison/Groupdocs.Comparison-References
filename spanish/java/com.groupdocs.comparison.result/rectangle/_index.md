---
title: "Rectángulo"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase Rectangle representa el área modificada en un documento."
type: docs
weight: 12
url: /es/java/com.groupdocs.comparison.result/rectangle/
---
**Inheritance:**
java.lang.Object
```
public final class Rectangle
```

La clase Rectangle representa el área modificada en un documento.


Ejemplo de uso:

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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Rectangle()](#Rectangle--) | Inicializa una nueva instancia de la clase Rectángulo. |
|
|  | [Rectangle(Rectangle other)](#Rectangle-com.groupdocs.comparison.result.Rectangle-) | Crea un nuevo objeto Rectángulo que es una copia del rectángulo especificado. |
|
|  | [Rectangle(double x, double y, double width, double height)](#Rectangle-double-double-double-double-) | Crea una nueva instancia de la clase Rectángulo con los valores x, y, ancho y alto especificados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getHeight()](#getHeight--) | Obtiene la altura del rectángulo. |
|
|  | [setHeight(double value)](#setHeight-double-) | Establece la altura del rectángulo. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho del rectángulo. |
|
|  | [setWidth(double value)](#setWidth-double-) | Establece el ancho del rectángulo. |
|
|  | [getX()](#getX--) | Obtiene la coordenada x de la esquina superior izquierda del rectángulo. |
|
|  | [setX(double value)](#setX-double-) | Establece la coordenada x de la esquina superior izquierda del rectángulo. |
|
|  | [getY()](#getY--) | Obtiene la coordenada y de la esquina superior izquierda del rectángulo. |
|
|  | [setY(double value)](#setY-double-) | Establece la coordenada y de la esquina superior izquierda del rectángulo. |
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


Inicializa una nueva instancia de la clase Rectángulo.


### Rectangle(Rectangle other) {#Rectangle-com.groupdocs.comparison.result.Rectangle-}
```
public Rectangle(Rectangle other)
```


Crea un nuevo objeto Rectángulo que es una copia del rectángulo especificado.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | El rectángulo a copiar |
|

### Rectangle(double x, double y, double width, double height) {#Rectangle-double-double-double-double-}
```
public Rectangle(double x, double y, double width, double height)
```


Crea una nueva instancia de la clase Rectángulo con los valores x, y, ancho y alto especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | x | double | La coordenada x de la esquina superior izquierda del rectángulo |
|
|  | y | double | La coordenada y de la esquina superior izquierda del rectángulo |
|
|  | width | double | El ancho del rectángulo |
|
|  | height | double | La altura del rectángulo |
|

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura del rectángulo.


**Returns:**
double - la altura del rectángulo

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Establece la altura del rectángulo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La altura del rectángulo |
|

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho del rectángulo.


**Returns:**
double - el ancho del rectángulo

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Establece el ancho del rectángulo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | El ancho del rectángulo |
|

### getX() {#getX--}
```
public double getX()
```


Obtiene la coordenada x de la esquina superior izquierda del rectángulo.


**Returns:**
double - la coordenada x de la esquina superior izquierda del rectángulo

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Establece la coordenada x de la esquina superior izquierda del rectángulo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La coordenada x de la esquina superior izquierda del rectángulo |
|

### getY() {#getY--}
```
public double getY()
```


Obtiene la coordenada y de la esquina superior izquierda del rectángulo.


**Returns:**
double - la coordenada y de la esquina superior izquierda del rectángulo

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Establece la coordenada y de la esquina superior izquierda del rectángulo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La coordenada y de la esquina superior izquierda del rectángulo |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
