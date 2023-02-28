---
title: ComparisonAction
second_title: GroupDocs.Comparison for Java API Reference
description: An action that can be applied to change.
type: docs
weight: 17
url: /java/com.groupdocs.comparison.result/comparisonaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ComparisonAction extends Enum<ComparisonAction>
```

An action that can be applied to change.
## Fields

| Field | Description |
| --- | --- |
| [NONE](#NONE) | Nothing to do |
| [ACCEPT](#ACCEPT) | Change will be visible on result file |
| [REJECT](#REJECT) | Reject will be invisible on result file |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) |  |
| [toString()](#toString--) |  |
### NONE {#NONE}
```
public static final ComparisonAction NONE
```


Nothing to do

### ACCEPT {#ACCEPT}
```
public static final ComparisonAction ACCEPT
```


Change will be visible on result file

### REJECT {#REJECT}
```
public static final ComparisonAction REJECT
```


Reject will be invisible on result file

### values() {#values--}
```
public static ComparisonAction[] values()
```




**Returns:**
com.groupdocs.comparison.result.ComparisonAction[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ComparisonAction valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static ComparisonAction fromString(String toStringValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String |  |

**Returns:**
[ComparisonAction](../../com.groupdocs.comparison.result/comparisonaction)
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
