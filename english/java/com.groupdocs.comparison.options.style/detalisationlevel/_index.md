---
title: DetalisationLevel
second_title: GroupDocs.Comparison for Java API Reference
description: Specifies the level of comparison details.
type: docs
weight: 13
url: /java/com.groupdocs.comparison.options.style/detalisationlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetalisationLevel extends Enum<DetalisationLevel>
```

Specifies the level of comparison details.
## Fields

| Field | Description |
| --- | --- |
| [LOW](#LOW) | Low level. |
| [MIDDLE](#MIDDLE) | Middle level. |
| [HIGH](#HIGH) | High level. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) |  |
| [toString()](#toString--) |  |
### LOW {#LOW}
```
public static final DetalisationLevel LOW
```


Low level. Provides the best speed comparison sacrificing comparison quality. Comparison is performed per-word.

### MIDDLE {#MIDDLE}
```
public static final DetalisationLevel MIDDLE
```


Middle level. A reasonable compromise between comparison speed and quality. Comparison is performed per-character, but ignoring character case and spaces count.

### HIGH {#HIGH}
```
public static final DetalisationLevel HIGH
```


High level. The best comparison quality, but the lowest speed. Comparison is performed per-character considering character case and spaces count.

### values() {#values--}
```
public static DetalisationLevel[] values()
```




**Returns:**
com.groupdocs.comparison.options.style.DetalisationLevel[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static DetalisationLevel valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static DetalisationLevel fromString(String toStringValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String |  |

**Returns:**
[DetalisationLevel](../../com.groupdocs.comparison.options.style/detalisationlevel)
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
