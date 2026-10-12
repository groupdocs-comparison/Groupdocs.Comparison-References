---
title: "Size"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa el tamaño del documento en la comparación."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison.options.style/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Representa el tamaño del documento en la comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     final Size originalSize = new Size(100, 200);

     StyleSettings styleSettings = new StyleSettings();
     styleSettings.setOriginalSize(originalSize);

     final CompareOptions compareOptions = new CompareOptions();
     compareOptions.setInsertedItemStyle(styleSettings);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Size()](#Size--) | Inicializa una nueva instancia de la clase Size. |
|
|  | [Size(int width, int height)](#Size-int-int-) | Inicializa una nueva instancia de la clase Size con el ancho y alto de un documento. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtiene el ancho de un documento original. |
|
|  | [setWidth(int value)](#setWidth-int-) | Establece el ancho de un documento original. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de un documento original. |
|
|  | [setHeight(int value)](#setHeight-int-) | Establece la altura de un documento original. |
|
### Size() {#Size--}
```
public Size()
```


Inicializa una nueva instancia de la clase Size.


### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Inicializa una nueva instancia de la clase Size con el ancho y alto de un documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int |  |
| height | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de un documento original.


**Returns:**
int - el ancho del documento

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de un documento original.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho del documento |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de un documento original.


**Returns:**
int - la altura del documento

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de un documento original.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La altura del documento |
|

