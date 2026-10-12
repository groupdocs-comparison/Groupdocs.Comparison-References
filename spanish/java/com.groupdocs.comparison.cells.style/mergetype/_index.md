---
title: "MergeType"
second_title: "Referencia de API de GroupDocs.Comparison for Java"
description: "Enumera el tipo de combinación de celdas."
type: docs
weight: 10
url: /es/java/com.groupdocs.comparison.cells.style/mergetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MergeType extends Enum<MergeType>
```

Enumera el tipo de combinación de celdas.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [NONE](#NONE) | Indica que la celda no se combina. |
|
|  | [HORIZONTAL](#HORIZONTAL) | Indica que la celda se combina a lo largo de la fila. |
|
|  | [VERTICAL](#VERTICAL) | Indica que la celda se combina a lo largo de la columna. |
|
|  | [RANGE](#RANGE) | Indica que la celda se combina a lo largo de la fila y la columna, creando un área. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final MergeType NONE
```


Indica que la celda no se combina.


### HORIZONTAL {#HORIZONTAL}
```
public static final MergeType HORIZONTAL
```


Indica que la celda se combina a lo largo de la fila.


### VERTICAL {#VERTICAL}
```
public static final MergeType VERTICAL
```


Indica que la celda se combina a lo largo de la columna.


### RANGE {#RANGE}
```
public static final MergeType RANGE
```


Indica que la celda se combina a lo largo de la fila y la columna, creando un área.


### values() {#values--}
```
public static MergeType[] values()
```




**Returns:**
com.groupdocs.comparison.cells.style.MergeType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MergeType valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[MergeType](../../com.groupdocs.comparison.cells.style/mergetype)
