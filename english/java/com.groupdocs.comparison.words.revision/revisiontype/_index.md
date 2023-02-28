---
title: RevisionType
second_title: GroupDocs.Comparison for Java API Reference
description: Specifies the type of change being tracked
type: docs
weight: 14
url: /java/com.groupdocs.comparison.words.revision/revisiontype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum RevisionType extends Enum<RevisionType>
```

Specifies the type of change being tracked
## Fields

| Field | Description |
| --- | --- |
| [INSERTION](#INSERTION) | New content was inserted in the document. |
| [DELETION](#DELETION) | Content was removed from the document. |
| [FORMAT_CHANGE](#FORMAT-CHANGE) | Change of formatting was applied to the parent node. |
| [STYLE_DEFINITION_CHANGE](#STYLE-DEFINITION-CHANGE) | Change of formatting was applied to the parent style. |
| [MOVING](#MOVING) | Content was moved in the document. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromInt(int toIntValue)](#fromInt-int-) |  |
| [fromString(String toStringValue)](#fromString-java.lang.String-) |  |
| [toInt()](#toInt--) |  |
| [toString()](#toString--) |  |
### INSERTION {#INSERTION}
```
public static final RevisionType INSERTION
```


New content was inserted in the document.

### DELETION {#DELETION}
```
public static final RevisionType DELETION
```


Content was removed from the document.

### FORMAT_CHANGE {#FORMAT-CHANGE}
```
public static final RevisionType FORMAT_CHANGE
```


Change of formatting was applied to the parent node.

### STYLE_DEFINITION_CHANGE {#STYLE-DEFINITION-CHANGE}
```
public static final RevisionType STYLE_DEFINITION_CHANGE
```


Change of formatting was applied to the parent style.

### MOVING {#MOVING}
```
public static final RevisionType MOVING
```


Content was moved in the document.

### values() {#values--}
```
public static RevisionType[] values()
```




**Returns:**
com.groupdocs.comparison.words.revision.RevisionType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static RevisionType valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromInt(int toIntValue) {#fromInt-int-}
```
public static RevisionType fromInt(int toIntValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toIntValue | int |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### fromString(String toStringValue) {#fromString-java.lang.String-}
```
public static RevisionType fromString(String toStringValue)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toStringValue | java.lang.String |  |

**Returns:**
[RevisionType](../../com.groupdocs.comparison.words.revision/revisiontype)
### toInt() {#toInt--}
```
public int toInt()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
