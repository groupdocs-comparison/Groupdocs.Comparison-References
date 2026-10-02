---
title: "ChangeInfo"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase ChangeInfo representa información sobre un cambio específico en una comparación de documentos."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.result/changeinfo/
---
**Inheritance:**
java.lang.Object
```
public class ChangeInfo
```

La clase ChangeInfo representa información sobre un cambio específico en una comparación de documentos.


Proporciona detalles como el tipo de cambio, el área afectada y el contenido antes y después del cambio.
Utilice esta clase para obtener información sobre cambios individuales dentro de un resultado de comparación.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare(resultFile);
     // Get a list of changes from the comparison result
     ChangeInfo[] changes = comparer.getChanges();
     // Iterate through the changes and retrieve information
     for (ChangeInfo change : changes) {
         ChangeType changeType = change.getType();
         String componentType = change.getComponentType();
         PageInfo pageInfo = change.getPageInfo();
         // Process the change information as needed
         // ...
     }
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [ChangeInfo()](#ChangeInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRow()](#getRow--) |  |
| [setRow(Integer row)](#setRow-java.lang.Integer-) |  |
| [getColumn()](#getColumn--) |  |
| [setColumn(Integer column)](#setColumn-java.lang.Integer-) |  |
| [getColumnHeader()](#getColumnHeader--) |  |
| [setColumnHeader(String columnHeader)](#setColumnHeader-java.lang.String-) |  |
|  | [getId()](#getId--) | Obtiene el id único del cambio. |
|
|  | [setId(int value)](#setId-int-) | Establece el id único del cambio. |
|
|  | [getComparisonAction()](#getComparisonAction--) | Obtiene la acción que se aplicará al cambio. |
|
|  | [setComparisonAction(ComparisonAction value)](#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-) | Establece la acción que debe aplicarse al cambio. |
|
|  | [getPageInfo()](#getPageInfo--) | Obtiene información sobre la página en la que se encontró el cambio actual. |
|
|  | [setPageInfo(PageInfo value)](#setPageInfo-com.groupdocs.comparison.result.PageInfo-) | Establece información sobre la página en la que se encontró el cambio actual. |
|
|  | [getBox()](#getBox--) | Obtiene las coordenadas del elemento modificado en la página. |
|
|  | [setBox(Rectangle value)](#setBox-com.groupdocs.comparison.result.Rectangle-) | Establece las coordenadas del elemento modificado en la página. |
|
|  | [getText()](#getText--) | Obtiene el valor de texto del cambio. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Establece el valor de texto del cambio. |
|
|  | [getStyleChanges()](#getStyleChanges--) | Obtiene la lista de cambios de estilo. |
|
|  | [setStyleChanges(List<StyleChangeInfo> value)](#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--) | Establece la lista de cambios de estilo. |
|
|  | [getAuthors()](#getAuthors--) | Obtiene la lista de autores. |
|
|  | [setAuthors(List<String> value)](#setAuthors-java.util.List-java.lang.String--) | Establece la lista de autores. |
|
|  | [getType()](#getType--) | Obtiene el tipo de cambio representado por el enum [ChangeType](../../com.groupdocs.comparison.result/changetype). |
|
|  | [getTargetText()](#getTargetText--) | Obtiene el texto modificado del documento de destino. |
|
|  | [setTargetText(String value)](#setTargetText-java.lang.String-) | Establece el texto modificado del documento de destino. |
|
|  | [getSourceText()](#getSourceText--) | Obtiene el texto modificado del documento de origen. |
|
|  | [setSourceText(String value)](#setSourceText-java.lang.String-) | Establece el texto modificado del documento fuente. |
|
|  | [getComponentType()](#getComponentType--) | Obtiene el tipo del componente modificado. |
|
|  | [setComponentType(String value)](#setComponentType-java.lang.String-) | Establece el tipo del componente modificado. |
|
| [toString()](#toString--) |  |
### ChangeInfo() {#ChangeInfo--}
```
public ChangeInfo()
```


### getRow() {#getRow--}
```
public Integer getRow()
```




**Returns:**
java.lang.Integer
### setRow(Integer row) {#setRow-java.lang.Integer-}
```
public void setRow(Integer row)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fila | java.lang.Integer |  |

### getColumn() {#getColumn--}
```
public Integer getColumn()
```




**Returns:**
java.lang.Integer
### setColumn(Integer column) {#setColumn-java.lang.Integer-}
```
public void setColumn(Integer column)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columna | java.lang.Integer |  |

### getColumnHeader() {#getColumnHeader--}
```
public String getColumnHeader()
```




**Returns:**
java.lang.String
### setColumnHeader(String columnHeader) {#setColumnHeader-java.lang.String-}
```
public void setColumnHeader(String columnHeader)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encabezadoDeColumna | java.lang.String |  |

### getId() {#getId--}
```
public final int getId()
```


Obtiene el id único del cambio.


**Returns:**
int - el id del cambio

### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Establece el id único del cambio.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El id del cambio |
|

### getComparisonAction() {#getComparisonAction--}
```
public final ComparisonAction getComparisonAction()
```


Obtiene la acción que se aplicará al cambio.
La Acción ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) o [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) indica a la comparación qué hacer con este cambio.


**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) - the action that will be applied to the change

### setComparisonAction(ComparisonAction value) {#setComparisonAction-com.groupdocs.comparison.result.ComparisonAction-}
```
public final void setComparisonAction(ComparisonAction value)
```


Establece la acción que debe aplicarse al cambio.
La Acción ([ComparisonAction.ACCEPT](../../com.groupdocs.comparison.result/comparisonaction#ACCEPT) o [ComparisonAction.REJECT](../../com.groupdocs.comparison.result/comparisonaction#REJECT)) indica a la comparación qué hacer con este cambio.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction) | La acción que debe aplicarse al cambio |
|

### getPageInfo() {#getPageInfo--}
```
public final PageInfo getPageInfo()
```


Obtiene información sobre la página en la que se encontró el cambio actual.


**Returns:**
[PageInfo](../../com.groupdocs.comparison.result/pageinfo) - information about the page

### setPageInfo(PageInfo value) {#setPageInfo-com.groupdocs.comparison.result.PageInfo-}
```
public final void setPageInfo(PageInfo value)
```


Establece información sobre la página en la que se encontró el cambio actual.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PageInfo](../../com.groupdocs.comparison.result/pageinfo) | Información sobre la página |
|

### getBox() {#getBox--}
```
public final Rectangle getBox()
```


Obtiene las coordenadas del elemento modificado en la página.


**Returns:**
[Rectangle](../../com.groupdocs.comparison.result/rectangle) - coordinates of changed element

### setBox(Rectangle value) {#setBox-com.groupdocs.comparison.result.Rectangle-}
```
public final void setBox(Rectangle value)
```


Establece las coordenadas del elemento modificado en la página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [Rectangle](../../com.groupdocs.comparison.result/rectangle) | Coordenadas del elemento modificado, no nulo |
|

### getText() {#getText--}
```
public final String getText()
```


Obtiene el valor de texto del cambio.


**Returns:**
java.lang.String - valor de texto del cambio

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Establece el valor de texto del cambio.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Valor de texto del cambio |
|

### getStyleChanges() {#getStyleChanges--}
```
public final List<StyleChangeInfo> getStyleChanges()
```


Obtiene la lista de cambios de estilo.


**Returns:**
java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> - la lista de cambios de estilo

### setStyleChanges(List<StyleChangeInfo> value) {#setStyleChanges-java.util.List-com.groupdocs.comparison.result.StyleChangeInfo--}
```
public final void setStyleChanges(List<StyleChangeInfo> value)
```


Establece la lista de cambios de estilo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.util.List<com.groupdocs.comparison.result.StyleChangeInfo> | La lista de cambios de estilo |
|

### getAuthors() {#getAuthors--}
```
public final List<String> getAuthors()
```


Obtiene la lista de autores.


**Returns:**
java.util.List<java.lang.String> - la lista de autores

### setAuthors(List<String> value) {#setAuthors-java.util.List-java.lang.String--}
```
public final void setAuthors(List<String> value)
```


Establece la lista de autores.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.util.List<java.lang.String> | La lista de autores |
|

### getType() {#getType--}
```
public final ChangeType getType()
```


Obtiene el tipo de cambio representado por el enum [ChangeType](../../com.groupdocs.comparison.result/changetype).


**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - the type of the change

### getTargetText() {#getTargetText--}
```
public String getTargetText()
```


Obtiene el texto modificado del documento de destino.


**Returns:**
java.lang.String - el texto modificado

### setTargetText(String value) {#setTargetText-java.lang.String-}
```
public void setTargetText(String value)
```


Establece el texto modificado del documento de destino.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El texto modificado |
|

### getSourceText() {#getSourceText--}
```
public String getSourceText()
```


Obtiene el texto modificado del documento de origen.


**Returns:**
java.lang.String - el texto modificado

### setSourceText(String value) {#setSourceText-java.lang.String-}
```
public void setSourceText(String value)
```


Establece el texto modificado del documento fuente.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El texto modificado |
|

### getComponentType() {#getComponentType--}
```
public String getComponentType()
```


Obtiene el tipo del componente modificado.


**Returns:**
java.lang.String - el tipo del componente modificado

### setComponentType(String value) {#setComponentType-java.lang.String-}
```
public void setComponentType(String value)
```


Establece el tipo del componente modificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El tipo del componente modificado |
|

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
