---
title: "StyleChangeInfo"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "La clase StyleChangeInfo representa información sobre un cambio de estilo en un documento comparado."
type: docs
weight: 13
url: /es/java/com.groupdocs.comparison.result/stylechangeinfo/
---
**Inheritance:**
java.lang.Object
```
public class StyleChangeInfo
```

La clase StyleChangeInfo representa información sobre un cambio de estilo en un documento comparado.


Proporciona detalles como el nombre de la propiedad cambiada, los valores antes y después del cambio, etc.
Utilice esta clase para obtener información sobre los cambios de estilo durante el proceso de comparación de documentos.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);

     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo change : changes) {
         // Access the style change information
         final List styleChanges = change.getStyleChanges();
         for (StyleChangeInfo styleChange : styleChanges) {
             // Print the style change information
             System.out.println("PropertyName: " + styleChange.getPropertyName());
             System.out.println("OldValue: " + styleChange.getOldValue());
             System.out.println("NewValue: " + styleChange.getNewValue());
         }
     }
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [StyleChangeInfo()](#StyleChangeInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPropertyName()](#getPropertyName--) | Obtiene el nombre de la propiedad que se cambió. |
|
|  | [setPropertyName(String value)](#setPropertyName-java.lang.String-) | Establece el nombre de la propiedad que se cambió. |
|
|  | [getNewValue()](#getNewValue--) | Obtiene el nuevo valor de la propiedad. |
|
|  | [setNewValue(Object value)](#setNewValue-java.lang.Object-) | Establece el nuevo valor de la propiedad. |
|
|  | [getOldValue()](#getOldValue--) | Obtiene el valor antiguo de la propiedad. |
|
|  | [setOldValue(Object value)](#setOldValue-java.lang.Object-) | Establece el valor antiguo de la propiedad. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | {@inheritDoc} |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### StyleChangeInfo() {#StyleChangeInfo--}
```
public StyleChangeInfo()
```


### getPropertyName() {#getPropertyName--}
```
public final String getPropertyName()
```


Obtiene el nombre de la propiedad que se cambió.


**Returns:**
java.lang.String - el nombre de la propiedad

### setPropertyName(String value) {#setPropertyName-java.lang.String-}
```
public final void setPropertyName(String value)
```


Establece el nombre de la propiedad que se cambió.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de la propiedad |
|

### getNewValue() {#getNewValue--}
```
public final Object getNewValue()
```


Obtiene el nuevo valor de la propiedad.


**Returns:**
java.lang.Object - el nuevo valor de la propiedad

### setNewValue(Object value) {#setNewValue-java.lang.Object-}
```
public final void setNewValue(Object value)
```


Establece el nuevo valor de la propiedad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Object | El nuevo valor de la propiedad |
|

### getOldValue() {#getOldValue--}
```
public final Object getOldValue()
```


Obtiene el valor antiguo de la propiedad.


**Returns:**
java.lang.Object - el valor antiguo de la propiedad

### setOldValue(Object value) {#setOldValue-java.lang.Object-}
```
public final void setOldValue(Object value)
```


Establece el valor antiguo de la propiedad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Object | El valor antiguo de la propiedad |
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
