---
title: "MergeType"
second_title: "Référence API de GroupDocs.Comparison for Java"
description: "Énumère le type de fusion de cellules."
type: docs
weight: 10
url: /fr/java/com.groupdocs.comparison.cells.style/mergetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MergeType extends Enum<MergeType>
```

Énumère le type de fusion de cellules.

## Champs

| Champ | Description |
| --- | --- |
|  | [NONE](#NONE) | Indique que la cellule ne se fusionne pas. |
|
|  | [HORIZONTAL](#HORIZONTAL) | Indique que la cellule se fusionne le long de la ligne. |
|
|  | [VERTICAL](#VERTICAL) | Indique que la cellule se fusionne le long de la colonne. |
|
|  | [RANGE](#RANGE) | Indique que la cellule se fusionne le long de la ligne et de la colonne, créant une zone. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NONE {#NONE}
```
public static final MergeType NONE
```


Indique que la cellule ne se fusionne pas.


### HORIZONTAL {#HORIZONTAL}
```
public static final MergeType HORIZONTAL
```


Indique que la cellule se fusionne le long de la ligne.


### VERTICAL {#VERTICAL}
```
public static final MergeType VERTICAL
```


Indique que la cellule se fusionne le long de la colonne.


### RANGE {#RANGE}
```
public static final MergeType RANGE
```


Indique que la cellule se fusionne le long de la ligne et de la colonne, créant une zone.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[MergeType](../../com.groupdocs.comparison.cells.style/mergetype)
