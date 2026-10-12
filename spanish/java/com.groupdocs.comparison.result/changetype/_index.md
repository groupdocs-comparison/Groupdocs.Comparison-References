---
title: "ChangeType"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "El enum ChangeType representa los tipos de cambios que pueden ocurrir durante el proceso de comparación de documentos."
type: docs
weight: 14
url: /es/java/com.groupdocs.comparison.result/changetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ChangeType extends Enum<ChangeType>
```

El enum ChangeType representa los tipos de cambios que pueden ocurrir durante el proceso de comparación de documentos.


Cada constante en este enum representa un tipo específico de cambio y proporciona una descripción legible para humanos y un valor numérico.


Ejemplo de uso:

````

 try (Comparer comparer = new Comparer(sourceFile)) {
     comparer.add(targetFile);
     comparer.compare();
     final ChangeInfo[] changes = comparer.getChanges();
     for (ChangeInfo changeInfo : changes) {
         // Get the ChangeType for a specific change
         final ChangeType changeType = changeInfo.getType();
         // Print the ChangeType information
         System.out.println("Description: " + changeType.toString());
         System.out.println("Value: " + changeType.toInt());
     }
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [NONE](#NONE) | Representa ningún cambio. |
|
|  | [MODIFIED](#MODIFIED) | Representa un cambio modificado. |
|
|  | [INSERTED](#INSERTED) | Representa un cambio insertado. |
|
|  | [DELETED](#DELETED) | Representa un cambio eliminado. |
|
|  | [ADDED](#ADDED) | Representa un cambio añadido. |
|
|  | [NOT_MODIFIED](#NOT-MODIFIED) | Representa un cambio no modificado. |
|
|  | [STYLE_CHANGED](#STYLE-CHANGED) | Representa un cambio de estilo. |
|
|  | [RESIZED](#RESIZED) | Representa un cambio redimensionado. |
|
|  | [MOVED](#MOVED) | Representa un cambio movido. |
|
|  | [MOVED_AND_RESIZED](#MOVED-AND-RESIZED) | Representa un cambio movido y redimensionado. |
|
|  | [SHIFTED_AND_RESIZED](#SHIFTED-AND-RESIZED) | Representa un cambio desplazado y redimensionado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromString(String toStringValue)](#fromString-java.lang.String-) | Analiza la representación en cadena de ChangeType para obtener la constante enum. |
|
|  | [fromInt(int intValue)](#fromInt-int-) | Crea una nueva constante del enum ChangeType usando el valor numérico proporcionado. |
|
|  | [toString()](#toString--) | Representación en cadena de ChangeType. |
|
|  | [toInt()](#toInt--) | Representación numérica de ChangeType. |
|
### NONE {#NONE}
```
public static final ChangeType NONE
```


Representa ningún cambio.


### MODIFIED {#MODIFIED}
```
public static final ChangeType MODIFIED
```


Representa un cambio modificado.


### INSERTED {#INSERTED}
```
public static final ChangeType INSERTED
```


Representa un cambio insertado.


### DELETED {#DELETED}
```
public static final ChangeType DELETED
```


Representa un cambio eliminado.


### ADDED {#ADDED}
```
public static final ChangeType ADDED
```


Representa un cambio añadido.


### NOT_MODIFIED {#NOT-MODIFIED}
```
public static final ChangeType NOT_MODIFIED
```


Representa un cambio no modificado.


### STYLE_CHANGED {#STYLE-CHANGED}
```
public static final ChangeType STYLE_CHANGED
```


Representa un cambio de estilo.


### RESIZED {#RESIZED}
```
public static final ChangeType RESIZED
```


Representa un cambio redimensionado.


### MOVED {#MOVED}
```
public static final ChangeType MOVED
```


Representa un cambio movido.


### MOVED_AND_RESIZED {#MOVED-AND-RESIZED}
```
public static final ChangeType MOVED_AND_RESIZED
```


Representa un cambio movido y redimensionado.


### SHIFTED_AND_RESIZED {#SHIFTED-AND-RESIZED}
```
public static final ChangeType SHIFTED_AND_RESIZED
```


Representa un cambio desplazado y redimensionado.


### values() {#values--}
```
public static ChangeType[] values()
```




**Returns:**
com.groupdocs.comparison.result.ChangeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ChangeType valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ChangeType fromString(String toStringValue)
```


Analiza la representación en cadena de ChangeType para obtener la constante enum.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | toStringValue | java.lang.String | La representación en cadena de ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with input string

### fromInt(int intValue) {#fromInt-int-}
```
public static ChangeType fromInt(int intValue)
```


Crea una nueva constante del enum ChangeType usando el valor numérico proporcionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | intValue | int | La representación numérica de ChangeType |
|

**Returns:**
[ChangeType](../../com.groupdocs.comparison.result/changetype) - ChangeType enum constant associated with numeric value

### toString() {#toString--}
```
public String toString()
```


Representación en cadena de ChangeType.


**Returns:**
java.lang.String - valor en cadena de la constante del enum

### toInt() {#toInt--}
```
public int toInt()
```


Representación numérica de ChangeType.


**Returns:**
int - valor numérico de la constante del enum

