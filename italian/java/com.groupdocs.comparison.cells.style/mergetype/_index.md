---
title: "MergeType"
second_title: "Riferimento API di GroupDocs.Comparison per Java"
description: "Enumera il tipo di unione di celle."
type: docs
weight: 10
url: /it/java/com.groupdocs.comparison.cells.style/mergetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MergeType extends Enum<MergeType>
```

Enumera il tipo di unione di celle.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NONE](#NONE) | Indica che la cella non si unisce. |
|
|  | [HORIZONTAL](#HORIZONTAL) | Indica che la cella si unisce lungo la riga. |
|
|  | [VERTICAL](#VERTICAL) | Indica che la cella si unisce lungo la colonna. |
|
|  | [RANGE](#RANGE) | Indica che la cella si unisce lungo la riga e la colonna, creando un'area. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final MergeType NONE
```


Indica che la cella non si unisce.


### HORIZONTAL {#HORIZONTAL}
```
public static final MergeType HORIZONTAL
```


Indica che la cella si unisce lungo la riga.


### VERTICAL {#VERTICAL}
```
public static final MergeType VERTICAL
```


Indica che la cella si unisce lungo la colonna.


### RANGE {#RANGE}
```
public static final MergeType RANGE
```


Indica che la cella si unisce lungo la riga e la colonna, creando un'area.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[MergeType](../../com.groupdocs.comparison.cells.style/mergetype)
