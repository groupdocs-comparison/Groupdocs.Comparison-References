---
title: "OriginalSize"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Representa el tamaño original de un documento en un resultado de comparación."
type: docs
weight: 14
url: /es/java/com.groupdocs.comparison.options/originalsize/
---
**Inheritance:**
java.lang.Object
```
public class OriginalSize
```

Representa el tamaño original de un documento en un resultado de comparación.


El tamaño original incluye las dimensiones (ancho y alto) de las páginas del documento.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     CompareOptions compareOptions = new CompareOptions();
     final OriginalSize originalSize = compareOptions.getOriginalSize();
     originalSize.setWidth(480);
     originalSize.setHeight(640);

     comparer.compare(resultFile, compareOptions);
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [OriginalSize()](#OriginalSize--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtiene el ancho de las páginas del documento. |
|
|  | [setWidth(int value)](#setWidth-int-) | Establece el ancho de las páginas del documento. |
|
|  | [getHeight()](#getHeight--) | Obtiene el alto de las páginas del documento. |
|
|  | [setHeight(int value)](#setHeight-int-) | Establece el alto de las páginas del documento. |
|
### OriginalSize() {#OriginalSize--}
```
public OriginalSize()
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de las páginas del documento.


**Returns:**
int - el ancho de las páginas del documento.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de las páginas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho de las páginas del documento. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene el alto de las páginas del documento.


**Returns:**
int - el alto de las páginas del documento.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece el alto de las páginas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El alto de las páginas del documento. |
|

