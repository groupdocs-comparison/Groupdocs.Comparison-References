---
title: Utils
second_title: GroupDocs.Comparison for Java API Reference
description: The type Utils.
type: docs
weight: 10
url: /java/com.groupdocs.comparison.common/utils/
---
**Inheritance:**
java.lang.Object
```
public class Utils
```

The type Utils.
## Constructors

| Constructor | Description |
| --- | --- |
| [Utils()](#Utils--) |  |
## Fields

| Field | Description |
| --- | --- |
| [ARGB_TEMPLATE](#ARGB-TEMPLATE) |  |
| [SINGLE](#SINGLE) |  |
| [DOUBLE](#DOUBLE) |  |
| [NONE](#NONE) |  |
| [AUTOMATIC](#AUTOMATIC) |  |
| [GRADIENT](#GRADIENT) |  |
| [SOLID](#SOLID) |  |
| [HEAVY](#HEAVY) |  |
| [DOTTED](#DOTTED) |  |
| [GROUP](#GROUP) |  |
| [DASH_DOT](#DASH-DOT) |  |
| [DASH_DOT_DOT](#DASH-DOT-DOT) |  |
| [CUSTOM](#CUSTOM) |  |
## Methods

| Method | Description |
| --- | --- |
| [closeStreams(Closeable[] streams)](#closeStreams-java.io.Closeable...-) | Close all streams in array of streams |
| [wordsRevisionTypeToComparison(int wordRevisionType)](#wordsRevisionTypeToComparison-int-) |  |
| [ifNotNullAnd(Object objToCheck, Utils.IfNotNullAnd ifNotNullAndCallback)](#ifNotNullAnd-java.lang.Object-com.groupdocs.comparison.common.Utils.IfNotNullAnd-) |  |
### Utils() {#Utils--}
```
public Utils()
```


### ARGB_TEMPLATE {#ARGB-TEMPLATE}
```
public static final String ARGB_TEMPLATE
```


### SINGLE {#SINGLE}
```
public static final String SINGLE
```


### DOUBLE {#DOUBLE}
```
public static final String DOUBLE
```


### NONE {#NONE}
```
public static final String NONE
```


### AUTOMATIC {#AUTOMATIC}
```
public static final String AUTOMATIC
```


### GRADIENT {#GRADIENT}
```
public static final String GRADIENT
```


### SOLID {#SOLID}
```
public static final String SOLID
```


### HEAVY {#HEAVY}
```
public static final String HEAVY
```


### DOTTED {#DOTTED}
```
public static final String DOTTED
```


### GROUP {#GROUP}
```
public static final String GROUP
```


### DASH_DOT {#DASH-DOT}
```
public static final String DASH_DOT
```


### DASH_DOT_DOT {#DASH-DOT-DOT}
```
public static final String DASH_DOT_DOT
```


### CUSTOM {#CUSTOM}
```
public static final String CUSTOM
```


### closeStreams(Closeable[] streams) {#closeStreams-java.io.Closeable...-}
```
public static void closeStreams(Closeable[] streams)
```


Close all streams in array of streams

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streams | java.io.Closeable[] | streams |

### wordsRevisionTypeToComparison(int wordRevisionType) {#wordsRevisionTypeToComparison-int-}
```
public static RevisionType wordsRevisionTypeToComparison(int wordRevisionType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wordRevisionType | int |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### ifNotNullAnd(Object objToCheck, Utils.IfNotNullAnd ifNotNullAndCallback) {#ifNotNullAnd-java.lang.Object-com.groupdocs.comparison.common.Utils.IfNotNullAnd-}
```
public static boolean ifNotNullAnd(Object objToCheck, Utils.IfNotNullAnd ifNotNullAndCallback)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objToCheck | java.lang.Object |  |
| ifNotNullAndCallback | [IfNotNullAnd](../../com.groupdocs.comparison.common/ifnotnulland) |  |

**Returns:**
boolean
