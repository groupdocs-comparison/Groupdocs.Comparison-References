---
title: "PageInfo"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase PageInfo representa información sobre una página específica en un documento."
type: docs
weight: 11
url: /es/java/com.groupdocs.comparison.result/pageinfo/
---
**Inheritance:**
java.lang.Object
```
public class PageInfo
```

La clase PageInfo representa información sobre una página específica en un documento.


Proporciona detalles como el número de página, el ancho, la altura y otras propiedades relevantes.
Utilice esta clase para obtener información sobre páginas individuales en un documento durante el proceso de comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         final PageInfo pageInfo = change.getPageInfo();
         // Print the page information
         System.out.println("Page Number: " + pageInfo.getPageNumber());
         System.out.println("Page Width: " + pageInfo.getWidth());
         System.out.println("Page Height: " + pageInfo.getHeight());
     }
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PageInfo(int pageNumber, int width, int height)](#PageInfo-int-int-int-) | Inicializa una nueva instancia de la clase PageInfo configurando pageNumber, ancho y altura. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtiene el ancho de la página |
|
|  | [setWidth(int value)](#setWidth-int-) | Establece el ancho de la página |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de la página |
|
|  | [setHeight(int value)](#setHeight-int-) | Establece la altura de la página |
|
|  | [getPageNumber()](#getPageNumber--) | Obtiene el número de la página |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | Establece el número de la página |
|
| [toString()](#toString--) |  |
### PageInfo(int pageNumber, int width, int height) {#PageInfo-int-int-int-}
```
public PageInfo(int pageNumber, int width, int height)
```


Inicializa una nueva instancia de la clase PageInfo configurando pageNumber, ancho y altura.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageNumber | int | El número de la página |
|
|  | width | int | El ancho de la página |
|
|  | height | int | La altura de la página |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de la página


**Returns:**
int - el ancho de la página

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de la página


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho de la página |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de la página


**Returns:**
int - la altura de la página

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de la página


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La altura de la página |
|

### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Obtiene el número de la página


**Returns:**
int - el número de la página

### setPageNumber(int value) {#setPageNumber-int-}
```
public final void setPageNumber(int value)
```


Establece el número de la página


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El número de la página |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
